# Guide 7: Custom Skills

[⬅ Back to Level 3 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 20 minutes  
**Goal:** Create reusable instruction sets for specific tasks

---

## What Are Skills?

Skills are modular instruction sets that Cline loads **on-demand**. Unlike rules (always active), skills only activate when you need them. This saves context tokens.

**Example skills:**
- `aws-deploy` — knows exactly how to deploy to AWS
- `pr-review-checklist` — has a detailed code review process
- `database-migration` — step-by-step migration guide

---

## Step 1: Create a Skill Directory

Skills live in `.cline/skills/` (project-level) or `~/.cline/skills/` (global).

Create a skill for data analysis:

```
.cline/skills/data-analysis/
  SKILL.md          ← Required: main instructions
  docs/             ← Optional: additional docs
  scripts/          ← Optional: helper scripts
```

## Step 2: Write the SKILL.md

`.cline/skills/data-analysis/SKILL.md`:

```markdown
---
name: data-analysis
description: Analyze CSV and Excel data files. Use when working with data that needs exploration, cleaning, or visualization.
---

# Data Analysis Skill

When analyzing data files, follow this process:

## 1. Understand the Data
- Read a sample of the file
- Identify column types and data quality issues

## 2. Perform Analysis
- Use Python/pandas for data manipulation
- Use matplotlib or seaborn for visualization
- Handle missing values appropriately

## 3. Present Results
- Summarize key findings in bullet points
- Include visualizations when helpful
- Note any data quality concerns
```

## Step 3: Enable the Skill

1. Open Cline settings → **Features** → **Skills**
2. Toggle Skills ON
3. Cline will auto-detect skills in `.cline/skills/`

## Step 4: Use the Skill

Cline auto-triggers skills based on your prompt. Or type:

```
/ data-analysis
```

To force-trigger the skill.

---

## Pro Tips

- Skill descriptions are critical — write clear, action-oriented descriptions
- Keep SKILL.md under 5K tokens
- Use `scripts/` for deterministic operations (validation, formatting)
- Skills load on-demand — they don't waste context when not needed

[⬆️ Back to Level 3 Plan →](../PLAN.md)