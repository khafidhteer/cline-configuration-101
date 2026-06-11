# Guide 2: Model Mix & Match

[⬅ Back to Level 3 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 30 minutes  
**Goal:** Use cheap models for simple tasks, expensive models for complex ones

---

## The Strategy

Different models cost 10-500x difference. Use the right model for each phase:

```
PLAN (cheap) → EXECUTE (mid-tier) → REVIEW (premium)
DeepSeek         Sonnet                Opus
$0.14/1M         $3.00/1M              $15.00/1M
```

---

## Step 1: Create Model Config Directories

```bash
# Create separate config directories for each model
mkdir -p ~/.cline-haiku ~/.cline-sonnet ~/.cline-opus
```

## Step 2: Configure Each Directory

```bash
# Cheap model for planning/summaries
cline --config ~/.cline-haiku auth --provider openrouter \
  -k YOUR_API_KEY -m anthropic/claude-3.5-haiku

# Mid-tier for general coding
cline --config ~/.cline-sonnet auth --provider openrouter \
  -k YOUR_API_KEY -m anthropic/claude-sonnet-4-6

# Premium for complex reasoning 
cline --config ~/.cline-opus auth --provider openrouter \
  -k YOUR_API_KEY -m anthropic/claude-opus-4-5
```

## Step 3: Build a Pipeline

```bash
# Phase 1: Summarize with cheap model
SUMMARY=$(cline --config ~/.cline-haiku --auto-approve true \
  "summarize this codebase in 3 sentences")

# Phase 2: Plan with mid-tier
PLAN=$(echo "$SUMMARY" | cline --config ~/.cline-sonnet --auto-approve true \
  "create an implementation plan")

# Phase 3: Deep review with premium
echo "$PLAN" | cline --config ~/.cline-opus --auto-approve true \
  "review this plan for edge cases"
```

**Cost impact:** This pipeline costs ~$0.10 vs ~$2.00 if you used Opus for everything.

---

## Cost Savings Example

| Approach | Cost for 100 tasks |
|----------|-------------------|
| All Opus | ~$200 |
| Mixed (Haiku + Sonnet + Opus) | ~$15 |
| All DeepSeek | ~$1 |

---

## Pro Tips

- Use DeepSeek or Haiku for **80% of tasks**
- Switch to Sonnet when you need **quality code**
- Use Opus only for **architecture and deep analysis**
- The `--config` flag lets you switch models per-task

[📖 Next: GitHub Automation →](03-github-automation.md)