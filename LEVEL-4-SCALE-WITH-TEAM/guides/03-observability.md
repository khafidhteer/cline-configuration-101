# Guide 3: Observability

[⬅ Back to Level 4 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 30 minutes  
**Goal:** Track usage and costs across your team

---

## What is Observability?

Observability means **seeing what's happening** with Cline across your team:
- Who's using which models?
- How much are we spending?
- Are there errors or issues?

---

## Option 1: OpenTelemetry (Advanced)

Cline supports exporting metrics to your own observability stack:

1. Set up an OTLP endpoint (Datadog, Grafana, New Relic, etc.)
2. Configure in Cline remote settings → OpenTelemetry
3. Export metrics: task counts, token usage, error rates, costs

**This is for teams with existing observability infrastructure.**

## Option 2: Prompt Storage (Compliance)

Back up all Cline conversations to cloud storage:

1. Configure in Cline remote settings → Prompt Storage
2. Choose AWS S3 or Cloudflare R2
3. Conversations are automatically backed up

**Useful for:**
- Audit trails
- Compliance requirements
- Analyzing how your team uses Cline

## Option 3: Built-in Cost Tracking

Every Cline task shows costs in the header. For team tracking:

- Ask team members to monitor their own task headers
- Set monthly budgets on OpenRouter
- Review usage in the OpenRouter dashboard

---

## When to Start

| Team Size | Recommended Approach |
|-----------|---------------------|
| 1 person (solo) | Just watch the task header |
| 2-5 people | Shared OpenRouter budget |
| 5+ people | OpenTelemetry + Prompt Storage |

[📖 Next: Supply Chain Security →](04-security-supply-chain.md)