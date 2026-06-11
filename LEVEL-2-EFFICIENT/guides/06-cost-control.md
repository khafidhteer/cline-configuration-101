# Guide 6: Cost Control

[⬅ Back to Level 2 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 15 minutes  
**Goal:** Understand and control your API spending

---

## Where to See Your Costs

Every task in Cline shows a **cost estimate** in the task header. It looks like:

```
Tokens: 2,500 in / 850 out | Cost: $0.0043
```

This updates after every API call so you can see spending in real-time.

---

## Step 1: Understand Your Costs

Cline charges per **token** (roughly = 1 word). The cost depends on:

1. **Model choice** — DeepSeek ($0.14/1M tokens) vs Opus ($15.00/1M tokens)
2. **Input tokens** — Your prompts + file context + conversation history
3. **Output tokens** — Cline's responses and code
4. **Cached tokens** — Repeated context costs less

[📊 Full pricing comparison →](../../CHEAT-SHEETS/model-pricing-comparison.md)

---

## Step 2: Set a Monthly Budget on OpenRouter

1. Go to [openrouter.ai/account](https://openrouter.ai/account)
2. Click **Spending Limits**
3. Set a monthly limit (e.g., $20/month)
4. OpenRouter will stop requests when you hit the limit

This is your **safety net** — you'll never be surprised by a big bill.

---

## Step 3: Use the Right Model for Each Task

| Task | Model | Cost per Task |
|------|-------|--------------|
| "Fix this typo" | DeepSeek ($0.14/1M) | ~$0.0001 |
| "Build a component" | DeepSeek or Sonnet | ~$0.001 - $0.02 |
| "Design database schema" | Sonnet ($3.00/1M) | ~$0.05 |
| "Architecture review" | Opus ($15.00/1M) | ~$0.50 |

**Switch models in VS Code:** Click the model dropdown → select a different model

**Switch models in CLI:** `cline -m deepseek/deepseek-chat "simple task"`

---

## Step 4: Reduce Input Tokens

The biggest cost driver is **input tokens** (everything Cline reads). Reduce them:

1. **Add .clineignore** → cuts project context by 75%
2. **Use /newtask** when conversations get long
3. **Scope tasks** — don't let one conversation grow forever
4. **Use @ mentions** to give Cline only the files it needs

---

## Budget Estimates

| Usage Level | Model | Monthly Cost |
|-------------|-------|-------------|
| Light (2 hrs/day) | DeepSeek | ~$1-2 |
| Moderate (4 hrs/day) | DeepSeek + Sonnet mix | ~$10-20 |
| Heavy (8 hrs/day) | Mixed models | ~$30-60 |
| Heavy with Opus | Mostly Opus | ~$200+ |

With DeepSeek as your daily driver, you can code for **~50 hours for $1**.

---

## Pro Tips

- **Use DeepSeek for 80% of tasks** — switch to Sonnet/Opus only for complex work
- **Monitor the task header** — if cost is higher than expected, check your model
- **Set a $20/month limit** on OpenRouter — adjust up if needed

[📖 Next: Subagents →](07-subagents-parallel.md)