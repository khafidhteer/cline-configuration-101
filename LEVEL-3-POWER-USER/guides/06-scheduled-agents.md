# Guide 6: Scheduled Agents

[⬅ Back to Level 3 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 20 minutes  
**Goal:** Cline runs tasks automatically on a schedule

---

## What Are Scheduled Agents?

Cline can run tasks on a **cron schedule** — like a recurring alarm that triggers Cline to do something. It works when combined with connectors (Telegram, Slack, etc.) to deliver results.

**Examples:**
- Daily standup summary at 8 AM
- Weekly dependency check every Monday
- Codebase health report every Sunday

---

## Step 1: Set Up a Connector (Optional)

Scheduled agents can deliver results to Telegram/Slack. If you have a connector running, results go there automatically.

[📖 Connector Setup →](05-connectors.md)

## Step 2: Create a Schedule

```bash
cline schedule create "Daily standup" \
  --cron "0 8 * * MON-FRI" \
  --prompt "Summarize: 1) PRs merged yesterday, 2) PRs in review, 3) open issues" \
  --workspace /path/to/your/project
```

## Step 3: View and Manage Schedules

```bash
# List all schedules
cline schedule list

# See upcoming runs
cline schedule list

# Run a schedule immediately (for testing)
cline schedule trigger <schedule-id>

# Pause a schedule
cline schedule pause <schedule-id>

# Delete a schedule
cline schedule delete <schedule-id>
```

---

## Useful Schedule Examples

**Weekly dependency check:**
```bash
cline schedule create "Dependency check" \
  --cron "0 10 * * MON" \
  --prompt "Check for outdated npm packages with security vulnerabilities" \
  --workspace /path/to/your/project
```

**Codebase health report:**
```bash
cline schedule create "Code health" \
  --cron "0 6 * * MON" \
  --prompt "Analyze: 1) files with no tests, 2) TODO comments, 3) large functions" \
  --workspace /path/to/your/project
```

---

## Cron Expression Reference

| Expression | Schedule |
|-----------|----------|
| `0 8 * * *` | Every day at 8 AM |
| `0 9 * * 1-5` | Weekdays at 9 AM |
| `0 10 * * MON` | Every Monday at 10 AM |
| `0 0 1 * *` | First of every month |
| `*/30 * * * *` | Every 30 minutes |

---

## Pro Tips

- Test with `cline schedule trigger <id>` before waiting for cron
- Combine with Telegram connector to get results on your phone
- The hub must be running for schedules to work (it auto-starts)

[📖 Next: Custom Skills →](07-skills-custom.md)