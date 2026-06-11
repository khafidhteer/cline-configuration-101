# 💰 Model Pricing Comparison

[⬅ Back to Home](../GETTING-STARTED.md) | [📊 Full Roadmap](../ROADMAP.md)

---

> **Use this table** to choose the right model for each task. Switch models often — use cheap ones for simple tasks, expensive ones only when you need them.

---

## OpenRouter Pricing (per 1 million tokens)

| Model | Input Cost | Output Cost | Speed | Best For |
|-------|-----------|-------------|-------|----------|
| `deepseek/deepseek-chat` | **$0.14** | $0.28 | Fast | 🏆 **Daily driver** |
| `minimax/minimax-m2.5` | **FREE** | **FREE** | Fast | Learning, testing |
| `google/gemini-2.0-flash` | $0.10 | $0.40 | Very Fast | Quick tasks |
| `deepseek/deepseek-r1` | $0.55 | $2.19 | Medium | Reasoning, analysis |
| `anthropic/claude-3.5-haiku` | $0.80 | $4.00 | Fast | Summaries, quick coding |
| `google/gemini-2.5-pro` | $1.30 | $5.20 | Medium | Long documents |
| `anthropic/claude-sonnet-4-6` | $3.00 | $15.00 | Medium | 🏆 **Best coding model** |
| `openai/gpt-4o` | $5.00 | $15.00 | Medium | Complex tasks |
| `openai/o1-mini` | $3.00 | $12.00 | Slow | Hard reasoning |
| `openai/o1-preview` | $15.00 | $60.00 | Slow | Complex reasoning |
| `anthropic/claude-opus-4-5` | $15.00 | $75.00 | Slow | Architecture, deep analysis |
| `openai/gpt-4.5` | $75.00 | $150.00 | Slow | Maximum capability |

---

## What This Means for You

### Daily Driver Strategy (Recommended)

| Task | Model | Cost per hour |
|------|-------|--------------|
| Simple coding, debugging | `deepseek/deepseek-chat` | ~$0.02 |
| Medium complexity | `anthropic/claude-sonnet-4-6` | ~$0.30 |
| Complex architecture | `anthropic/claude-opus-4-5` | ~$1.50 |

### Solo Founder Budget Estimates

| Usage Level | Model | Monthly Cost |
|-------------|-------|-------------|
| Light (2-3 hrs/day) | DeepSeek | ~$1-2/month |
| Moderate (4-6 hrs/day) | DeepSeek + Sonnet mix | ~$10-20/month |
| Heavy (8+ hrs/day) | Mixed models | ~$30-60/month |

---

## Cost Comparison: Real Task Examples

| Task | DeepSeek | Sonnet 4.6 | Opus 4.5 |
|------|---------|------------|----------|
| "Fix this CSS bug" | $0.0004 | $0.008 | $0.04 |
| "Build a login form" | $0.001 | $0.02 | $0.10 |
| "Design full auth system" | $0.005 | $0.10 | $0.50 |
| "Refactor entire codebase" | $0.02 | $0.40 | $2.00 |

---

## Pro Tips

1. **Use DeepSeek for daily work** — it's 100x cheaper than Opus and handles 80% of tasks
2. **Switch to Sonnet for complex code** — it writes better code than cheap models
3. **Use Opus only for architecture** — it's 500x more expensive than DeepSeek
4. **Free models are great for learning** — Minimax is free forever
5. **Set a monthly budget** on OpenRouter: Settings → Spending Limits

---

## How to Switch Models

**In VS Code:** Click the model dropdown in Cline panel → select a different model

**In CLI:**
```bash
cline -m deepseek/deepseek-chat "simple task"
cline -m anthropic/claude-sonnet-4-6 "complex task"
```

[📖 Model Orchestration Guide →](../LEVEL-3-POWER-USER/guides/02-model-mix-and-match.md)