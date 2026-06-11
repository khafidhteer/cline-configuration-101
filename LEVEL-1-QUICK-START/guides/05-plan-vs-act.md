# Guide 5: Plan vs Act — When to Use Each Mode

[⬅ Back to Level 1 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 5 minutes  
**Goal:** Understand when to use Plan mode and when to use Act mode

---

## The Analogy

Imagine you're building a house:

- **Plan mode** = Drawing the blueprints. You figure out room sizes, window placement, materials. No construction happens.
- **Act mode** = Actually building. You pour concrete, frame walls, install windows.

You wouldn't start building without a plan. And you wouldn't keep planning forever without building.

---

## Plan Mode

**What it does:** Cline can read files, search code, and discuss strategy — but **cannot modify files or run commands**.

Use Plan mode when:

| Scenario | Example |
|----------|---------|
| You're not sure how to approach a problem | "How should I structure my database?" |
| You want to explore a codebase | "What does this app do?" |
| You need architectural advice | "Should I use React or Vue?" |
| You want to estimate effort | "How long would it take to add auth?" |
| You're learning a new concept | "Explain how API authentication works" |

**How to start:**
1. Click the **Plan** toggle at the top of the Cline panel
2. Type your question
3. Cline will research and discuss without making changes

---

## Act Mode

**What it does:** Cline can read files, write code, run commands, and make changes.

Use Act mode when:

| Scenario | Example |
|----------|---------|
| You have a clear plan | "Now implement what we discussed" |
| You need code written | "Create a login form component" |
| You want to fix something | "Fix the navigation bug" |
| You need to refactor | "Split this file into smaller modules" |
| Quick, obvious tasks | "Add a missing import" |

**How to start:**
1. Click the **Act** toggle
2. Type your task
3. Cline will execute and ask for approvals

---

## The Typical Workflow

For most tasks, follow this pattern:

```
1. Start in PLAN mode
   └─ Describe what you want
   └─ Discuss approach, ask questions
   └─ Agree on a plan

2. Switch to ACT mode
   └─ Cline implements the plan
   └─ You approve changes
   └─ You review the result

3. Switch back to PLAN if needed
   └─ "Actually, I want a different approach"
```

## Example: Building a Feature

```
YOU (PLAN mode): "I want to add a contact form to my website"

CLINE: "I see you have a React app. I suggest:
  - A ContactForm component with name, email, message fields
  - Form validation using standard HTML5
  - Email sending via a free service like EmailJS
  - A confirmation message after submission
  Does this approach work for you?"

YOU: "Yes, but use a modal instead of a separate page"

CLINE: "Makes sense. I'll create:
  - ContactModal component
  - Open/close state management
  - Form with validation
  Should I proceed?"

YOU (switch to ACT mode): "Yes, implement it now"

CLINE: Creates the files, shows you the code, asks for approval
```

---

## Common Mistakes

| Mistake | Why It Happens | How to Fix |
|---------|---------------|------------|
| Starting in Act mode for complex tasks | You want results fast | Switch to Plan first — it saves time in the long run |
| Staying in Plan mode too long | Analysis paralysis | Once you have a direction, switch to Act and start building |
| Not clarifying requirements | Assumptions are wrong | Use Plan mode to ask Cline to clarify its understanding |
| Being too vague | Cline guesses wrong | Be specific: "Create a React component" vs "Make a thing" |

---

## Quick Decision Guide

```
Is the approach obvious?
  ├─ Yes → START IN ACT MODE
  │        Examples: fix a typo, add a simple component, change a color
  │
  └─ No → START IN PLAN MODE
           Examples: new feature, architecture change, refactoring
           
During Act mode, getting confused?
  └─ SWITCH BACK TO PLAN MODE
     Discuss, clarify, then switch back to Act
```

---

## Pro Tip: Use Different Models for Each Mode

In Cline settings, you can configure different models for Plan and Act:

- **Plan mode**: Use a cheaper model (DeepSeek, Haiku) since you're just discussing
- **Act mode**: Use a more capable model (Sonnet, GPT-4o) for writing code

This saves money! You're not paying Claude Opus rates just to chat about approaches.

[📖 Learn more about model orchestration →](../LEVEL-3-POWER-USER/guides/02-model-mix-and-match.md)

---

## What's Next?

> **Next:** [VS Code vs CLI →](06-vscode-vs-cli.md)