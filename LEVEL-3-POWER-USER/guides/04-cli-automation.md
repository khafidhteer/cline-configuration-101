# Guide 4: CLI Automation

[⬅ Back to Level 3 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 30 minutes  
**Goal:** Write scripts that use Cline without you watching

---

## Headless Mode

Cline can run autonomously without a chat interface:

```bash
# Run a task, auto-approve everything, finish immediately
cline --auto-approve true "run tests and fix failures"
```

---

## Pipe Content to Cline

```bash
# Summarize a file
cat README.md | cline "summarize this in 3 bullet points"

# Analyze git diff
git diff | cline "review these changes for bugs"

# Process error output
npm run build 2>&1 | cline "fix these build errors and explain fixes"
```

---

## Write Your First Script

Create `daily-summary.sh`:

```bash
#!/bin/bash
# Daily standup summary script

echo "=== Yesterday's Changes ==="
git log --since="yesterday" --oneline

echo "=== AI Summary ==="
git log --since="yesterday" -p | cline --auto-approve true \
  "Summarize what was done yesterday in bullet points"

echo "=== Open PRs ==="
gh pr list --state open
```

Make it executable: `chmod +x daily-summary.sh`

Run it daily: `./daily-summary.sh`

---

## Safety: Restrict Command Permissions

To prevent Cline from running dangerous commands in scripts:

```bash
export CLINE_COMMAND_PERMISSIONS='{
  "allow": ["npm *", "git *", "gh *", "ls *", "cat *"],
  "deny": ["rm -rf *", "sudo *", "chmod *"]
}'
```

---

## Pro Tips

- Use `--json` flag for machine-readable output
- Use `--timeout` to prevent runaway tasks: `cline -t 60 "task"`
- Always test scripts with a cheap model first

[📖 Next: Connectors →](05-connectors.md)