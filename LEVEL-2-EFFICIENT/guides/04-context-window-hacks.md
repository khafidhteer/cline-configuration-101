# Guide 4: Context Window Hacks

[⬅ Back to Level 2 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 15 minutes  
**Goal:** Never run out of context mid-task again

---

## What is a Context Window?

Cline's **short-term memory** — it can only process a limited amount of text at once. When the window fills up, older parts get compressed or forgotten.

A full context window means:
- Cline forgets earlier parts of the conversation
- Responses become less relevant
- You have to repeat yourself

---

## Hack 1: Add a .clineignore (Instant 75% Savings)

Cline loads your entire project into context by default. Without a `.clineignore`, it reads `node_modules`, build folders, and lock files — wasting thousands of tokens.

**Copy this to your project root:** [minimal.clineignore](../LEVEL-1-QUICK-START/configs/minimal.clineignore)

**Result:** Drops from ~200K tokens to ~50K tokens instantly.

## Hack 2: Use /newtask (The "Fresh Start" Command)

When your conversation gets long, type:

```
/newtask
```

This creates a new task with a clean context window, but **preserves**:
- The plan and decisions made
- File changes and progress
- Important context

It's like a "developer handoff" to yourself.

## Hack 3: Use /smol (The "Compress" Command)

When you're deep in a debugging session and don't want to lose your train of thought:

```
/smol
```

This compresses your conversation history into a summary, freeing up space while keeping the key insights. You can continue in the same task.

## Hack 4: Enable Auto-Compact

Cline can automatically compress conversations when you're getting close to the limit.

1. Open Cline settings (gear icon)
2. Scroll to **Auto-Compact**
3. Toggle it ON

Now Cline will summarize your conversation automatically when needed. You'll see a summarization tool call in the chat.

## Hack 5: Scope Your Tasks

**One task = one goal.** Don't try to fix a CSS bug AND build a login system in the same task.

| Task Scope | Context Usage | Result |
|-----------|--------------|--------|
| "Implement user authentication" | Full window for auth | ✅ Good |
| "Implement auth AND fix CSS AND add API" | Overflows quickly | ❌ Bad |

If you're 75% through a 10-step plan, use `/newtask` to hand off to a fresh session.

---

## Pro Tip

Combine all 5 hacks:
1. Add `.clineignore` → cut baseline by 75%
2. Scope tasks → keep context focused
3. Use `/newtask` between major phases
4. Use `/smol` during long sessions
5. Enable Auto-Compact as a safety net

[📖 Next: Memory Bank →](05-memory-bank.md)