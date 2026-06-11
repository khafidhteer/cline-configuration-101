# 🟡 Level 2: Efficient — Save Money & Time

[⬅ Back to Home](../GETTING-STARTED.md) | [📖 Full Roadmap](../ROADMAP.md) | [🔴 Level 3 Next →](../LEVEL-3-POWER-USER/PLAN.md)

---

**Time Investment:** ~2 hours  
**Goal:** Master context management, rules, and memory for consistent results  
**Cost Strategy:** Smart model selection (cheap for simple, expensive for complex)

---

## Learning Objectives

By the end of this level, you will be able to:

- [ ] Create Cline Rules so Cline remembers your preferences
- [ ] Use Checkpoints to experiment without fear
- [ ] Set up Auto-Approve for safe, fast workflows
- [ ] Manage context windows so you never run out mid-task
- [ ] Set up Memory Bank so Cline remembers your project across sessions
- [ ] Track and control your API costs
- [ ] Use Subagents for parallel research

---

## Prerequisites

- ✅ Completed [Level 1: Quick Start](../LEVEL-1-QUICK-START/PLAN.md)
- ✅ Cline working in VS Code with OpenRouter configured
- ✅ A project you're actively developing

---

## Action Items

### Guide 1: Rules for Consistency (15 min)
- [ ] Create a `.clinerules/` directory in your project
- [ ] Add rules for coding style, testing, and architecture
- [ ] Test rules with a sample task

📖 [Rules Guide →](guides/01-rules-for-consistency.md)

### Guide 2: Checkpoints Safety Net (10 min)
- [ ] Understand how checkpoints work
- [ ] Practice restoring files after a change
- [ ] Combine with auto-approve for safe speed

📖 [Checkpoints Guide →](guides/02-checkpoints-safety-net.md)

### Guide 3: Auto-Approve Smartly (10 min)
- [ ] Configure safe auto-approve settings
- [ ] Understand safe vs approval-required commands
- [ ] Learn when to use (and not use) YOLO mode

📖 [Auto-Approve Guide →](guides/03-auto-approve-smartly.md)

### Guide 4: Context Window Hacks (15 min)
- [ ] Add `.clineignore` to your project
- [ ] Practice using `/newtask` and `/smol`
- [ ] Enable Auto-Compact
- [ ] Master task scoping

📖 [Context Window Hacks →](guides/04-context-window-hacks.md)

### Guide 5: Memory Bank (20 min)
- [ ] Create Memory Bank files for your project
- [ ] Add Memory Bank custom instructions to Cline Rules
- [ ] Practice: initialize Memory Bank, start fresh session, resume

📖 [Memory Bank Guide →](guides/05-memory-bank.md)

### Guide 6: Cost Control (15 min)
- [ ] Understand task header cost display
- [ ] Set a monthly budget on OpenRouter
- [ ] Learn which models to use for which tasks
- [ ] Calculate your monthly costs

📖 [Cost Control Guide →](guides/06-cost-control.md)

### Guide 7: Subagents (10 min)
- [ ] Enable subagents
- [ ] Try a task that benefits from parallel research
- [ ] Understand when to use subagents vs not

📖 [Subagents Guide →](guides/07-subagents-parallel.md)

### Guide 8: When to Move to CLI (5 min)
- [ ] Identify your first automation opportunity
- [ ] Install CLI if you haven't yet
- [ ] Write your first CLI command

📖 [When to Move to CLI →](guides/08-when-to-move-to-cli.md)

---

## Verification Checklist

After completing this level, confirm you can:

- [ ] ✅ Cline follows your project-specific rules automatically
- [ ] ✅ You can undo changes using checkpoints
- [ ] ✅ Safe operations run without approval prompts
- [ ] ✅ You understand your weekly/monthly API costs
- [ ] ✅ Cline remembers your project context across sessions
- [ ] ✅ You can use `/newtask` and `/smol` when context fills up

---

## Configs in This Level

| File | What It Does |
|------|-------------|
| `.clinerules/coding.md` | Code style preferences |
| `.clinerules/testing.md` | Test requirements |
| `.clinerules/architecture.md` | Architecture decisions |
| Memory Bank template | Project memory structure |

---

## Key Takeaways

- ✅ Rules are the #1 way to get consistent results from Cline
- ✅ Checkpoints make "try anything, undo if wrong" practical
- ✅ Auto-Approve for reads, manual for writes = sweet spot
- ✅ `.clineignore` can cut your token usage by 75%
- ✅ Memory Bank solves the "Cline forgot" problem forever

---

## Next Steps

⬆️ [Level 3: Power User →](../LEVEL-3-POWER-USER/PLAN.md)