# 📁 Configuration File Locations

[⬅ Back to Home](../GETTING-STARTED.md) | [📖 Full Roadmap](../ROADMAP.md)

---

> **When to use this:** When you need to find where Cline stores its files on your computer.

---

## Quick Reference

| What | Location | Purpose |
|------|----------|---------|
| **Global config** | `~/.cline/` | Settings shared across all projects |
| **Project config** | `.cline/` (in your project) | Settings for a specific project |
| **VS Code settings** | VS Code settings UI | Provider, model, API key |
| **MCP servers** | `.cline/mcp.json` | MCP server definitions |
| **Session history** | `~/.cline/data/sessions/` | Past conversations |
| **Checkpoints** | Shadow Git in project | Undo/redo snapshots |

---

## Where Everything Lives

### 🏠 Home Directory (`~/.cline/`)

```
~/.cline/
  data/
    settings/
      providers.json           # API keys and provider configs
    sessions/                  # Session database (SQLite) - past chats
    logs/                      # Log files
    teams/                     # Team state (if using agent teams)
    db/                        # Other databases (cron, etc.)
  rules/                       # Global rules (applies to all projects)
  skills/                      # Global skills (applies to all projects)
  hooks/                       # Global lifecycle hooks
  plugins/                     # Global plugins
  agents/                      # Global agent definitions
  cron/                        # Global cron schedules
```

> **Windows path:** `C:\Users\YOUR_USERNAME\.cline\`

### 📂 Project Root (`.cline/`)

```
your-project/
  .cline/
    rules/                     # Project-specific rules
    skills/                    # Project-specific skills
    hooks/                     # Project-specific hooks
    agents/                    # Project-specific agents
    plugins/                   # Project-specific plugins
    mcp.json                   # MCP server definitions for this project
```

### 📄 Rules Files

```
your-project/
  .clinerules/                 # Project rules directory
    coding.md                  # Coding standards
    testing.md                 # Test requirements

~/.cline/rules/                # Global rules (macOS/Linux)
~/Documents/Cline/Rules/       # Global rules (alternative path)
```

### 📄 VS Code Extension Settings

Open VS Code:
1. Click the Cline icon (🤖) in the left sidebar
2. Click the gear icon (⚙️) to open settings
3. Or use `Ctrl + ,` to open VS Code settings, then search for "Cline"

---

## Important Notes

| Rule Type | How to Find It |
|-----------|---------------|
| Rules apply: Global + Project combined | Global is fallback, project takes precedence |
| .clineignore | Must be in your project root |
| Cline Rules priority | Workspace rules > Global rules |
| API key stored | In VS Code's secret storage (not in a file) |

---

## Cross-Reference

| Need This? | Go To |
|-----------|-------|
| Setup your first config | [OpenRouter Config](../LEVEL-1-QUICK-START/configs/openrouter-config-vscode.md) |
| Create Cline Rules | [Level 2: Rules Guide](../LEVEL-2-EFFICIENT/guides/01-rules-for-consistency.md) |
| Troubleshoot config issues | [Troubleshooting Quick Fix](troubleshooting-quick-fix.md) |