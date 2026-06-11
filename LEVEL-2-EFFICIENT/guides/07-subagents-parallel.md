# Guide 7: Subagents — Parallel Research

[⬅ Back to Level 2 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 10 minutes  
**Goal:** Use multiple agents to research different parts of your codebase at the same time

---

## What Are Subagents?

Subagents are **mini Cline agents** that Cline can spawn to explore your codebase in parallel. Instead of reading files one by one, Cline can send multiple subagents to investigate different areas simultaneously.

**Without subagents:** Cline reads files sequentially — slow for large codebases  
**With subagents:** Multiple agents research in parallel — much faster

---

## Step 1: Enable Subagents

Subagents are enabled by default. To verify:

1. Open Cline settings (gear icon)
2. Click **Features** → **Agent**
3. Ensure `use_subagents` is enabled

## Step 2: Try It

Start a new task and type something like:

```
Use subagents to explore how authentication works and where the database models are defined.
```

Cline will spawn subagents to investigate each area simultaneously. You'll see them running in the chat UI with their own token usage and costs.

## Step 3: When to Use Subagents

| Task | Without Subagents | With Subagents |
|------|------------------|----------------|
| "Understand this codebase" | Reads files one by one | Researches multiple areas simultaneously |
| "Find all API endpoints" | Searches sequentially | Searches routes, controllers, tests in parallel |
| "Debug a complex issue" | Investigates one theory at a time | Checks multiple potential causes at once |

## Limitations

Subagents are **read-only**. They can:
- Read files
- Search code
- List directories
- Run read-only commands (`ls`, `grep`, `git log`)

They cannot:
- Write files
- Use the browser
- Access MCP servers
- Spawn their own subagents

[📖 Next: When to Move to CLI →](08-when-to-move-to-cli.md)