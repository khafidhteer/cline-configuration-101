# 🔴 Level 3: Power User — Automate Everything

[⬅ Back to Home](../GETTING-STARTED.md) | [📖 Full Roadmap](../ROADMAP.md) | [⬅ Level 2](../LEVEL-2-EFFICIENT/PLAN.md) | [⚫ Level 4 Next →](../LEVEL-4-SCALE-WITH-TEAM/PLAN.md)

---

**Time Investment:** ~4 hours  
**Goal:** CI/CD pipelines, model orchestration, MCP tools, and CLI automation  
**Cost Strategy:** Multi-model optimization (Haiku for summaries → Sonnet for coding → Opus for architecture)

---

## Learning Objectives

By the end of this level, you will be able to:

- [ ] Set up MCP servers to extend Cline's capabilities
- [ ] Orchestrate multiple models for different task phases
- [ ] Automate GitHub PR reviews and issue analysis
- [ ] Write CLI scripts for headless automation
- [ ] Connect Cline to Telegram/Slack/Discord
- [ ] Schedule recurring agents (daily standups, health checks)
- [ ] Build custom skills for repetitive tasks

---

## Prerequisites

- ✅ Completed [Level 2: Efficient](../LEVEL-2-EFFICIENT/PLAN.md)
- ✅ Cline CLI installed (`npm install -g cline`)
- ✅ A GitHub repository you want to automate
- ✅ Basic familiarity with your terminal

---

## Action Items

### Guide 1: MCP Made Easy (30 min)
- [ ] Understand what MCP servers are (no coding needed)
- [ ] Install an MCP server from the marketplace
- [ ] Configure MCP in `.cline/mcp.json`
- [ ] Test Cline using the MCP server

📖 [MCP Made Easy →](guides/01-mcp-made-easy.md)

### Guide 2: Model Mix & Match (30 min)
- [ ] Create separate config directories for different models
  ```bash
  mkdir -p ~/.cline-haiku ~/.cline-sonnet ~/.cline-opus
  ```
- [ ] Configure each with a different model
- [ ] Build a pipeline: cheap model → summarize → expensive model → analyze
- [ ] Run parallel reviews with multiple models

📖 [Model Mix & Match →](guides/02-model-mix-and-match.md)

### Guide 3: GitHub Automation (45 min)
- [ ] Create a GitHub workflow for PR review
- [ ] Create a GitHub workflow for issue analysis
- [ ] Add secrets for your API key
- [ ] Test: open a PR and see Cline review it

📖 [GitHub Automation →](guides/03-github-automation.md)

### Guide 4: CLI Automation (30 min)
- [ ] Master headless mode: `cline --auto-approve true`
- [ ] Pipe content: `cat file | cline "do something"`
- [ ] Write your first automation script
- [ ] Set up `CLINE_COMMAND_PERMISSIONS` for safety

📖 [CLI Automation →](guides/04-cli-automation.md)

### Guide 5: Connectors (30 min)
- [ ] Create a Telegram bot via @BotFather
- [ ] Connect Cline to Telegram
- [ ] Send a message and get a response
- [ ] Secure the bot with user ID restrictions

📖 [Connectors →](guides/05-connectors.md)

### Guide 6: Scheduled Agents (20 min)
- [ ] Create a daily standup schedule
- [ ] Create a weekly dependency check
- [ ] Create a codebase health report schedule
- [ ] Test: trigger a schedule immediately

📖 [Scheduled Agents →](guides/06-scheduled-agents.md)

### Guide 7: Custom Skills (20 min)
- [ ] Create a skill directory with SKILL.md
- [ ] Write effective descriptions for auto-triggering
- [ ] Bundle supporting files (scripts, templates)
- [ ] Test: trigger the skill via slash command

📖 [Custom Skills →](guides/07-skills-custom.md)

---

## Verification Checklist

After completing this level, confirm you can:

- [ ] ✅ Cline can use MCP servers for external tools/data
- [ ] ✅ You have a model pipeline: cheap → expensive for complex tasks
- [ ] ✅ GitHub Actions auto-reviews PRs and analyzes issues
- [ ] ✅ You can write a bash script using Cline CLI
- [ ] ✅ You can chat with Cline via Telegram
- [ ] ✅ You have at least one scheduled task running
- [ ] ✅ You have a custom skill that auto-triggers

---

## Configs in This Level

| File | What It Does |
|------|-------------|
| `model-configs/haiku-config.json` | Cheap model config (~$0.80/1M) |
| `model-configs/sonnet-config.json` | Mid-tier model config (~$3.00/1M) |
| `model-configs/opus-config.json` | Premium model config (~$15.00/1M) |
| `github-workflows/pr-review.yml` | Auto-review PRs workflow |
| `github-workflows/issue-rca.yml` | Issue analysis workflow |
| `mcp-servers.json` | MCP server definitions |

---

## Key Takeaways

- ✅ Different models for different tasks = 10-100x cost savings
- ✅ MCP servers let Cline interact with your tools and data
- ✅ GitHub Actions + Cline = free AI code review
- ✅ Connectors let you chat with Cline from your phone
- ✅ Scheduled agents run while you sleep

---

## Next Steps

⬆️ [Level 4: Scale →](../LEVEL-4-SCALE-WITH-TEAM/PLAN.md)