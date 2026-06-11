# OpenRouter Configuration Reference

[⬅ Back to Level 1 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

## How to Configure OpenRouter in VS Code

1. Open VS Code
2. Click the Cline icon (🤖) in the left sidebar
3. Click the **provider dropdown** (below the chat input, shows the current model name)
4. Scroll down and select **OpenRouter**
5. Paste your API key from [openrouter.ai/keys](https://openrouter.ai/keys)
6. Enter the model: `deepseek/deepseek-chat`
7. Click **Save**

**That's it.** Cline stores this configuration internally in VS Code.

---

## Model Cheat Sheet

Copy-paste these into the model field:

| Model ID | Cost per 1M tokens | Best For |
|----------|-------------------|----------|
| `deepseek/deepseek-chat` | ~$0.14 | **Daily driver** — cheap and capable |
| `minimax/minimax-m2.5` | **FREE** | Learning and testing |
| `google/gemini-2.0-flash` | Free tier available | Quick tasks |
| `anthropic/claude-3.5-haiku` | ~$0.80 | Fast responses, summaries |
| `anthropic/claude-sonnet-4-6` | ~$3.00 | Complex coding tasks |
| `openai/gpt-4o` | ~$5.00 | Hard problems, reasoning |
| `anthropic/claude-opus-4-5` | ~$15.00 | Architecture, deep analysis |

---

## CLI Configuration

If you're using the CLI, configure OpenRouter with:

```bash
cline auth --provider openrouter -k YOUR_API_KEY -m deepseek/deepseek-chat
```

---

## Quick Switch Between Models

You don't need to re-configure. Just:
- **In VS Code**: Click the model name dropdown in Cline panel → Select a different model
- **In CLI**: `cline -m anthropic/claude-sonnet-4-6 "your task"`

[📖 More on model orchestration →](../../LEVEL-3-POWER-USER/guides/02-model-mix-and-match.md)