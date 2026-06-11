# 📂 How This Repository Works

[⬅ Back to Home](../GETTING-STARTED.md) | [📖 Full Roadmap](../ROADMAP.md)

---

## Repository Structure

```
cline-configuration-101/
│
├── GETTING-STARTED.md          ← Start here (hub page)
├── ROADMAP.md                  ← Full learning path with ASCII visual
├── README.md                   ← Overview, quick start, structure
├── STORY.md                    ← Why this repo exists
├── LICENSE                     ← MIT license
│
├── LEVEL-1-QUICK-START/        ← ~30 min: Get Cline working
│   ├── PLAN.md                 ← 6 action items with checklists
│   ├── guides/                 ← 6 guides (install VS Code, CLI, OpenRouter, first task, Plan vs Act, VS Code vs CLI)
│   └── configs/                ← OpenRouter config reference + .clineignore template
│
├── LEVEL-2-EFFICIENT/          ← ~2 hrs: Save money & time
│   ├── PLAN.md                 ← 8 action items with checklists
│   ├── guides/                 ← 8 guides (rules, checkpoints, auto-approve, context, memory, cost, subagents, CLI transition)
│   └── configs/                ← 3 sample .clinerules + 2 memory bank templates
│
├── LEVEL-3-POWER-USER/         ← ~4 hrs: Automate everything
│   ├── PLAN.md                 ← 7 action items with checklists
│   ├── guides/                 ← 7 guides (MCP, model orchestration, GitHub, CLI, connectors, scheduled agents, skills)
│   └── configs/                ← MCP server config, 3 model configs, 2 GitHub Actions workflows
│
├── LEVEL-4-SCALE-WITH-TEAM/    ← ~2 hrs: Prepare for growth
│   ├── PLAN.md                 ← 5 action items with checklists
│   └── guides/                 ← 5 guides (onboarding, remote config, observability, supply chain, enterprise)
│
├── CHEAT-SHEETS/               ← Quick references (4 files)
│   ├── CLI-commands.md         ← All CLI commands with examples
│   ├── model-pricing-comparison.md ← Cost comparison table
│   ├── config-file-locations.md← Where Cline stores files on disk
│   └── troubleshooting-quick-fix.md ← Common errors and fixes
│
└── APPENDIX/                   ← Reference material
    ├── glossary.md             ← Plain English definitions (30+ terms, linked to guides)
    └── how-this-repo-works.md  ← This file
```

**Total: 55+ files** across 4 levels, 4 cheat sheets, and 2 appendix pages.

---

## How to Navigate

### For Beginners (Never used Cline)
1. Read [STORY.md](../STORY.md) — understand the motivation
2. Go to [Level 1 Quick Start](../LEVEL-1-QUICK-START/PLAN.md) — get Cline working in 30 minutes
3. Follow the guides in order

### For Intermediate Users (Have used Cline but want to optimize)
1. Check [GETTING-STARTED.md](../GETTING-STARTED.md) — find the topic you need
2. Use the "I want to..." table to jump to the right guide
3. Focus on Level 2 (cost savings) and Level 3 (automation)

### For Advanced Users (Looking for specific configs)
1. Browse the [Cheat Sheets](../CHEAT-SHEETS/CLI-commands.md) for quick references
2. Check the [configs](../LEVEL-1-QUICK-START/configs/) for copy-paste configurations
3. Use [Glossary](../APPENDIX/glossary.md) for terminology — every term links to the guide that covers it

---

## What Each Level Actually Covers

| Level | Guides | Configs | Key Topics |
|-------|--------|---------|------------|
| 🟢 Level 1 | 6 | 2 | VS Code install, CLI install, OpenRouter setup, first task, Plan vs Act, VS Code vs CLI |
| 🟡 Level 2 | 8 | 5 | Rules (.clinerules), checkpoints, auto-approve, context hacks, memory bank, cost control, subagents, CLI transition |
| 🔴 Level 3 | 7 | 6 | MCP servers, model orchestration, GitHub Actions, CLI automation, Telegram/Slack connectors, scheduled agents, custom skills |
| ⚫ Level 4 | 5 | 0 | Team onboarding, remote config, OpenTelemetry, Bumblebee supply chain, SSO/RBAC enterprise |

---

## Guide Format

Every guide follows the same structure:

```
[⬅ Back to Level] [🏠 Home]          ← Navigation links at top
---
**Time:** X minutes
**Goal:** What you'll achieve
---
Step-by-step instructions with:
- Clear action items
- Code snippets (copy-paste ready)
- Troubleshooting notes
---
> **Next:** Link to the next guide
```

---

## Config Files

Config files are in `configs/` folders. They're copy-paste ready:

- **`.clineignore`** → Copy to your project root to reduce token usage by up to 75%
- **`.clinerules/`** → Copy to your project root to teach Cline your coding preferences (coding.md, testing.md, architecture.md)
- **Model configs** → Reference docs showing how to configure Haiku, Sonnet, and Opus
- **GitHub workflows** → Drop-in YAML for auto-reviewing PRs and analyzing issues
- **Memory Bank templates** → Starter files for project memory persistence
- **MCP server config** → JSON template for extending Cline with external tools

---

## The Learning Approach

| You learn by... | How this repo supports it |
|----------------|--------------------------|
| Reading | Guides explain concepts in plain English, no jargon |
| Doing | Each guide has hands-on steps with time estimates |
| Copying | Config files are ready to use — just paste into your project |
| Practicing | Every PLAN.md has a checklist of action items |
| Referencing | Cheat Sheets and Glossary (with guide links) are always accessible |

---

## Still Lost?

- Use the [Troubleshooting Quick Fix](../CHEAT-SHEETS/troubleshooting-quick-fix.md)
- Check the [Glossary](../APPENDIX/glossary.md) for unfamiliar terms — every definition links to the guide that teaches it
- Start from the beginning: [Level 1](../LEVEL-1-QUICK-START/PLAN.md)