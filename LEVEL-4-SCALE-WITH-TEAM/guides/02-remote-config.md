# Guide 2: Remote Configuration

[⬅ Back to Level 4 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 30 minutes  
**Goal:** Centralize Cline settings across your team

---

## What is Remote Configuration?

Remote Configuration lets you **push settings to all team members** from a central dashboard. Instead of everyone configuring Cline individually, you set it once and it applies to everyone.

**When you need this:**
- You have 3+ developers using Cline
- You want everyone using the same models
- You need to control costs centrally

---

## How It Works

1. **Admin configures** settings at [app.cline.bot](https://app.cline.bot)
2. **Cline auto-syncs** when team members sign in
3. **Users can't override** locked settings

**What you can control:**
- Which AI providers are available
- Which models can be used
- Base URLs (for custom endpoints)
- Feature toggles (YOLO mode, MCP, etc.)

## Supported Providers

| Provider | Best For |
|----------|----------|
| OpenRouter | Most flexible, many models |
| Anthropic | Direct Claude access |
| OpenAI | Direct GPT access |
| AWS Bedrock | If you use AWS infrastructure |
| Google Vertex | If you use GCP |
| OpenAI Compatible | Self-hosted models (vLLM, etc.) |

---

## When to Start

For a solo founder: **not yet.** Remote config is for teams.

When you hire your first developer, share your `.clinerules/` and `.clineignore` via Git first. Move to remote config when you have 3+ people and need central control.

[📖 Next: Observability →](03-observability.md)