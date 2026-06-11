# Guide 1: MCP Made Easy

[⬅ Back to Level 3 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 30 minutes  
**Goal:** Give Cline access to external tools and data via MCP servers

---

## What is MCP?

MCP (Model Context Protocol) lets Cline connect to **external tools and data sources**. Think of it as plugins for Cline.

**Without MCP:** Cline can only read files and run commands  
**With MCP:** Cline can query databases, access APIs, search documentation, and more

[📖 MCP Marketplace →](https://docs.cline.bot/mcp/mcp-marketplace)

---

## Step 1: Install an MCP Server

Cline provides an MCP Marketplace inside VS Code:

1. Open Cline panel
2. Click the **MCP Marketplace** tab (plug icon 🔌)
3. Browse available servers
4. Click **Install** on any server

**Good starter MCP servers:**
- **Filesystem** — safe file access
- **GitHub** — manage issues, PRs, repos
- **Web search** — search the internet

## Step 2: Configure MCP (Manual Method)

Create `.cline/mcp.json` in your project root:

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "."]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_TOKEN": "your_github_token"
      }
    }
  }
}
```

## Step 3: Test Your MCP Server

1. Start a new task
2. Tell Cline: "Use the filesystem MCP server to list my project"
3. Cline should use the MCP tool

## Step 4: Find More MCP Servers

- Browse the [MCP Marketplace](https://docs.cline.bot/mcp/mcp-marketplace)
- Search GitHub for `mcp-server`
- Popular ones: PostgreSQL, SQLite, Docker, Puppeteer, Slack

---

## Pro Tips

- Start with the **Filesystem** server — it's the simplest
- MCP servers require **your approval** for each use (unless auto-approved)
- Some MCP servers need API keys — store them in `.cline/mcp.json`

[📖 Next: Model Mix & Match →](02-model-mix-and-match.md)