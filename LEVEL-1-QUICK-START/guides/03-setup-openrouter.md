# Guide 3: Setup OpenRouter

[⬅ Back to Level 1 Plan](../PLAN.md) | [🏠 Home](../../GETTING-STARTED.md)

---

**Time:** 10 minutes  
**Goal:** Get an OpenRouter API key and configure Cline to use it

---

## What is OpenRouter?

OpenRouter is a service that gives you access to **100+ AI models** (Anthropic, OpenAI, Google, DeepSeek, etc.) through **one API key** and **one bill**.

Instead of creating separate accounts for each AI provider, you use OpenRouter for everything.

**Why OpenRouter for solo founders:**
- One API key to manage — not 5 separate ones
- Pay-as-you-go — no monthly commitments
- Free models available (Minimax, etc.)
- Cheaper than most direct APIs
- Can set spending limits

---

## Step 1: Create an OpenRouter Account

1. Go to [openrouter.ai](https://openrouter.ai)
2. Click **Sign Up** (top right corner)
3. Sign up with Google, GitHub, or email
4. Verify your email if needed

## Step 2: Add Credits (Optional — Free Models Available)

OpenRouter works on a credit system. You add money to your account, and it deducts per API call.

**But you can start with free models:**

1. After signing in, look for **"Free Models"** in the models list
2. Models like `minimax/minimax-m2.5` are completely free
3. You can test Cline without spending a cent

**When you're ready to add credits:**
1. Go to [openrouter.ai/account](https://openrouter.ai/account)
2. Click **Add Credits**
3. Start with $5–$10 — this will last a long time if you use cheap models

## Step 3: Generate an API Key

1. Go to [openrouter.ai/keys](https://openrouter.ai/keys)
2. Click **Create Key**
3. Give it a name like "cline-vscode"
4. Click **Create**
5. **Copy the key immediately** — you won't be able to see it again

> ⚠️ **Important:** Treat this key like a password. Never share it, never commit it to code.

## Step 4: Configure Cline in VS Code

1. Open VS Code
2. Click the Cline icon (🤖) in the left sidebar
3. You'll see a provider dropdown — click it
4. Scroll down and select **OpenRouter**
5. In the **API Key** field, paste your OpenRouter API key
6. In the **Model** field, enter: `deepseek/deepseek-chat` (cheap and good — ~$0.14 per million tokens)
7. Click **Save**

**If you don't see OpenRouter in the list:**
- Make sure you have the latest version of the Cline extension
- Restart VS Code
- Open the Cline panel again

## Step 5: Test the Connection

1. In the Cline chat panel, type: `Hello! What model are you using?`
2. Press Enter
3. Cline should respond with something like: "I'm using DeepSeek Chat via OpenRouter"
4. ✅ If you get a response, everything is working!

**If you get an error:**
- Check that your API key is correct
- Make sure you selected "OpenRouter" as the provider
- Verify the model name: try `deepseek/deepseek-chat`

---

## Good First Models

| Model | Cost (per 1M tokens) | Best For |
|-------|----------------------|----------|
| `deepseek/deepseek-chat` | ~$0.14 | Daily driver — cheap and capable |
| `anthropic/claude-3.5-haiku` | ~$0.80 | Fast responses, summaries |
| `minimax/minimax-m2.5` | **FREE** | Learning and testing |
| `google/gemini-2.0-flash` | **Free tier available** | Quick tasks |
| `anthropic/claude-sonnet-4-6` | ~$3.00 | Complex coding tasks |
| `openai/gpt-4o` | ~$5.00 | Hard problems, reasoning |

> 💡 **Save money:** Use `deepseek/deepseek-chat` for daily work. Switch to `claude-sonnet-4-6` or `gpt-4o` only when you have a complex task.

---

## How Much Does This Cost?

Cline charges per **token** (roughly = 1 word). Here's what a typical session costs with DeepSeek:

| Task | Input Tokens | Output Tokens | Approx Cost |
|------|-------------|--------------|-------------|
| "Fix this bug" | 2,000 | 500 | $0.00035 |
| "Build a login page" | 5,000 | 3,000 | $0.00112 |
| Full hour of coding | 100,000 | 50,000 | $0.021 |

With DeepSeek, you can code for **~50 hours for $1**.

---

## What's Next?

> **Next:** [Run Your First Task →](04-your-first-task.md)

---

> 🔒 **Security Tip:** Your API key is stored locally in VS Code's settings. It never leaves your machine. To remove it, go to Cline settings and clear the API Key field.