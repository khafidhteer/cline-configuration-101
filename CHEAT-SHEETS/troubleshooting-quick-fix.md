# 🔧 Troubleshooting Quick Fix

[⬅ Back to Home](../GETTING-STARTED.md) | [📖 Full Roadmap](../ROADMAP.md)

---

> **Most problems have simple fixes.** Try these before asking for help.

---

## "Cline isn't responding"

| Symptom | Likely Cause | Fix |
|---------|-------------|-----|
| Cline panel is blank | Extension not loaded | Restart VS Code |
| "No response" after sending prompt | API key issue | Check [Setup OpenRouter](../LEVEL-1-QUICK-START/guides/03-setup-openrouter.md) |
| "Connection timeout" | Network issue | Check internet, VPN, proxy |
| Cursor shows loading but nothing happens | Model overloaded | Switch to a different model (try DeepSeek) |
| Error in bottom right corner | Extension error | Update Cline extension, restart VS Code |

## "Cost is too high"

| Likely Cause | Fix |
|-------------|-----|
| Using expensive models for simple tasks | Switch to `deepseek/deepseek-chat` (~$0.14/1M) |
| No .clineignore file | [Add .clineignore](../LEVEL-1-QUICK-START/configs/minimal.clineignore) to cut tokens by 75% |
| Long conversations filling context | Use `/newtask` or `/smol` to compress context |
| Reading entire project into context | Cline reads files automatically; use `.clineignore` to exclude |

## "Cline forgot what we were building"

| Likely Cause | Fix |
|-------------|-----|
| Context window full | Ask Cline to "update memory bank" then start a new task |
| New session, no memory | Set up [Memory Bank](../LEVEL-2-EFFICIENT/guides/05-memory-bank.md) |
| Long conversation with no summarization | Enable [Auto-Compact](../LEVEL-2-EFFICIENT/guides/04-context-window-hacks.md) |

## "Cline keeps asking for approval"

| Likely Cause | Fix |
|-------------|-----|
| Auto-approve not configured | [Set up Auto-Approve](../LEVEL-2-EFFICIENT/guides/03-auto-approve-smartly.md) for safe operations |
| Working outside project folder | Add the folder to your workspace |
| YOLO mode not enabled | Enable YOLO mode in settings (use with caution) |

## "Cline created files I don't want"

| Fix | How |
|-----|-----|
| Undo the last change | Use the **Restore** button next to the checkpoint in the chat |
| Go back to a specific point | Click **Restore Files & Task** to undo changes and conversation |
| Delete a file | Right-click the file in VS Code → Delete |

## "The CLI isn't working"

| Likely Cause | Fix |
|-------------|-----|
| CLI not installed | Run `npm install -g cline` |
| "command not found" | Node.js not installed — install from [nodejs.org](https://nodejs.org) |
| Permission error | Run terminal as Administrator (Windows) or use `sudo` (Mac/Linux) |
| Auth not configured | Run `cline auth` to set up your provider |

## "MCP server not connecting"

| Likely Cause | Fix |
|-------------|-----|
| Server URL wrong | Check the URL in `.cline/mcp.json` |
| API key missing | Add the required auth header |
| Firewall blocking | Check your network/firewall settings |

## Still Stuck?

1. Run `cline doctor` in the terminal — it checks common issues automatically
2. Check the [Cline Official Docs](https://docs.cline.bot)
3. Ask in the [Cline Discord](https://discord.gg/cline)

[📖 Glossary →](../APPENDIX/glossary.md)