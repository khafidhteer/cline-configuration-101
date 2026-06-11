# Guide 3: Auto-Approve Smartly

[⬅ Back to Level 2 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 10 minutes  
**Goal:** Speed up Cline without losing control

---

## What Auto-Approve Does

Normally, Cline asks for approval before every action (read file, edit file, run command). Auto-Approve lets Cline skip the approval for **specific types** of actions.

---

## Step 1: Open Auto-Approve Settings

1. Open VS Code
2. Click the Cline icon (🤖) in the left sidebar
3. Click the gear icon (⚙️) to open settings
4. Find the **Auto-Approve** section

## Step 2: Configure Your Settings

**Recommended safe defaults for solo founders:**

| Setting | Recommended | Why |
|---------|------------|-----|
| Read project files | ✅ ON | Reading files is always safe |
| Read all files | ❌ OFF | Only enable if needed |
| Edit project files | ❌ OFF | Keep manual approval for writes |
| Edit all files | ❌ OFF | Don't let Cline edit system files |
| Execute safe commands | ✅ ON | Commands like `npm test`, `git status` |
| Execute all commands | ❌ OFF | Keep approval for installs, deletes |
| Use the browser | ❌ OFF | Keep approval for web searches |
| Use MCP servers | ❌ OFF | Keep approval for external tools |

## Step 3: Understand Safe vs Risky Commands

**Safe (auto-approve with setting on):**
- `npm run build`, `npm test`
- `git status`, `ls -la`, `cat package.json`
- Read-only file operations

**Requires approval (even with setting on):**
- `npm install <package>` — modifies dependencies
- `rm -rf <path>` — deletes files
- `mv <a> <b>` — moves files (can overwrite)
- `sudo ...` — system-level changes

---

## When to Use YOLO Mode

YOLO mode auto-approves **everything** — file changes, terminal commands, browser actions. It's dangerous but useful in specific situations:

**✅ Safe uses:**
- Throwaway projects and experiments
- Repetitive tasks you've validated
- CI/CD pipelines with existing safety checks

**❌ Don't use for:**
- Production code
- Projects without version control
- Tasks you don't fully understand

> ⚠️ **Warning:** YOLO mode removes ALL safety checks. Only enable it when you're prepared to lose everything Cline does.

---

## Pro Tip: Checkpoints + Auto-Approve = Best Combo

Enable auto-approve for reads + safe commands, then let Cline fly. If something goes wrong, just **restore a checkpoint**. You get speed AND a safety net.

[📖 Next: Context Window Hacks →](04-context-window-hacks.md)