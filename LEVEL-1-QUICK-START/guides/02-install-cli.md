# Guide 2: Install the Cline CLI

[⬅ Back to Level 1 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 5 minutes  
**Goal:** Install the Cline command-line interface (CLI)

---

## Should You Do This?

**You can skip this if:**
- You only want to use Cline inside VS Code
- You don't plan on automating tasks yet

**Do this if:**
- You want to run Cline from your terminal
- You want to automate tasks (scripts, CI/CD)
- You want to use Telegram/Slack bots with Cline

> 💡 **Tip:** Start with VS Code only. Come back to the CLI when you hit a task that needs automation.

---

## Step 1: Install Node.js

The CLI requires Node.js. Check if you already have it:

1. Open your **terminal** (Command Prompt on Windows, Terminal on Mac/Linux)
2. Type: `node --version`
3. If you see a version number (like `v22.0.0`), you have Node.js ✓
4. If you get an error, download Node.js from [nodejs.org](https://nodejs.org) (choose LTS version)

## Step 2: Install Cline CLI

In your terminal, run:

```bash
npm install -g cline
```

This installs the Cline CLI globally on your computer.

## Step 3: Verify Installation

Run:

```bash
cline --version
```

If you see a version number (like `1.0.0`), it worked!

## Step 4: Understand What You Just Installed

The CLI lets you:
- Run Cline from the terminal: `cline "build a login page"`
- Automate tasks in scripts
- Process files with pipes: `cat README.md | cline "summarize this"`
- Use headless mode for automation

You'll explore these in Level 3. For now, just know it exists.

## What's Next?

> **Next:** [Setup OpenRouter →](03-setup-openrouter.md)

---

> 💡 **Troubleshooting:** If `npm install -g cline` fails, try:
> - Windows: Run your terminal as Administrator
> - Mac/Linux: Use `sudo npm install -g cline` (you'll need to enter your password)