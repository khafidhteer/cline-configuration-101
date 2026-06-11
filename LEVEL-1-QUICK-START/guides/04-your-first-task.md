# Guide 4: Your First Task with Cline

[⬅ Back to Level 1 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 5 minutes  
**Goal:** Give Cline your first task and understand what happens

---

## What You're About to Do

You'll ask Cline to create a simple landing page. This will show you:
1. How Cline thinks through a problem (Plan mode)
2. How Cline writes code (Act mode)
3. What the cost looks like
4. How to review Cline's work

---

## Step 1: Open Cline in VS Code

1. Click the Cline icon (🤖) in the left sidebar
2. You'll see a chat panel open on the right side
3. At the bottom, there's a text input — this is where you type your prompts

## Step 2: Start in Plan Mode

At the top of the Cline chat panel, you'll see a toggle: **Plan** | **Act**

1. Make sure **Plan** is selected
2. In the text input, type:

```
I want to build a simple landing page for my app called "TaskFlow" — a task management app. The page should have:
- A hero section with the app name and tagline
- A features section with 3 features
- A call-to-action button
- A footer with copyright

Can you plan this out for me?
```

3. Press Enter
4. Cline will think and respond with a plan

**What you'll see:** Cline might ask clarifying questions about design preferences, colors, or layout. This is the planning phase — no code is being written yet.

## Step 3: Switch to Act Mode

1. After Cline presents the plan, switch the toggle from **Plan** to **Act**
2. Cline will see the plan from the planning phase
3. Type:

```
Great plan. Now implement it. Create the HTML file and a basic CSS file.
```

4. Press Enter

**What you'll see:** Cline will:
- Create an HTML file (`index.html`)
- Create a CSS file (`styles.css`)
- Show you previews of the code
- Ask for approval before creating each file (unless you set up auto-approve)

## Step 4: Approve Changes

Cline will ask for your approval before:
1. Reading files
2. Writing files
3. Running commands

For each request:
- Click **Approve** to allow it
- Click **Reject** to skip it
- Or check **"Auto-approve this session"** to speed things up

> 💡 **Tip:** For now, review each change. In Level 2, you'll learn how to set up safe auto-approve rules.

## Step 5: Review the Result

After Cline finishes:
1. Look at the files it created (`index.html` and `styles.css`)
2. Click them in the file explorer to preview them
3. If you have the "Live Server" extension, right-click `index.html` → "Open with Live Server" to see it in a browser
4. If you want changes, tell Cline: "Make the button blue" or "Add a navbar"

## Step 6: Check the Cost

Look at the **task header** in the Cline panel. You'll see:
- **Tokens used** (how much text was processed)
- **Estimated cost** (what you'll be charged)

With DeepSeek, this entire task should cost **less than $0.01**.

---

## Understanding What Just Happened

| Step | What Cline Did | What You Did |
|------|---------------|--------------|
| Plan | Analyzed requirements, asked questions | Gave the task description |
| Act | Created files, wrote code | Approved changes |
| Review | Responded to feedback | Gave direction |

---

## Pro Tips

- **Be specific in your prompts**: "Create a landing page" is vague. "Create a landing page for a task management app called TaskFlow with a hero section, features grid, and CTA button" gives Cline clear direction.
- **You can correct Cline mid-task**: Just type "Stop, I want to change direction" — Cline will adjust.
- **Use @ mentions**: Type `@` followed by a filename to give Cline context from existing files.
- **Multiple files**: Cline can create, edit, and organize many files in one session.

---

## What's Next?

> **Next:** [Understand Plan vs Act →](05-plan-vs-act.md)

---

> 💡 **Troubleshooting:** If Cline isn't responding:
> - Check your API key is correct (see [Setup OpenRouter](03-setup-openrouter.md))
> - Check your internet connection
> - Restart VS Code