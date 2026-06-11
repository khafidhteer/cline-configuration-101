# Guide 2: Checkpoints — Your Safety Net

[⬅ Back to Level 2 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 10 minutes  
**Goal:** Experiment without fear — undo any change Cline makes

---

## What Are Checkpoints?

Every time Cline modifies a file or runs a command, it saves a **snapshot** of your project. You can restore your project to any snapshot — like an "undo" button for everything Cline did.

**Checkpoints are enabled by default.** You don't need to set anything up.

---

## How to Use Checkpoints

### Restore Files (Undo code changes, keep conversation)
After each Cline action, look for the **bookmark icon** in the chat. Click **Restore** next to any step and choose:

| Option | What It Does | When to Use |
|--------|-------------|-------------|
| **Restore Files** | Reverts code to this snapshot | Cline's code broke something, but the conversation was good |
| **Restore Task Only** | Deletes messages after this point | Keep the code, try a different prompt |
| **Restore Files & Task** | Reverts both code and conversation | Start completely over |

### Compare Changes
Click **Compare** next to any checkpoint to see a diff (what changed) in your editor.

---

## Combining Checkpoints with Auto-Approve

Checkpoints make auto-approve **safe**. Here's the workflow:

1. Enable auto-approve for file reads and safe commands
2. Let Cline work quickly through your task
3. Review the final result
4. If something is wrong, restore to the last good checkpoint
5. Give Cline more specific guidance

This is faster than reviewing every single change individually.

---

## Pro Tip

- Checkpoints are stored in a **shadow Git repository** — they don't interfere with your real Git history
- They persist across editor sessions (close VS Code, come back tomorrow)
- Disable checkpoints in Cline settings if your project is very large (they use storage)

[📖 Next: Auto-Approve Smartly →](03-auto-approve-smartly.md)