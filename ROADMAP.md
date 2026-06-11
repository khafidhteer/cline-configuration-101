# 🗺️ Cline Configuration Roadmap

> Your complete learning path from zero to Cline mastery.

---

## Learning Path Visual

```
LEVEL 1 (30 min)     LEVEL 2 (2 hrs)      LEVEL 3 (4 hrs)      LEVEL 4 (2 hrs)
══════════════════   ══════════════════   ══════════════════   ══════════════════
                   
Install & Run ───→   Rules & Skills ──→   MCP Servers ──────→   Team Onboarding
                    │                    │                    │
OpenRouter ──────→   Checkpoints ─────→   Model Mix & Match →   Remote Config
                    │                    │                    │
First Task ──────→   Auto-Approve ────→   GitHub CI/CD ────→   Observability
                    │                    │                    │
Plan vs Act ─────→   Context Hacks ───→   CLI Automation ──→   Supply Chain Security
                    │                    │                    │
VS Code vs CLI ──→   Memory Bank ─────→   Connectors ──────→   Enterprise Features
                    │                    │
                    Cost Control ──────→   Scheduled Agents
                    │                    │
                    Subagents ─────────→   Custom Skills
```

---

## Level Details

### 🟢 Level 1: Quick Start — "Get Cline Working Today"
**Time Investment:** ~30 minutes  
**Goal:** Install Cline, configure OpenRouter, run your first task  
**Cost Strategy:** Start with cheap/free models  

| Step | Guide | What You'll Learn |
|------|-------|-------------------|
| 1 | [Install VS Code](LEVEL-1-QUICK-START/guides/01-install-vscode.md) | Install and set up VS Code for Cline |
| 2 | [Install CLI](LEVEL-1-QUICK-START/guides/02-install-cli.md) | Install the Cline CLI (optional for now) |
| 3 | [Setup OpenRouter](LEVEL-1-QUICK-START/guides/03-setup-openrouter.md) | Get your API key and configure Cline |
| 4 | [Your First Task](LEVEL-1-QUICK-START/guides/04-your-first-task.md) | Walkthrough: "Build a landing page" |
| 5 | [Plan vs Act](LEVEL-1-QUICK-START/guides/05-plan-vs-act.md) | When to use each mode |
| 6 | [VS Code vs CLI](LEVEL-1-QUICK-START/guides/06-vscode-vs-cli.md) | When to move from VS Code to CLI |

**Configs to copy:**
- [OpenRouter Config for VS Code](LEVEL-1-QUICK-START/configs/openrouter-config-vscode.md)
- [Minimal .clineignore](LEVEL-1-QUICK-START/configs/minimal.clineignore)

---

### 🟡 Level 2: Efficient — "Save Money & Time"
**Time Investment:** ~2 hours  
**Goal:** Master context management, rules, and memory for consistent results  
**Cost Strategy:** Smart model selection (cheap for simple, expensive for complex)

| Step | Guide | What You'll Learn |
|------|-------|-------------------|
| 1 | [Rules for Consistency](LEVEL-2-EFFICIENT/guides/01-rules-for-consistency.md) | Teach Cline your coding preferences |
| 2 | [Checkpoints Safety Net](LEVEL-2-EFFICIENT/guides/02-checkpoints-safety-net.md) | Experiment without fear of breaking things |
| 3 | [Auto-Approve Smartly](LEVEL-2-EFFICIENT/guides/03-auto-approve-smartly.md) | Speed up without losing control |
| 4 | [Context Window Hacks](LEVEL-2-EFFICIENT/guides/04-context-window-hacks.md) | Stop running out of context mid-task |
| 5 | [Memory Bank](LEVEL-2-EFFICIENT/guides/05-memory-bank.md) | Cline remembers your project across sessions |
| 6 | [Cost Control](LEVEL-2-EFFICIENT/guides/06-cost-control.md) | Track spending, choose the right model |
| 7 | [Subagents: Parallel Research](LEVEL-2-EFFICIENT/guides/07-subagents-parallel.md) | Research faster with parallel agents |
| 8 | [When to Move to CLI](LEVEL-2-EFFICIENT/guides/08-when-to-move-to-cli.md) | Milestone: your first CLI automation task |

**Configs to copy:**
- [Sample .clinerules](LEVEL-2-EFFICIENT/configs/sample.clinerules/)
- [Memory Bank Template](LEVEL-2-EFFICIENT/configs/memory-bank-template/)

---

### 🔴 Level 3: Power User — "Automate Everything"
**Time Investment:** ~4 hours  
**Goal:** CI/CD pipelines, model orchestration, MCP tools  
**Cost Strategy:** Multi-model optimization (Haiku for summaries → Sonnet for general → Opus for complex)

| Step | Guide | What You'll Learn |
|------|-------|-------------------|
| 1 | [MCP Made Easy](LEVEL-3-POWER-USER/guides/01-mcp-made-easy.md) | Extend Cline with MCP servers (no coding needed) |
| 2 | [Model Mix & Match](LEVEL-3-POWER-USER/guides/02-model-mix-and-match.md) | Use cheap models for simple tasks, expensive for complex |
| 3 | [GitHub Automation](LEVEL-3-POWER-USER/guides/03-github-automation.md) | Auto-review PRs, analyze issues |
| 4 | [CLI Automation](LEVEL-3-POWER-USER/guides/04-cli-automation.md) | Headless mode, bash scripts, CI/CD |
| 5 | [Connectors](LEVEL-3-POWER-USER/guides/05-connectors.md) | Chat with Cline via Telegram/Slack/Discord |
| 6 | [Scheduled Agents](LEVEL-3-POWER-USER/guides/06-scheduled-agents.md) | Daily standups, health checks, cron jobs |
| 7 | [Custom Skills](LEVEL-3-POWER-USER/guides/07-skills-custom.md) | Build your own Cline skills |

**Configs to copy:**
- [Model Configs](LEVEL-3-POWER-USER/configs/model-configs/)
- [GitHub Workflows](LEVEL-3-POWER-USER/configs/github-workflows/)
- [MCP Servers](LEVEL-3-POWER-USER/configs/mcp-servers.json)

---

### ⚫ Level 4: Scale — "Prepare for Growth"
**Time Investment:** ~2 hours  
**Goal:** Organization-wide deployment, security, observability  
**Cost Strategy:** BYO inference, centralized billing

| Step | Guide | What You'll Learn |
|------|-------|-------------------|
| 1 | [Onboarding a Team](LEVEL-4-SCALE-WITH-TEAM/guides/01-onboarding-team.md) | From solo to team setup |
| 2 | [Remote Configuration](LEVEL-4-SCALE-WITH-TEAM/guides/02-remote-config.md) | Control settings centrally |
| 3 | [Observability](LEVEL-4-SCALE-WITH-TEAM/guides/03-observability.md) | Track usage and costs across team |
| 4 | [Security & Supply Chain](LEVEL-4-SCALE-WITH-TEAM/guides/04-security-supply-chain.md) | Bumblebee scanning for vulnerabilities |
| 5 | [Enterprise Features](LEVEL-4-SCALE-WITH-TEAM/guides/05-enterprise-features.md) | SSO, RBAC (when you need them) |

---

## Quick Cost Reference

| Model | Provider | Input Cost (per 1M tokens) | Use For |
|-------|----------|---------------------------|---------|
| Claude Haiku | Anthropic | $0.80 | Summaries, simple tasks |
| DeepSeek Chat | DeepSeek | $0.14 | Cheap daily driver |
| Gemini 2.0 Flash | Google | Free tier | Experimentation |
| Claude Sonnet | Anthropic | $3.00 | General development |
| GPT-4o | OpenAI | $5.00 | Complex reasoning |
| Claude Opus | Anthropic | $15.00 | Architecture, deep analysis |

[📊 Full Pricing Comparison →](CHEAT-SHEETS/model-pricing-comparison.md)

---

> **Next step:** [Read my story →](STORY.md) or [Start Level 1 →](LEVEL-1-QUICK-START/PLAN.md)