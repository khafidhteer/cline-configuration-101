# Guide 6: VS Code vs CLI — When to Use Each

[⬅ Back to Level 1 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 2 minutes  
**Goal:** Understand the difference between VS Code and CLI, and when to use each

---

## The Short Answer

| Use This | When | Example |
|----------|------|---------|
| **VS Code** | Daily development | Writing code, debugging, building features |
| **CLI** | Automation | Running scripts, CI/CD, batch processing |

---

## VS Code (Your Daily Driver)

**Best for:**
- Writing and editing code
- Browsing files in the editor
- Seeing real-time changes
- Having conversations with Cline
- Using Cline Rules and Memory Bank

**You'll use VS Code** for 90% of your Cline work. It's where you build your product day-to-day.

## CLI (Your Automation Tool)

**Best for:**
- Running Cline in scripts
- Processing files in bulk
- CI/CD pipelines (GitHub Actions)
- Headless automation (no GUI needed)
- Scheduling tasks (daily reports, health checks)

**You'll use the CLI** when you want Cline to work without you watching.

---

## When to Move from VS Code to CLI

Think of it like this:

1. **You start** in VS Code — having conversations, building features, learning how Cline works
2. **You discover a repetitive task** — like "I need to summarize my PR every morning"
3. **You write a script** that uses the CLI to automate that task
4. **Cline runs automatically** — you wake up to a summary in your email or Slack

**The milestone is:** The first time you think "I wish Cline would just do this automatically" — that's when you switch to CLI.

---

## Practical Examples

### VS Code Session
```
You type: "Add a dark mode toggle to my app"
Cline: Reads your files, plans the approach, writes the code
You: Review changes, approve, test
```

### CLI Session
```bash
# Single command
cline "summarize all changes since yesterday"

# Pipe a file
cat README.md | cline "improve this documentation"

# With a script
./daily-standup.sh  # Runs cline internally
```

---

## Can You Use Both?

**Yes.** They share the same configuration. Whatever you set up in VS Code (API keys, rules, etc.) is also available when you run the CLI.

```bash
# This works because VS Code already configured your auth
cline "what's the status of this project?"
```

---

## Quick Comparison Table

| Feature | VS Code | CLI |
|---------|---------|-----|
| Chat interface | ✅ Graphical | ✅ Terminal |
| File editing | ✅ Built-in | ❌ Needs separate editor |
| File browsing | ✅ Visual | ❌ Terminal only |
| Script automation | ❌ Manual | ✅ Headless mode |
| CI/CD integration | ❌ | ✅ GitHub Actions |
| Cron scheduling | ❌ | ✅ Scheduled agents |
| Cost display | ✅ In task header | ✅ With --verbose |
| Context menu | ✅ Right-click | ❌ |
| Multi-model config | ✅ Settings | ✅ --config flag |

---

## Your Path

1. **Start with VS Code only** (Level 1)
2. **Master VS Code features** (Level 2)
3. **Add CLI for automation** (Level 3)

You don't need to learn everything at once. Move to CLI when you feel the need.

---

## What's Next?

You've completed Level 1! 🎉

> **Congrats!** [Return to Level 1 Plan](../PLAN.md) to check off the final items, or move to [Level 2: Efficient →](../../LEVEL-2-EFFICIENT/PLAN.md)