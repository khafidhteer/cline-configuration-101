# Guide 5: Connectors — Chat with Cline via Telegram

[⬅ Back to Level 3 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 30 minutes  
**Goal:** Chat with Cline from your phone via Telegram

---

## What Are Connectors?

Connectors let other platforms send messages to Cline. Each message creates or continues a session, and Cline's response goes back to that platform.

**Supported platforms:** Telegram, Slack, Discord, WhatsApp, Google Chat

---

## Step 1: Create a Telegram Bot

1. Open Telegram and search for **@BotFather**
2. Start a chat and send: `/newbot`
3. Follow the prompts:
   - Bot display name: `My Cline Bot`
   - Bot username: `yourname_cline_bot` (must end in `bot`)
4. BotFather gives you a **bot token** — save it

## Step 2: Connect Cline to Telegram

```bash
cline connect telegram -k YOUR_BOT_TOKEN --cwd /path/to/your/project
```

This starts a connector process. Keep it running in a terminal.

## Step 3: Chat with Your Bot

1. Open Telegram
2. Search for your bot's username
3. Send any message — Cline will respond

## Step 4: Secure Your Bot

By default, anyone who finds your bot can use it. Restrict it to yourself:

1. Get your Telegram user ID: message **@userinfobot** on Telegram
2. Restart the connector:

```bash
cline connect telegram -k YOUR_BOT_TOKEN \
  --allowed-user-id YOUR_USER_ID \
  --cwd /path/to/your/project
```

---

## Pro Tips

- Keep the connector running in a terminal (or use a process manager)
- The connector shares the same config as your VS Code setup
- You can run multiple connectors simultaneously (Telegram + Slack)

[📖 Next: Scheduled Agents →](06-scheduled-agents.md)