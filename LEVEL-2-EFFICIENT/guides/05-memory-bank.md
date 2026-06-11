# Guide 5: Memory Bank — Cline Never Forgets

[⬅ Back to Level 2 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 20 minutes  
**Goal:** Cline remembers your project across sessions — forever

---

## What is Memory Bank?

Memory Bank is a set of markdown files in your project that Cline reads at the start of every session. It transforms Cline from a **stateless assistant** (forgets everything between chats) into a **persistent partner** (remembers your project context).

**Without Memory Bank:** Every session starts from zero  
**With Memory Bank:** Cline knows your project, architecture, and what you were working on

---

## Step 1: Add Memory Bank Instructions to Cline Rules

Create a file at `.clinerules/memory-bank.md` with these instructions:

```markdown
# Memory Bank Instructions

I am Cline, an expert software engineer. My memory resets completely between sessions.
I rely ENTIRELY on my Memory Bank to understand the project and continue work.

## Core Files

1. `memory-bank/projectbrief.md` — Core requirements and goals
2. `memory-bank/productContext.md` — Why this project exists
3. `memory-bank/activeContext.md` — Current work focus (updates most frequently)
4. `memory-bank/systemPatterns.md` — Architecture and design patterns
5. `memory-bank/techContext.md` — Tech stack and setup
6. `memory-bank/progress.md` — What works and what's left

## Commands

- "initialize memory bank" — Create initial structure
- "update memory bank" — Review and update all files
- "follow your custom instructions" — Read Memory Bank and continue
```

## Step 2: Initialize Memory Bank

1. Start a new Cline task
2. Type: `initialize memory bank`
3. Cline will create the `memory-bank/` directory with starter files

**Or create the files manually:**

Create `memory-bank/projectbrief.md`:
```markdown
# Project Brief

## Core Requirements
- [What does your app do?]
- [Who is it for?]
- [Key features]

## Goals
- [What are you building towards?]
```

Create `memory-bank/activeContext.md`:
```markdown
# Active Context

## Current Focus
- [What are you working on right now?]

## Recent Changes
- [What changed in the last session?]

## Next Steps
- [What to do next]
```

## Step 3: Practice the Workflow

1. **Work normally** with Cline for a while
2. **Ask Cline** to "update memory bank" before you finish
3. **Close VS Code** (or start a new task)
4. **Say** "follow your custom instructions"
5. ✅ Cline remembers everything

---

## Pro Tips

- Update `activeContext.md` after every session — it's the most important file
- Commit `memory-bank/` to Git so your team can see project context
- Use `/newtask` when context fills up, then say "follow your custom instructions"

[📖 Next: Cost Control →](06-cost-control.md)