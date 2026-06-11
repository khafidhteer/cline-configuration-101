# 📖 Glossary — Plain English Terms

[⬅ Back to Home](../GETTING-STARTED.md) | [📖 Full Roadmap](../ROADMAP.md)

---

> **Plain English explanations** of terms used in this repository. No jargon, no assumptions.

---

## A

**Act Mode**
One of Cline's two modes. In Act mode, Cline can modify files, run commands, and make changes. Use this when you have a clear plan and want Cline to execute it.
[📖 Learn more →](../LEVEL-1-QUICK-START/guides/05-plan-vs-act.md)

**API (Application Programming Interface)**
A way for programs to talk to each other. Cline uses APIs to communicate with AI models like Claude or GPT.

**API Key**
A secret password that lets Cline access an AI provider (like OpenRouter). Never share it or commit it to code.

**Auto-Approve**
A setting that lets Cline perform certain actions without asking you first. You control which actions are auto-approved.
[📖 Learn more →](../LEVEL-2-EFFICIENT/guides/03-auto-approve-smartly.md)

**Auto-Compact**
A feature that automatically summarizes long conversations to free up context space. Cline does this when it's running out of room.
[📖 Learn more →](../LEVEL-2-EFFICIENT/guides/04-context-window-hacks.md)

---

## C

**Checkpoint**
A snapshot of your project files. Cline saves a checkpoint after every change. You can restore to any checkpoint if something goes wrong.
[📖 Learn more →](../LEVEL-2-EFFICIENT/guides/02-checkpoints-safety-net.md)

**CLI (Command Line Interface)**
The terminal/command prompt version of Cline. Instead of clicking buttons in VS Code, you type commands like `cline "do this"`.
[📖 Learn more →](../LEVEL-1-QUICK-START/guides/02-install-cli.md)

**Cline Rules**
Markdown files (`.clinerules/`) that tell Cline how you want things done. For example: "Always use TypeScript" or "Use camelCase for variables."
[📖 Learn more →](../LEVEL-2-EFFICIENT/guides/01-rules-for-consistency.md)

**Context Window**
Cline's short-term memory. It can only remember a limited amount of conversation at a time. When full, older parts get compressed or forgotten.
[📖 Learn more →](../LEVEL-2-EFFICIENT/guides/04-context-window-hacks.md)

---

## D

**DeepSeek**
A cheap, capable AI model. Costs ~$0.14 per million tokens. Great as a daily driver for most tasks.

---

## H

**Headless Mode**
Running Cline without a user interface (no chatting, just execute and finish). Used for scripts and automation.

**Hooks**
Scripts that run automatically at certain points (before/after Cline does something). Used for enforcing policies.
[📖 Learn more →](../LEVEL-3-POWER-USER/guides/07-skills-custom.md)

---

## M

**MCP (Model Context Protocol)**
A way to give Cline access to external tools and data sources. For example, an MCP server could let Cline query your database or access your project management tool.
[📖 Learn more →](../LEVEL-3-POWER-USER/guides/01-mcp-made-easy.md)

**Memory Bank**
A set of markdown files that Cline reads at the start of each session to remember your project. Like a project journal that Cline reads before starting work.
[📖 Learn more →](../LEVEL-2-EFFICIENT/guides/05-memory-bank.md)

**Model**
The AI brain that powers Cline. Different models have different prices, speeds, and capabilities. Examples: DeepSeek Chat, Claude Sonnet, GPT-4o.

**Model Orchestration**
Using different models for different parts of a task. For example: use a cheap model for planning, a mid-tier model for coding, and an expensive model only for complex problems.
[📖 Learn more →](../LEVEL-3-POWER-USER/guides/02-model-mix-and-match.md)

---

## O

**OpenRouter**
A service that gives you access to 100+ AI models through one API key and one bill. The recommended provider for solo founders.
[📖 Learn more →](../LEVEL-1-QUICK-START/guides/03-setup-openrouter.md)

---

## P

**Plan Mode**
One of Cline's two modes. In Plan mode, Cline can read files and discuss strategy but cannot make changes. Use this to plan before executing.
[📖 Learn more →](../LEVEL-1-QUICK-START/guides/05-plan-vs-act.md)

**Prompt**
The message you send to Cline. A good prompt is specific and clear. Example: "Create a React component that shows a list of users" instead of "Make a thing."

**Provider**
The company that provides AI model access. Examples: OpenRouter, Anthropic (Claude), OpenAI (GPT).

---

## S

**Skills**
Modular instruction sets that extend Cline's capabilities. A deployment skill might know exactly how to deploy to AWS. Skills load on-demand to save context.
[📖 Learn more →](../LEVEL-3-POWER-USER/guides/07-skills-custom.md)

**Subagents**
Smaller AI agents that Cline can spawn to research things in parallel. They read files and report back, so Cline doesn't have to do everything sequentially.
[📖 Learn more →](../LEVEL-2-EFFICIENT/guides/07-subagents-parallel.md)

---

## T

**Task**
A single conversation with Cline. Starts when you send a prompt, ends when you're done. Each task has its own context window.

**Token**
The basic unit that AI models measure. Roughly 1 token = 1 word. You're charged based on tokens used. 1 million tokens ≈ 750,000 words.

---

## Y

**YOLO Mode**
Extreme mode where Cline auto-approves everything — file changes, terminal commands, everything. Use with extreme caution.
[📖 Learn more →](../LEVEL-2-EFFICIENT/guides/03-auto-approve-smartly.md)

---

## More Resources

| Resource | Link |
|----------|------|
| Official Cline Docs | [docs.cline.bot](https://docs.cline.bot) |
| Cline Discord | [discord.gg/cline](https://discord.gg/cline) |
| OpenRouter | [openrouter.ai](https://openrouter.ai) |