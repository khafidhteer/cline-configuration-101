# Guide 3: GitHub Automation

[⬅ Back to Level 3 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 45 minutes  
**Goal:** Auto-review PRs and analyze issues with Cline

---

## What You're Building

A GitHub Actions workflow that:
1. Detects when a PR is opened
2. Runs Cline to review the code
3. Posts a review comment with feedback

---

## Prerequisites

- GitHub repository with Actions enabled
- OpenRouter API key added as a GitHub secret: `OPENROUTER_API_KEY`

**Adding a secret:** GitHub → Settings → Secrets and variables → Actions → New repository secret

---

## Step 1: Create the Workflow File

Create `.github/workflows/cline-pr-review.yml`:

```yaml
name: Cline PR Review
on:
  pull_request:
    types: [opened, ready_for_review]

jobs:
  review:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
        with:
          fetch-depth: 0

      - name: Setup Node.js
        uses: actions/setup-node@v4
        with:
          node-version: 22

      - name: Install Cline CLI
        run: npm install -g cline

      - name: Configure OpenRouter
        run: |
          cline auth --provider openrouter \
            --apikey "${{ secrets.OPENROUTER_API_KEY }}" \
            --modelid deepseek/deepseek-chat

      - name: Review PR
        env:
          PR_NUMBER: ${{ github.event.pull_request.number }}
          GH_TOKEN: ${{ github.token }}
        run: |
          cline --auto-approve true \
            "Review PR #${PR_NUMBER}. 
            1. Use 'gh pr view' and 'gh pr diff' to get context
            2. Check for bugs, security issues, and code quality
            3. Post a comment with your review"
```

## Step 2: Add Issue Analysis (Optional)

Create `.github/workflows/cline-issue-analysis.yml`:

```yaml
name: Cline Issue Analysis
on:
  issue_comment:
    types: [created]

jobs:
  analyze:
    if: contains(github.event.comment.body, '@cline')
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-node@v4
        with:
          node-version: 22

      - name: Install Cline
        run: npm install -g cline

      - name: Configure OpenRouter
        run: |
          cline auth --provider openrouter \
            --apikey "${{ secrets.OPENROUTER_API_KEY }}" \
            --modelid deepseek/deepseek-chat

      - name: Analyze Issue
        run: |
          cline --auto-approve true \
            "Analyze issue #${{ github.event.issue.number }}"
```

Now when someone comments `@cline` on an issue, Cline automatically analyzes it.

---

## Pro Tips

- Use **DeepSeek** for reviews to keep costs near zero
- Restrict command permissions with `CLINE_COMMAND_PERMISSIONS`
- Test with a draft PR first to verify the workflow

[📖 Next: CLI Automation →](04-cli-automation.md)