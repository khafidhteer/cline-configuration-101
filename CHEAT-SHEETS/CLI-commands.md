# 🖥️ CLI Commands Reference

[⬅ Back to Home](../GETTING-STARTED.md) | [📖 Full Roadmap](../ROADMAP.md)

---

> **When to use this:** You've installed the CLI (`npm install -g cline`) and want to run Cline from your terminal.

---

## Quick Start

```bash
# Run Cline in interactive mode (starts a chat in terminal)
cline

# Run Cline with a prompt (Act mode, auto-approved)
cline "build a login page"

# Run Cline in Plan mode
cline -p "how should I structure my database?"

# Show help
cline --help
```

---

## All Commands

| Command | What It Does | Example |
|---------|-------------|---------|
| `cline <prompt>` | Run a task | `cline "fix this bug"` |
| `cline --plan` | Plan mode | `cline -p "design auth system"` |
| `cline --tui` | Open terminal UI | `cline -i` |
| `cline auth` | Configure API provider | `cline auth` |
| `cline config` | Show current config | `cline config` |
| `cline history` | Show past sessions | `cline h` |
| `cline doctor` | Diagnose issues | `cline doctor` |
| `cline update` | Update Cline | `cline update` |
| `cline version` | Show version | `cline -V` |
| `cline mcp` | Manage MCP servers | `cline mcp` |
| `cline plugin` | Manage plugins | `cline plugin install ...` |
| `cline connect` | Connect to messaging | `cline connect telegram ...` |
| `cline schedule` | Manage scheduled tasks | `cline schedule list` |
| `cline hub` | Manage hub daemon | `cline hub start` |
| `cline kanban` | Launch kanban board | `cline kanban` |

---

## Auth & Provider Configuration

```bash
# Interactive auth setup
cline auth

# Auth with OpenRouter (one-liner)
cline auth --provider openrouter -k YOUR_API_KEY -m deepseek/deepseek-chat

# Auth with Anthropic directly
cline auth --provider anthropic -k YOUR_API_KEY -m claude-sonnet-4-20250514

# List saved providers
cline config
```

---

## Useful CLI Patterns

### Pipe content to Cline
```bash
# Summarize a file
cat README.md | cline "summarize this"

# Analyze git diff
git diff | cline "review these changes"

# Process error output
npm run build 2>&1 | cline "fix these build errors"
```

### Use different models
```bash
# Use a cheap model for simple tasks
cline -m deepseek/deepseek-chat "what's in this directory?"

# Use a powerful model for complex tasks
cline -m anthropic/claude-sonnet-4-6 "design the architecture"
```

### Headless mode (for automation/scripts)
```bash
# Auto-approve everything (use with caution)
cline --auto-approve true "run tests and fix failures"

# JSON output for parsing
cline --json "list all files and their sizes" | jq
```

### Work with directories
```bash
# Run in a specific directory
cline -c /path/to/project "analyze this codebase"

# Use custom config directory
cline --config ~/.cline-haiku "quick task"
```

---

## Environment Variables

| Variable | What It Does |
|----------|-------------|
| `CLINE_DATA_DIR` | Custom config directory |
| `CLINE_HUB_ADDRESS` | Override hub address |
| `CLINE_COMMAND_PERMISSIONS` | Restrict shell commands |

Example:
```bash
# Restrict Cline to safe commands only
export CLINE_COMMAND_PERMISSIONS='{"allow": ["npm *", "git *"], "deny": ["rm -rf *", "sudo *"]}'
```

---

## Cost-Saving Flags

```bash
# Set thinking level (uses fewer tokens)
cline --thinking low "summarize this file"

# Use a cheap model explicitly
cline -m deepseek/deepseek-chat "quick task"

# Set timeout (stop if takes too long)
cline -t 30 "complex task"  # 30 second timeout
```

---

## Pro Tips

1. **Pipe is your friend**: `cat file | cline "do something"` is faster than opening VS Code
2. **Use `--plan` first**: Always plan complex tasks before executing
3. **Auto-approve carefully**: Use `--auto-approve true` only for trusted scripts
4. **Different configs for different models**: `--config ~/.cline-haiku` vs `--config ~/.cline-opus`

[📖 Model Orchestration →](../LEVEL-3-POWER-USER/guides/02-model-mix-and-match.md)  
[📖 CLI Automation →](../LEVEL-3-POWER-USER/guides/04-cli-automation.md)