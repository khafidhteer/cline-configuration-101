# 📖 Glossary — Plain English Terms

[⬅ Back to Home](../GETTING-STARTED.md) | [📖 Full Roadmap](../ROADMAP.md)

---

> **Plain English explanations** of terms used in this repository. No jargon, no assumptions.

---

## A

**Act Mode**
One of Cline's two modes. In Act mode, Cline can modify files, run commands, and make changes. Use this when you have a clear plan and want Cline to execute it.
📖 Covered in: [Plan vs Act Guide](../LEVEL-1-QUICK-START/guides/05-plan-vs-act.md)

**API (Application Programming Interface)**
A way for programs to talk to each other. Cline uses APIs to communicate with AI models like Claude or GPT.

**API Key**
A secret password that lets Cline access an AI provider (like OpenRouter). Never share it or commit it to code.
📖 Covered in: [Setup OpenRouter Guide](../LEVEL-1-QUICK-START/guides/03-setup-openrouter.md)

**Auto-Approve**
A setting that lets Cline perform certain actions without asking you first. You control which actions are auto-approved (e.g., reads only, or reads + writes).
📖 Covered in: [Auto-Approve Guide](../LEVEL-2-EFFICIENT/guides/03-auto-approve-smartly.md)

**Auto-Compact**
A feature that automatically summarizes long conversations to free up context space. Cline does this when it's running out of room.
📖 Covered in: [Context Window Hacks Guide](../LEVEL-2-EFFICIENT/guides/04-context-window-hacks.md)

---

## B

**Bumblebee**
A supply chain security scanner that checks your installed packages for known vulnerabilities. You can automate it with scheduled Cline agents.
📖 Covered in: [Supply Chain Security Guide](../LEVEL-4-SCALE-WITH-TEAM/guides/04-security-supply-chain.md)

---

## C

**Checkpoint**
A snapshot of your project files. Cline saves a checkpoint after every change. You can restore to any checkpoint if something goes wrong.
📖 Covered in: [Checkpoints Guide](../LEVEL-2-EFFICIENT/guides/02-checkpoints-safety-net.md)

**CLI (Command Line Interface)**
The terminal/command prompt version of Cline. Instead of clicking buttons in VS Code, you type commands like `cline "do this"`.
📖 Covered in: [Install CLI Guide](../LEVEL-1-QUICK-START/guides/02-install-cli.md) | [VS Code vs CLI Guide](../LEVEL-1-QUICK-START/guides/06-vscode-vs-cli.md)

**Cline Rules**
Markdown files (`.clinerules/`) that tell Cline how you want things done. For example: "Always use TypeScript" or "Use camelCase for variables." You can create conditional rules that only apply in certain directories.
📖 Covered in: [Rules for Consistency Guide](../LEVEL-2-EFFICIENT/guides/01-rules-for-consistency.md)

**Connectors**
Tools that let you chat with Cline from other apps like Telegram, Slack, or Discord. You can send messages and get responses without being at your computer.
📖 Covered in: [Connectors Guide](../LEVEL-3-POWER-USER/guides/05-connectors.md)

**Context Window**
Cline's short-term memory. It can only remember a limited amount of conversation at a time. When full, older parts get compressed or forgotten. Use `/newtask` to start fresh, or `/smol` to summarize.
📖 Covered in: [Context Window Hacks Guide](../LEVEL-2-EFFICIENT/guides/04-context-window-hacks.md)

---

## D

**DeepSeek**
A cheap, capable AI model. Costs ~$0.14 per million tokens. Great as a daily driver for most tasks.
📖 Covered in: [Cost Control Guide](../LEVEL-2-EFFICIENT/guides/06-cost-control.md)

---

## G

**GitHub Actions**
Automation that runs in the cloud when events happen on GitHub (like a pull request). You can set up Cline to auto-review PRs or analyze issues.
📖 Covered in: [GitHub Automation Guide](../LEVEL-3-POWER-USER/guides/03-github-automation.md)

---

## H

**Headless Mode**
Running Cline without a user interface (no chatting, just execute and finish). Used for scripts and automation.
📖 Covered in: [CLI Automation Guide](../LEVEL-3-POWER-USER/guides/04-cli-automation.md)

**Hooks**
Scripts that run automatically at certain points (before/after Cline does something). Used for enforcing policies.
📖 Covered in: [Custom Skills Guide](../LEVEL-3-POWER-USER/guides/07-skills-custom.md)

---

## M

**MCP (Model Context Protocol)**
A way to give Cline access to external tools and data sources. For example, an MCP server could let Cline query your database or access your project management tool.
📖 Covered in: [MCP Made Easy Guide](../LEVEL-3-POWER-USER/guides/01-mcp-made-easy.md)

**Memory Bank**
A set of markdown files that Cline reads at the start of each session to remember your project. Like a project journal that Cline reads before starting work.
📖 Covered in: [Memory Bank Guide](../LEVEL-2-EFFICIENT/guides/05-memory-bank.md)

**Model**
The AI brain that powers Cline. Different models have different prices, speeds, and capabilities. Examples: DeepSeek Chat, Claude Sonnet, GPT-4o.
📖 Covered in: [Cost Control Guide](../LEVEL-2-EFFICIENT/guides/06-cost-control.md) | [Model Mix & Match Guide](../LEVEL-3-POWER-USER/guides/02-model-mix-and-match.md)

**Model Orchestration**
Using different models for different parts of a task. For example: use a cheap model for planning, a mid-tier model for coding, and an expensive model only for complex problems.
📖 Covered in: [Model Mix & Match Guide](../LEVEL-3-POWER-USER/guides/02-model-mix-and-match.md)

---

## O

**OpenRouter**
A service that gives you access to 100+ AI models through one API key and one bill. The recommended provider for solo founders.
📖 Covered in: [Setup OpenRouter Guide](../LEVEL-1-QUICK-START/guides/03-setup-openrouter.md)

**OpenTelemetry**
A standard for exporting metrics and logs from your tools to dashboards like Datadog or Grafana. Cline can export usage data to help you monitor costs.
📖 Covered in: [Observability Guide](../LEVEL-4-SCALE-WITH-TEAM/guides/03-observability.md)

---

## P

**Plan Mode**
One of Cline's two modes. In Plan mode, Cline can read files and discuss strategy but cannot make changes. Use this to plan before executing.
📖 Covered in: [Plan vs Act Guide](../LEVEL-1-QUICK-START/guides/05-plan-vs-act.md)

**Plugins**
Add-ons that extend Cline's functionality. You can install plugins from npm, GitHub repos, or local directories.
📖 Covered in: [cline-documentation.md](../cline-documentation.md)

**Prompt**
The message you send to Cline. A good prompt is specific and clear. Example: "Create a React component that shows a list of users" instead of "Make a thing."
📖 Covered in: [Your First Task Guide](../LEVEL-1-QUICK-START/guides/04-your-first-task.md)

**Provider**
The company that provides AI model access. Examples: OpenRouter, Anthropic (Claude), OpenAI (GPT).
📖 Covered in: [Setup OpenRouter Guide](../LEVEL-1-QUICK-START/guides/03-setup-openrouter.md)

---

## R

**Remote Configuration**
A way for admins to push Cline settings to all team members from a central dashboard. Users can't override locked settings.
📖 Covered in: [Remote Configuration Guide](../LEVEL-4-SCALE-WITH-TEAM/guides/02-remote-config.md)

---

## S

**Scheduled Agents**
Cline tasks that run automatically on a schedule (like cron). Useful for daily standups, health checks, and recurring reports.
📖 Covered in: [Scheduled Agents Guide](../LEVEL-3-POWER-USER/guides/06-scheduled-agents.md)

**Skills**
Modular instruction sets that extend Cline's capabilities. A deployment skill might know exactly how to deploy to AWS. Skills load on-demand to save context.
📖 Covered in: [Custom Skills Guide](../LEVEL-3-POWER-USER/guides/07-skills-custom.md)

**SSO (Single Sign-On)**
A way for companies to let employees log in using their work credentials (like Google Workspace or Okta). Part of Cline's enterprise features.
📖 Covered in: [Enterprise Features Guide](../LEVEL-4-SCALE-WITH-TEAM/guides/05-enterprise-features.md)

**Subagents**
Smaller AI agents that Cline can spawn to research things in parallel. They read files and report back, so Cline doesn't have to do everything sequentially.
📖 Covered in: [Subagents Guide](../LEVEL-2-EFFICIENT/guides/07-subagents-parallel.md)

**Supply Chain Security**
Protecting your project from malicious packages. Tools like Bumblebee scan your dependencies for known vulnerabilities.
📖 Covered in: [Supply Chain Security Guide](../LEVEL-4-SCALE-WITH-TEAM/guides/04-security-supply-chain.md)

---

## T

**Task**
A single conversation with Cline. Starts when you send a prompt, ends when you're done. Each task has its own context window.
📖 Covered in: [Your First Task Guide](../LEVEL-1-QUICK-START/guides/04-your-first-task.md)

**Token**
The basic unit that AI models measure. Roughly 1 token ≈ ¾ of a word. You're charged based on tokens used. 1 million tokens ≈ 750,000 words.
📖 Covered in: [Cost Control Guide](../LEVEL-2-EFFICIENT/guides/06-cost-control.md)

---

## Y

**YOLO Mode**
Extreme mode where Cline auto-approves everything — file changes, terminal commands, everything. Use with extreme caution.
📖 Covered in: [Auto-Approve Guide](../LEVEL-2-EFFICIENT/guides/03-auto-approve-smartly.md)

---

## More Resources

| Resource | Link |
|----------|------|
| Official Cline Docs | [docs.cline.bot](https://docs.cline.bot) |
| Cline Discord | [discord.gg/cline](https://discord.gg/cline) |
| OpenRouter | [openrouter.ai](https://openrouter.ai) |