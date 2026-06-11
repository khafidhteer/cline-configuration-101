# Guide 8: When to Move to CLI

[⬅ Back to Level 2 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 5 minutes  
**Goal:** Know when and why to start using the CLI

---

## The CLI vs VS Code Decision

| Use VS Code When | Use CLI When |
|-----------------|-------------|
| Writing code | Running scripts |
| Having conversations | Automating tasks |
| Exploring your codebase | Processing files in bulk |
| Setting up rules and configs | CI/CD pipelines |
| Learning Cline features | Running Cline without watching |

## The Milestone

You'll know it's time to move to CLI when you think:

> "I wish Cline would just do this automatically every day."

Common examples:
- "Summarize my PR changes every morning"
- "Check for outdated dependencies every Monday"
- "Analyze this error log every time I get an alert"

## Your First CLI Command

If you have the CLI installed, try:

```bash
cline "list all files changed in the last commit and summarize the changes"
```

This is the simplest automation — one command, no watching needed.

## What CLI Enables

Level 3 is entirely about CLI capabilities:
- Headless automation
- GitHub Actions integration
- Telegram/Slack bots
- Scheduled agents
- Custom scripts

You don't need to learn these now. Just know the CLI exists and what it can do.

## What's Next?

[⬆️ Level 3: Power User →](../../LEVEL-3-POWER-USER/PLAN.md)