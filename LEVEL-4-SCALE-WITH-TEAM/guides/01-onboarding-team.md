# Guide 1: Onboarding a Team

[⬅ Back to Level 4 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 30 minutes  
**Goal:** Set up Cline so new team members can get productive fast

---

## The Solo-to-Team Transition

As a solo founder, you had full control over Cline config. When you add team members, you need:

1. **Shared rules** — everyone follows the same standards
2. **Shared configs** — consistent settings across the team
3. **Easy onboarding** — new devs get productive in <30 minutes

---

## Step 1: Commit Cline Rules to Git

Your team should share rules via version control:

```
your-project/
  .clinerules/              ← Commit this!
    coding.md
    testing.md
    architecture.md
  .clineignore              ← Commit this!
  memory-bank/              ← Commit this!
```

New developers just clone the repo and Cline auto-loads the rules.

## Step 2: Document Your Onboarding

Create a simple `ONBOARDING.md` in your project:

```markdown
# Cline Onboarding

## Step 1: Install
- VS Code + Cline extension
- Or CLI: `npm install -g cline`

## Step 2: Configure Provider
- Get an OpenRouter key from [openrouter.ai/keys](https://openrouter.ai/keys)
- Configure in VS Code: OpenRouter provider, DeepSeek model

## Step 3: Start Coding
- Open the project
- Cline auto-loads `.clinerules/` and `.clineignore`
- Read `memory-bank/` for project context
- Run your first task
```

## Step 3: Set Up Memory Bank for the Team

Create `memory-bank/productContext.md`:
```markdown
# Product Context

## What We're Building
[What does the app do?]

## Who It's For
[Target users]

## Current Status
[Where are we in development?]

## Key Decisions
[Important architectural decisions]
```

---

## Pro Tips

- Make onboarding a **checklist**, not a narrative
- New devs should use the same model (DeepSeek) by default
- Let team members customize their own model choices later

[📖 Next: Remote Configuration →](02-remote-config.md)