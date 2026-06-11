# docs.cline.bot Documentation

> **Source**: [https://docs.cline.bot](https://docs.cline.bot)
> **Generated**: 2026-06-11 01:02 UTC
> **Pages**: 114
---

## Table of Contents

- [Home / Overview](#home-overview-0)
- [Home / Overview](#home-overview-1)
  - [Authentication](#authentication-2)
  - [Chat Completions](#chat-completions-3)
  - [Errors](#errors-4)
  - [Getting Started](#getting-started-5)
  - [Models](#models-6)
  - [Overview](#overview-7)
  - [Sdk Examples](#sdk-examples-8)
  - [Memory Bank](#memory-bank-9)
  - [Acp Editor Integrations](#acp-editor-integrations-10)
  - [Agent Teams](#agent-teams-11)
  - [Cli Reference](#cli-reference-12)
  - [Configuration](#configuration-13)
  - [Connectors](#connectors-14)
  - [Github Integration](#github-integration-15)
  - [Github Issue Rca](#github-issue-rca-16)
  - [Github Pr Review](#github-pr-review-17)
  - [Model Orchestration](#model-orchestration-18)
  - [Supply Chain Alerts](#supply-chain-alerts-19)
  - [Scheduling](#scheduling-20)
- [Cline Overview](#cline-overview-21)
  - [Checkpoints](#checkpoints-22)
  - [Plan And Act](#plan-and-act-23)
  - [Task Management](#task-management-24)
  - [Using Commands](#using-commands-25)
  - [Working With Files](#working-with-files-26)
  - [Cline Rules](#cline-rules-27)
  - [Clineignore](#clineignore-28)
  - [Hooks](#hooks-29)
  - [Plugins](#plugins-30)
  - [Skills](#skills-31)
  - [Api Reference](#api-reference-32)
  - [Mcp Marketplace](#mcp-marketplace-33)
  - [Yolo Mode](#yolo-mode-34)
  - [Admin Configuration](#admin-configuration-35)
  - [Member Configuration](#member-configuration-36)
  - [Admin Configuration](#admin-configuration-37)
  - [Member Configuration](#member-configuration-38)
  - [Admin Configuration](#admin-configuration-39)
  - [Member Configuration](#member-configuration-40)
  - [Admin Configuration](#admin-configuration-41)
  - [Member Configuration](#member-configuration-42)
  - [Admin Configuration](#admin-configuration-43)
  - [Member Configuration](#member-configuration-44)
  - [Overview](#overview-45)
  - [Opentelemetry](#opentelemetry-46)
  - [Opentelemetry Events](#opentelemetry-events-47)
  - [Opentelemetry Override](#opentelemetry-override-48)
  - [Overview](#overview-49)
  - [Prompt Storage](#prompt-storage-50)
  - [Telemetry](#telemetry-51)
  - [Onboarding](#onboarding-52)
  - [Overview](#overview-53)
  - [Sso Setup](#sso-setup-54)
  - [Managing Members](#managing-members-55)
  - [Auto Approve](#auto-approve-56)
  - [Auto Compact](#auto-compact-57)
  - [Jupyter Notebooks](#jupyter-notebooks-58)
  - [Multiroot Workspace](#multiroot-workspace-59)
  - [Subagents](#subagents-60)
  - [Yolo Mode](#yolo-mode-61)
  - [Authorizing With Cline](#authorizing-with-cline-62)
  - [Cline Provider](#cline-provider-63)
  - [Config](#config-64)
  - [Installing Cline](#installing-cline-65)
  - [Core Workflow](#core-workflow-66)
  - [Remote Access](#remote-access-67)
  - [Mcp Marketplace](#mcp-marketplace-68)
  - [Mcp Overview](#mcp-overview-69)
  - [Anthropic](#anthropic-70)
  - [Api Key](#api-key-71)
  - [Cli Profile](#cli-profile-72)
  - [Iam Credentials](#iam-credentials-73)
  - [Deepseek](#deepseek-74)
  - [Google Gemini](#google-gemini-75)
  - [Minimax](#minimax-76)
  - [Openai](#openai-77)
  - [Openai Compatible](#openai-compatible-78)
  - [Openrouter](#openrouter-79)
  - [Other 30 Plus Providers](#other-30-plus-providers-80)
  - [Qwen](#qwen-81)
  - [Zai](#zai-82)
  - [Overview](#overview-83)
  - [Hub Spoke](#hub-spoke-84)
  - [Overview](#overview-85)
  - [Clinecore](#clinecore-86)
  - [Events](#events-87)
  - [Examples](#examples-88)
  - [Building An Agent](#building-an-agent-89)
  - [Creating Custom Tools](#creating-custom-tools-90)
  - [Going To Production](#going-to-production-91)
  - [Multi Agent Teams](#multi-agent-teams-92)
  - [Permission Handling](#permission-handling-93)
  - [Scheduled Agents](#scheduled-agents-94)
  - [Writing Plugins](#writing-plugins-95)
  - [Model Providers](#model-providers-96)
  - [Overview](#overview-97)
  - [Plugin Examples](#plugin-examples-98)
  - [Plugin Install](#plugin-install-99)
  - [Plugins](#plugins-100)
  - [Agent](#agent-101)
  - [Cline Core](#cline-core-102)
  - [Events](#events-103)
  - [Gateway](#gateway-104)
  - [Tools Api](#tools-api-105)
  - [Types](#types-106)
  - [Tools](#tools-107)
  - [All Cline Tools](#all-cline-tools-108)
  - [Networking And Proxies](#networking-and-proxies-109)
  - [Cli Overview](#cli-overview-110)
  - [Ide](#ide-111)
  - [Kanban](#kanban-112)
  - [Tui](#tui-113)

---

## Home / Overview

*Source: [https://docs.cline.bot](https://docs.cline.bot)*

Welcome to the Cline documentation. Whether you’re just getting started or looking to unlock advanced capabilities, you’ll find everything you need here.

## [​](#what-is-cline) What is Cline?

Cline is an AI coding agent that lives in your editor and your terminal. It can read and write files, run terminal commands, use a browser, and help you build features through natural conversation. Every action requires your explicit approval. You’re always in control.

### [​](#agent-core-sdk) Agent Core (SDK)

The SDK is Cline’s agent core—use it to build your own applications, automations, and integrations. See SDK section for detailed functionality and architectural design of the Cline Agent.

## SDK

Build AI agents and integrations powered by the same core engine behind the CLI, Kanban, VS Code extension, and JetBrains plugin.`npm install @cline/sdk`

### [​](#applications) Applications

These are end-user applications built on top of Cline’s agent core:

## CLI

Run Cline in your terminal with interactive chat or fully headless automation for CI/CD and scripting.`npm i -g cline`

## Kanban

Run many agents in parallel from a web-based task board with per-card worktrees, auto-commit, and dependency chains.`npx kanban`

## VS Code Extension

AI coding assistant in your editor. Create files, run commands, browse the web, and use tools with human-in-the-loop approval.

## JetBrains Plugin

The same Cline experience in IntelliJ IDEA, PyCharm, WebStorm, GoLand, and the rest of the JetBrains family.

## [​](#other-ide-supports) Other IDE Supports

Cline works across all major editors: **VS Code**, **Cursor**, **Windsurf**, **JetBrains** (IntelliJ, PyCharm, WebStorm), **Antigravity**, and **Zed**, **Neovim** via ACP mode.

## [​](#enterprise-solutions) Enterprise Solutions

## Security & Governance

SSO, role-based access control, model and tool controls per team, and remote configuration.

## Observability

OpenTelemetry, Datadog, Grafana, Splunk integrations with real-time analytics.

## Team Management

Manage members, roles, and permissions across your organization.

## API Reference

Programmatic access to Cline’s enterprise features.

Was this page helpful?

YesNo

[Installing Cline](/getting-started/installing-cline)

⌘I

---

## Home / Overview

*Source: [https://docs.cline.bot/](https://docs.cline.bot/)*

Welcome to the Cline documentation. Whether you’re just getting started or looking to unlock advanced capabilities, you’ll find everything you need here.

## [​](#what-is-cline) What is Cline?

Cline is an AI coding agent that lives in your editor and your terminal. It can read and write files, run terminal commands, use a browser, and help you build features through natural conversation. Every action requires your explicit approval. You’re always in control.

### [​](#agent-core-sdk) Agent Core (SDK)

The SDK is Cline’s agent core—use it to build your own applications, automations, and integrations. See SDK section for detailed functionality and architectural design of the Cline Agent.

## SDK

Build AI agents and integrations powered by the same core engine behind the CLI, Kanban, VS Code extension, and JetBrains plugin.`npm install @cline/sdk`

### [​](#applications) Applications

These are end-user applications built on top of Cline’s agent core:

## CLI

Run Cline in your terminal with interactive chat or fully headless automation for CI/CD and scripting.`npm i -g cline`

## Kanban

Run many agents in parallel from a web-based task board with per-card worktrees, auto-commit, and dependency chains.`npx kanban`

## VS Code Extension

AI coding assistant in your editor. Create files, run commands, browse the web, and use tools with human-in-the-loop approval.

## JetBrains Plugin

The same Cline experience in IntelliJ IDEA, PyCharm, WebStorm, GoLand, and the rest of the JetBrains family.

## [​](#other-ide-supports) Other IDE Supports

Cline works across all major editors: **VS Code**, **Cursor**, **Windsurf**, **JetBrains** (IntelliJ, PyCharm, WebStorm), **Antigravity**, and **Zed**, **Neovim** via ACP mode.

## [​](#enterprise-solutions) Enterprise Solutions

## Security & Governance

SSO, role-based access control, model and tool controls per team, and remote configuration.

## Observability

OpenTelemetry, Datadog, Grafana, Splunk integrations with real-time analytics.

## Team Management

Manage members, roles, and permissions across your organization.

## API Reference

Programmatic access to Cline’s enterprise features.

Was this page helpful?

YesNo

[Installing Cline](/getting-started/installing-cline)

⌘I

---

## Authentication

*Source: [https://docs.cline.bot/api/authentication](https://docs.cline.bot/api/authentication)*

Every request to the Cline API requires authentication via a Bearer token in the `Authorization` header.

## [​](#authentication-methods) Authentication Methods

There are two ways to authenticate:

| Method | Use case | How to get it |
| --- | --- | --- |
| **API key** | Direct API calls, scripts, CI/CD | Create at [app.cline.bot](https://app.cline.bot) Settings > API Keys |
| **Account auth token** | Cline extension and CLI | Generated automatically when you sign in |

Both methods use the same header format:

```
Authorization: Bearer YOUR_TOKEN
```

## [​](#api-keys) API Keys

API keys are the recommended authentication method for programmatic access.

### [​](#creating-a-key) Creating a Key

1

Sign in

Go to [app.cline.bot](https://app.cline.bot) and sign in.

2

Open API Keys

Navigate to **Settings** > **API Keys**.

3

Create and copy

Create a new key. Copy it immediately as you will not be able to see it again.

### [​](#deleting-a-key) Deleting a Key

You can revoke an API key at any time from the same Settings > API Keys page. Deleted keys stop working immediately.
You can also manage keys programmatically through the [Enterprise API](/enterprise-solutions/api-reference#api-keys):

```
# List your keys
curl https://api.cline.bot/api/v1/api-keys \
  -H "Authorization: Bearer YOUR_TOKEN"

# Delete a key
curl -X DELETE https://api.cline.bot/api/v1/api-keys/KEY_ID \
  -H "Authorization: Bearer YOUR_TOKEN"
```

## [​](#account-auth-tokens) Account Auth Tokens

When you sign in to the Cline extension (VS Code, JetBrains) or CLI, an account auth token is generated and managed automatically. You do not need to handle these tokens manually.
The Cline CLI uses these tokens when you authenticate via:

```
# Interactive sign-in
cline auth

# Or quick setup with an API key
cline auth -p cline -k "YOUR_API_KEY" -m anthropic/claude-sonnet-4-6
```

See the [CLI Reference](/cli/cli-reference#cline-auth) for all auth options.

## [​](#security-best-practices) Security Best Practices

**Do:**

- Store API keys in environment variables or a secrets manager
- Use different keys for development and production
- Rotate keys periodically
- Delete keys you no longer use

**Do not:**

- Commit keys to version control
- Share keys in chat or email
- Embed keys in client-side code (browsers, mobile apps)
- Log keys in application output

### [​](#using-environment-variables) Using Environment Variables

```
# Set the key
export CLINE_API_KEY="your_api_key_here"

# Use it in requests
curl -X POST https://api.cline.bot/api/v1/chat/completions \
  -H "Authorization: Bearer $CLINE_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model": "anthropic/claude-sonnet-4-6", "messages": [{"role": "user", "content": "Hello"}]}'
```

### [​](#using-a-env-file) Using a .env File

```
# .env (add to .gitignore)
CLINE_API_KEY=your_api_key_here
```

```
import os
from openai import OpenAI

client = OpenAI(
    base_url="https://api.cline.bot/api/v1",
    api_key=os.environ["CLINE_API_KEY"],
)
```

## [​](#custom-headers) Custom Headers

The Cline API accepts optional headers for tracking and identification:

| Header | Description |
| --- | --- |
| `HTTP-Referer` | Your application’s URL. Helps with usage tracking. |
| `X-Title` | Your application’s name. Appears in usage logs. |
| `X-Task-ID` | A unique task identifier. Used internally by the Cline extension. |

## [​](#related) Related

## Getting Started

Create your first API key and make a request.

## Enterprise API Keys

Manage API keys programmatically.

Was this page helpful?

YesNo

[Getting Started](/api/getting-started)[Chat Completions](/api/chat-completions)

⌘I

---

## Chat Completions

*Source: [https://docs.cline.bot/api/chat-completions](https://docs.cline.bot/api/chat-completions)*

The Chat Completions endpoint generates model responses from a conversation. It follows the [OpenAI Chat Completions](https://platform.openai.com/docs/api-reference/chat/create) format.

## [​](#endpoint) Endpoint

```
POST https://api.cline.bot/api/v1/chat/completions
```

## [​](#request-headers) Request Headers

| Header | Required | Description |
| --- | --- | --- |
| `Authorization` | Yes | `Bearer YOUR_API_KEY` |
| `Content-Type` | Yes | `application/json` |
| `HTTP-Referer` | No | Your application URL (for usage tracking) |
| `X-Title` | No | Your application name (for usage logs) |

## [​](#request-body) Request Body

| Parameter | Type | Required | Default | Description |
| --- | --- | --- | --- | --- |
| `model` | string | Yes |  | Model ID in `provider/model` format. See [Models](/api/models). |
| `messages` | array | Yes |  | Conversation messages. Each has `role` (`system`, `user`, `assistant`) and `content`. |
| `stream` | boolean | No | `true` | Return the response as a stream of Server-Sent Events. |
| `tools` | array | No |  | Tool/function definitions in OpenAI format. |
| `temperature` | number | No | Model default | Sampling temperature (0.0 to 2.0). Lower values are more deterministic. |

### [​](#message-format) Message Format

Each message in the `messages` array has this structure:

```
{
  "role": "user",
  "content": "Your message here"
}
```

**Roles:**

| Role | Purpose |
| --- | --- |
| `system` | Sets the model’s behavior and persona. Place first in the array. |
| `user` | The human’s input. |
| `assistant` | Previous model responses (for multi-turn conversations). |

### [​](#multi-turn-conversation) Multi-Turn Conversation

Include previous messages to maintain context:

```
{
  "model": "anthropic/claude-sonnet-4-6",
  "messages": [
    {"role": "system", "content": "You are a helpful coding assistant."},
    {"role": "user", "content": "What is a closure in JavaScript?"},
    {"role": "assistant", "content": "A closure is a function that..."},
    {"role": "user", "content": "Can you show me an example?"}
  ]
}
```

## [​](#streaming-response) Streaming Response

When `stream: true` (the default), the response is a series of [Server-Sent Events](https://developer.mozilla.org/en-US/docs/Web/API/Server-Sent_Events):

```
data: {"id":"gen-abc123","choices":[{"delta":{"role":"assistant"},"index":0}],"model":"anthropic/claude-sonnet-4-6"}

data: {"id":"gen-abc123","choices":[{"delta":{"content":"The capital"},"index":0}],"model":"anthropic/claude-sonnet-4-6"}

data: {"id":"gen-abc123","choices":[{"delta":{"content":" of France"},"index":0}],"model":"anthropic/claude-sonnet-4-6"}

data: {"id":"gen-abc123","choices":[{"delta":{"content":" is Paris."},"index":0,"finish_reason":"stop"}],"model":"anthropic/claude-sonnet-4-6","usage":{"prompt_tokens":14,"completion_tokens":8,"cost":0.000066}}

data: [DONE]
```

Each `data:` line contains a JSON chunk. Key fields:

| Field | Description |
| --- | --- |
| `id` | Generation ID, consistent across all chunks |
| `choices[0].delta.content` | The new text in this chunk |
| `choices[0].delta.reasoning` | Reasoning/thinking content (for reasoning models) |
| `choices[0].finish_reason` | `stop` when complete, `error` on failure |
| `usage` | Token counts and cost (included in the final chunk) |

### [​](#usage-object) Usage Object

The final chunk includes token usage and cost:

```
{
  "usage": {
    "prompt_tokens": 25,
    "completion_tokens": 42,
    "prompt_tokens_details": {
      "cached_tokens": 0
    },
    "cost": 0.000315
  }
}
```

| Field | Description |
| --- | --- |
| `prompt_tokens` | Total input tokens |
| `completion_tokens` | Total output tokens |
| `prompt_tokens_details.cached_tokens` | Tokens served from cache (reduces cost) |
| `cost` | Total cost in USD for this request |

## [​](#non-streaming-response) Non-Streaming Response

When `stream: false`, the response is a single JSON object:

```
{
  "id": "gen-abc123",
  "model": "anthropic/claude-sonnet-4-6",
  "choices": [
    {
      "message": {
        "role": "assistant",
        "content": "The capital of France is Paris."
      },
      "finish_reason": "stop",
      "index": 0
    }
  ],
  "usage": {
    "prompt_tokens": 14,
    "completion_tokens": 8
  }
}
```

## [​](#tool-calling) Tool Calling

You can define tools that the model can call using the OpenAI function calling format:

```
{
  "model": "anthropic/claude-sonnet-4-6",
  "messages": [
    {"role": "user", "content": "What's the weather in San Francisco?"}
  ],
  "tools": [
    {
      "type": "function",
      "function": {
        "name": "get_weather",
        "description": "Get the current weather for a location",
        "parameters": {
          "type": "object",
          "properties": {
            "location": {
              "type": "string",
              "description": "City and state, e.g. San Francisco, CA"
            }
          },
          "required": ["location"]
        }
      }
    }
  ]
}
```

When the model decides to call a tool, the response includes a `tool_calls` array:

```
{
  "choices": [
    {
      "message": {
        "role": "assistant",
        "tool_calls": [
          {
            "id": "call_abc123",
            "type": "function",
            "function": {
              "name": "get_weather",
              "arguments": "{\"location\": \"San Francisco, CA\"}"
            }
          }
        ]
      },
      "finish_reason": "tool_calls"
    }
  ]
}
```

To continue the conversation after a tool call, include the tool result:

```
{
  "messages": [
    {"role": "user", "content": "What's the weather in San Francisco?"},
    {"role": "assistant", "tool_calls": [{"id": "call_abc123", "type": "function", "function": {"name": "get_weather", "arguments": "{\"location\": \"San Francisco, CA\"}"}}]},
    {"role": "tool", "tool_call_id": "call_abc123", "content": "{\"temperature\": 62, \"condition\": \"foggy\"}"},
  ]
}
```

## [​](#reasoning-models) Reasoning Models

Some models support extended thinking (reasoning). When using these models, the response may include reasoning content in the streaming delta:

```
{"choices":[{"delta":{"reasoning":"Let me think about this step by step..."}}]}
```

Reasoning tokens are separate from the main content and appear in the `delta.reasoning` field. Some providers return encrypted reasoning blocks via `delta.reasoning_details` that can be passed back in subsequent requests to preserve the reasoning trace.

Not all models support reasoning. See [Models](/api/models) for which models have reasoning capabilities.

## [​](#complete-example) Complete Example

```
curl -X POST https://api.cline.bot/api/v1/chat/completions \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "anthropic/claude-sonnet-4-6",
    "messages": [
      {"role": "system", "content": "You are a concise assistant. Answer in one sentence."},
      {"role": "user", "content": "Explain what an API is."}
    ],
    "stream": true
  }'
```

## [​](#related) Related

## Models

Browse available models and their capabilities.

## Errors

Handle errors and implement retry logic.

## SDK Examples

Use this endpoint from Python, Node.js, and more.

## Authentication

API key management and security practices.

Was this page helpful?

YesNo

[Authentication](/api/authentication)[Models](/api/models)

⌘I

---

## Errors

*Source: [https://docs.cline.bot/api/errors](https://docs.cline.bot/api/errors)*

The Cline API returns errors in a consistent JSON format. Understanding these errors helps you build reliable integrations.

## [​](#error-format) Error Format

All errors follow the OpenAI error format:

```
{
  "error": {
    "code": 401,
    "message": "Invalid API key",
    "metadata": {}
  }
}
```

| Field | Type | Description |
| --- | --- | --- |
| `code` | number/string | HTTP status code or error identifier |
| `message` | string | Human-readable description of the error |
| `metadata` | object | Additional context (provider details, request IDs) |

## [​](#error-codes) Error Codes

### [​](#http-errors) HTTP Errors

These are returned as the HTTP response status code and in the error body:

| Code | Name | Cause | What to do |
| --- | --- | --- | --- |
| `400` | Bad Request | Malformed request body, missing required fields | Check your JSON syntax and required parameters |
| `401` | Unauthorized | Invalid or missing API key | Verify your API key in the `Authorization` header |
| `402` | Payment Required | Insufficient credits | Add credits at [app.cline.bot](https://app.cline.bot) |
| `403` | Forbidden | Key does not have access to this resource | Check key permissions |
| `404` | Not Found | Invalid endpoint or model ID | Verify the URL and model ID format |
| `429` | Too Many Requests | Rate limit exceeded | Wait and retry with exponential backoff |
| `500` | Internal Server Error | Server-side issue | Retry after a short delay |
| `502` | Bad Gateway | Upstream provider error | Retry after a short delay |
| `503` | Service Unavailable | Service temporarily down | Retry after a short delay |

### [​](#mid-stream-errors) Mid-Stream Errors

When streaming, errors can occur after the response has started. These appear as a chunk with `finish_reason: "error"`:

```
{
  "choices": [
    {
      "finish_reason": "error",
      "error": {
        "code": "context_length_exceeded",
        "message": "The input exceeds the model's maximum context length."
      }
    }
  ]
}
```

Common mid-stream error codes:

| Code | Meaning |
| --- | --- |
| `context_length_exceeded` | Input tokens exceed the model’s context window |
| `content_filter` | Content was blocked by a safety filter |
| `rate_limit` | Rate limit hit during generation |
| `server_error` | Upstream provider failed during generation |

Mid-stream errors do not produce an HTTP error code (the connection was already 200 OK). Always check `finish_reason` in your streaming handler.

## [​](#retry-strategies) Retry Strategies

### [​](#exponential-backoff) Exponential Backoff

For transient errors (429, 500, 502, 503), retry with exponential backoff:

```
import time
import requests

def call_api_with_retry(payload, max_retries=3):
    for attempt in range(max_retries):
        response = requests.post(
            "https://api.cline.bot/api/v1/chat/completions",
            headers={
                "Authorization": "Bearer YOUR_API_KEY",
                "Content-Type": "application/json",
            },
            json=payload,
        )

        if response.status_code == 200:
            return response.json()

        if response.status_code in (429, 500, 502, 503):
            delay = (2 ** attempt) + 1
            print(f"Retrying in {delay}s (attempt {attempt + 1}/{max_retries})")
            time.sleep(delay)
            continue

        # Non-retryable error
        response.raise_for_status()

    raise Exception("Max retries exceeded")
```

### [​](#when-to-retry) When to Retry

| Error | Retry? | Strategy |
| --- | --- | --- |
| `401 Unauthorized` | No | Fix your API key |
| `402 Payment Required` | No | Add credits |
| `429 Too Many Requests` | Yes | Exponential backoff (start at 1s) |
| `500 Internal Server Error` | Yes | Retry once after 1s |
| `502 Bad Gateway` | Yes | Retry up to 3 times with backoff |
| `503 Service Unavailable` | Yes | Retry up to 3 times with backoff |
| Mid-stream `error` | Depends | Retry the full request for transient errors |

### [​](#rate-limits) Rate Limits

If you hit rate limits frequently:

- Add delays between requests
- Reduce the number of concurrent requests
- Contact support if you need higher limits

## [​](#debugging) Debugging

When reporting issues, include:

1. The **error code and message** from the response
2. The **model ID** you were using
3. The **request ID** (from the `x-request-id` response header, if available)
4. Whether the error was **immediate** (HTTP error) or **mid-stream** (finish\_reason error)

## [​](#related) Related

## Chat Completions

Endpoint reference with request and response schemas.

## Authentication

Verify your API key is configured correctly.

Was this page helpful?

YesNo

[Models](/api/models)[Code Examples](/api/sdk-examples)

⌘I

---

## Getting Started

*Source: [https://docs.cline.bot/api/getting-started](https://docs.cline.bot/api/getting-started)*

This guide walks you through creating an API key and making your first Chat Completions request.

## [​](#prerequisites) Prerequisites

- A Cline account at [app.cline.bot](https://app.cline.bot)
- `curl` or any HTTP client (Python, Node.js, etc.)

## [​](#create-an-api-key) Create an API Key

1

Sign in to app.cline.bot

Go to [app.cline.bot](https://app.cline.bot) and sign in with your account.

2

Navigate to API Keys

Open **Settings** and select **API Keys**.

3

Create a new key

Click **Create API Key**. Copy the key immediately. You will not be able to see it again after leaving this page.

Treat your API key like a password. Do not commit it to version control or share it publicly.

## [​](#make-your-first-request) Make Your First Request

Replace `YOUR_API_KEY` with the key you just created:

```
curl -X POST https://api.cline.bot/api/v1/chat/completions \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "anthropic/claude-sonnet-4-6",
    "messages": [
      {"role": "user", "content": "What is the capital of France?"}
    ],
    "stream": false
  }'
```

## [​](#verify-the-response) Verify the Response

You should get a JSON response like this:

```
{
  "id": "gen-abc123",
  "model": "anthropic/claude-sonnet-4-6",
  "choices": [
    {
      "message": {
        "role": "assistant",
        "content": "The capital of France is Paris."
      },
      "finish_reason": "stop",
      "index": 0
    }
  ],
  "usage": {
    "prompt_tokens": 14,
    "completion_tokens": 8
  }
}
```

The `choices[0].message.content` field contains the model’s reply. The `usage` field shows how many tokens were consumed.

## [​](#try-streaming) Try Streaming

For real-time output, set `stream: true`. The response arrives as Server-Sent Events:

```
curl -X POST https://api.cline.bot/api/v1/chat/completions \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "anthropic/claude-sonnet-4-6",
    "messages": [
      {"role": "user", "content": "Write a haiku about programming."}
    ],
    "stream": true
  }'
```

Each chunk arrives as a `data:` line. The stream ends with `data: [DONE]`.

## [​](#try-a-free-model) Try a Free Model

To test without spending credits, use one of the [free models](/api/models#free-models):

```
curl -X POST https://api.cline.bot/api/v1/chat/completions \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "minimax/minimax-m2.5",
    "messages": [
      {"role": "user", "content": "Hello! What can you help me with?"}
    ],
    "stream": false
  }'
```

## [​](#troubleshooting) Troubleshooting

| Problem | Solution |
| --- | --- |
| `401 Unauthorized` | Check that your API key is correct and included in the `Authorization` header |
| `402 Payment Required` | Your account has insufficient credits. Add credits at [app.cline.bot](https://app.cline.bot) |
| Empty response | Make sure `messages` is a non-empty array with at least one user message |
| Connection timeout | Verify your network can reach `api.cline.bot`. Check proxy settings if on a corporate network |

## [​](#next-steps) Next Steps

## Authentication

Learn about API keys, token scoping, and security practices.

## Chat Completions

Full endpoint reference with all parameters and options.

## Models

Browse available models and find the right one for your use case.

## SDK Examples

Use the API from Python, Node.js, or the Cline CLI.

Was this page helpful?

YesNo

[Overview](/api/overview)[Authentication](/api/authentication)

⌘I

---

## Models

*Source: [https://docs.cline.bot/api/models](https://docs.cline.bot/api/models)*

The Cline API gives you access to models from multiple providers through a single endpoint. Model IDs follow the `provider/model-name` format, the same convention used by [OpenRouter](https://openrouter.ai).

## [​](#model-id-format) Model ID Format

Every model is identified by a string in the format:

```
provider/model-name
```

For example:

- `anthropic/claude-sonnet-4-6` - Claude Sonnet 4.6 from Anthropic
- `openai/gpt-4o` - GPT-4o from OpenAI
- `google/gemini-2.5-pro` - Gemini 2.5 Pro from Google

Pass this string as the `model` parameter in your [Chat Completions](/api/chat-completions) request.
Example:

```
curl -X POST https://api.cline.bot/api/v1/chat/completions \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "minimax/minimax-m2.5",
    "messages": [{"role": "user", "content": "Hello!"}]
  }'
```

## [​](#reasoning-models) Reasoning Models

Some models support extended thinking, where the model reasons through a problem before responding. When using these models:

- Reasoning content appears in `delta.reasoning` during streaming
- Some providers return encrypted reasoning blocks in `delta.reasoning_details`
- Reasoning tokens are counted separately from output tokens

Models with reasoning support include most Claude, Gemini 2.5, and Grok 3 models. Check the model’s `supportsReasoning` capability in the model catalog.

## [​](#choosing-a-model) Choosing a Model

| If you need… | Consider |
| --- | --- |
| Best coding performance | `anthropic/claude-sonnet-4-6` |
| Long document analysis | `google/gemini-2.5-pro` (1M context) |
| Fast, cheap responses | `deepseek/deepseek-chat` |
| Free experimentation | `minimax/minimax-m2.5` |
| Multi-modal (text + images) | `openai/gpt-4o` or `anthropic/claude-sonnet-4-6` |
| Complex reasoning | Any model with reasoning support |

For setup and account flow details, see the [Cline provider guide](/getting-started/cline-provider).

## [​](#image-support) Image Support

Models that support images accept base64-encoded image content in the `messages` array:

```
{
  "model": "anthropic/claude-sonnet-4-6",
  "messages": [
    {
      "role": "user",
      "content": [
        {"type": "text", "text": "What's in this image?"},
        {"type": "image_url", "image_url": {"url": "data:image/png;base64,..."}}
      ]
    }
  ]
}
```

Not all models support images. Check the model’s `supportsImages` capability before sending image content.

## [​](#related) Related

## Chat Completions

Use these models in your API requests.

## Cline provider

Fastest setup path with built-in authentication and billing.

Was this page helpful?

YesNo

[Chat Completions](/api/chat-completions)[Errors](/api/errors)

⌘I

---

## Overview

*Source: [https://docs.cline.bot/api/overview](https://docs.cline.bot/api/overview)*

Welcome to the Cline API documentation. Use the same models that power the Cline extension and CLI from any language, framework, or tool that speaks the OpenAI format.

## [​](#what-is-the-cline-api) What is the Cline API?

The Cline API is an OpenAI-compatible Chat Completions endpoint. You authenticate once with a Cline API key and get access to models from Anthropic, OpenAI, Google, and more through a single base URL. No need to manage separate keys for each provider.

```
Your App  →  Cline API (api.cline.bot)  →  Anthropic / OpenAI / Google / etc.
```

## Getting Started

Create an API key and make your first request in under a minute.

## Authentication

API keys, account tokens, key rotation, and security best practices.

## Chat Completions

Full endpoint reference with request schemas, streaming, and tool calling.

## Code Examples

Ready-to-copy examples for Python, Node.js, curl, and the Cline CLI.

## [​](#explore-the-reference) Explore the Reference

## Models

Browse available models, free tier options, reasoning support, and selection guidance.

## Errors

Error codes, mid-stream errors, retry strategies, and debugging tips.

## Enterprise API

Admin endpoints for managing users, organizations, billing, and API keys.

## [​](#quick-start) Quick Start

```
curl -X POST https://api.cline.bot/api/v1/chat/completions \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "anthropic/claude-sonnet-4-6",
    "messages": [{"role": "user", "content": "Hello!"}]
  }'
```

Get your API key at [app.cline.bot](https://app.cline.bot) (Settings > API Keys), then follow the [Getting Started](/api/getting-started) guide.

Was this page helpful?

YesNo

[Getting Started](/api/getting-started)

⌘I

---

## Sdk Examples

*Source: [https://docs.cline.bot/api/sdk-examples](https://docs.cline.bot/api/sdk-examples)*

The Cline API is OpenAI-compatible, so any library or tool that works with OpenAI also works with the Cline API. Just change the base URL and API key.

## [​](#curl) curl

### [​](#non-streaming) Non-Streaming

```
curl -X POST https://api.cline.bot/api/v1/chat/completions \
  -H "Authorization: Bearer $CLINE_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "anthropic/claude-sonnet-4-6",
    "messages": [{"role": "user", "content": "What is 2+2?"}],
    "stream": false
  }'
```

### [​](#streaming) Streaming

```
curl -X POST https://api.cline.bot/api/v1/chat/completions \
  -H "Authorization: Bearer $CLINE_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "anthropic/claude-sonnet-4-6",
    "messages": [{"role": "user", "content": "Write a short poem about code."}],
    "stream": true
  }'
```

## [​](#python) Python

### [​](#openai-sdk) OpenAI SDK

The [OpenAI Python SDK](https://github.com/openai/openai-python) works with the Cline API by setting `base_url`:

```
from openai import OpenAI

client = OpenAI(
    base_url="https://api.cline.bot/api/v1",
    api_key="YOUR_API_KEY",
)

# Non-streaming
response = client.chat.completions.create(
    model="anthropic/claude-sonnet-4-6",
    messages=[{"role": "user", "content": "Explain recursion in one sentence."}],
)
print(response.choices[0].message.content)
```

### [​](#streaming-in-python) Streaming in Python

```
from openai import OpenAI

client = OpenAI(
    base_url="https://api.cline.bot/api/v1",
    api_key="YOUR_API_KEY",
)

stream = client.chat.completions.create(
    model="anthropic/claude-sonnet-4-6",
    messages=[{"role": "user", "content": "Write a function to reverse a string in Python."}],
    stream=True,
)

for chunk in stream:
    content = chunk.choices[0].delta.content
    if content:
        print(content, end="", flush=True)
print()
```

### [​](#tool-calling-in-python) Tool Calling in Python

```
from openai import OpenAI
import json

client = OpenAI(
    base_url="https://api.cline.bot/api/v1",
    api_key="YOUR_API_KEY",
)

tools = [
    {
        "type": "function",
        "function": {
            "name": "get_weather",
            "description": "Get weather for a location",
            "parameters": {
                "type": "object",
                "properties": {
                    "location": {"type": "string", "description": "City name"}
                },
                "required": ["location"],
            },
        },
    }
]

response = client.chat.completions.create(
    model="anthropic/claude-sonnet-4-6",
    messages=[{"role": "user", "content": "What's the weather in Tokyo?"}],
    tools=tools,
)

# Check if the model wants to call a tool
choice = response.choices[0]
if choice.message.tool_calls:
    tool_call = choice.message.tool_calls[0]
    print(f"Tool: {tool_call.function.name}")
    print(f"Args: {tool_call.function.arguments}")
```

### [​](#using-requests) Using requests

If you prefer not to use the OpenAI SDK:

```
import requests

response = requests.post(
    "https://api.cline.bot/api/v1/chat/completions",
    headers={
        "Authorization": "Bearer YOUR_API_KEY",
        "Content-Type": "application/json",
    },
    json={
        "model": "anthropic/claude-sonnet-4-6",
        "messages": [{"role": "user", "content": "Hello!"}],
        "stream": False,
    },
)

data = response.json()
print(data["choices"][0]["message"]["content"])
```

## [​](#node-js-/-typescript) Node.js / TypeScript

### [​](#openai-sdk-2) OpenAI SDK

The [OpenAI Node.js SDK](https://github.com/openai/openai-node) works with the Cline API by setting `baseURL`:

```
import OpenAI from "openai"

const client = new OpenAI({
  baseURL: "https://api.cline.bot/api/v1",
  apiKey: "YOUR_API_KEY",
})

// Non-streaming
const response = await client.chat.completions.create({
  model: "anthropic/claude-sonnet-4-6",
  messages: [{ role: "user", content: "Explain async/await in one sentence." }],
})
console.log(response.choices[0].message.content)
```

### [​](#streaming-in-node-js) Streaming in Node.js

```
import OpenAI from "openai"

const client = new OpenAI({
  baseURL: "https://api.cline.bot/api/v1",
  apiKey: "YOUR_API_KEY",
})

const stream = await client.chat.completions.create({
  model: "anthropic/claude-sonnet-4-6",
  messages: [{ role: "user", content: "Write a haiku about TypeScript." }],
  stream: true,
})

for await (const chunk of stream) {
  const content = chunk.choices[0]?.delta?.content
  if (content) {
    process.stdout.write(content)
  }
}
console.log()
```

### [​](#using-fetch) Using fetch

```
const response = await fetch("https://api.cline.bot/api/v1/chat/completions", {
  method: "POST",
  headers: {
    Authorization: "Bearer YOUR_API_KEY",
    "Content-Type": "application/json",
  },
  body: JSON.stringify({
    model: "anthropic/claude-sonnet-4-6",
    messages: [{ role: "user", content: "Hello!" }],
    stream: false,
  }),
})

const data = await response.json()
console.log(data.choices[0].message.content)
```

## [​](#cline-cli) Cline CLI

The [Cline CLI](/cli/cli-reference) is the fastest way to use the Cline API from your terminal. It handles authentication, streaming, and tool execution for you.

### [​](#setup) Setup

```
# Install
npm install -g @anthropic-ai/cline

# Authenticate with a Cline API key
cline auth -p cline -k "YOUR_API_KEY" -m anthropic/claude-sonnet-4-6
```

### [​](#run-tasks) Run Tasks

```
# Simple prompt
cline "Explain what a REST API is."

# Pipe input
cat README.md | cline "Summarize this document."

# Use a specific model
cline -m google/gemini-2.5-pro "Analyze this codebase."

# YOLO mode for automation
cline -y "Run tests and fix failures."
```

See the [CLI Reference](/cli/cli-reference) for all commands and options.

## [​](#vs-code-/-jetbrains) VS Code / JetBrains

The Cline extension handles the API integration for you:

1. Open the Cline panel in your editor
2. Select **Cline** as the provider in the model picker
3. Sign in with your Cline account
4. Start chatting or give Cline a task

Your API key is managed automatically. No manual configuration needed.
For setup instructions, see [Installing Cline](/getting-started/installing-cline) and [Authorizing with Cline](/getting-started/authorizing-with-cline).

## [​](#related) Related

## Chat Completions

Full endpoint reference with all parameters.

## Authentication

API key management and security practices.

## Models

Browse available models.

## CLI Reference

Complete Cline CLI command reference.

Was this page helpful?

YesNo

[Errors](/api/errors)

⌘I

---

## Memory Bank

*Source: [https://docs.cline.bot/best-practices/memory-bank](https://docs.cline.bot/best-practices/memory-bank)*

Memory Bank is a documentation methodology that transforms Cline from a stateless assistant into a persistent development partner. Through structured markdown files, Cline can “remember” your project details across sessions.

## [​](#quick-setup) Quick Setup

1. Copy the [custom instructions below](#memory-bank-custom-instructions)
2. Add them to a [Cline Rules file](/customization/cline-rules), such as `.clinerules/memory-bank.md`
3. Ask Cline to “initialize memory bank”

## [​](#how-it-works) How It Works

Memory Bank files are regular markdown files in your project that both you and Cline can access. They’re organized hierarchically to build a complete picture of your project:

```
memory-bank/
├── projectbrief.md      # Foundation document
├── productContext.md    # Why this project exists
├── activeContext.md     # Current work focus
├── systemPatterns.md    # Architecture & patterns
├── techContext.md       # Tech stack & setup
└── progress.md          # Status & milestones
```

## [​](#core-files) Core Files

| File | Purpose |
| --- | --- |
| `projectbrief.md` | Foundation document with core requirements and goals |
| `productContext.md` | Why the project exists, problems it solves, UX goals |
| `activeContext.md` | Current focus, recent changes, next steps (updates most frequently) |
| `systemPatterns.md` | Architecture, design patterns, component relationships |
| `techContext.md` | Tech stack, setup, constraints, dependencies |
| `progress.md` | What works, what’s left, known issues |

## [​](#key-commands) Key Commands

- **“follow your custom instructions”** - Tells Cline to read Memory Bank and continue where you left off
- **“initialize memory bank”** - Creates the initial structure for a new project
- **“update memory bank”** - Triggers a full documentation review and update

These work alongside Cline’s built-in [slash commands](/core-workflows/using-commands). In particular, [`/newtask`](/core-workflows/using-commands#newtask) and [`/smol`](/core-workflows/using-commands#smol) help you manage context windows without losing progress.

## [​](#managing-context-windows) Managing Context Windows

Every AI model has a [context window](/core-workflows/task-management#context-window) that limits how much information it can process at once. As you work, this window fills with conversation history, file contents, and tool results. Memory Bank helps you preserve important knowledge when you need to free up space.

### [​](#manual-approach) Manual approach

When your context window fills up:

1. Ask Cline to “update memory bank” to document the current state
2. Start a new conversation
3. Ask Cline to “follow your custom instructions”

This preserves important context in your Memory Bank files before the window clears, letting you continue seamlessly in a fresh conversation.

## [​](#best-practices) Best Practices

- Start with a basic project brief and let structure evolve
- Let Cline help create the initial structure
- `activeContext.md` changes most frequently; update it after each session
- `progress.md` tracks milestones; review it when resuming work
- Update after significant milestones or direction changes
- Use [Cline Rules](/customization/cline-rules) to store the Memory Bank instructions per project

---

## [​](#memory-bank-custom-instructions) Memory Bank Custom Instructions

Copy this into a Cline Rules file (for example, `.clinerules/memory-bank.md`) or your global custom instructions:

```
# Cline's Memory Bank

I am Cline, an expert software engineer with a unique characteristic: my memory resets completely between sessions. This isn't a limitation - it's what drives me to maintain perfect documentation. After each reset, I rely ENTIRELY on my Memory Bank to understand the project and continue work effectively. I MUST read ALL memory bank files at the start of EVERY task - this is not optional.

## Memory Bank Structure

The Memory Bank consists of core files and optional context files, all in Markdown format. Files build upon each other in a clear hierarchy:

### Core Files (Required)
1. `projectbrief.md`
   - Foundation document that shapes all other files
   - Created at project start if it doesn't exist
   - Defines core requirements and goals
   - Source of truth for project scope

2. `productContext.md`
   - Why this project exists
   - Problems it solves
   - How it should work
   - User experience goals

3. `activeContext.md`
   - Current work focus
   - Recent changes
   - Next steps
   - Active decisions and considerations
   - Important patterns and preferences
   - Learnings and project insights

4. `systemPatterns.md`
   - System architecture
   - Key technical decisions
   - Design patterns in use
   - Component relationships
   - Critical implementation paths

5. `techContext.md`
   - Technologies used
   - Development setup
   - Technical constraints
   - Dependencies
   - Tool usage patterns

6. `progress.md`
   - What works
   - What's left to build
   - Current status
   - Known issues
   - Evolution of project decisions

### Additional Context
Create additional files/folders within memory-bank/ when they help organize:
- Complex feature documentation
- Integration specifications
- API documentation
- Testing strategies
- Deployment procedures

## Documentation Updates

Memory Bank updates occur when:
1. Discovering new project patterns
2. After implementing significant changes
3. When user requests with **update memory bank** (MUST review ALL files)
4. When context needs clarification

REMEMBER: After every memory reset, I begin completely fresh. The Memory Bank is my only link to previous work. It must be maintained with precision and clarity, as my effectiveness depends entirely on its accuracy.
```

## [​](#faq) FAQ

**Custom instructions or Cline Rules?**
Either works. Custom instructions apply globally across all projects. A [Cline Rules file](/customization/cline-rules) is project-specific and stored in your repo, which makes it easy to share with collaborators. You can also use [conditional rules](/customization/cline-rules#conditional-rules) to activate Memory Bank instructions only when working with `memory-bank/` files.
**How often should I update?**
After significant milestones or direction changes. For active development, every few sessions. You can also let [Auto Compact](/features/auto-compact) handle routine context management and reserve manual “update memory bank” for important checkpoints.
**Does this work with other AI tools?**
Yes. Memory Bank is a documentation methodology that works with any AI that can read docs. Commands may differ but the approach works across tools.
**Different from README files?**
Memory Bank provides structured, comprehensive documentation designed for AI context management, going beyond what a single README covers. It includes files for active context and progress tracking that change frequently, unlike a typical README.

Was this page helpful?

YesNo

[Subagents](/features/subagents)[Auto Approve](/features/auto-approve)

⌘I

---

## Acp Editor Integrations

*Source: [https://docs.cline.bot/cli/acp-editor-integrations](https://docs.cline.bot/cli/acp-editor-integrations)*

Cline CLI supports the [Agent Client Protocol (ACP)](https://agentclientprotocol.com/), an open standard that enables AI coding agents to work across different editors and IDEs. This means you can use the full Cline agent—with all its capabilities including Skills, Hooks, and MCP integrations—in your preferred development environment.

## [​](#why-acp) Why ACP?

- **Editor flexibility**: Use Cline in JetBrains, Neovim, Zed, or any ACP-compatible editor
- **No feature compromises**: Full access to Cline’s capabilities regardless of editor
- **Team consistency**: Same AI assistant across different developer workflows
- **Open standard**: Built on Zed’s open Agent Client Protocol specification

## [​](#jetbrains-ides) JetBrains IDEs

[JetBrains](https://www.jetbrains.com) IDEs include IntelliJ IDEA, PyCharm, WebStorm, and more. They offer built-in AI Assistant with ACP support.

**Recommended: Native JetBrains Plugin**For the best JetBrains experience, install the [native Cline plugin](/getting-started/installing-cline#jetbrains-ides) from the JetBrains Marketplace. It provides full IDE integration and the complete Cline experience.The ACP setup below is an alternative way to use Cline CLI features in JetBrains IDEs.

Alternatively, you can run Cline CLI in IntelliJ IDEA, PyCharm, WebStorm, and all other JetBrains IDEs through their built-in AI Assistant with ACP support.
[](https://storage.googleapis.com/cline_public_images/cline-acp-jetbrains.mp4)

### [​](#setup) Setup

1. **Install Cline CLI** (if not already installed):

   ```
   npm i -g cline
   ```
2. **Authenticate with Cline**:

   ```
   cline auth
   ```
3. **Configure JetBrains AI Assistant**:
   - Open your JetBrains IDE
   - Navigate to `Settings | Tools | AI Assistant | Agents`
   - Click “Add Custom Agent”
   - This opens/creates `~/.jetbrains/acp.json`
4. **Add Cline to `acp.json`**:

   ```
   {
     "agent_servers": {
       "Cline": {
         "command": "cline",
         "args": ["--acp"],
         "env": {}
       }
     }
   }
   ```
5. **Use Cline**:
   - Open the AI Chat tool window
   - Select “Cline” from the agent dropdown
   - Start coding with Cline in your JetBrains IDE!

JetBrains AI Assistant can expose its built-in MCP server to Cline, giving Cline access to IDE-specific tools and context.

## [​](#neovim) Neovim

[Neovim](https://neovim.io) is a hyperextensible Vim-based text editor loved by developers for its speed and flexibility. Use Cline in Neovim through the [agentic.nvim](https://github.com/carlos-algms/agentic.nvim) or [avante.nvim](https://github.com/yetone/avante.nvim) plugins, which provide ACP integration.
[](https://storage.googleapis.com/cline_public_images/cline-acp-neovim-avante.mp4)

### [​](#setup-with-agentic-nvim) Setup with agentic.nvim

1. **Install Cline CLI** (if not already installed):

   ```
   npm i -g cline
   ```
2. **Authenticate with Cline**:

   ```
   cline auth
   ```
3. **Install agentic.nvim** using lazy.nvim:

   ```
   {
     "carlos-algms/agentic.nvim",
     opts = {
       provider = "cline-acp",
       acp_providers = {
         ["cline-acp"] = {
           command = "cline",
           args = {"--acp"},
         },
       },
     },
     keys = {
       {"<C-\\>", function() require("agentic").toggle() end, mode={"n","v","i"}, desc="Toggle Cline Chat"},
     },
   }
   ```
4. **Use Cline**:
   - Press `<C-\>` to toggle Cline chat
   - Start coding with Cline in Neovim!

### [​](#setup-with-avante-nvim) Setup with avante.nvim

Follow the [avante.nvim documentation](https://github.com/yetone/avante.nvim) for configuring external ACP agents and point it to `cline --acp`.

## [​](#zed) Zed

[Zed](https://zed.dev) is a high-performance, multiplayer code editor built from the ground up for speed and collaboration. Zed’s team created the Agent Client Protocol, making Cline a natural fit for this editor.

### [​](#setup-2) Setup

1. **Install Cline CLI** (if not already installed):

   ```
   npm i -g cline
   ```
2. **Authenticate with Cline**:

   ```
   cline auth
   ```
3. **Configure Zed**:
   - Open Zed settings (`Cmd/Ctrl + ,`)
   - Add Cline to your `settings.json`:

   ```
   {
     "agent_servers": {
       "Cline": {
         "type": "custom",
         "command": "cline",
         "args": ["--acp"],
         "env": {}
       }
     }
   }
   ```
4. **Use Cline**:
   - Open the AI assistant panel
   - Select “Cline” from the agent dropdown
   - Start coding with Cline in Zed!

## [​](#other-editors) Other Editors

Any editor that supports the Agent Client Protocol can run Cline. Check your editor’s documentation for ACP configuration instructions, then point it to:

```
cline --acp
```

## [​](#troubleshooting) Troubleshooting

### [​](#agent-not-appearing) Agent not appearing

- Ensure Cline CLI is installed globally: `npm i -g cline`
- Verify authentication: `cline auth`
- Check that `cline --acp` runs without errors
- Restart your editor after configuration changes

### [​](#permission-errors) Permission errors

If Cline can’t access files or run commands:

- Check that your editor’s ACP integration passes the correct working directory
- Verify file permissions in your project
- Ensure Cline has approval settings configured correctly

### [​](#connection-issues) Connection issues

- Make sure no other Cline instance is using the same configuration directory
- Check editor logs for ACP-related errors
- Try running `cline --acp` manually to test the connection

## [​](#learn-more) Learn More

## CLI Overview

Learn about Cline CLI’s core capabilities and use cases.

## Headless Mode

Run Cline autonomously in scripts, CI/CD pipelines, and automated workflows.

## Skills

Understand how Cline’s Skills work across all editors via ACP.

## Hooks

Learn how to enforce policies with Hooks in any editor.

Was this page helpful?

YesNo

[Supply-Chain Scan Alerts](/cli/samples/supply-chain-alerts)[Overview](/usage/kanban)

⌘I

---

## Agent Teams

*Source: [https://docs.cline.bot/cli/agent-teams](https://docs.cline.bot/cli/agent-teams)*

This feature currently only applies to Cline SDK, CLI, and Kanban. This feature is not applicable on VSCode and JetBrains Extension for now.

Agent teams let you break complex work across multiple agents that coordinate through a shared task board. One agent acts as the coordinator, delegating subtasks to specialist agents.

## [​](#starting-a-team) Starting a Team

```
cline --team-name auth-sprint "Plan and implement user authentication with tests"
```

The `--team-name` flag enables team mode. The coordinator agent gets additional tools for spawning teammates and delegating tasks.

## [​](#resuming-team-work) Resuming Team Work

Team state persists across sessions. Resume where you left off:

```
cline --team-name auth-sprint "Continue with incomplete tasks"
```

## [​](#interactive-mode) Interactive Mode

In interactive mode, use the `/team` slash command:

```
/team Plan and implement a REST API with tests
```

## [​](#team-state) Team State

Team state is stored at `~/.cline/data/teams/[team-name]/` and includes:

- Task board with current tasks and status
- Inter-agent mailbox
- Mission log with activity history

## [​](#disabling-teams) Disabling Teams

Teams are enabled by default. Disable them with:

```
cline --no-teams "your prompt"
```

## [​](#sub-agents) Sub-Agents

For simpler delegation within a single session (no persistent state), use [sub-agents](/features/subagents). Sub-agents run in parallel for read-only research and return focused reports to the main agent.
See the [SDK Multi-Agent Teams guide](/sdk/guides/multi-agent-teams) for the programmatic API.

Was this page helpful?

YesNo

[Checkpoints](/core-workflows/checkpoints)[Subagents](/features/subagents)

⌘I

---

## Cli Reference

*Source: [https://docs.cline.bot/cli/cli-reference](https://docs.cline.bot/cli/cli-reference)*

```
cline --help           # Show all commands
cline <command> --help # Show help for a specific command
```

## [​](#synopsis) Synopsis

```
cline [options] [command] [prompt]
```

## [​](#help-menu-source-of-truth) Help Menu (Source of Truth)

```
Usage: cline [options] [command] [prompt]

Cline CLI - AI coding assistant in your terminal

Arguments:
  prompt                       Your prompt. Default to start in act mode with auto-approve enabled.

Options:
  -V, --version                Output the version number
  -p, --plan                   Run in plan mode
  --json                       Output messages as JSON instead of styled text
  --auto-approve <boolean>     Set tool auto-approval for all tools (default: true)
  -t, --timeout <seconds>      Optional timeout in seconds (default: 0 for no timeout)
  -m, --model <model-id>       Model to use for the session with the selected provider
  -v, --verbose                Show verbose output
  -c, --cwd <path>             Working directory
  --config <path>              Configuration directory (default: ~/.cline/data/settings)
  --data-dir <path>            Use isolated local state at this directory path (default: ~/.cline)
  --thinking <level>           Set reasoning effort level between none|low|medium|high|xhigh (default: medium)
  --retries <count>            Maximum consecutive mistakes (retries) before halting
  --hooks-dir <path>           Directory path to additional hooks for runtime hook injection (default: ~/.cline/hooks)
  --acp                        Run in Agent Client Protocol (ACP) mode for editor integration
  -i, --tui                    Open the terminal user interface (TUI) for interactive sessions
  --id <session-id>            Resume an existing session by ID
  -k, --key <api-key>          API key override for this run
  -P, --provider <id>          Provider id (default: cline)
  -s, --system <system-prompt> Override the default system prompt
  -z, --zen                    Start a session that runs in the background hub
  -h, --help                   display help for command

Commands:
  auth [options] [provider]    Authenticate a provider and configure what model is used
  config [options]             Show current configuration
  connect [options] [adapter]  Connect to an editor or IDE adapter
  mcp                          Manage MCP servers
  dev                          Developer tools and utilities
  doctor                       Diagnose and fix configuration issues
  history|h [options]          List session history or manage saved sessions
  hook                         Handle a hook payload from stdin
  plugin                       Manage Cline Plugins
  schedule                     Manage scheduled tasks
  hub                          Manage the local hub daemon
  update [options]             Check for updates and install if available
  version                      Show Cline CLI version number
  kanban                       Launch the kanban app and exit
```

## [​](#global-options) Global Options

| Option | Description |
| --- | --- |
| `-V, --version` | Output the version number |
| `-p, --plan` | Run in plan mode |
| `--json` | Output messages as JSON instead of styled text |
| `--auto-approve <boolean>` | Set tool auto-approval for all tools (default: `true`) |
| `-t, --timeout <seconds>` | Optional timeout in seconds (default: `0` for no timeout) |
| `-m, --model <model-id>` | Model to use for the session with the selected provider |
| `-v, --verbose` | Show verbose output |
| `-c, --cwd <path>` | Working directory |
| `--config <path>` | Configuration directory (default: `~/.cline/data/settings`) |
| `--data-dir <path>` | Use isolated local state at this directory path (default: `~/.cline`) |
| `--thinking <level>` | Set reasoning effort: `none|low|medium|high|xhigh` (default `medium`) |
| `--retries <count>` | Maximum consecutive mistakes (retries) before halting |
| `--hooks-dir <path>` | Directory path to additional hooks for runtime hook injection (default: `~/.cline/hooks`) |
| `--acp` | Run in Agent Client Protocol (ACP) mode for editor integration |
| `-i, --tui` | Open the terminal user interface (TUI) for interactive sessions |
| `--id <session-id>` | Resume an existing session by ID |
| `-k, --key <api-key>` | API key override for this run |
| `-P, --provider <id>` | Provider id (default: `cline`) |
| `-s, --system <system-prompt>` | Override the default system prompt |
| `-z, --zen` | Start a session that runs in the background hub |
| `-h, --help` | Display help for command |

## [​](#commands) Commands

### [​](#cline-default) `cline` (default)

Start a task or enter interactive mode.

```
cline
cline "your prompt here"
cline "Run tests and fix failures"
echo "prompt" | cline
```

### [​](#auth-options-provider) `auth [options] [provider]`

Configure authentication with an AI provider.

```
cline auth
```

### [​](#config-options) `config [options]`

Show current configuration.

```
cline config
```

### [​](#connect-options-adapter) `connect [options] [adapter]`

Connect to messaging platforms. See [Connectors](/cli/connectors).

```
cline connect
cline connect [adapter]
```

### [​](#mcp) `mcp`

Manage MCP servers. See [MCP](/mcp/mcp-overview).

```
cline mcp
```

### [​](#dev) `dev`

Developer tools and utilities.

```
cline dev
```

### [​](#doctor) `doctor`

Diagnose and fix configuration issues.

```
cline doctor
```

### [​](#history|h-options) `history|h [options]`

List session history or manage saved sessions.

```
cline history
cline h
```

### [​](#hook) `hook`

Handle a hook payload from stdin.

```
cat payload.json | cline hook
```

### [​](#plugin) `plugin`

Manage Cline plugins. Install plugins from file URLs, npm, git repositories, or local paths. See [Plugins](/customization/plugins) for full details and the plugin manifest format.

```
cline plugin install <source>  # Install a plugin
cline plugin i <source>        # Shorthand alias
```

| Option | Description |
| --- | --- |
| `--npm` | Treat source as an npm package |
| `--git` | Treat source as a git repository |
| `--force` | Replace an existing install for the same source |
| `--json` | Output result as JSON |
| `--cwd <path>` | Install to `<path>/.cline/plugins` instead of the global directory |

Try it with the [TypeScript Navigation Plugin](https://github.com/cline/typescript-lsp-plugin):

```
cline plugin install https://github.com/cline/typescript-lsp-plugin.git
```

### [​](#schedule) `schedule`

Manage scheduled agents. See [Scheduling](/cli/scheduling).

```
cline schedule
```

### [​](#hub) `hub`

Manage the local hub daemon.

```
cline hub
```

### [​](#update-options) `update [options]`

Check for updates and install if available.

```
cline update
```

### [​](#version) `version`

Show Cline CLI version number.

```
cline version
cline -V
```

### [​](#kanban) `kanban`

Launch the kanban app and exit.

```
cline kanban
```

## [​](#environment-variables) Environment Variables

| Variable | Description |
| --- | --- |
| `CLINE_DATA_DIR` | Custom configuration directory (replaces `~/.cline/data/`) |
| `CLINE_HUB_ADDRESS` | Override hub address (default: `127.0.0.1:25463`) |
| `CLINE_SESSION_BACKEND_MODE` | Force backend mode (`local`, `hub`, `remote`, `auto`) |
| `CLINE_SANDBOX_DATA_DIR` | Sandbox session storage directory |
| `CLINE_SANDBOX` | Enable sandbox mode |
| `CLINE_HOOKS_DIR` | Additional hooks directory |
| `CLINE_BUILD_ENV` | Set to `development` for debug features |
| `CLINE_DEBUG_PORT_BASE` | Base port for Node.js inspector |
| `CLINE_COMMAND_PERMISSIONS` | JSON policy restricting shell commands (see below) |

### [​](#cline_command_permissions) CLINE\_COMMAND\_PERMISSIONS

Restrict which shell commands the agent can execute:

```
export CLINE_COMMAND_PERMISSIONS='{"allow": ["npm *", "git *"], "deny": ["rm -rf *", "sudo *"]}'
```

| Field | Type | Description |
| --- | --- | --- |
| `allow` | `string[]` | Glob patterns for allowed commands. If set, only matching commands are permitted. |
| `deny` | `string[]` | Glob patterns for denied commands. Deny rules always take precedence. |
| `allowRedirects` | `boolean` | Whether to allow shell redirects (`>`, `>>`, `<`). Default: `false`. |

## [​](#json-output-format) JSON Output Format

When using `--json`, each message is a JSON object on its own line:

```
{"type": "say", "text": "I'll create the file now.", "ts": 1760501486669, "say": "text"}
```

| Field | Type | Description |
| --- | --- | --- |
| `type` | `"ask"` or `"say"` | Message category |
| `text` | `string` | Message content |
| `ts` | `number` | Unix timestamp in milliseconds |
| `say` | `string` | Subtype when `type` is `"say"` |
| `ask` | `string` | Subtype when `type` is `"ask"` |
| `reasoning` | `string` | Model reasoning (if available) |
| `partial` | `boolean` | `true` while streaming |

## [​](#configuration-files) Configuration Files

```
~/.cline/
  data/
    settings/
      providers.json             # API keys and provider config
      rules/                     # Global rules
      skills/                    # Global skills
    teams/                       # Team state
    sessions/                    # Session database (SQLite)
    logs/
      hub-daemon.log             # Hub logs
  plugins/                       # Global plugins
    _installed/                  # Managed by `cline plugin install`

.cline/                          # Project root
  rules/                         # Project rules
  skills/                        # Project skills
  hooks/                         # Lifecycle hooks
  plugins/                       # Project plugins
  mcp.json                       # MCP server config
  agents.yaml                    # Agent definitions
```

Was this page helpful?

YesNo

[CLI Overview](/usage/cli-overview)[GitHub Issue RCA Sample](/cli/samples/github-issue-rca)

⌘I

---

## Configuration

*Source: [https://docs.cline.bot/cli/configuration](https://docs.cline.bot/cli/configuration)*

Cline configuration lives in two scopes:

- **Global configuration** in `~/.cline/` (applies globally across all Cline applications, including IDE, CLI, and SDK)
- **Project configuration** in `.cline/` (applies only to the current workspace)

## [​](#configuration-directory-layout) Configuration Directory Layout

Cline stores shared configuration across a few well-known locations. The primary root is `~/.cline/`, with structured app state under `~/.cline/data/`:

```
~/.cline/
  data/
    settings/
      providers.json           # API keys and provider configuration
      global-settings.json     # Global settings
      cline_mcp_settings.json  # MCP settings
    teams/                     # Team state
    sessions/                  # Session data
    db/                        # SQLite databases (for example cron.db)
    workflows/                 # Global workflows
  rules/                       # Global rules
  hooks/                       # Global hooks
  skills/                      # Global skills
  agents/                      # Global agent definitions
  plugins/                     # Global plugins (.js, .ts)
  cron/                        # Global cron specs
```

Additional global search paths supported by the code:

```
~/Documents/Cline/
  Rules/                       # Additional global rules
  Hooks/                       # Additional global hooks
  Plugins/                     # Additional global plugins
  Workflows/                   # Additional global workflows
```

Project-level configuration lives in `.cline/` at your repository root:

```
.cline/
  rules/                       # Project rules
  skills/                      # Project skills
  hooks/                       # Lifecycle hooks
  agents/                      # Project agent definitions
  plugins/                     # Project plugins
  cron/                        # Workspace cron specs
```

Notes:

- Global provider settings, global settings, and MCP settings are stored under `~/.cline/data/settings/`.
- Global workflows resolve from `~/.cline/data/workflows/`.
- Global rules, hooks, skills, agents, plugins, and cron specs resolve directly under `~/.cline/`.
- Rules, hooks, plugins, and workflows may also be discovered from `~/Documents/Cline/` for compatibility.

## [​](#what-goes-where) What Goes Where?

- Use **global (`~/.cline/`)** for defaults shared across all Cline applications (IDE, CLI, SDK) on your machine.
- Use **project (`.cline/`)** for team-shared behavior that should travel with the repo.

Commit `.cline/` files you want to share with your team. Keep secrets out of the repo.

## [​](#configure-through-the-cli) Configure Through the CLI

Use the interactive config UI:

```
cline config
```

From there, you can view/edit:

- Settings (global + workspace)
- Rules
- Skills
- Hooks

## [​](#useful-configuration-commands) Useful Configuration Commands

Use a custom configuration directory:

```
cline --config /path/to/custom/config "your task"
```

Or via environment variable:

```
export CLINE_DATA_DIR=/custom/path/to/cline
cline "your task"
```

View CLI logs when troubleshooting:

```
cline dev log
```

## [​](#environment-variables) Environment Variables

| Variable | Description |
| --- | --- |
| `CLINE_DATA_DIR` | Custom data directory (replaces `~/.cline/data/`) |
| `CLINE_HUB_ADDRESS` | Override hub address (default: `127.0.0.1:25463`) |
| `CLINE_SESSION_BACKEND_MODE` | Force backend mode (`local`, `hub`, `remote`, `auto`) |
| `CLINE_SANDBOX` | Enable sandbox mode |
| `CLINE_SANDBOX_DATA_DIR` | Sandbox session storage directory |
| `CLINE_HOOKS_DIR` | Additional hooks directory |
| `CLINE_COMMAND_PERMISSIONS` | JSON policy restricting shell commands |

### [​](#cline_data_dir) CLINE\_DATA\_DIR

```
export CLINE_DATA_DIR=/custom/path/to/cline
cline "your task"
```

### [​](#cline_command_permissions) CLINE\_COMMAND\_PERMISSIONS

Restrict which shell commands Cline can execute:

```
export CLINE_COMMAND_PERMISSIONS='{"allow": ["npm *", "git *"], "deny": ["rm -rf *"]}'
```

Format:

```
{
  "allow": ["pattern1", "pattern2"],
  "deny": ["pattern3"],
  "allowRedirects": true
}
```

Rules:

- `deny` overrides `allow`
- If `allow` is set, commands not matching `allow` are denied
- `allowRedirects` controls shell redirects (`>`, `>>`, `<`), default `false`

## [​](#related-docs) Related Docs

- [CLI Configuration](/cli/configuration)
- [Rules](/customization/cline-rules)
- [Skills](/customization/skills)
- [Hooks](/customization/hooks)
- [Plugins](/customization/plugins)
- [.clineignore](/customization/clineignore)

## [​](#security-notes) Security Notes

Only use rules, hooks, skills, and plugins from sources you trust.

Hooks and plugins can execute code. Review them like any other executable artifact before adding them globally or to a project.

Was this page helpful?

YesNo

[Other 30+ Providers](/provider-config/other-30-plus-providers)[IDE](/usage/ide)

⌘I

---

## Connectors

*Source: [https://docs.cline.bot/cli/connectors](https://docs.cline.bot/cli/connectors)*

This feature currently only applies to Cline CLI.

Connectors let you chat with your agent from messaging platforms. Each incoming message creates or continues an agent session, and the agent’s response is sent back to the conversation.

## [​](#setup-wizard) Setup Wizard

Run `cline connect` to open an interactive wizard that guides you through platform selection, credential entry, security configuration, and advanced options (provider, model, system prompt, agent mode).

```
cline connect
```

## [​](#supported-platforms) Supported Platforms

| Platform | Direct Command | Required Credentials |
| --- | --- | --- |
| Telegram | `cline connect telegram` | Bot token |
| Slack | `cline connect slack` | Bot token plus webhook signing secret/base URL or socket app token |
| Discord | `cline connect discord` | Application ID, bot token, public key, base URL |
| Google Chat | `cline connect gchat` | Service account credentials JSON, base URL |
| WhatsApp | `cline connect whatsapp` | Phone number ID, access token, app secret, verify token, base URL |
| Linear | `cline connect linear` | API key, webhook signing secret, base URL |

## [​](#telegram) Telegram

1

Create a Telegram bot

Open Telegram and start a chat with [@BotFather](https://t.me/BotFather). Send `/newbot` and follow the prompts:

1. Enter a display name (e.g., “Cline”)
2. Enter a username ending in `bot` (e.g., `cline_myname_bot`). Must be unique across Telegram.
3. BotFather responds with your bot token (looks like `7123456789:AAH...`)

2

Start the connector

```
cline connect telegram -k <BOT-TOKEN>
```

The connector discovers the bot username from the token. Use `--bot-username` only if you need to override it.

3

Chat with your bot

Open Telegram, search for your bot’s username, and send a message. The agent processes it and replies in the chat.

### [​](#security) Security

By default, anyone who finds your bot can message it and it will execute tasks on your machine. The `cline connect` wizard asks whether to restrict Telegram access and can configure this for you.

1

Get your Telegram user ID

Message [@userinfobot](https://t.me/userinfobot) on Telegram. It replies with your numeric user ID immediately.

2

Use the wizard

```
cline connect
```

Choose Telegram, enter the bot token, answer yes to access restriction, then enter your user ID.

3

Or pass the flag manually

Replace `12345` with your Telegram user ID:

```
cline connect telegram -k <BOT-TOKEN> \
  --allowed-user-id 12345
```

Use `--hook-command` only when you need custom access logic. The hook receives each incoming message with sender info via stdin. Your script returns `{"action": "allow"}` or `{"action": "deny", "message": "reason"}`. Without `--allowed-user-id` or `--hook-command`, everything is auto-approved, so restrict Telegram bots that can reach a running Cline instance.

## [​](#slack) Slack

Slack supports webhook mode and socket mode. Each Slack thread maps to an agent session, so the agent maintains conversation context within a thread.
Webhook mode requires a bot token, signing secret, and public base URL:

```
cline connect slack \
  --bot-token <BOT-TOKEN> \
  --signing-secret <SECRET> \
  --base-url <URL>
```

Configure the Slack app’s event subscription and interactivity request URLs to `<URL>/api/webhooks/slack`.
Socket mode requires a bot token and an app-level token with the `connections:write` scope:

```
cline connect slack \
  --bot-token <BOT-TOKEN> \
  --app-token <APP-LEVEL-TOKEN>
```

Enable Socket Mode in the Slack app. Socket mode does not need a public request URL and is single-workspace only.

## [​](#discord) Discord

Requires a Discord application ID, bot token, public key, and public base URL.
The connector listens for Discord interactions at `/api/webhooks/discord` and
also starts a Discord gateway listener for mentions, replies, reactions, and DMs.

1

Create a Discord application and bot

Open [Discord Developer Portal](https://discord.com/developers/applications)
and create an application.

1. In **General Information**, copy the **Application ID** and **Public Key**.
2. In **Bot**, create a bot if one does not exist, then reset and copy the bot token.
3. Enable **Message Content Intent** if you want normal messages, replies, and DMs to include text content.

2

Expose a public base URL

For local development, use a tunnel such as ngrok:

```
ngrok http 8788
```

Copy the HTTPS forwarding URL. This is your connector base URL, for example
`https://1234-5678.ngrok-free.app`.

3

Start the connector

```
cline connect discord \
  --application-id <ID> \
  --bot-token <TOKEN> \
  --public-key <KEY> \
  --base-url <URL> \
  --port 8788 \
  --cwd /path/to/repo \
  --enable-tools
```

`--app-id` is an alias for `--application-id`, and `--token` is an alias for
`--bot-token`.`--enable-tools` allows the agent to inspect files, run commands, edit code,
and prepare PRs from Discord. Omit it if the bot should only chat.

4

Configure the Discord interactions endpoint

In the Discord Developer Portal, set **Interactions Endpoint URL** to:

```
<base-url>/api/webhooks/discord
```

For example:

```
https://1234-5678.ngrok-free.app/api/webhooks/discord
```

You can verify the connector is reachable with:

```
curl <base-url>/health
```

5

Invite the bot to a test server

In **OAuth2 > URL Generator**, select the `bot` and
`applications.commands` scopes, then give the bot permission to send
messages and read message history. Open the generated URL and install the bot
into your test server.

6

Chat with the bot

Mention the bot in a server channel, reply in a bot-created thread, or DM the
bot. Each Discord conversation keeps its own agent session and context.

### [​](#discord-command-reference) Discord Command Reference

Send these commands in Discord:

| Command | Description |
| --- | --- |
| `/help` or `/start` | Show connector help |
| `/new` or `/clear` | Start a fresh session for this Discord conversation |
| `/whereami` | Show thread, channel, DM state, `cwd`, `workspaceRoot`, tools, and yolo state |
| `/tools [on|off|toggle]` | View or change whether repo/file/shell tools are allowed |
| `/yolo [on|off|toggle]` | View or change automatic tool approval |
| `/cwd [path]` | View or change the working directory for this conversation |
| `/schedule create/list/trigger/delete` | Manage scheduled workflows targeting this conversation |
| `/abort` | Stop the current task |
| `/exit` | Stop the connector |

Normal messages are treated as agent tasks. If a task is already running, normal
messages steer the active task.

### [​](#discord-security) Discord Security

By default, anyone who can reach the bot can ask it to run tasks. Restrict access
with `--hook-command`. The hook receives the Discord user as a participant key
such as `discord:user:123456789`.

```
cline connect discord \
  --application-id <ID> \
  --bot-token <TOKEN> \
  --public-key <KEY> \
  --base-url <URL> \
  --hook-command 'jq -r ".payload.actor.participantKey" | grep -q "discord:user:123456789" && echo "{\"action\":\"allow\"}" || echo "{\"action\":\"deny\",\"message\":\"unauthorized\"}"'
```

## [​](#google-chat) Google Chat

Requires a service account credentials JSON file and public base URL.

```
cline connect gchat --credentials <JSON> --base-url <URL>
```

## [​](#whatsapp) WhatsApp

Requires a phone number ID, access token, app secret, webhook verify token, and public base URL.

```
cline connect whatsapp --phone-id <ID> --token <TOKEN> --app-secret <SECRET> --base-url <URL>
```

## [​](#linear) Linear

Requires an API key, webhook signing secret, and public base URL.

```
cline connect linear --api-key <KEY> --signing-secret <SECRET> --base-url <URL>
```

## [​](#managing-connectors) Managing Connectors

```
# Stop all connectors
cline connect --stop

# Stop a specific connector
cline connect telegram --stop
```

## [​](#hook-command-protocol) Hook Command Protocol

The `--hook-command` pattern works across all connectors. The script receives a JSON payload via stdin:

```
{
  "payload": {
    "actor": {
      "participantKey": "telegram:id:12345",
      "displayName": "User Name"
    },
    "message": "The incoming message text"
  }
}
```

Return `{"action": "allow"}` or `{"action": "deny", "message": "reason"}`.

## [​](#running-multiple-connectors) Running Multiple Connectors

Multiple connectors can run simultaneously. They all share the same hub:

```
# Terminal 1
cline connect telegram -k $TELEGRAM_TOKEN

# Terminal 2
cline connect slack --bot-token $SLACK_TOKEN --signing-secret $SECRET --base-url $URL
```

Connectors require the hub. Start it with `cline hub start` if it doesn’t auto-start.

Was this page helpful?

YesNo

[Scheduling](/cli/scheduling)[.clineignore](/customization/clineignore)

⌘I

---

## Github Integration

*Source: [https://docs.cline.bot/cli/samples/github-integration](https://docs.cline.bot/cli/samples/github-integration)*

Automate GitHub issue analysis with AI. Mention `@cline` in any issue comment to trigger an autonomous investigation that reads files, analyzes code, and provides actionable insights - all running automatically in GitHub Actions.

**New to Cline CLI?** This sample assumes you understand Cline CLI basics and have completed the [Installation Guide](https://docs.cline.bot/getting-started/installing-cline). If you’re new to Cline CLI, we recommend starting with the [GitHub RCA sample](/cli/samples/github-issue-rca) first, as it’s simpler and will help you understand the fundamentals before setting up GitHub Actions.

## [​](#the-workflow) The Workflow

Trigger Cline by mentioning `@cline` in any issue comment:Cline’s automated analysis appears as a new comment, with insights drawn from your actual codebase:The entire investigation runs autonomously in GitHub Actions - from file exploration to posting results.
Let’s configure your repository.

## [​](#prerequisites) Prerequisites

Before you begin, you’ll need:

- **Cline CLI knowledge** - Completed the [Installation Guide](https://docs.cline.bot/getting-started/installing-cline) and understand basic usage
- **GitHub repository** - With admin access to configure Actions and secrets
- **GitHub Actions familiarity** - Basic understanding of workflows and CI/CD
- **API provider account** - OpenRouter, Anthropic, or similar with API key

## [​](#setup) Setup

### [​](#1-copy-the-workflow-file) 1. Copy the Workflow File

Copy the workflow file from this sample to your repository. The workflow file must be placed in the `.github/workflows/` directory in your repository root for GitHub Actions to detect and run it. In this case, we’ll name it `cline-responder.yml`.

```
# In your repository root
mkdir -p .github/workflows
curl -o .github/workflows/cline-responder.yml https://raw.githubusercontent.com/cline/cline/main/src/samples/cli/github-integration/cline-responder.yml
```

Alternatively, you can copy the full workflow file directly into `.github/workflows/cline-responder.yml`:


Click to view the complete cline-responder.yml workflow

```
name: Cline Issue Assistant

on:
  issue_comment:
    types: [created, edited]

permissions:
  issues: write

jobs:
  respond:
    runs-on: ubuntu-latest
    environment: cline-actions
    steps:
      - name: Check for @cline mention
        id: detect
        uses: actions/github-script@v7
        with:
          script: |
            const body = context.payload.comment?.body || "";
            const isPR = !!context.payload.issue?.pull_request;
            const hit = body.toLowerCase().includes("@cline");
            core.setOutput("hit", (!isPR && hit) ? "true" : "false");
            core.setOutput("issue_number", String(context.payload.issue?.number || ""));
            core.setOutput("issue_url", context.payload.issue?.html_url || "");
            core.setOutput("comment_body", body);

      - name: Checkout repository
        if: steps.detect.outputs.hit == 'true'
        uses: actions/checkout@v4

      # Node v20+ is needed for Cline CLI on GitHub Actions Linux
      - name: Setup Node.js
        uses: actions/setup-node@v4
        with:
          node-version: '22'
          cache: 'npm'

      - name: Install Cline CLI
        if: steps.detect.outputs.hit == 'true'
        run: npm install -g cline

      - name: Configure Cline Authentication
        if: steps.detect.outputs.hit == 'true'
        env:
          CLINE_DIR: ${{ runner.temp }}/cline
        run: |
          # Configure API key using the auth command
          cline auth --provider openrouter --apikey "${{ secrets.OPENROUTER_API_KEY }}"

      - name: Download analyze script
        if: steps.detect.outputs.hit == 'true'
        run: |
          export GITORG="YOUR-GITHUB-ORG"
          export GITREPO="YOUR-GITHUB-REPO"

          curl -L https://raw.githubusercontent.com/${GITORG}/${GITREPO}/refs/heads/main/git-scripts/analyze-issue.sh -o analyze-issue.sh
          chmod +x analyze-issue.sh

      - name: Run analysis
        if: steps.detect.outputs.hit == 'true'
        id: analyze
        env:
          ISSUE_URL: ${{ steps.detect.outputs.issue_url }}
          COMMENT: ${{ steps.detect.outputs.comment_body }}
        run: |
          set -euo pipefail
          RESULT=$(./analyze-issue.sh "${ISSUE_URL}" "Analyze this issue. The user asked: ${COMMENT}")
          {
            echo 'result<<EOF'
            printf "%s\n" "$RESULT"
            echo 'EOF'
          } >> "$GITHUB_OUTPUT"

      - name: Post response
        if: steps.detect.outputs.hit == 'true'
        uses: actions/github-script@v7
        env:
          ISSUE_NUMBER: ${{ steps.detect.outputs.issue_number }}
          RESULT: ${{ steps.analyze.outputs.result }}
        with:
          script: |
            await github.rest.issues.createComment({
              owner: context.repo.owner,
              repo: context.repo.repo,
              issue_number: Number(process.env.ISSUE_NUMBER),
              body: process.env.RESULT || "(no output)"
            });
```

**You MUST edit the workflow file before committing!**Open `.github/workflows/cline-responder.yml` and update the “Download analyze script” step within the workflow to specify your GitHub organization and repository where the analysis script is stored:

```
export GITORG="YOUR-GITHUB-ORG"      # Change this!
export GITREPO="YOUR-GITHUB-REPO"    # Change this!
```

**Example:** If your repository is `github.com/acme/myproject`, set:

```
export GITORG="acme"
export GITREPO="myproject"
```

This tells the workflow where to download the analysis script from your repository after you commit it in step 3.

The workflow will look for new or updated issues, check for `@cline` mentions, and then
start up the Cline CLI to dig into the issue, providing feedback as a reply to the issue.

### [​](#2-configure-api-keys) 2. Configure API Keys

Add your AI provider API keys as repository secrets:

1. Go to your GitHub repository
2. Navigate to **Settings** → **Environment** and Add a new environment.Make sure to name it “cline-actions” so that it matches the `environment`
   value at the top of the `cline-responder.yml` file.
3. Click **New repository secret**
4. Add a secret for the `OPENROUTER_API_KEY` with a value of an API key from
   [openrouter.com](https://openrouter.com).
5. Verify your secret is configured:

Now you’re ready to supply Cline with the credentials it needs in a GitHub Action.

### [​](#3-add-analysis-script) 3. Add Analysis Script

Add the analysis script from the `github-issue-rca` sample to your repository. **First, you’ll need to create a `git-scripts` directory in your repository root where the script will be located.** Choose one of these options:
**Option A: Download directly (Recommended)**

```
# In your repository root, create the directory and download the script
mkdir -p git-scripts
curl -o git-scripts/analyze-issue.sh https://raw.githubusercontent.com/cline/cline/main/src/samples/cli/github-issue-rca/analyze-issue.sh
chmod +x git-scripts/analyze-issue.sh
```

**Option B: Manual copy-paste**
Create the directory and file manually, then paste the script content:

```
# In your repository root
mkdir -p git-scripts
# Create and edit the file with your preferred editor
nano git-scripts/analyze-issue.sh  # or use vim, code, etc.
```

Click to view the complete analyze-issue.sh script

```
#!/bin/bash
# Analyze a GitHub issue using Cline CLI

if [ -z "$1" ]; then
    echo "Usage: $0 <github-issue-url> [prompt]"
    echo "Example: $0 https://github.com/owner/repo/issues/123"
    echo "Example: $0 https://github.com/owner/repo/issues/123 'What is the root cause of this issue?'"
    exit 1
fi

# Gather the args
ISSUE_URL="$1"
PROMPT="${2:-What is the root cause of this issue?}"

# Ask Cline for its analysis, showing only the summary
cline --auto-approve true --json "$PROMPT: $ISSUE_URL" | \
    jq -r 'select(.type == "agent_event" and .event.type == "done") | .event.text' | \
    sed 's/\\n/\n/g'
```

After pasting the script content, make it executable:

```
chmod +x git-scripts/analyze-issue.sh
```

This analysis script calls Cline to execute a prompt on a GitHub issue,
summarizing the output to populate the reply to the issue.

### [​](#4-commit-and-push) 4. Commit and Push

```
git add .github/workflows/cline-responder.yml
git add git-scripts/analyze-issue.sh
git commit -m "Add Cline issue assistant workflow"
git push
```

## [​](#usage) Usage

Once set up, simply mention `@cline` in any issue comment:

```
@cline what's causing this error?

@cline analyze the root cause

@cline what are the security implications?
```

GitHub Actions will:

1. Detect the `@cline` mention
2. Start a Cline CLI instance
3. Download the analysis script
4. Analyze the issue using Act mode with auto-approval enabled
5. Post Cline’s analysis as a new comment

**Note**: The workflow only triggers on issue comments, not pull request
comments.

## [​](#how-it-works) How It Works

The workflow (`cline-responder.yml`):

1. **Triggers** on issue comments (created or edited)
2. **Detects** `@cline` mentions (case-insensitive)
3. **Installs** Cline CLI globally using npm
4. **Configures** authentication using `cline auth --provider openrouter --apikey ...`
5. **Downloads** the reusable `analyze-issue.sh` script from the
   `github-issue-rca` sample
6. **Runs** analysis in Cline CLI
7. **Posts** the analysis result as a comment

## [​](#related-samples) Related Samples

- **[github-issue-rca](/cli/samples/github-issue-rca)**: The reusable script that powers this integration

Was this page helpful?

YesNo

[GitHub Issue RCA Sample](/cli/samples/github-issue-rca)[GitHub PR Review](/cli/samples/github-pr-review)

⌘I

---

## Github Issue Rca

*Source: [https://docs.cline.bot/cli/samples/github-issue-rca](https://docs.cline.bot/cli/samples/github-issue-rca)*

Automated GitHub issue analysis using Cline CLI. This script uses Cline’s autonomous AI capabilities to fetch, analyze, and identify root causes of GitHub issues, outputting clean, parseable results that can be easily integrated into your development workflows.

**New to Cline CLI?** This sample assumes you have already completed the [Installation Guide](https://docs.cline.bot/getting-started/installing-cline) and authenticated with `cline auth`. If you haven’t set up Cline CLI yet, please start there first.

## [​](#prerequisites) Prerequisites

This sample assumes you have already:

- **Cline CLI** installed and authenticated ([Installation Guide](https://docs.cline.bot/getting-started/installing-cline))
- **At least one AI model provider** configured (e.g., OpenRouter, Anthropic, OpenAI)
- **Basic familiarity** with Cline CLI commands

Additionally, you’ll need:

- **GitHub CLI** (`gh`) installed and authenticated
- **jq** installed for JSON parsing
- **bash** shell (or compatible shell)

### [​](#installation-instructions) Installation Instructions

#### [​](#macos) macOS

These instructions require [Homebrew](https://brew.sh/) to be installed. If you don’t have Homebrew, install it first by running:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```
# Install GitHub CLI
brew install gh

# Install jq
brew install jq

# Authenticate with GitHub
gh auth login
```

#### [​](#linux) Linux

```
# Install GitHub CLI (Debian/Ubuntu)
sudo apt install gh

# Or for other Linux distributions, see: https://cli.github.com/manual/installation

# Install jq (Debian/Ubuntu)
sudo apt install jq

# Authenticate with GitHub
gh auth login
```

## [​](#getting-the-script) Getting the Script

**Option 1: Download directly with curl**

```
curl -O https://raw.githubusercontent.com/cline/cline/main/src/samples/cli/github-issue-rca/analyze-issue.sh
```

**Option 2: Copy the full script**


Click to view the complete analyze-issue.sh script

```
#!/bin/bash
# Analyze a GitHub issue using Cline CLI

if [ -z "$1" ]; then
    echo "Usage: $0 <github-issue-url> [prompt]"
    echo "Example: $0 https://github.com/owner/repo/issues/123"
    echo "Example: $0 https://github.com/owner/repo/issues/123 'What is the root cause of this issue?'"
    exit 1
fi

# Gather the args
ISSUE_URL="$1"
PROMPT="${2:-What is the root cause of this issue?}"
# Ask Cline for its analysis, showing only the summary
cline --auto-approve true --json "$PROMPT: $ISSUE_URL" | \
    jq -r 'select(.type == "agent_event" and .event.type == "done") | .event.text' | \
    sed 's/\\n/\n/g'
```

**After downloading or creating the script**, make it executable by running:

```
chmod +x analyze-issue.sh
```

## [​](#quick-usage-examples) Quick Usage Examples

### [​](#basic-usage) Basic Usage

Run this command in your terminal from the directory where you saved the script to analyze an issue with the default root cause prompt:

```
./analyze-issue.sh https://github.com/owner/repo/issues/123
```

This will:

- Fetch issue #123 from the repository
- Analyze the issue to identify root causes
- Provide detailed analysis with recommendations

### [​](#custom-analysis-prompt) Custom Analysis Prompt

Ask specific questions about the issue:

```
./analyze-issue.sh https://github.com/owner/repo/issues/456 "What is the security impact?"
```

The script will automatically handle everything: fetching the issue, analyzing it with Cline, and displaying the results. The analysis typically takes 30-60 seconds depending on the issue complexity.

## [​](#how-it-works) How It Works

Let’s analyze each component of the script to understand how it works.

### [​](#argument-validation) Argument Validation

The script validates input and provides usage instructions:

```
if [ -z "$1" ]; then
    echo "Usage: $0 <github-issue-url> [prompt]"
    echo "Example: $0 https://github.com/owner/repo/issues/123"
    echo "Example: $0 https://github.com/owner/repo/issues/123 'What is the root cause?'"
    exit 1
fi
```

**Key Points:**

- Validates required GitHub issue URL
- Shows clear usage examples
- Supports optional custom prompt

### [​](#argument-parsing) Argument Parsing

The script extracts and sets up the arguments:

```
# Gather the args
ISSUE_URL="$1"
PROMPT="${2:-What is the root cause of this issue?}"
```

**Explanation:**

- `ISSUE_URL="$1"` - First argument is always the issue URL
- `PROMPT="${2:-...}"` - Second argument is optional, defaults to root cause analysis
- The SDK CLI runs the task directly, so no address flag is required.

### [​](#the-core-analysis-pipeline) The Core Analysis Pipeline

This is where the magic happens:

```
# Ask Cline for its analysis, showing only the summary
cline --auto-approve true --json "$PROMPT: $ISSUE_URL" | \
    jq -r 'select(.type == "agent_event" and .event.type == "done") | .event.text' | \
    sed 's/\\n/\n/g'
```

Pipeline Breakdown: Understanding Each Component

**1. `cline --auto-approve true --json "$PROMPT: $ISSUE_URL"`**

- `cline` is the Cline CLI binary
- Act mode is the default for prompt runs
- `--auto-approve true` allows tool use without interactive prompts
- `--json` emits newline-delimited JSON for parsing
- Constructs prompt with issue URL

**2. `jq -r 'select(.type == "agent_event" and .event.type == "done") | .event.text'`**

- Filters for the final agent `done` event
- Extracts the final text field
- `-r` outputs raw strings (no JSON quotes)

**3. `sed 's/\\n/\n/g'`**

- Converts escaped newlines to actual newlines
- Makes output readable

## [​](#sample-output) Sample Output

Here’s an example analyzing a real Flutter issue:

```
$ ./analyze-issue.sh https://github.com/csells/flutter_counter/issues/2
```

**Output:**

```
**Root Cause Analysis of Issue #2: "setState isn't cutting it"**

After examining the GitHub issue and analyzing the Flutter counter codebase,
I've identified the root cause of why setState() is insufficient for this
project's needs:

## Current Implementation Problems

The current Flutter counter app uses setState() for state management, which
has several limitations:

1. **Local State Only**: setState() only works within a single widget, making
   it difficult to share state across the app
2. **Rebuild Overhead**: Every setState() call rebuilds the entire widget tree,
   causing performance issues with complex UIs
3. **No State Persistence**: State is lost when the widget is disposed
4. **Testing Challenges**: setState-based logic is tightly coupled to the UI,
   making unit testing difficult

## Why This Matters

As the app grows beyond a simple counter, these limitations become critical:
- Multiple screens need to access the count
- State needs to persist across navigation
- Business logic should be testable independently
- UI should only rebuild when necessary

## Recommended Solutions

The issue mentions "Provider or Bloc" - both are excellent alternatives:

1. **Provider**: Simple, lightweight state management using InheritedWidget
   - Easy migration path from setState
   - Good for small to medium apps
   - Official Flutter recommendation

2. **Bloc**: More structured approach with clear separation between events,
   states, and business logic
   - Better for complex apps
   - Excellent testability
   - Clear architectural patterns

3. **Riverpod**: Modern alternative to Provider with better performance and
   developer experience
   - Compile-time safety
   - Better testing support
   - More flexible than Provider

4. **GetX**: Full-featured solution with state management, routing, and
   dependency injection
   - Minimal boilerplate
   - Fast and lightweight
   - All-in-one solution

## Next Steps

The current codebase needs refactoring to implement proper state management
architecture to handle more complex state scenarios effectively. Provider
would be the easiest migration path while Bloc provides better long-term
scalability.
```

## [​](#when-to-use-this-pattern) When to Use This Pattern

This script pattern is ideal for various development scenarios where automated GitHub issue analysis can accelerate your workflow.

### [​](#bug-investigation) Bug Investigation

Quickly analyze bug reports and identify root causes without manual code exploration:

```
./analyze-issue.sh https://github.com/project/repo/issues/123 \
    "What is the root cause of this bug?"
```

### [​](#feature-request-analysis) Feature Request Analysis

Understand context and implications of feature requests:

```
./analyze-issue.sh https://github.com/project/repo/issues/456 \
    "What are the implementation challenges?"
```

### [​](#security-audits) Security Audits

Assess security implications of reported issues:

```
./analyze-issue.sh https://github.com/project/repo/issues/789 \
    "What are the security implications?"
```

### [​](#documentation-generation) Documentation Generation

Generate detailed technical documentation from issues:

```
./analyze-issue.sh https://github.com/project/repo/issues/654 \
    "Provide detailed technical documentation for this issue"
```

### [​](#code-review-assistance) Code Review Assistance

Get second opinions on proposed changes:

```
./analyze-issue.sh https://github.com/project/repo/issues/987 \
    "Review the proposed solution approach"
```

## [​](#conclusion) Conclusion

This sample demonstrates how to build an autonomous GitHub issue analysis tool using Cline CLI:

1. **Building autonomous CLI tools** using Cline’s capabilities
2. **Parsing structured JSON output** from Cline CLI
3. **Creating flexible automation scripts** with custom prompting
4. **Integrating with GitHub** for issue analysis
5. **Handling command-line arguments** effectively

This pattern can be adapted for many other automation scenarios, from pull request reviews to documentation generation to code quality analysis.

## [​](#related-resources) Related Resources

- [CLI Installation Guide](https://docs.cline.bot/getting-started/installing-cline)
- [CLI Reference Documentation](https://docs.cline.bot/cli/cli-reference)
- [Headless Mode](https://docs.cline.bot/usage/cli-overview#headless-mode)

Was this page helpful?

YesNo

[CLI Reference](/cli/cli-reference)[GitHub Actions Integration](/cli/samples/github-integration)

⌘I

---

## Github Pr Review

*Source: [https://docs.cline.bot/cli/samples/github-pr-review](https://docs.cline.bot/cli/samples/github-pr-review)*

Automate code review for every Pull Request. Detailed analysis, security checks, and code suggestions provided by Cline running autonomously in GitHub Actions.

## [​](#the-workflow) The Workflow

When a PR is opened or marked ready for review, this workflow:

1. **Checks out** the code.
2. **Installs** Node.js and Cline CLI.
3. **Configures** authentication (e.g., Anthropic, OpenAI).
4. **Runs Cline** with a comprehensive system prompt to analyze the diff, context, and related issues using GitHub CLI (`gh`).
5. **Posts** a detailed review comment with inline code suggestions.

## [​](#prerequisites) Prerequisites

- **GitHub repository** with Actions enabled.
- **AI Provider API Key** (e.g., Anthropic, OpenRouter) added as a repository secret (e.g., `ANTHROPIC_API_KEY`).
- **GitHub Token** (automatically provided by Actions as `GITHUB_TOKEN`).

## [​](#setup) Setup

### [​](#1-create-the-workflow-file) 1. Create the Workflow File

Create a file named `.github/workflows/cline-pr-review.yml` in your repository:

```
name: Cline PR Code Review

on:
  pull_request:
    types: [opened, ready_for_review]
  workflow_dispatch:
    inputs:
      pr_number:
        description: "PR number to review"
        required: true
        type: string

concurrency:
  group: pr-review-${{ github.event.pull_request.number || inputs.pr_number }}
  cancel-in-progress: true

jobs:
  cline-pr-review:
    if: |
      (github.event_name == 'pull_request' && github.event.pull_request.draft == false) ||
      github.event_name == 'workflow_dispatch'
    runs-on: ubuntu-latest
    timeout-minutes: 60

    permissions:
      contents: read
      pull-requests: write
      issues: read

    steps:
      - name: Checkout repository
        uses: actions/checkout@v4
        with:
          fetch-depth: 0

      - name: Setup Node.js
        uses: actions/setup-node@v4
        with:
          node-version: 22
          cache: "npm"

      - name: Install Cline CLI
        run: npm install -g cline

      - name: Configure Cline Authentication
        # Replace 'anthropic' with your provider of choice (openai, openrouter, etc.)
        # and ensure the corresponding secret is set in your repo settings.
        run: |
          cline auth --provider anthropic \
            --apikey "${{ secrets.ANTHROPIC_API_KEY }}" \
            --modelid claude-opus-4-5-20251101

      - name: Get PR number
        id: pr
        run: |
          if [ "${{ github.event_name }}" == "workflow_dispatch" ]; then
            echo "number=${{ inputs.pr_number }}" >> $GITHUB_OUTPUT
          else
            echo "number=${{ github.event.pull_request.number }}" >> $GITHUB_OUTPUT
          fi

      - name: Review PR with Cline
        env:
          PR_NUMBER: ${{ steps.pr.outputs.number }}
          GITHUB_REPO: ${{ github.repository }}
          GH_TOKEN: ${{ github.token }}
          # Restrict Cline to only safe, read-only GitHub CLI commands
          CLINE_COMMAND_PERMISSIONS: |
            {
              "allow": [
                "gh pr diff *",
                "gh pr view *",
                "gh pr checks *",
                "gh pr list *",
                "gh issue list *",
                "gh issue view *",
                "git log *",
                "gh pr comment ${{ steps.pr.outputs.number }} *",
                "gh api repos/${{ github.repository }}/pulls/${{ steps.pr.outputs.number }}/comments *",
                "gh api repos/${{ github.repository }}/pulls/${{ steps.pr.outputs.number }}/reviews *"
              ]
            }
        run: |
          cline --auto-approve true 'You are a GitHub PR reviewer for this repository. Your goal is to give the PR author helpful feedback and give maintainers the context they need to review efficiently.

          PR: #'"${PR_NUMBER}"'

          ## Gather context
          Use `gh` commands to fetch the PR diff, details, and checks.
          ```bash
          # Get full PR details
          gh pr view '"${PR_NUMBER}"' --json number,title,body,author,createdAt,updatedAt,isDraft,labels,commits,files,additions,deletions,changedFiles,baseRefName,headRefName,mergeable,reviewDecision

          # Get the diff
          gh pr diff '"${PR_NUMBER}"'

          # Check CI status
          gh pr checks '"${PR_NUMBER}"'
```

## [​](#deep-code-review) Deep code review

Analyze the code changes. Look for:

- Logic errors and edge cases
- Security vulnerabilities
- Performance issues
- adherence to patterns in the codebase

## [​](#submit-review) Submit Review

Post a single comprehensive comment summarizing your review.
If you have specific code suggestions, use the GitHub API to post inline comments:

```
gh api repos/'"${GITHUB_REPO}"'/pulls/'"${PR_NUMBER}"'/reviews \
  -X POST \
  -f event="COMMENT" \
  -f body="" \
  -F comments='[{"path": "src/file.ts", "line": 10, "body": "Suggestion: ..."}]'
```

Start your main comment with “Reviewed by Cline”.’

```
### 2. Configure Secrets

1.  Go to your repository settings -> **Secrets and variables** -> **Actions**.
2.  Add a **New repository secret**.
3.  Name: `ANTHROPIC_API_KEY` (or match the key used in your workflow).
4.  Value: Your actual API key.

## Key Components Explained

### Permissions
```yaml
permissions:
  contents: read
  pull-requests: write
  issues: read
```

We grant `pull-requests: write` so Cline can post comments and inline reviews. `contents: read` ensures it can analyze the code but **cannot push changes directly**, providing a security boundary.

### [​](#authentication) Authentication

```
cline auth --provider anthropic --apikey "..."
```

The `auth` command configures Cline in the CI environment without interactive prompts. You can switch providers (e.g., `openai`, `openrouter`) by changing the flags.

### [​](#autonomous-mode-auto-approve-true) Autonomous Mode (`--auto-approve true`)

```
cline --auto-approve true '...'
```

The `--auto-approve true` flag tells Cline to run autonomously, executing approved tools without waiting for interactive confirmation. Prompt runs start in Act mode by default, so CI/CD workflows can perform the requested work immediately.

### [​](#command-permissions) Command Permissions

We explicitly restrict what commands Cline can run using `CLINE_COMMAND_PERMISSIONS`. This ensures Cline can only use `gh` and `git` commands relevant to reviewing, preventing any accidental or malicious system modifications.

## [​](#customizing-the-reviewer) Customizing the Reviewer

The “System Prompt” passed to Cline in the final step is fully customizable. You can modify it to:

- Enforce specific style guides.
- Focus on security vs. performance.
- Ask for specific types of feedback (e.g., “Roast my code” vs. “Be gentle”).

Was this page helpful?

YesNo

[GitHub Actions Integration](/cli/samples/github-integration)[Model Orchestration](/cli/samples/model-orchestration)

⌘I

---

## Model Orchestration

*Source: [https://docs.cline.bot/cli/samples/model-orchestration](https://docs.cline.bot/cli/samples/model-orchestration)*

Cline CLI’s `--config` and `--thinking` flags enable sophisticated multi-model workflows. Instead of using a single model for all tasks, you can route different work to different models based on cost, capability, and specialization.

## [​](#why-orchestrate-multiple-models) Why Orchestrate Multiple Models?

**Cost Optimization**
By routing work to the right model for the job, you can dramatically reduce API costs. Fast, inexpensive models like Haiku and Gemini Flash handle simple tasks such as summarization, while expensive models like Opus and O1 are reserved for complex reasoning and planning. This approach can reduce costs by 10-100x on routine operations.
**Bias Reduction**
Different models catch different issues, so cross-validating solutions with multiple AI perspectives helps reduce blind spots that come from relying on a single model. In code reviews especially, combining viewpoints surfaces problems that any one model might miss.
**Specialization**
Certain models excel in specific domains: Codex and DeepSeek are strong at code generation, while GPT-4 and Claude shine at documentation and prose. Security analysis in particular benefits from combining multiple model viewpoints, since each brings different training data and heuristics to the table.

## [​](#pattern-1-ci/cd-code-review) Pattern 1: CI/CD Code Review

See our production GitHub Actions workflow that uses Cline CLI for automated PR reviews: [cline-pr-review.yml](https://github.com/cline/cline/blob/main/.github/workflows/cline-pr-review.yml)
**Key capabilities demonstrated:**

- **Automated inline suggestions**: Creates GitHub suggestion blocks that authors can commit with one click
- **SME identification**: Analyzes git history to find subject matter experts for each file
- **Related issue discovery**: Searches for context from past issues and PRs
- **Security-first permissions**: Read-only codebase access, can only post reviews
- **Deep code analysis**: Understands intent, compares approaches, identifies edge cases

The workflow runs on every PR and provides maintainers with comprehensive context to make faster, more informed decisions.

## [​](#pattern-2-task-phase-optimization) Pattern 2: Task Phase Optimization

Use different models for different phases of work. Route simple tasks to cheap models, complex reasoning to premium models.

### [​](#example-issue-analysis-pipeline) Example: Issue Analysis Pipeline

```
# Get latest issue content
ISSUE_CONTENT=$(gh issue view $(gh issue list -L 1 | awk '{print $1}'))

# Phase 1: Quick summary with cheap model
SUMMARY=$(echo "$ISSUE_CONTENT" | cline --auto-approve true --config ~/.cline-haiku \
  "summarize this issue in 2-3 sentences")

# Phase 2: Detailed plan with expensive model + thinking
PLAN=$(echo "$SUMMARY" | cline --auto-approve true --thinking high --config ~/.cline-opus \
  "create detailed implementation plan with edge cases")

# Phase 3: Execute with mid-tier model
echo "$PLAN" | cline --auto-approve true --config ~/.cline-sonnet \
  "implement the plan from above"
```

Each `cline` invocation needs to complete before passing output to the next phase. Use shell variables to store intermediate results rather than piping `cline` commands directly.

**Cost impact:**

- Haiku: $0.80 per million input tokens
- Opus: $15 per million input tokens
- Sonnet: $3 per million input tokens

This pattern uses Opus only when needed for complex reasoning, saving ~10x on API costs compared to using Opus for everything.

### [​](#setting-up-model-configs) Setting Up Model Configs

Create separate configuration directories for each model:

```
# Create config directories
mkdir -p ~/.cline-haiku ~/.cline-sonnet ~/.cline-opus

# Configure each with different models
cline --config ~/.cline-haiku auth anthropic --modelid claude-haiku-4-20250514
cline --config ~/.cline-sonnet auth anthropic --modelid claude-sonnet-4-20250514
cline --config ~/.cline-opus auth anthropic --modelid claude-opus-4-5-20251101

# Or use different providers entirely
cline --config ~/.cline-gemini auth gemini --modelid gemini-2.0-flash-exp
cline --config ~/.cline-codex auth openai-codex --modelid gpt-5-latest
```

Now you can switch models per-task with `--config`:

```
cline --config ~/.cline-haiku "quick task"
cline --config ~/.cline-opus "complex reasoning task"
```

## [​](#pattern-3-multi-model-review-&-consensus) Pattern 3: Multi-Model Review & Consensus

Get multiple AI perspectives on the same change, then synthesize their feedback.

### [​](#example-diff-review-pipeline) Example: Diff Review Pipeline

```
# Get the latest commit
DIFF=$(git show)

# Review 1: Gemini's perspective
echo "$DIFF" | cline --auto-approve true --config ~/.cline-gemini \
    "review this diff and write your analysis to gemini-review.md"

# Review 2: Codex's perspective
echo "$DIFF" | cline --auto-approve true --config ~/.cline-codex \
    "review this diff and write your analysis to codex-review.md"

# Review 3: Opus's perspective
echo "$DIFF" | cline --auto-approve true --config ~/.cline-opus \
    "review this diff and write your analysis to opus-review.md"

# Synthesize all reviews into a consensus
cat gemini-review.md codex-review.md opus-review.md | cline --auto-approve true \
    "summarize these 3 reviews and identify: 1) issues all models agree on, 2) issues only one model caught, 3) your final recommendation"
```

**Why this works:**

- **Redundancy**: Issues caught by all 3 models are high-confidence
- **Coverage**: Each model has blind spots; together they cover more ground
- **Prioritization**: Consensus issues should be fixed first
- **Learning**: See which model types catch which issue types

### [​](#advanced-parallel-reviews) Advanced: Parallel Reviews

Run reviews in parallel for faster feedback:

```
# Run all reviews simultaneously
git show | cline --auto-approve true --config ~/.cline-gemini "review and save to gemini-review.md" &
git show | cline --auto-approve true --config ~/.cline-codex "review and save to codex-review.md" &
git show | cline --auto-approve true --config ~/.cline-opus "review and save to opus-review.md" &

# Wait for all to complete
wait

# Synthesize
cat *-review.md | cline --auto-approve true "create consensus review"
```

Parallel execution requires managing multiple Cline instances. See [Multi-instance workflows](/usage/cli-overview#automation-patterns) for details.

## [​](#extended-thinking-for-complex-tasks) Extended Thinking for Complex Tasks

Use the `--thinking` flag when Cline needs to analyze multiple approaches:

```
# Without thinking: Fast but may miss nuances
cline --auto-approve true "refactor this codebase"

# With thinking: Slower but more thorough
cline --auto-approve true --thinking high \
    "refactor this codebase - consider: performance, maintainability, backward compatibility"
```

The `--thinking <level>` flag sets reasoning effort. Use `--thinking high` or `--thinking xhigh` when you want the model to spend more effort on complex tradeoffs. Best for:

- Architectural decisions
- Security analysis
- Complex refactoring
- Multi-step planning

## [​](#best-practices) Best Practices

1. **Profile your workload**: Track which tasks are simple vs. complex
2. **Match models to tasks**: Use fast models for summaries, powerful models for reasoning
3. **Automate switching**: Script model selection based on task type
4. **Monitor costs**: Different models have 10-100x price differences
5. **Validate important decisions**: Use multi-model consensus for critical changes

## [​](#production-examples) Production Examples

### [​](#cost-optimized-pr-review) Cost-Optimized PR Review

```
# Haiku: Quick summary and issue identification
gh pr view $PR | cline --auto-approve true --config ~/.cline-haiku \
    "list all issues to fix, output as JSON"

# Opus with thinking: Deep analysis only if issues found
if [ -s issues.json ]; then
    cline --auto-approve true --thinking high --config ~/.cline-opus \
        "analyze these issues and recommend fixes"
fi
```

### [​](#security-focused-multi-model-scan) Security-Focused Multi-Model Scan

```
# Different models have different security perspectives
git diff main | cline --auto-approve true --config ~/.cline-gemini "security review" > gemini-sec.md &
git diff main | cline --auto-approve true --config ~/.cline-opus "security review" > opus-sec.md &
git diff main | cline --auto-approve true --config ~/.cline-codex "security review" > codex-sec.md &
wait

# High-priority: Issues all 3 models found
cat *-sec.md | cline --auto-approve true "find security issues all 3 reviews mentioned"
```

## [​](#related-documentation) Related Documentation

## CLI Reference

Complete documentation for —config and —thinking flags

## Headless Mode

Run Cline autonomously in scripts, CI/CD pipelines, and automated workflows.

## Cline provider

Fastest built-in model access setup and account workflow

## CI/CD Integration

Automate GitHub workflows with Cline CLI

Was this page helpful?

YesNo

[GitHub PR Review](/cli/samples/github-pr-review)[Supply-Chain Scan Alerts](/cli/samples/supply-chain-alerts)

⌘I

---

## Supply Chain Alerts

*Source: [https://docs.cline.bot/cli/samples/supply-chain-alerts](https://docs.cline.bot/cli/samples/supply-chain-alerts)*

npm worms like Shai-Hulud spread through install scripts: the moment you run `npm install`, a `preinstall` hook executes and steals your npm, GitHub, AWS, and SSH credentials. New campaigns are reported almost every week.
This guide wires three pieces together so your machine checks itself automatically and pings your phone only when it matters:

- [Bumblebee](https://github.com/perplexityai/bumblebee), Perplexity’s open-source, read-only supply-chain scanner. It maintains catalogs of recent campaigns and checks whether any compromised package or version is present on disk.
- The Cline CLI scheduler, which runs an agent on a cron schedule.
- The Cline CLI Telegram connector, which delivers the result to a chat.

The end result: every morning, a Cline agent pulls the latest threat intelligence, runs a read-only scan, and texts you a green check if you are clean or a red alert with details if you are exposed.


## [​](#how-bumblebee-works) How Bumblebee works

Bumblebee answers one narrow question fast: when an advisory names a package and version, is it present on this machine right now?
The important design choice is that it is read-only. A scanner that runs `npm`, `pnpm`, or `pip` to enumerate your dependencies would trigger the very install-script payload it is looking for. Bumblebee never does that. It only reads metadata files directly:

| Surface | What it reads |
| --- | --- |
| npm / pnpm / yarn / bun | lockfiles and installed `package.json` metadata |
| PyPI | `*.dist-info/METADATA`, `*.egg-info/PKG-INFO` |
| Go modules | `go.sum`, `go.mod` |
| RubyGems | `Gemfile.lock`, installed gemspecs |
| Composer | `composer.lock`, `vendor/composer/installed.json` |
| MCP servers | `mcp.json`, `claude_desktop_config.json`, and similar configs |
| Editor extensions | VS Code-family extension manifests |
| Browser extensions | Chromium-family and Firefox extension manifests |

It never runs package managers, never executes install scripts or lifecycle hooks, and never reads your application source. It ships no bundled threat intelligence either: you point it at an exposure catalog, and it reports exact `(ecosystem, name, version)` matches.
The catalogs live in the repo under `threat_intel/`, maintained by Perplexity and updated via pull requests as new campaigns are reported. That is why this automation simply pulls the latest before each scan: a `git pull` is all it takes to stay current.
Read the announcement: [Perplexity is open-sourcing Bumblebee](https://www.perplexity.ai/hub/blog/perplexity-is-open-sourcing-bumblebee).

## [​](#prerequisites) Prerequisites

- Node.js 22 or newer (for the Cline CLI).
- Go 1.22 or newer (to build Bumblebee).
- A Telegram account.
- An AI provider key, or a Cline account.

## [​](#1-install-the-cline-cli) 1. Install the Cline CLI

```
npm install -g cline
cline # run once to configure inference provider and model
```

## [​](#2-clone-and-build-bumblebee) 2. Clone and build Bumblebee

Clone the repository somewhere stable. The clone is both the scanner and the catalog source, so the scheduled job will run from inside it.

```
mkdir -p ~/tools
git clone https://github.com/perplexityai/bumblebee.git ~/tools/bumblebee
cd ~/tools/bumblebee
go build -o bumblebee ./cmd/bumblebee
```

Confirm it works with the built-in self test, which runs embedded fixtures and makes no network calls:

```
./bumblebee selftest
# selftest OK (2 findings in 1ms)
```

## [​](#3-run-a-scan-manually) 3. Run a scan manually

Point `--exposure-catalog` at the whole `threat_intel/` directory to use every maintained catalog at once. The `--findings-only` flag suppresses the full inventory so you only get matches.

```
cd ~/tools/bumblebee
./bumblebee scan --profile deep --root "$HOME" \
  --exposure-catalog ./threat_intel/ \
  --findings-only
```

Output is NDJSON, one JSON object per line. A match looks like this:

```
{ "record_type": "finding", "severity": "critical", "ecosystem": "npm",
  "package_name": "example-pkg", "version": "1.2.3",
  "source_file": "/Users/you/code/app/pnpm-lock.yaml",
  "evidence": "exact name+version match (version=1.2.3)" }
```

If you are clean, you get no `finding` records. Exit code is `0` on a successful run, `1` if the scan hit errors, `2` for bad arguments.

Scan profiles control where Bumblebee looks. `baseline` checks standard global tool, editor, and browser locations. `project` scans your development directories (pass `--root ~/code`). `deep` walks whatever roots you give it, typically your whole home directory. Use `deep` for the most thorough “am I exposed anywhere” check, or `project` for a faster daily scan of your repos.

## [​](#4-create-a-telegram-bot-and-start-the-connector) 4. Create a Telegram bot and start the connector

1

Create a bot

Open Telegram, start a chat with [@BotFather](https://t.me/BotFather), send `/newbot`, and follow the prompts. Copy the bot token it gives you (it looks like `7123456789:AAH...`). Treat it like a password.

2

Start the connector

Run the connector and point its working directory at your Bumblebee clone, so the scheduled agent runs there:

```
cline connect telegram -k "<BOT-TOKEN>" --cwd ~/tools/bumblebee
```

Leave this process running. It polls Telegram and delivers scheduled results, so it must stay alive.

3

Open the chat

In Telegram, search for your bot’s username and send it any message (for example `/whereami`). This creates the thread binding that delivery needs.

By default, anyone who finds your bot can message it and it will run tasks on your machine. Lock it down before leaving the connector running. The `cline connect` wizard can guide you through Telegram user ID setup, or you can message [@userinfobot](https://t.me/userinfobot) and restart the connector with your allowed user ID:

```
cline connect telegram -k "<BOT-TOKEN>" --cwd ~/tools/bumblebee \
  --allowed-user-id 12345
```

Replace `12345` with your Telegram user ID.

## [​](#5-schedule-the-scan) 5. Schedule the scan

There are two ways to create the scheduled scan. Both run the same agent and deliver the result to Telegram, so pick whichever you prefer.

### [​](#option-a-from-the-telegram-chat) Option A: From the Telegram chat

Creating the schedule from the chat automatically targets that thread for delivery, so results come straight back to you. Send this to your bot as a single message:

```
/schedule create "supply-chain-watch" --cron "0 8 * * *" --prompt "Pull the latest Bumblebee catalogs and scan this machine for compromised packages. Run: git pull --quiet && go build -o bumblebee ./cmd/bumblebee && ./bumblebee scan --profile deep --root $HOME --exposure-catalog ./threat_intel/ --findings-only. Read the NDJSON output. If any line has record_type set to finding, reply starting with '🚨 COMPROMISE DETECTED' and list each package name, version, ecosystem, and source_file. If there are no findings, reply with exactly '✅ Clean: no compromised packages found.'"
```

The bot replies with the new schedule, including its id.

### [​](#option-b-from-your-terminal) Option B: From your terminal

Create the schedule with the Cline CLI on the same machine and pass the delivery method explicitly. The running Telegram connector delivers the result to its chat:

```
cline schedule create "supply-chain-watch" \
  --cron "0 8 * * *" \
  --workspace ~/tools/bumblebee \
  --delivery-adapter telegram \
  --delivery-bot <bot-username> \
  --prompt "Pull the latest Bumblebee catalogs and scan this machine for compromised packages. Run: git pull --quiet && go build -o bumblebee ./cmd/bumblebee && ./bumblebee scan --profile deep --root \$HOME --exposure-catalog ./threat_intel/ --findings-only. Read the NDJSON output. If any line has record_type set to finding, reply starting with '🚨 COMPROMISE DETECTED' and list each package name, version, ecosystem, and source_file. If there are no findings, reply with exactly '✅ Clean: no compromised packages found.'"
```

Either way, this schedules a daily scan at 8am.

## [​](#why-the-green-check-matters) Why the green check matters

Scheduled delivery always sends the run’s final reply, so the prompt is written to make that reply meaningful either way:

- Clean run: one line, `✅ Clean: no compromised packages found.` You get a daily heartbeat confirming the scan actually ran.
- Exposure: `🚨 COMPROMISE DETECTED` followed by the package, version, and the file where it was found, so you can act immediately (rotate credentials, remove the package, pin a safe version).

## [​](#test-it) Test it

Trigger the scan now instead of waiting for 8am.
First find your schedule id. The create step returns it (the Telegram bot’s reply shows `id=...`), or list your schedules at any time:

```
cline schedule list
```

Then trigger it with that id. From the terminal:

```
cline schedule trigger <schedule-id>
```

Or from Telegram: `/schedule trigger <schedule-id>`. Within a few seconds you should get the result in your chat.
To see a real alert, add a package and version that matches a catalog entry to a throwaway project’s lockfile and run the scan against it. Bumblebee reports the match, and the agent texts you the red alert.

## [​](#keep-it-running) Keep it running

- The connector process (`cline connect telegram`) must stay running for delivery to work. Run it under a process manager (systemd, launchd, `pm2`, or a `tmux`/`screen` session) so it survives reboots.
- The hub runs the schedule and starts automatically when you create one. If it is not running, start it with `cline hub start`.
- Manage schedules anytime with `cline schedule list`, `cline schedule pause <id>`, `cline schedule resume <id>`, and `cline schedule delete <id>`.

## [​](#customize) Customize

- Cadence: change the cron expression. `0 */6 * * *` scans every six hours; `0 8 * * MON-FRI` runs on weekdays only.
- Scope: swap `--profile deep --root $HOME` for `--profile project --root ~/code` for a faster scan of just your repos, or `--profile baseline` for global tools, editors, and browser extensions.
- Channels: the same delivery pattern works for Slack, Discord, WhatsApp, and Google Chat. See [Connectors](/cli/connectors).
- Fleet use: Bumblebee can `POST` NDJSON to an ingest endpoint with `--output http --http-url <url>` if you want to centralize findings across many machines.

## [​](#credits) Credits

Bumblebee is built and open-sourced by Perplexity. See the [announcement](https://www.perplexity.ai/hub/blog/perplexity-is-open-sourcing-bumblebee) and the [repository](https://github.com/perplexityai/bumblebee).

Was this page helpful?

YesNo

[Model Orchestration](/cli/samples/model-orchestration)[ACP: Editor Integrations](/cli/acp-editor-integrations)

⌘I

---

## Scheduling

*Source: [https://docs.cline.bot/cli/scheduling](https://docs.cline.bot/cli/scheduling)*

This feature currently only applies to Cline SDK, CLI, and Kanban. This feature is not applicable on VSCode and JetBrains Extension for now.

The CLI supports running agents on cron schedules through the hub. Scheduled agents persist across process restarts and run independently of any terminal session.

## [​](#schedule-wizard) Schedule Wizard

Run `cline schedule` to open an interactive menu for creating and managing schedules, browsing execution history, and viewing performance statistics.

```
cline schedule
```

The wizard provides:

| Action | Description |
| --- | --- |
| Create new schedule | Set up a recurring task with cron timing and prompt |
| List schedules | View all schedules with status and next run time |
| Upcoming runs | Preview the next 10 scheduled executions |
| Active executions | Show currently running tasks |
| Trigger now | Immediately run a selected schedule |
| Pause / Resume | Suspend or restart a schedule |
| Execution history | View past runs with status, duration, tokens, and cost |
| Statistics | Success rate, average duration, last failure |
| Delete | Remove a schedule |

## [​](#creating-schedules-with-flags) Creating Schedules with Flags

```
cline schedule create "PR summary" \
  --cron "0 9 * * MON-FRI" \
  --prompt "List all open PRs and their review status" \
  --workspace /path/to/repo \
  --model anthropic/claude-sonnet-4-6
```

## [​](#managing-schedules) Managing Schedules

```
cline schedule list
cline schedule trigger <schedule-id>
cline schedule pause <schedule-id>
cline schedule resume <schedule-id>
cline schedule delete <schedule-id>
cline schedule executions <schedule-id>
```

## [​](#cron-expression-reference) Cron Expression Reference

| Expression | Schedule |
| --- | --- |
| `*/5 * * * *` | Every 5 minutes |
| `*/15 * * * *` | Every 15 minutes |
| `0 * * * *` | Every hour |
| `0 */6 * * *` | Every 6 hours |
| `0 0 * * *` | Daily at midnight |
| `0 9 * * *` | Daily at 9am |
| `0 9 * * 1-5` | Every weekday at 9am |
| `0 9 * * 1` | Every Monday at 9am |
| `0 0 1 * *` | First of every month |

## [​](#examples) Examples

### [​](#daily-standup-summary) Daily Standup Summary

```
cline schedule create "Standup prep" \
  --cron "0 8 * * MON-FRI" \
  --prompt "Summarize: (1) PRs merged yesterday, (2) PRs currently in review, (3) open issues assigned to team members." \
  --workspace /path/to/repo
```

### [​](#weekly-dependency-check) Weekly Dependency Check

```
cline schedule create "Dependency check" \
  --cron "0 10 * * MON" \
  --prompt "Check for outdated npm dependencies. For any with security vulnerabilities, create a branch with the update and open a PR." \
  --workspace /path/to/project
```

### [​](#codebase-health-report) Codebase Health Report

```
cline schedule create "Code health" \
  --cron "0 6 * * MON" \
  --prompt "Analyze the codebase for: (1) files with no test coverage, (2) TODO/FIXME comments older than 30 days, (3) functions longer than 100 lines." \
  --workspace /path/to/project
```

## [​](#routing-results) Routing Results

Combine schedules with [connectors](/cli/connectors) to send results to messaging platforms:

```
cline connect telegram -k $BOT_TOKEN

cline schedule create "Morning briefing" \
  --cron "0 8 * * *" \
  --prompt "Summarize overnight activity in the repo"
```

Scheduling requires the hub. It starts automatically when you create a schedule.

Was this page helpful?

YesNo

[Hooks](/customization/hooks)[Connectors](/cli/connectors)

⌘I

---

## Cline Overview

*Source: [https://docs.cline.bot/cline-overview](https://docs.cline.bot/cline-overview)*

Welcome to the Cline documentation. Whether you’re just getting started or looking to unlock advanced capabilities, you’ll find everything you need here.

## [​](#what-is-cline) What is Cline?

Cline is an AI coding agent that lives in your editor and your terminal. It can read and write files, run terminal commands, use a browser, and help you build features through natural conversation. Every action requires your explicit approval. You’re always in control.

### [​](#agent-core-sdk) Agent Core (SDK)

The SDK is Cline’s agent core—use it to build your own applications, automations, and integrations. See SDK section for detailed functionality and architectural design of the Cline Agent.

## SDK

Build AI agents and integrations powered by the same core engine behind the CLI, Kanban, VS Code extension, and JetBrains plugin.`npm install @cline/sdk`

### [​](#applications) Applications

These are end-user applications built on top of Cline’s agent core:

## CLI

Run Cline in your terminal with interactive chat or fully headless automation for CI/CD and scripting.`npm i -g cline`

## Kanban

Run many agents in parallel from a web-based task board with per-card worktrees, auto-commit, and dependency chains.`npx kanban`

## VS Code Extension

AI coding assistant in your editor. Create files, run commands, browse the web, and use tools with human-in-the-loop approval.

## JetBrains Plugin

The same Cline experience in IntelliJ IDEA, PyCharm, WebStorm, GoLand, and the rest of the JetBrains family.

## [​](#other-ide-supports) Other IDE Supports

Cline works across all major editors: **VS Code**, **Cursor**, **Windsurf**, **JetBrains** (IntelliJ, PyCharm, WebStorm), **Antigravity**, and **Zed**, **Neovim** via ACP mode.

## [​](#enterprise-solutions) Enterprise Solutions

## Security & Governance

SSO, role-based access control, model and tool controls per team, and remote configuration.

## Observability

OpenTelemetry, Datadog, Grafana, Splunk integrations with real-time analytics.

## Team Management

Manage members, roles, and permissions across your organization.

## API Reference

Programmatic access to Cline’s enterprise features.

Was this page helpful?

YesNo

[Installing Cline](/getting-started/installing-cline)

⌘I

---

## Checkpoints

*Source: [https://docs.cline.bot/core-workflows/checkpoints](https://docs.cline.bot/core-workflows/checkpoints)*

Checkpoints let you undo code changes without losing your conversation. Every time Cline modifies a file or runs a command, it saves a snapshot of your project files. You can restore to any checkpoint, keeping the context you’ve built while reverting the code.
This changes how you work with Cline. Instead of carefully reviewing every change before approving, you can let Cline move fast and roll back if something goes wrong. The cost of a mistake drops to nearly zero.

Checkpoints are enabled by default. See [Enable or Disable Checkpoints](#enable-or-disable-checkpoints) if you need to turn them off.

## [​](#how-it-works) How It Works

Cline maintains a shadow Git repository separate from your project’s actual Git history. After each tool use (file edits, commands, etc.), Cline commits the current state of your files to this shadow repo. Your main Git repository stays untouched.
This means:

- Your Git history remains clean and under your control
- Checkpoints capture everything, including files not tracked by Git
- You can restore to any point in a task without affecting commits you’ve made
- Checkpoints persist across editor sessions

Each checkpoint captures the complete file state at that moment. If Cline edits three files in sequence, you get three checkpoints and can restore to any of them independently.

## [​](#enable-or-disable-checkpoints) Enable or Disable Checkpoints

Checkpoints are enabled by default. To toggle them:

1. Open Cline settings (gear icon in the Cline sidebar)
2. Scroll to the “Feature Settings” section
3. Toggle “Enable Checkpoints”

For very large repositories, checkpoints may use significant storage and slow down Cline as it commits file snapshots after each tool use. Consider disabling them if you notice performance issues.

## [​](#viewing-and-comparing-changes) Viewing and Comparing Changes

After each tool use, a checkpoint indicator appears in your conversation. Look for a bookmark icon labeled “Checkpoint” with a dotted line connecting to **Compare** and **Restore** buttons.
Click **Compare** to open a diff view showing exactly what changed at that checkpoint. This opens in your editor’s diff viewer, letting you see additions, deletions, and modifications across all affected files.
This is useful when Cline makes changes you want to understand before deciding whether to keep them. You can review the diff, then either continue or restore to undo.

## [​](#restoring-checkpoints) Restoring Checkpoints

Click **Restore** next to any step to open the restore menu. You have three options:

| Option | What It Does | When to Use It |
| --- | --- | --- |
| **Restore Files** | Reverts your project’s files to the snapshot at this checkpoint | Undoing code changes while keeping the conversation |
| **Restore Task Only** | Deletes messages after this point, does not affect files | Trying a different prompt while keeping current code |
| **Restore Files & Task** | Reverts files and deletes messages after this point | Starting over completely from a known good state |

The right choice depends on what went wrong:

- If the conversation is productive but the code changes broke something, use **Restore Files**. Cline keeps all the context you’ve discussed and can try a different implementation.
- If Cline’s code changes are good but the conversation went off track, use **Restore Task Only**. You keep the files and can guide the conversation differently.
- If you want to start over from a clean slate, use **Restore Files & Task**. This resets both your files and the conversation to that checkpoint.

## [​](#when-to-use-checkpoints) When to Use Checkpoints

| Scenario | Recommended Action |
| --- | --- |
| Cline refactored code and broke something | Restore Files, ask for a different approach |
| Experimenting with multiple solutions | Compare each checkpoint, restore to the best one |
| Cline misunderstood your intent | Restore Files & Task, rephrase your request |
| Want to try a different prompt | Restore Task Only, keep the files, resubmit |
| Reviewing changes before committing to Git | Use Compare to inspect, then commit manually |
| Testing risky changes | Let Cline proceed, restore if it fails |

## [​](#working-with-auto-approve) Working with Auto-Approve

Checkpoints make [auto-approve](/features/auto-approve) practical. Without checkpoints, auto-approve feels risky because Cline can make many changes before you notice a problem. With checkpoints, you can let Cline work autonomously and roll back if needed.
A typical workflow:

1. Enable auto-approve for file edits and commands
2. Let Cline work through your task quickly
3. Review the final result
4. If something is wrong, restore to the last good checkpoint
5. Give Cline more specific guidance

This approach is faster than reviewing every change individually, and checkpoints provide the safety net.

## [​](#checkpoints-and-message-editing) Checkpoints and Message Editing

The message editing feature integrates with checkpoints. When you edit a previous message and select “Restore All,” Cline restores your files to the checkpoint at that point before resubmitting your edited message.
This lets you fix a poorly worded prompt and undo all the changes that resulted from it in one action.

Was this page helpful?

YesNo

[Using Commands](/core-workflows/using-commands)[Agent Teams](/cli/agent-teams)

⌘I

---

## Plan And Act

*Source: [https://docs.cline.bot/core-workflows/plan-and-act](https://docs.cline.bot/core-workflows/plan-and-act)*

Plan & Act modes separate thinking from doing. Plan mode lets you explore and strategize without changing files. Act mode executes against your plan.

**New to Plan & Act?** Watch [Plan & Act Deep Dive](https://youtu.be/b7o6URFPp64) to see it in action.

## [​](#plan-mode) Plan Mode

Plan mode is where you and Cline figure out what you’re building and how. In this mode, Cline can read your codebase, run searches, and discuss strategy, but cannot modify any files or execute commands.
This constraint is intentional. It keeps the conversation focused on understanding and planning, without the distraction of implementation details. You can explore freely, ask questions, and iterate on the approach before committing to changes.
Use Plan mode to:

- Explore unfamiliar codebases before making changes
- Discuss architecture decisions and tradeoffs
- Identify edge cases and potential issues upfront
- Create a clear implementation strategy
- Review code and understand complex workflows

## [​](#act-mode) Act Mode

Once you have a plan, switch to Act mode. Cline retains the full context from your planning session and can now modify files, run commands, and execute your strategy.
The conversation history carries over when you switch modes. Cline remembers everything you discussed in Plan mode, so you don’t need to repeat yourself. This makes the transition seamless.

While you can start directly in Act mode, planning first is highly recommended. The planning phase intentionally builds context that Cline needs to implement changes effectively. Without it, Cline may lack the understanding required to make the right decisions.

## [​](#typical-workflow) Typical Workflow

1. Start in Plan mode and describe what you want to build
2. Let Cline explore relevant files and understand the codebase
3. Discuss the approach, considering edge cases and potential issues
4. When confident in the plan, switch to Act mode
5. Cline implements the solution based on your planning session

For complex projects, you may cycle between modes multiple times. Return to Plan mode when you hit unexpected complexity or need to rethink the approach, then switch back to Act mode to continue implementation.

## [​](#when-to-use-each-mode) When to Use Each Mode

| Scenario | Recommended Mode |
| --- | --- |
| Starting new features where the approach isn’t obvious | Plan |
| Debugging tricky issues where you’re unsure what’s wrong | Plan |
| Making architectural decisions affecting multiple files | Plan |
| Understanding complex workflows before modifying them | Plan |
| Code review and security analysis | Plan |
| Learning a new codebase | Plan |
| Implementing a solution you’ve already planned | Act |
| Making routine changes with a clear approach | Act |
| Following established patterns in the codebase | Act |
| Running tests and making adjustments | Act |
| Quick fixes where the solution is obvious | Act |

## [​](#using-different-models-for-each-mode) Using Different Models for Each Mode

You can configure separate models for Plan and Act modes. This is useful when you want to use a stronger reasoning model for planning and a faster model for implementation.
To enable this:

1. Open Cline Settings
2. Enable “Use different models for Plan and Act”
3. Select your preferred model for each mode

When enabled, switching between Plan and Act mode automatically switches to the configured model for that mode. Your model selection is preserved when you switch back.
**Example configurations:**

| Use Case | Plan Mode | Act Mode |
| --- | --- | --- |
| Cost optimization | GLM 4.6 | Grok Code Fast |
| Maximum quality | Claude Opus | Claude Sonnet |
| Speed-focused | Gemini 3 Flash | Cerebras |

## [​](#using-/deep-planning) Using `/deep-planning`

For complex tasks that need thorough analysis, use the `/deep-planning` slash command. This triggers an extended planning session where Cline:

1. Explores the codebase systematically
2. Identifies all affected files and dependencies
3. Creates a detailed implementation plan
4. Asks clarifying questions before proceeding

The deep planning prompt is optimized for each model family, so it adapts to the strengths of whatever model you’re using. See [/deep-planning](/core-workflows/using-commands#deep-planning) for more details.

## [​](#choosing-the-right-approach-by-task-size) Choosing the Right Approach by Task Size

### [​](#small-tasks-act-mode-only) Small tasks: Act mode only

For quick fixes like typos, simple bug fixes, or following established patterns, start directly in Act mode. Planning adds overhead when the solution is obvious.
**Examples:** Fix a typo, add a missing import, update a config value, rename a variable.

### [​](#medium-tasks-plan-→-act) Medium tasks: Plan → Act

For most development work, start in Plan mode to understand the scope and approach, then switch to Act mode to implement. This is the sweet spot for features that touch a few files and have some complexity.
**Examples:** Add a new API endpoint, implement a UI component, fix a bug that requires investigation, refactor a single module.

### [​](#large-tasks-use-/deep-planning) Large tasks: Use `/deep-planning`

For complex features that span multiple files, require architectural decisions, or will take multiple sessions to complete, use the `/deep-planning` slash command. This creates a detailed implementation plan that Cline can reference throughout the work.
**Examples:** Add a new feature across frontend and backend, major refactoring across the codebase, implementing a new system or integration, multi-step migrations.

## [​](#tips) Tips

- Have Cline write a markdown file summarizing the plan for future reference
- Use [file mentions](/core-workflows/working-with-files) to point Cline at relevant files during planning
- Switch back to Plan mode when encountering unexpected complexity rather than pushing through
- Enable [Checkpoints](/core-workflows/checkpoints) before Act mode so you can roll back if needed
- For large tasks, ask Cline to create a todo list during planning that you can track in Act mode

Was this page helpful?

YesNo

[.clineignore](/customization/clineignore)[Adding Context](/core-workflows/working-with-files)

⌘I

---

## Task Management

*Source: [https://docs.cline.bot/core-workflows/task-management](https://docs.cline.bot/core-workflows/task-management)*

Every interaction with Cline happens within a task. Tasks are self-contained work sessions that capture your entire conversation, code changes, command executions, and decisions.

## [​](#what-are-tasks) What are Tasks?

A task begins when you submit a prompt to Cline. Your prompt defines the goal, and Cline works toward it through conversation, code changes, and tool use. The quality of your initial prompt directly affects how well Cline performs - clear, specific prompts lead to better results.
Each task:

- Starts with your prompt and builds context through the conversation
- Has a unique identifier and dedicated storage directory
- Contains the full conversation history
- Tracks token usage, API costs, and execution time
- Can be interrupted and resumed across sessions
- Creates [checkpoints](/core-workflows/checkpoints) for file changes through Git-based snapshots

Want to get better results from Cline? Learn how to write effective prompts in our [Prompt Module](https://cline.bot/learn).

## [​](#scoping-your-tasks) Scoping Your Tasks

Each task carries its own context: the conversation history, decisions made, and understanding built up over the session. How you scope your tasks directly affects how well Cline can help you.
Think of it this way: **one task = one goal**. “Implement user authentication” is one task. “Fix an unrelated CSS bug” is a separate task, even if you notice it while working on auth.
A focused task produces better results. When a task tries to cover too many unrelated goals, the context becomes cluttered and responses become less relevant.

If you’re unsure, err on the side of starting fresh. You can always find previous sessions in your task history.

### [​](#context-window) Context Window

Every AI model has a context window - a limit on how much information it can process at once. Think of it as Cline’s working memory for the current task.
As you work, the context window fills up with:

- Your prompts and Cline’s responses
- File contents Cline reads or edits
- Command outputs and tool results
- System instructions that guide Cline’s behavior (including [Cline Rules](/customization/cline-rules))

When the context window approaches its limit, Cline automatically compresses older parts of the conversation to make room. This means very long tasks may lose some earlier details, though Cline preserves the most important context.
This is why task scoping matters: a focused task keeps relevant information in the context window. A sprawling task fills the window with noise, pushing out useful context.
If your starting context seems high even for simple prompts, add a [`.clineignore`](/customization/clineignore) file to exclude dependencies, build artifacts, and other files Cline doesn’t need. This can dramatically reduce your baseline token usage.

For long-running tasks, enable [Auto-Compact](/features/auto-compact) to intelligently manage context as you work.

### [​](#new-task-vs-continue) New Task vs. Continue

Knowing when to start fresh versus continue can feel unclear at first. As you work with Cline more, you’ll develop an intuition for it. Use this table as a starting point:

| Scenario | Action | Why |
| --- | --- | --- |
| Switching to a different feature | **New task** | Clean context, focused responses |
| Building on work Cline just completed | **Continue** | Shared understanding preserved |
| Cline keeps going off-track | **New task** | Fighting context wastes time |
| Iterating on the same files | **Continue** | Conversation history helps |
| Explaining what to ignore | **New task** | Cluttered context hurts quality |
| Refining Cline’s last output | **Continue** | Momentum and decisions preserved |

To start a new task, click the **+** button in the Cline sidebar or use the `/newtask` command. Your file changes are preserved through [checkpoints](/core-workflows/checkpoints), and you can reference previous tasks from history anytime.

## [​](#understanding-task-costs) Understanding Task Costs

Every cloud-based AI model charges for usage based on tokens, the units of text the model processes. Cline tracks these costs automatically and displays them in the task header so you can monitor spending as you work.

### [​](#how-costs-are-calculated) How Costs Are Calculated

When you interact with Cline, the model processes:

- **Input tokens**: Your prompts, file contents, conversation history, and system instructions
- **Output tokens**: The model’s responses, code suggestions, and tool calls

Cloud providers charge per million tokens, with output tokens typically costing more than input. Some providers also support **prompt caching**, which reduces costs when the same context (like your cline rules or large files) appears in multiple requests. Cline automatically tracks cache savings when available.
The estimated cost shown in the task header updates after each API request. This estimate uses the pricing information from your selected provider and may vary slightly from your final bill depending on how your provider rounds or bills usage.

### [​](#when-you-pay) When You Pay

You pay for AI usage when using cloud providers like Anthropic, OpenAI, OpenRouter, or Google. Costs vary significantly:

| Provider Type | Billing Model |
| --- | --- |
| **Cline Provider** | Pay-per-use with credits you purchase |
| **Direct API keys** | Billed by your provider (Anthropic, OpenAI, etc.) |
| **OpenRouter/Requesty** | Aggregated billing across multiple models |
| **Local models** | Free (you provide the hardware) |

If you’re using your own API keys, check your provider’s pricing page for current rates. Prices change frequently and vary by model.

### [​](#free-options) Free Options

Not ready to pay? Cline offers several free paths:

- **Free models**: Search “free” in the model selector when using the Cline provider. These models display a **FREE** tag and work well for learning and experimentation.
- **Free tiers**: Some providers offer limited free usage when you use your own API key.
- **Local models**: Run models on your own hardware with zero per-request costs.

### [​](#self-hosted-models) Self-Hosted Models

Running models locally means no API costs, ever. Your only expense is the hardware to run them.
To run local models effectively, you need:

- **32GB RAM minimum** for entry-level models (4-bit quantization)
- **64GB RAM** for better quality (8-bit quantization)
- **128GB+ RAM** for cloud-competitive performance

The trade-off is speed. Local models run at 5-20 tokens per second on typical hardware, compared to hundreds of tokens per second from cloud APIs. They also require more setup and configuration.

If you have the hardware, local models offer unlimited experimentation with complete privacy. See [Running Models Locally](/running-models-locally/overview) to get started.

For most users, starting with free cloud models and moving to paid options as needed provides the best balance of cost, speed, and capability. Check [Selecting Your Model](/getting-started/authorizing-with-cline) for guidance on choosing the right option for your workflow.

## [​](#task-history) Task History

Every task you work on is saved automatically to your local machine. You can revisit past conversations, resume interrupted work, or reference successful approaches from earlier sessions.

### [​](#finding-your-history) Finding Your History

Click the **History** button in the Cline sidebar (clock icon at the top-right) to open the history view. You’ll see all your past tasks with their initial prompt, timestamp, and token usage. Each task card expands to show a preview of the conversation.

### [​](#searching-tasks) Searching Tasks

Use the search bar at the top of the history view to find specific tasks. The fuzzy search looks across everything: your prompts, Cline’s responses, code snippets, and file names.
Sort results by:

- **Newest/Oldest** for chronological browsing
- **Most Expensive/Most Tokens** to find resource-heavy tasks
- **Most Relevant** when searching for specific content
- **Favorites** to show only starred tasks

Use favorites strategically. Star tasks that represent successful patterns, good prompts, or complex work you might want to reference later. Favorited tasks are protected from deletion.

## [​](#resuming-tasks) Resuming Tasks

Cline can resume interrupted tasks with full context:

1. Open the task from history
2. Cline loads the complete conversation
3. File states are checked against [checkpoints](/core-workflows/checkpoints)
4. The task continues with awareness of the interruption
5. Provide additional context if needed

This works across sessions. Even if you close the editor and return days later, Cline can pick up where you left off.

Was this page helpful?

YesNo

⌘I

---

## Using Commands

*Source: [https://docs.cline.bot/core-workflows/using-commands](https://docs.cline.bot/core-workflows/using-commands)*

Cline provides slash commands in chat that help you manage your conversation and plan complex implementations.

**New to slash commands?** Watch our [quick video walkthrough](https://youtu.be/MxS5Jerpf-o) to see these commands in action.

## [​](#slash-commands) Slash Commands

Type `/` in the chat input to see available slash commands:

| Command | What It Does |
| --- | --- |
| `/newtask` | Start fresh task with distilled context from current conversation |
| `/smol` | Compress conversation history while preserving essential context |
| `/newrule` | Create a rule file to teach Cline your preferences |
| `/deep-planning` | Investigate codebase, plan thoroughly, then create implementation task |
| `/explain-changes` | Generate AI explanations for any git diff (VS Code only) |
| `/reportbug` | Report a bug with diagnostic info |

### [​](#/newtask) /newtask

`/newtask` works like a developer handoff. It packages what matters (overall plan, work accomplished, relevant files, next steps) into a fresh task with a clean context window, leaving behind the noise of tool calls and implementation details.
I use `/newtask` when working through complex implementations. If I’ve completed 3 steps of a 10-step process and my context is already 75% full, I use `/newtask` to extract key decisions, file changes, and progress without all the noise.

### [​](#/smol) /smol

`/smol` (or its alias `/compact`) compresses your conversation history while preserving essential context. Unlike `/newtask` which creates a new task, `/smol` condenses your current conversation into a comprehensive summary, freeing up context window space while allowing you to continue working in the same task.
Use `/smol` when you’re deep into a debugging session or brainstorming and need to continue in the same task without losing the insights you’ve gained. For more details, see [Smol Command](#smol).

### [​](#/newrule) /newrule

`/newrule` creates a rule file that teaches Cline your preferences. Cline will guide you through setting up guidelines for communication style, coding standards, project context, and reusable practices. The rule is saved to your `.clinerules` directory and automatically loaded for future conversations.
Use `/newrule` when you find yourself repeating the same instructions across tasks. For more about rules, see [Cline Rules](/customization/cline-rules).

### [​](#/deep-planning) /deep-planning

Transform Cline into a meticulous architect who investigates your codebase, asks clarifying questions, and creates a comprehensive implementation plan before writing any code. Deep planning follows a four-step process:

1. **Silent Investigation** - Cline explores your codebase structure and patterns
2. **Discussion** - Targeted questions about requirements and approach
3. **Plan Creation** - Generates `implementation_plan.md` with detailed specifications
4. **Task Creation** - Creates a new task with trackable implementation steps

Use `/deep-planning` for features touching multiple parts of your codebase, architectural changes, or complex integrations.

### [​](#/explain-changes) /explain-changes

This command is only available in VS Code.

`/explain-changes` generates AI-powered explanations for any git diff. You can explain the last commit, uncommitted work, staged changes, specific commits, branches, PRs, or any range of changes.
Use `/explain-changes` when reviewing code, onboarding to a new codebase, or understanding what changed. For the full list of use cases and examples, see [Explain Changes Command](#explain-changes).

### [​](#/reportbug) /reportbug

`/reportbug` collects diagnostic information and helps you report issues with Cline. It gathers relevant context like your configuration, recent errors, and system details to make bug reports more useful for the development team.
Use `/reportbug` when you encounter unexpected behavior, crashes, or bugs you want to report.

## [​](#skills-via-slash-commands) Skills via Slash Commands

In addition to built-in commands, you can trigger enabled skills directly from chat using slash commands.

- Type `/` to open command suggestions.
- Select a skill command (for example, `/aws-deploy`).
- Cline loads that skill and applies its `SKILL.md` instructions for the task.

Any enabled skill can be triggered this way, which gives you a fast path to skill-specific guidance without rewriting the same instructions each time.
For setup and management details, see [Skills](/customization/skills#triggering-skills-with-slash-commands).

Was this page helpful?

YesNo

[Adding Context](/core-workflows/working-with-files)[Checkpoints](/core-workflows/checkpoints)

⌘I

---

## Working With Files

*Source: [https://docs.cline.bot/core-workflows/working-with-files](https://docs.cline.bot/core-workflows/working-with-files)*

Cline works best when it has the right context, not just more context. `@` mentions let you pull in the files and folders that matter for your task — no copying, no pasting, no context switching.
You can add context two ways:

- Type `@` in the chat input and select a file or folder
- Click the **+** button in the bottom left to browse files or images

## [​](#quick-reference) Quick Reference

| What you want | Syntax | Example |
| --- | --- | --- |
| File content | `@/path/to/file` | `@/src/index.ts` |
| Folder contents | `@/path/to/folder/` | `@/src/components/` |

For other context — git history, web pages, terminal errors — just describe it. Cline will run `git log`, fetch the URL, or read the output itself.

## [​](#file-mentions) File Mentions

Reference any file with `@/path/to/file`. Cline sees the complete file content, including imports, related functions, and surrounding context.

```
Can you refactor the error handling in @/src/api/users.ts?
```

## [​](#folder-mentions) Folder Mentions

Reference entire directories with `@/path/to/folder/` (note the trailing slash). Cline sees the folder structure and all file contents.

```
Explain how the components in @/src/components/auth/ work together.
```

In multi-root workspaces, prefix paths with the workspace name: `@workspace-name:/path/to/file`

## [​](#drag-&-drop) Drag & Drop

Drag files directly into the chat input to add them to your conversation.

In VS Code, hold **Shift** while dragging files into the chat input.

Dragging workspace files automatically creates file mentions. You can also drag files from Finder or File Explorer directly into Cline.

### [​](#supported-file-types) Supported File Types

Cline supports text files from your workspace, plus images, PDFs, CSVs, and Excel files from your file system.

Images require a multimodal model. Check the model selector to see which models support image inputs.

## [​](#context-menu-commands) Context Menu Commands

Right-click on selected code to access Cline without typing. This is the fastest way to get help with specific code since it automatically includes the selected text and its file location as context.

### [​](#code-editor-commands) Code Editor Commands

| Command | When to Use |
| --- | --- |
| **Add to Cline** | Ask questions about code, get suggestions, or start a conversation with specific code as context |
| **Fix with Cline** | Quick fixes for errors, bugs, or issues in the selected code |
| **Explain with Cline** | Understand unfamiliar code, complex logic, or code you’re reviewing |
| **Improve with Cline** | Get refactoring suggestions, performance improvements, or cleaner implementations |

**Fix with Cline** also appears in the lightbulb menu (Quick Fix) when your cursor is on an error or warning, making it easy to fix issues inline.

### [​](#terminal-commands) Terminal Commands

Right-click in the terminal to “Add to Cline” and get help with:

- Build errors and failed commands
- Test failures and stack traces
- Configuration issues
- Any terminal output you need help interpreting

### [​](#source-control-commands) Source Control Commands

In the Source Control panel, use “Generate Commit Message” to create AI-powered commit messages from your staged changes. Cline analyzes the diff and writes a descriptive commit message following conventional commit patterns.

Was this page helpful?

YesNo

[Plan & Act Mode](/core-workflows/plan-and-act)[Using Commands](/core-workflows/using-commands)

⌘I

---

## Cline Rules

*Source: [https://docs.cline.bot/customization/cline-rules](https://docs.cline.bot/customization/cline-rules)*

Rules are markdown files that provide persistent instructions across all conversations. Instead of repeating the same preferences every time you start a new task, rules let you define them once and have Cline follow them automatically.
Use rules when you want Cline to:

- Follow your team’s coding standards (naming conventions, file organization, error handling patterns)
- Understand project-specific context (tech stack, architecture decisions, dependencies)
- Apply consistent documentation or testing requirements
- Remember constraints like “don’t modify files in /legacy” or “always use TypeScript”

**New to Rules?** Watch [Cline Rules Explained](https://youtu.be/xQwsy2vkK5M) to see them in action.

## [​](#supported-rule-types) Supported Rule Types

Cline recognizes rules from multiple sources, so you can use existing rule files from other tools:

| Rule Type | Location | Description |
| --- | --- | --- |
| Cline Rules | `.clinerules/` | Primary rule format |
| Cursor Rules | `.cursorrules` | Automatically detected |
| Windsurf Rules | `.windsurfrules` | Automatically detected |
| AGENTS.md | `AGENTS.md`, `~/.agents/AGENTS.md` | [Standard format](https://agents.md/) for cross-tool compatibility |

All detected rule types appear in the Rules panel, where you can toggle them individually.

## [​](#where-rules-live) Where Rules Live

Rules can be stored in two locations: your project workspace or globally on your system.
**Workspace rules** go in `.clinerules/` at your project root. Use these for team standards, project-specific constraints, and anything you want to share with collaborators via version control.
**Global rules** go in your system’s Cline Rules directory. Use these for personal preferences that apply across all projects. Cline also reads cross-tool global AGENTS instructions from `~/.agents/AGENTS.md`.

```
your-project/
├── .clinerules/              # Workspace rules
│   ├── coding.md             # Coding standards
│   ├── testing.md            # Test requirements
│   └── architecture.md       # Structural decisions
├── src/
└── ...
```

Cline processes all `.md` and `.txt` files inside `.clinerules/`, combining them into a unified set of rules. Numeric prefixes (like `01-coding.md`) help organize files but are optional.
When both workspace and global rules exist, Cline combines them. Workspace rules take precedence when they conflict with global rules. See [Storage Locations](/getting-started/config#storage-locations) for more guidance.

### [​](#global-rules-directory) Global Rules Directory

| Operating System | Default Location |
| --- | --- |
| Windows | `Documents\Cline\Rules` |
| macOS | `~/Documents/Cline/Rules` |
| Linux/WSL | `~/Documents/Cline/Rules` |

Linux/WSL users: If you don’t find global rules in `~/Documents/Cline/Rules`, check `~/Cline/Rules`.

## [​](#creating-rules) Creating Rules

1

Open the Rules menu

Click the scale icon at the bottom of the Cline panel, to the left of the model selector.

2

Create a new rule file

Click “New rule file…” and enter a filename (e.g., `coding-standards`). The file will be created with a `.md` extension.

3

Write your rule

Add your instructions in markdown format. Keep each rule file focused on a single concern.

You can also use the [`/newrule` slash command](/core-workflows/using-commands#newrule) to have Cline create a rule interactively.

### [​](#toggling-rules) Toggling Rules

Every rule has a toggle to enable or disable it. This gives you fine-grained control over which rules apply to your current task without deleting the rule file.
For example, you might have a strict testing rule that you want to disable when prototyping, or a client-specific rule you only need when working on that client’s features.

## [​](#writing-effective-rules) Writing Effective Rules

### [​](#structure) Structure

Rules work best when they’re scannable and specific. Use markdown structure to organize instructions:

```
# Rule Title

Brief context about why this rule exists (optional but helpful).

## Category 1
- Specific instruction
- Another instruction with example: `like this`
- Reference to file: see /src/utils/example.ts

## Category 2
- More instructions
- Include the "why" when it's not obvious
```

Cline reads rules as context, so formatting matters. Headers help Cline understand the scope of each instruction. Bullet points make individual requirements clear. Code examples show exactly what you want.

### [​](#best-practices) Best Practices

**Be specific, not vague.** “Use descriptive variable names” is too broad. “Use camelCase for variables, PascalCase for classes, UPPER\_SNAKE for constants” gives Cline something concrete to follow.
**Include the why.** When a rule might seem arbitrary, explain the reason. “Don’t modify files in /legacy (this code is scheduled for removal in Q2)” helps Cline make better decisions in edge cases.
**Point to examples.** If your codebase already demonstrates the pattern you want, reference it. “Follow the error handling pattern in /src/utils/errors.ts” is more effective than describing the pattern from scratch.
**Keep rules current.** Outdated rules confuse Cline and waste context. If a constraint no longer applies, remove it. If your tech stack changes, update the rules.
**One concern per file.** Split rules by topic: `coding.md` for style, `testing.md` for test requirements, `architecture.md` for structural decisions. This makes it easy to toggle specific rules on or off.

Rules consume context tokens. Avoid lengthy explanations or pasting entire style guides. Keep rules concise and link to external documentation when detailed reference is needed.

## [​](#example) Example

```
# Project Guidelines

## Code Style
- Use TypeScript for all new files
- Prefer composition over inheritance
- Use repository pattern for data access
- Follow error handling pattern in /src/utils/errors.ts

## Documentation
- Update relevant docs when modifying features
- Keep README.md in sync with new capabilities

## Testing
- Unit tests required for business logic
- Integration tests for API endpoints
- E2E tests for critical user flows
```

## [​](#conditional-rules) Conditional Rules

Conditional rules let you scope rules to specific parts of your codebase. Rules activate only when you’re working with matching files, keeping your context focused and relevant.

- **Without conditionals**: every rule loads for every request.
- **With conditionals**, rules activate only when your current files match their defined scope.

For example, documentation style rules should only appear when you’re editing docs, not when you’re writing application code or tests.
As your rule library grows, loading every rule for every request wastes context tokens and can dilute Cline’s focus. Conditional rules solve this by giving Cline only the instructions that matter for the files you’re actually touching. This means faster, more accurate responses. Your frontend rules won’t compete for attention when you’re deep in backend code, and your testing standards appear exactly when you’re writing tests. It’s the difference between handing someone an entire policy manual versus the one page they need right now.

### [​](#how-it-works) How It Works

Conditional rules use YAML frontmatter at the top of your rule files. When Cline processes a request, it gathers context from your current work (open files, visible tabs, mentioned paths, edited files), evaluates each rule’s conditions, and activates matching rules.

When a conditional rule activates, you’ll see a notification: **“Conditional rules applied: workspace:frontend-rules.md”**

### [​](#writing-conditional-rules) Writing Conditional Rules

Add YAML frontmatter to the top of any rule file in your `.clinerules/` directory:

```
---
paths:
  - "src/components/**"
  - "src/hooks/**"
---

# React Component Guidelines

When creating or modifying React components:
- Use functional components with React hooks
- Extract reusable logic into custom React hooks
- Keep components focused on a single responsibility
```

The `---` markers delimit the frontmatter. Everything after the closing `---` is your rule content.

#### [​](#the-paths-conditional) The `paths` Conditional

Currently, `paths` is the supported conditional. It takes an array of glob patterns:

```
---
paths:
  - "src/**"           # All files under src/
  - "*.config.js"      # Config files in root
  - "packages/*/src/"  # Monorepo package sources
---
```

**Glob pattern syntax:**

- `*` matches any characters except `/`
- `**` matches any characters including `/` (recursive)
- `?` matches a single character
- `[abc]` matches any character in the brackets
- `{a,b}` matches either pattern

| Pattern | Matches |
| --- | --- |
| `src/**/*.ts` | All TypeScript files under `src/` |
| `*.md` | Markdown files in root only |
| `**/*.test.ts` | Test files anywhere in the project |
| `packages/{web,api}/**` | Files in web or api packages |
| `src/components/*.tsx` | TSX files directly in components (not nested) |

#### [​](#behavior-details) Behavior Details

**Multiple patterns**: A rule activates if any pattern matches any file in your context.

```
---
paths:
  - "frontend/**"
  - "mobile/**"
---
# Activates when working in frontend OR mobile
```

**No frontmatter**: Rules without frontmatter are always active.
**Empty paths array**: `paths: []` means the rule never activates. Use this to temporarily disable a rule.
**Invalid YAML**: If frontmatter can’t be parsed, Cline fails open. The rule activates with raw content visible to help debugging.

### [​](#what-counts-as-“current-context”) What Counts as “Current Context”

Cline evaluates rules based on:

1. **Your message**: File paths mentioned in your prompt (e.g., “update `src/App.tsx`”)
2. **Open tabs**: Files currently open in your editor
3. **Visible files**: Files visible in your active editor panes
4. **Edited files**: Files Cline has created, modified, or deleted during the task
5. **Pending operations**: Files Cline is about to edit

Conditional rules can activate on your first message, when relevant files are open, or mid-task when Cline starts working with matching files.

Be explicit about file paths in your prompts. “Update `src/services/user.ts`” reliably triggers path-based rules; “update the user service” may not.

### [​](#practical-examples) Practical Examples

Copy these patterns and adapt them to your project structure.

#### [​](#frontend-vs-backend-rules) Frontend vs Backend Rules

Keep frontend and backend rules separate to avoid noise. Frontend rules only load when working with UI code, backend rules only load when working with API or service code.

```
# .clinerules/frontend.md
---
paths:
  - "src/components/**"
  - "src/pages/**"
  - "src/hooks/**"
---

# Frontend Guidelines

- Use Tailwind CSS for styling
- Prefer server components where possible
- Keep client components small and focused
```

```
# .clinerules/backend.md
---
paths:
  - "src/api/**"
  - "src/services/**"
  - "src/db/**"
---

# Backend Guidelines

- Use dependency injection for services
- All database queries go through repositories
- Return typed errors, not thrown exceptions
```

#### [​](#test-file-rules) Test File Rules

Enforce testing standards automatically. This rule activates only when you’re writing or modifying tests, so testing guidance appears exactly when you need it.

```
# .clinerules/testing.md
---
paths:
  - "**/*.test.ts"
  - "**/*.spec.ts"
  - "**/__tests__/**"
---

# Testing Standards

- Use descriptive test names: "should [expected behavior] when [condition]"
- One assertion per test when possible
- Mock external dependencies, not internal modules
- Use factories for test data, not fixtures
```

#### [​](#documentation-rules) Documentation Rules

Apply documentation standards only when editing docs. Prevents style rules from cluttering your context when you’re writing code.

```
# .clinerules/docs.md
---
paths:
  - "docs/**"
  - "**/*.md"
  - "**/*.mdx"
---

# Documentation Guidelines

- Use sentence case for headings
- Include code examples for all features
- Keep paragraphs short (3-4 sentences max)
- Link to related documentation
```

### [​](#combining-with-rule-toggles) Combining with Rule Toggles

Conditional rules work alongside the rule toggle UI. Toggle off a conditional rule to disable it entirely (it won’t activate even if paths match). Toggle on to let it activate when conditions are met.
This provides two levels of control: manual toggles and automatic condition-based activation.

### [​](#tips-for-effective-conditional-rules) Tips for Effective Conditional Rules

**Start Broad, Then Narrow.** Begin with broader patterns and refine as you learn what works:

```
# Start here
paths:
  - "src/**"

# Then narrow down
paths:
  - "src/features/auth/**"
```

**Use Descriptive Filenames.** Name your rule files to indicate their scope:

```
.clinerules/
├── api-endpoints.md      # Rules for API code
├── database-models.md    # Rules for DB layer
├── react-components.md   # Rules for React
└── universal.md          # No frontmatter = always active
```

**Keep Universal Rules Separate.** Put always-on rules (coding standards, project conventions) in files without frontmatter. Reserve conditional rules for context-specific guidance.
**Test Your Patterns.** Not sure if a pattern matches? Create a simple test rule:

```
---
paths:
  - "your/pattern/here/**"
---
TEST: This rule should activate for your/pattern/here files.
```

Then work with a file in that path and check if you see the activation notification.

### [​](#troubleshooting-conditional-rules) Troubleshooting Conditional Rules

**Rule not activating:**

- Check that file paths in your context match the glob pattern
- Verify the rule is toggled on in the rules panel
- Ensure YAML frontmatter has proper `---` delimiters

**Rule activating unexpectedly:**

- Review glob patterns. `**` is recursive and may match more than intended
- Check for open files that match the pattern
- File paths mentioned in your message also count as context

**Frontmatter showing in output:**

- YAML couldn’t be parsed
- Check for syntax errors (unquoted special characters, improper indentation)

Was this page helpful?

YesNo

[Tools](/tools-reference/all-cline-tools)[Skills](/customization/skills)

⌘I

---

## Clineignore

*Source: [https://docs.cline.bot/customization/clineignore](https://docs.cline.bot/customization/clineignore)*

The `.clineignore` file tells Cline which files and directories to skip when analyzing your codebase. It works like `.gitignore`: create a file named `.clineignore` in your project root, add patterns for files you want excluded, and Cline will ignore them.

## [​](#why-it-matters) Why It Matters

Without a `.clineignore`, Cline may load your entire project into context, including dependencies, build artifacts, and generated files. This wastes tokens, increases costs, and can push useful context out of the window.
Adding a `.clineignore` can cut your starting context from 200k+ tokens to under 50k. That means faster responses, lower costs, and the ability to use smaller, cheaper models effectively.

## [​](#creating-a-clineignore) Creating a .clineignore

Create a file named `.clineignore` in your project root:

```
# Dependencies
node_modules/
**/node_modules/

# Build outputs
/build/
/dist/
/.next/
/out/

# Testing artifacts
/coverage/

# Environment variables
.env
.env.*

# Large data files
*.csv
*.xlsx
*.sqlite

# Generated/minified code
*.min.js
*.map
```

## [​](#pattern-syntax) Pattern Syntax

`.clineignore` uses the same pattern syntax as `.gitignore`:

| Pattern | Matches |
| --- | --- |
| `node_modules/` | The `node_modules` directory |
| `**/node_modules/` | `node_modules` at any depth |
| `*.csv` | All CSV files |
| `/build/` | The `build` directory at the project root only |
| `*.env.*` | Files like `.env.local`, `.env.production` |
| `!important.csv` | Exception: do not ignore this file |

Lines starting with `#` are comments. Blank lines are ignored.

## [​](#what-to-exclude) What to Exclude

Start with these categories and adjust for your project:
**Almost always exclude:**

- Package manager directories (`node_modules/`, `vendor/`, `.venv/`)
- Build outputs (`dist/`, `build/`, `.next/`, `out/`)
- Coverage reports (`coverage/`)
- Lock files if large (`package-lock.json`, `yarn.lock`)

**Exclude if present:**

- Large data files (`.csv`, `.xlsx`, `.sqlite`, `.parquet`)
- Binary assets (images, fonts, videos)
- Generated code (API clients, protobuf outputs, minified bundles)
- Environment files with secrets (`.env`, `.env.local`)

**Keep accessible:**

- Source code you actively work on
- Configuration files Cline needs to understand (`tsconfig.json`, `package.json`)
- Documentation and READMEs
- Test files (Cline often needs these for context)

## [​](#how-it-works) How It Works

When Cline scans your project to build context, it checks each file path against your `.clineignore` patterns. Matching files are excluded from:

- The file listing Cline sees when starting a task
- Automatic context gathering during conversations
- Search results when Cline looks for relevant code

You can still reference ignored files explicitly using [@ mentions](/core-workflows/working-with-files). If you type `@/node_modules/some-package/index.js`, Cline will read that specific file even though `node_modules/` is in your `.clineignore`. The ignore rules control automatic loading, not explicit access.

`.clineignore` is separate from `.gitignore`. Files tracked by Git but irrelevant to Cline (like large test fixtures or data files) should go in `.clineignore` even if they’re not in `.gitignore`.

## [​](#tips) Tips

- Add `.clineignore` early in your project. It’s easier to start with broad exclusions and narrow them than to debug why context is bloated later.
- Check your token usage in the task header after adding a `.clineignore`. The difference is often dramatic.
- If Cline seems to be missing context about a file, check whether it’s being excluded by your ignore patterns.
- For monorepos or multi-root workspaces, each workspace root can have its own `.clineignore`. See [Multi-Root Workspaces](/features/multiroot-workspace) for details.

## [​](#related) Related

- [Cline Rules](/customization/cline-rules) - Define persistent instructions for Cline
- [Task Management](/core-workflows/task-management#context-window) - Understand how context windows work
- [Auto-Compact](/features/auto-compact) - Automatic context compression during long tasks

Was this page helpful?

YesNo

[Connectors](/cli/connectors)[Plan & Act Mode](/core-workflows/plan-and-act)

⌘I

---

## Hooks

*Source: [https://docs.cline.bot/customization/hooks](https://docs.cline.bot/customization/hooks)*

See details under [SDK Plugins](/sdk/plugins).

Was this page helpful?

YesNo

[MCP](/mcp/mcp-overview)[Scheduling](/cli/scheduling)

⌘I

---

## Plugins

*Source: [https://docs.cline.bot/customization/plugins](https://docs.cline.bot/customization/plugins)*

This feature currently only applies to Cline SDK, CLI, and Kanban. This feature is not applicable on VSCode and JetBrains Extension for now.

Plugins extend Cline with custom tools, lifecycle hooks, slash commands, and more. They can be installed globally (available in all sessions) or per-project.

## [​](#installing-plugins-via-cli) Installing Plugins via CLI

The `cline plugin install` command installs plugins from four source types:

- File URL
- Git Repository
- npm Package
- Local Path

```
cline plugin install https://github.com/owner/repo/blob/main/plugins/my-plugin.ts
cline plugin install https://raw.githubusercontent.com/owner/repo/main/plugins/my-plugin.ts
```

File URLs install a single `.ts` or `.js` plugin file directly. GitHub `blob` and raw URLs are supported, and remote plugin file URLs must use `https://`.

```
cline plugin install https://github.com/owner/repo.git
cline plugin install git@github.com:owner/repo.git
```

The installer clones the repository, installs production dependencies, and registers the plugin entry files.To install a specific branch or tag, append `@ref`:

```
cline plugin install https://github.com/owner/repo.git@v1.2.0
cline plugin install https://github.com/owner/repo.git@main
```

```
cline plugin install npm:@scope/my-plugin
cline plugin install --npm my-plugin
```

```
cline plugin install ./my-plugin
cline plugin install ~/plugins/my-tool
cline plugin install /absolute/path/to/plugin.ts
```

Local installs copy the file or directory into the plugin store. Both single `.ts`/`.js` files and directories with a `package.json` are supported.

Additional flags:

| Flag | Description |
| --- | --- |
| `--force` | Replace an existing install for the same source |
| `--json` | Output the result as JSON (useful for scripting) |
| `--cwd <path>` | Install to `<path>/.cline/plugins` instead of the global directory |

After installation, confirm the plugin is loaded by running `cline config` and checking the plugin tab.

### [​](#example-typescript-navigation-plugin) Example: TypeScript Navigation Plugin

The [typescript-lsp-plugin](https://github.com/cline/typescript-lsp-plugin) is a good reference for how plugins work. It adds a `goto_definition` tool that uses the TypeScript Language Service API to resolve symbol definitions through imports, re-exports, and type aliases.
Install it with:

```
cline plugin install https://github.com/cline/typescript-lsp-plugin.git
```

Once installed, Cline can call `goto_definition` with a file path and line number to find where symbols are defined, which is much more precise than text search.

## [​](#plugin-manifest-format) Plugin Manifest Format

For a repository or npm package to be installable as a Cline plugin, its `package.json` should include a `cline` field that declares plugin entry points:

```
{
  "name": "my-cline-plugin",
  "version": "1.0.0",
  "cline": {
    "plugins": [
      {
        "paths": ["./index.ts"],
        "capabilities": ["tools", "hooks"]
      }
    ]
  }
}
```

The `cline.plugins` array accepts:

| Format | Example |
| --- | --- |
| Object with `paths` array | `{ "paths": ["./src/plugin.ts"], "capabilities": ["tools"] }` |
| Plain string | `"./index.ts"` |

Each path should point to a `.ts` or `.js` file that exports an `AgentPlugin` (either as the default export or a named export).
If no `cline.plugins` field is present, the installer falls back to auto-discovery: it looks for standard entry points, then recursively scans for `.ts` and `.js` files (skipping `node_modules` and `.git`).

### [​](#host-provided-dependencies) Host-Provided Dependencies

Dependencies under the `@cline/` scope are provided by the host runtime. The installer automatically strips these from the plugin’s dependency list before running `npm install`, so declare any `@cline/*` package your plugin imports as an optional peer dependency. The host currently provides `@cline/sdk`, `@cline/core`, `@cline/agents`, `@cline/llms`, and `@cline/shared`.

```
{
  "peerDependencies": {
    "@cline/sdk": "*"
  },
  "peerDependenciesMeta": {
    "@cline/sdk": {
      "optional": true
    }
  }
}
```

## [​](#plugin-directory-structure) Plugin Directory Structure

Plugins are stored in the `plugins` directory at two levels:

```
~/.cline/
  plugins/                     # Global plugins
    _installed/                # Managed by `cline plugin install`
      npm/                     # npm-sourced plugins
      git/                     # git-sourced plugins
      remote/                  # file URL-sourced plugins
      local/                   # local-sourced plugins

.cline/                        # Project root
  plugins/                     # Project-scoped plugins
```

Global plugins (`~/.cline/plugins/`) are available across all sessions. Project plugins (`.cline/plugins/` in your repo) are available only when working in that project.

## [​](#writing-plugins) Writing Plugins

For a guide on building plugins with the SDK, see [Writing Plugins](/sdk/guides/writing-plugins). For the plugin API reference, see [SDK Plugins](/sdk/plugins).

Was this page helpful?

YesNo

[Skills](/customization/skills)[MCP](/mcp/mcp-overview)

⌘I

---

## Skills

*Source: [https://docs.cline.bot/customization/skills](https://docs.cline.bot/customization/skills)*

Skills are modular instruction sets that extend Cline’s capabilities for specific tasks. Each skill packages detailed guidance, processes, and optional resources that Cline loads only when relevant to your request.
Install multiple skills and Cline only loads what it needs. A deployment skill stays dormant until you ask about deploying. Unlike [rules](/customization/cline-rules) (which are always active), skills load on-demand so they don’t consume context when you’re working on something unrelated.

Skills is an experimental feature. Enable it in **Settings → Features → Enable Skills**.

## [​](#how-skills-work) How Skills Work

Skills use progressive loading to maximize efficiency:

| Level | When Loaded | Token Cost | Content |
| --- | --- | --- | --- |
| Metadata | Always (at startup) | ~100 tokens per skill | `name` and `description` from YAML frontmatter |
| Instructions | When skill is triggered | Under 5k tokens | SKILL.md body with instructions and guidance |
| Resources | As needed | Effectively unlimited | Bundled files accessed via `read_file` or executed scripts |

When you send a message, Cline sees a list of available skills with their descriptions. If your request matches a skill’s description, Cline activates it using the `use_skill` tool, which loads the full instructions from SKILL.md.

## [​](#triggering-skills-with-slash-commands) Triggering Skills with Slash Commands

You can also invoke enabled skills explicitly from the chat input using slash commands.

1. Type `/` in chat to open command suggestions.
2. Select the skill command you want to run (for example, `/aws-deploy`).
3. Cline triggers that skill and loads its `SKILL.md` instructions.

This is useful when you want to force a specific skill immediately instead of waiting for auto-matching based on description.

## [​](#skill-structure) Skill Structure

Every skill is a directory containing a `SKILL.md` file with YAML frontmatter.

Skill directory structure

```
my-skill/
├── SKILL.md          # Required: main instructions
├── docs/             # Optional: additional documentation
│   └── advanced.md
└── scripts/          # Optional: utility scripts
    └── helper.sh
```

The `SKILL.md` file has two parts: metadata and instructions.

SKILL.md

```
---
name: my-skill
description: Brief description of what this skill does and when to use it.
---

# My Skill

Detailed instructions for Cline to follow when this skill is activated.

## Steps
1. First, do this
2. Then do that
3. For advanced usage, see [advanced.md](docs/advanced.md)
```

Required fields:

- `name` must exactly match the directory name
- `description` tells Cline when to use this skill (max 1024 characters)

## [​](#creating-a-skill) Creating a Skill

1

Open the Skills menu

Click the scale icon at the bottom of the Cline panel, to the left of the model selector. Switch to the Skills tab.

2

Create a new skill

Click “New skill…” and enter a name for your skill (e.g., `aws-deploy`). Cline creates a skill directory with a template `SKILL.md` file.

3

Write your skill instructions

Edit the `SKILL.md` file:

- Update the `description` field to specify when this skill should trigger
- Add detailed instructions in the body
- Optionally add supporting files in `docs/`, `templates/`, or `scripts/` subdirectories

You can also create skills manually by creating the directory structure in your file system. Place skill directories in `.cline/skills/` (workspace) or `~/.cline/skills/` (global) and Cline will detect them automatically.
Put the important information first in your SKILL.md. Cline reads the file sequentially, so front-load the common cases. Use clear section headers like ”## Error Handling” or ”## Configuration” so Cline can scan for relevant sections.

### [​](#toggling-skills) Toggling Skills

Every skill has a toggle to enable or disable it. This lets you control which skills are active without deleting the skill directory. Skills are enabled by default when discovered.
For example, you might disable a CI/CD skill when working on local development, or enable a client-specific skill only when working on that client’s project.

## [​](#writing-your-skill-md) Writing Your SKILL.md

### [​](#naming-conventions) Naming Conventions

The skill name appears in the `name` field and must match the directory name exactly. Use lowercase with hyphens (kebab-case) and be descriptive about what the skill does.
Good names:

- `aws-cdk-deploy`
- `pr-review-checklist`
- `database-migration`
- `api-client-generator`

Avoid:

- `aws` (too vague)
- `my_skill` (underscores, not descriptive)
- `DeployToAWS` (use kebab-case, not PascalCase)
- `misc-helpers` (too generic)

### [​](#writing-effective-descriptions) Writing Effective Descriptions

The description determines when Cline activates the skill. A vague description means the skill won’t trigger when you expect it to.
Good descriptions are specific and actionable:

```
description: Deploy applications to AWS using CDK. Use when deploying, updating infrastructure, or managing AWS resources.

description: Generate release notes from git commits. Use when preparing releases, writing changelogs, or summarizing recent changes.

description: Analyze CSV and Excel data files. Use when exploring datasets, generating statistics, or creating visualizations from tabular data.
```

Weak descriptions leave too much ambiguity:

```
description: Helps with AWS stuff.

description: Data analysis helper.

description: Useful for releases.
```

Start with what the skill does (action verbs), include trigger phrases users might say, and mention specific file types, tools, or domains. Test your descriptions by trying different phrasings of requests to see if the skill triggers.

### [​](#keeping-skills-focused) Keeping Skills Focused

Keep SKILL.md under 5k tokens. If your skill needs more content, split it into separate files in a `docs/` directory and reference them from the main instructions. Cline loads referenced files only when needed.
Include real examples. Show what commands to run, what output to expect, and what the result should look like. Abstract instructions are harder to follow than concrete examples.

## [​](#where-skills-live) Where Skills Live

Skills can be stored globally or in a project workspace. See [Storage Locations](/getting-started/config#storage-locations) for guidance on when to use each.
Project skills:

- `.cline/skills/` (recommended)
- `.clinerules/skills/`
- `.claude/skills/`

Global skills:

- `~/.cline/skills/` (macOS/Linux)
- `C:\Users\USERNAME\.cline\skills\` (Windows)

When a global skill and project skill have the same name, the global skill takes precedence. This lets you keep general-purpose skills globally while using project-specific skills in `.cline/skills/` so the whole team can use them.
Version control your project skills by committing `.cline/skills/`. Your team can share, review, and improve them together.

## [​](#bundling-supporting-files) Bundling Supporting Files

Skills can include additional files that Cline accesses only when needed.

Directory structure

```
complex-skill/
├── SKILL.md
├── docs/
│   ├── setup.md
│   └── troubleshooting.md
├── templates/
│   └── config.yaml
└── scripts/
    └── validate.py
```

### [​](#docs/) docs/

Use docs for information that’s too detailed for SKILL.md or only relevant in specific situations:

- Advanced configuration options
- Troubleshooting guides for edge cases
- Reference material (API schemas, database schemas)
- Platform-specific instructions

A deployment skill might have `docs/aws.md`, `docs/gcp.md`, and `docs/azure.md`. Cline loads only the relevant platform guide based on your request.

### [​](#templates/) templates/

Use templates when your skill creates configuration files, boilerplate code, or structured documents:

- Config files (Terraform, Docker Compose, CI/CD pipelines)
- Code scaffolding (component templates, test fixtures)
- Documentation templates (README, API docs)

A project setup skill could include `templates/dockerfile`, `templates/docker-compose.yml`, and `templates/.env.example` that Cline customizes for each new project.

### [​](#scripts/) scripts/

Use scripts for deterministic operations where you want consistent behavior:

- Validation (linting configs, checking prerequisites)
- Data processing (parsing, formatting, transforming)
- Complex calculations (cost estimation, resource sizing)
- API interactions (fetching data, running health checks)

Scripts are token-efficient because only their output enters context, not the code itself. A 500-line validation script produces a simple “Passed” or detailed error messages without consuming any context for the script logic.

### [​](#referencing-bundled-files) Referencing Bundled Files

Reference these files in your SKILL.md instructions:

SKILL.md (referencing bundled files)

```
For initial setup, follow [setup.md](docs/setup.md).
Use the config template at `templates/config.yaml` as a starting point.
Run the validation script to check your configuration:

python scripts/validate.py
```

Cline reads documentation files using `read_file` when the instructions reference them. Scripts can be executed directly, and only the script’s output enters the context window.

| Use Scripts For | Use Instructions For |
| --- | --- |
| Deterministic operations (validation, formatting) | Flexible guidance that adapts to context |
| Complex computations | Decision-making processes |
| Operations that need reliability | Steps that might vary by situation |
| Anything you’d rather not consume tokens explaining | Best practices and patterns |

## [​](#example-data-analysis-skill) Example: Data Analysis Skill

Here’s a practical skill for data analysis tasks. Create a directory called `data-analysis/` with this `SKILL.md`:

data-analysis/SKILL.md

```
---
name: data-analysis
description: Analyze data files and generate insights. Use when working with CSV, Excel, or JSON data files that need exploration, cleaning, or visualization.
---

# Data Analysis

When analyzing data files, follow this process:

## 1. Understand the Data
- Read a sample of the file to understand its structure
- Identify column types and data quality issues
- Note any missing values or anomalies

## 2. Ask Clarifying Questions
Before diving in, ask the user:
- What specific insights are they looking for?
- Are there any known data quality issues?
- What format do they want for the output?

## 3. Perform Analysis
Use pandas for data manipulation:

import pandas as pd

# Load and explore
df = pd.read_csv("data.csv")
print(df.head())
print(df.describe())
print(df.info())

For visualization, prefer matplotlib or seaborn depending on complexity.
```

Skills transform Cline from a general-purpose assistant into a specialist that knows your domain. Start with one skill for a task you repeat often, test it, and iterate on the description until it triggers reliably.

Was this page helpful?

YesNo

[Rules](/customization/cline-rules)[Plugins](/customization/plugins)

⌘I

---

## Api Reference

*Source: [https://docs.cline.bot/enterprise-solutions/api-reference](https://docs.cline.bot/enterprise-solutions/api-reference)*

The Enterprise API provides REST endpoints for account management, organization administration, billing, and API key management. These are separate from the [Chat Completions API](/api/overview), which handles model inference.

## [​](#base-url) Base URL

```
https://api.cline.bot
```

## [​](#authentication) Authentication

All endpoints require a Bearer token in the `Authorization` header:

```
Authorization: Bearer YOUR_AUTH_TOKEN
```

Use the same API key or account auth token described in the [public API reference](/api/overview#authentication).

## [​](#quick-example) Quick Example

```
# Get your user profile
curl https://api.cline.bot/api/v1/users/me \
  -H "Authorization: Bearer YOUR_AUTH_TOKEN"
```

```
{
  "id": "user_abc123",
  "email": "you@company.com",
  "name": "Your Name",
  "active_account_id": "org_xyz789"
}
```

---

## [​](#users) Users

Manage user accounts, accept terms, check balances, view usage, and configure payment methods.

| Method | Endpoint | Description |
| --- | --- | --- |
| `GET` | `/api/v1/users/me` | Get current user profile |
| `PATCH` | `/api/v1/users/me` | Update current user profile |
| `DELETE` | `/api/v1/users/me` | Delete current user account |
| `POST` | `/api/v1/users/me/accept-terms` | Accept terms of service |
| `GET` | `/api/v1/users/me/remote-config` | Get remote configuration for the current user |
| `PUT` | `/api/v1/users/active-account` | Switch active account (personal or organization) |
| `GET` | `/api/v1/users/{id}/balance` | Get credit balance |
| `GET` | `/api/v1/users/{id}/usages` | Get usage history |

### [​](#payments-and-credits) Payments and Credits

| Method | Endpoint | Description |
| --- | --- | --- |
| `GET` | `/api/v1/users/{id}/payments` | List payment history |
| `GET` | `/api/v1/users/{id}/payments/{paymentId}` | Get payment details |
| `GET` | `/api/v1/users/{id}/payments/{paymentId}/status` | Check payment status |
| `GET` | `/api/v1/users/{id}/payments/provider/{paymentId}` | Get provider-side payment details |
| `POST` | `/api/v1/users/credits/checkout` | Start a credit purchase checkout |
| `POST` | `/api/v1/users/{id}/credits/purchase` | Purchase credits directly |

### [​](#billing-configuration) Billing Configuration

| Method | Endpoint | Description |
| --- | --- | --- |
| `GET` | `/api/v1/users/{id}/auto-top-up` | Get auto top-up settings |
| `PUT` | `/api/v1/users/{id}/auto-top-up` | Configure auto top-up |
| `GET` | `/api/v1/users/{id}/payment-method/default` | Get default payment method |
| `POST` | `/api/v1/users/{id}/payment-method/setup-session` | Start payment method setup |
| `GET` | `/api/v1/users/{id}/promotions` | List active promotions |

---

## [​](#organizations) Organizations

Create and manage organizations. Organization admins can configure remote settings, manage members, and control billing.

| Method | Endpoint | Description |
| --- | --- | --- |
| `POST` | `/api/v1/organizations` | Create a new organization |
| `GET` | `/api/v1/organizations/{id}` | Get organization details |
| `PUT` | `/api/v1/organizations/{id}` | Update organization settings |
| `DELETE` | `/api/v1/organizations/{id}` | Delete an organization |
| `GET` | `/api/v1/organizations/{id}/api-keys` | List organization API keys |
| `GET` | `/api/v1/organizations/{id}/remote-config` | Get remote config for the org |
| `GET` | `/api/v1/organizations/{orgId}/metrics` | Get organization usage metrics |

---

## [​](#organization-members) Organization Members

Manage who has access to the organization and what role they hold.

| Method | Endpoint | Description |
| --- | --- | --- |
| `GET` | `/api/v1/organizations/{orgId}/members` | List all members |
| `DELETE` | `/api/v1/organizations/{orgId}/members` | Remove members |
| `GET` | `/api/v1/organizations/{orgId}/members/available-roles` | List assignable roles |
| `PUT` | `/api/v1/organizations/{orgId}/members/{memberId}/role` | Change a member’s role |
| `GET` | `/api/v1/organizations/{orgId}/members/{memberId}/usages` | Get a member’s usage |

For a walkthrough of member management in the UI, see [Managing Members](/enterprise-solutions/team-management/managing-members).

---

## [​](#organization-invites) Organization Invites

Invite new members to join your organization.

| Method | Endpoint | Description |
| --- | --- | --- |
| `GET` | `/api/v1/organizations/{orgId}/invites` | List pending invites |
| `POST` | `/api/v1/organizations/{orgId}/invites` | Send new invites |
| `GET` | `/api/v1/organizations/{orgId}/invites/count` | Get invite count |
| `DELETE` | `/api/v1/organizations/{orgId}/invites/{inviteId}` | Revoke an invite |
| `POST` | `/api/v1/invites/accept` | Accept an invite (called by the invitee) |

---

## [​](#organization-balance-and-payments) Organization Balance and Payments

Manage credits and payments at the organization level. These mirror the user-level payment endpoints but operate on the organization’s account.

| Method | Endpoint | Description |
| --- | --- | --- |
| `GET` | `/api/v1/organizations/{orgId}/balance` | Get org credit balance |
| `GET` | `/api/v1/organizations/{orgId}/payments` | List payment history |
| `GET` | `/api/v1/organizations/{orgId}/payments/{paymentId}` | Get payment details |
| `GET` | `/api/v1/organizations/{orgId}/payments/{paymentId}/status` | Check payment status |
| `GET` | `/api/v1/organizations/{orgId}/payments/provider/{paymentId}` | Provider-side payment details |
| `POST` | `/api/v1/organizations/{orgId}/credits/checkout` | Start credit checkout |
| `POST` | `/api/v1/organizations/{orgId}/credits/purchase` | Purchase credits |
| `GET` | `/api/v1/organizations/{orgId}/auto-top-up` | Get auto top-up config |
| `PUT` | `/api/v1/organizations/{orgId}/auto-top-up` | Configure auto top-up |
| `GET` | `/api/v1/organizations/{orgId}/payment-method/default` | Get default payment method |
| `POST` | `/api/v1/organizations/{orgId}/payment-method/setup-session` | Start payment method setup |
| `GET` | `/api/v1/organizations/{id}/promotions` | List active promotions |

---

## [​](#organization-plans) Organization Plans

Subscribe to, upgrade, or cancel plans. Manage seat counts for your team.

| Method | Endpoint | Description |
| --- | --- | --- |
| `GET` | `/api/v1/plans` | List all available plans |
| `GET` | `/api/v1/organizations/{orgId}/plan` | Get current plan |
| `GET` | `/api/v1/organizations/{orgId}/plan/history` | View plan change history |
| `GET` | `/api/v1/organizations/{orgId}/plan/{planId}` | Get specific plan details |
| `POST` | `/api/v1/organizations/{orgId}/plan` | Subscribe to a plan |
| `PUT` | `/api/v1/organizations/{orgId}/plan/seats` | Update seat count |
| `DELETE` | `/api/v1/organizations/{orgId}/plan/{planId}` | Cancel a plan |

---

## [​](#organization-usage) Organization Usage

Track token consumption and costs across your organization.

| Method | Endpoint | Description |
| --- | --- | --- |
| `GET` | `/api/v1/organizations/{orgId}/usages` | Get aggregated usage data |

For dashboards and monitoring, see [Monitoring Overview](/enterprise-solutions/monitoring/overview) and [Telemetry](/enterprise-solutions/monitoring/telemetry).

---

## [​](#api-keys) API Keys

Create and manage API keys for programmatic access. Keys created here work with both the [Chat Completions API](/api/overview) and the endpoints on this page.

| Method | Endpoint | Description |
| --- | --- | --- |
| `GET` | `/api/v1/api-keys` | List your API keys |
| `POST` | `/api/v1/api-keys` | Create a new API key |
| `DELETE` | `/api/v1/api-keys/{key_id}` | Delete an API key |

---

## [​](#related) Related

## Chat Completions API

The public inference API for sending prompts and receiving completions.

## SSO Setup

Configure single sign-on for your organization.

## Managing Members

Add, remove, and manage member roles in the UI.

## Monitoring

Track usage, costs, and telemetry across your organization.

Was this page helpful?

YesNo

[OpenTelemetry Override](/enterprise-solutions/monitoring/opentelemetry_override)

⌘I

---

## Mcp Marketplace

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/infrastructure-configuration/control-other-cline-features/mcp-marketplace](https://docs.cline.bot/enterprise-solutions/configuration/infrastructure-configuration/control-other-cline-features/mcp-marketplace)*

The MCP Marketplace lets developers discover and install MCP servers that extend Cline’s capabilities. For Enterprise administrators, this page covers how to control marketplace access, restrict which servers are available, and push pre-configured MCP servers to your organization.

For complete details about the MCP Marketplace and how developers use it, see [MCP Made Easy](/mcp/mcp-marketplace).

## [​](#overview) Overview

Enterprise administrators have four configuration options to govern MCP server usage across their organization:

| Setting | Purpose |
| --- | --- |
| `mcpMarketplaceEnabled` | Enable or disable the MCP Marketplace entirely |
| `allowedMCPServers` | Restrict the marketplace to only approved MCP servers |
| `remoteMCPServers` | Push pre-configured remote MCP servers to all users |
| `blockPersonalRemoteMCPServers` | Prevent users from adding their own remote MCP servers |

These settings are applied through your organization’s [remote configuration](/enterprise-solutions/configuration/remote-configuration/overview) and take effect immediately for all team members.

## [​](#disabling-the-mcp-marketplace) Disabling the MCP Marketplace

To completely disable the MCP Marketplace for your organization, set `mcpMarketplaceEnabled` to `false`:

```
{
  "mcpMarketplaceEnabled": false
}
```

When `mcpMarketplaceEnabled` is set to `false`:

- The MCP Marketplace tab is hidden from all users
- Users cannot browse or install MCP servers from the marketplace
- Locally configured MCP servers are blocked
- Enterprise policy takes precedence over individual preferences

When `mcpMarketplaceEnabled` is set to `true` or omitted:

- Users can freely browse and install MCP servers from the marketplace
- No organizational restrictions apply to marketplace access

Disabling the marketplace entirely also blocks locally configured MCP servers. If you want to allow specific servers while restricting others, use the allowlist approach described below instead.

## [​](#restricting-the-marketplace-to-approved-servers) Restricting the Marketplace to Approved Servers

Rather than disabling the marketplace entirely, you can restrict it to a curated list of approved MCP servers using the `allowedMCPServers` setting. This is the recommended approach for most enterprises — it lets developers benefit from MCP while ensuring only vetted servers are available.

### [​](#configuration) Configuration

Add an `allowedMCPServers` array to your remote configuration. Each entry requires an `id` field set to the server’s GitHub repository path:

```
{
  "allowedMCPServers": [
    { "id": "github.com/modelcontextprotocol/server-filesystem" },
    { "id": "github.com/modelcontextprotocol/server-github" },
    { "id": "github.com/your-org/internal-mcp-server" }
  ]
}
```

### [​](#how-it-works) How It Works

When `allowedMCPServers` is configured:

- The marketplace catalog is filtered to show **only** the servers in your allowlist
- Users can browse, view details, and install any server on the list
- Servers not on the list are completely hidden from the marketplace
- The allowlist applies to all team members in the organization

When `allowedMCPServers` is omitted or `undefined`:

- The full marketplace catalog is available with no restrictions

When `allowedMCPServers` is set to an empty array (`[]`):

- The marketplace shows no servers — effectively disabling installation while keeping the UI visible

### [​](#finding-server-ids) Finding Server IDs

The `id` for each allowed server is its GitHub repository path (without the `https://` prefix). For example:

| Server | ID |
| --- | --- |
| Filesystem | `github.com/modelcontextprotocol/server-filesystem` |
| GitHub | `github.com/modelcontextprotocol/server-github` |
| Custom internal server | `github.com/your-org/your-mcp-server` |

You can find the correct ID by checking the `githubUrl` field of any server in the [MCP Marketplace](/mcp/mcp-marketplace) and removing the `https://` prefix.

## [​](#pushing-pre-configured-remote-mcp-servers) Pushing Pre-Configured Remote MCP Servers

Use `remoteMCPServers` to push MCP servers directly to all users without requiring them to install anything from the marketplace. This is ideal for internal MCP servers or third-party servers that need specific configuration.

### [​](#configuration-2) Configuration

```
{
  "remoteMCPServers": [
    {
      "name": "Internal Code Search",
      "url": "https://mcp.internal.yourcompany.com/code-search",
      "alwaysEnabled": true,
      "headers": {
        "Authorization": "Bearer ${AUTH_TOKEN}"
      }
    },
    {
      "name": "Documentation Server",
      "url": "https://mcp.internal.yourcompany.com/docs",
      "alwaysEnabled": false
    }
  ]
}
```

### [​](#remote-server-options) Remote Server Options

Each remote MCP server entry supports the following fields:

| Field | Type | Required | Description |
| --- | --- | --- | --- |
| `name` | string | Yes | Display name for the server |
| `url` | string | Yes | The URL endpoint of the MCP server |
| `alwaysEnabled` | boolean | No | When `true`, users cannot disable this server |
| `headers` | object | No | Custom HTTP headers for authentication |

### [​](#always-enabled-servers) Always-Enabled Servers

When `alwaysEnabled` is set to `true`:

- The server is automatically active for all users
- Users cannot toggle the server off
- The server appears in the user’s MCP configuration but the disable control is locked
- This is useful for compliance, security, or internal tooling servers that must always be available

## [​](#blocking-personal-remote-mcp-servers) Blocking Personal Remote MCP Servers

To prevent users from adding their own remote MCP servers, set `blockPersonalRemoteMCPServers` to `true`:

```
{
  "blockPersonalRemoteMCPServers": true
}
```

When `blockPersonalRemoteMCPServers` is `true`:

- Users cannot add or configure remote MCP servers on their own
- Only servers defined in the organization’s `remoteMCPServers` configuration are available
- This ensures all remote MCP connections go through approved, organization-managed endpoints

When `blockPersonalRemoteMCPServers` is `false` or omitted:

- Users can freely add their own remote MCP server connections

## [​](#combined-configuration-examples) Combined Configuration Examples

### [​](#locked-down-environment) Locked-Down Environment

For organizations that need strict control over all MCP server access:

```
{
  "mcpMarketplaceEnabled": true,
  "allowedMCPServers": [
    { "id": "github.com/modelcontextprotocol/server-filesystem" },
    { "id": "github.com/modelcontextprotocol/server-github" }
  ],
  "remoteMCPServers": [
    {
      "name": "Internal API Gateway",
      "url": "https://mcp.internal.yourcompany.com/gateway",
      "alwaysEnabled": true,
      "headers": {
        "X-Api-Key": "org-managed-key"
      }
    }
  ],
  "blockPersonalRemoteMCPServers": true
}
```

This configuration:

- Allows the marketplace but limits it to two approved servers
- Pushes an always-enabled internal MCP server to all users
- Blocks users from adding their own remote MCP servers

### [​](#open-environment-with-internal-servers) Open Environment with Internal Servers

For organizations that want flexibility with internal server access:

```
{
  "remoteMCPServers": [
    {
      "name": "Company Knowledge Base",
      "url": "https://mcp.yourcompany.com/kb",
      "alwaysEnabled": true
    }
  ]
}
```

This configuration:

- Leaves the full marketplace open (no `allowedMCPServers` restriction)
- Ensures all developers have access to the company knowledge base
- Allows users to add their own remote MCP servers

### [​](#marketplace-disabled-with-internal-servers-only) Marketplace Disabled with Internal Servers Only

For organizations that want to fully manage the MCP experience:

```
{
  "mcpMarketplaceEnabled": false,
  "remoteMCPServers": [
    {
      "name": "Approved Code Assistant",
      "url": "https://mcp.internal.yourcompany.com/code-assist",
      "alwaysEnabled": true
    },
    {
      "name": "Internal Docs Search",
      "url": "https://mcp.internal.yourcompany.com/docs",
      "alwaysEnabled": true
    }
  ],
  "blockPersonalRemoteMCPServers": true
}
```

This configuration:

- Disables the marketplace completely
- Provides only organization-managed MCP servers
- Prevents users from adding any additional remote servers

## [​](#enterprise-policy-recommendations) Enterprise Policy Recommendations

### [​](#recommended-approach) Recommended Approach

Most organizations should **use the allowlist** (`allowedMCPServers`) rather than disabling the marketplace entirely. This gives developers access to useful tools while ensuring security review of each server.

Security Review Process

Before adding an MCP server to your allowlist:

- Review the server’s source code on GitHub
- Evaluate the server’s permissions and data access patterns
- Check for active maintenance and security practices
- Assess whether the server’s data handling meets your compliance requirements
- Test the server in a sandbox environment before approving

Internal MCP Servers

For internal tooling, use `remoteMCPServers` with `alwaysEnabled: true`:

- Connect Cline to internal APIs, databases, and knowledge bases
- Ensure consistent access across all developers
- Manage authentication centrally through custom headers
- Use `blockPersonalRemoteMCPServers` to prevent shadow IT

Compliance Considerations

MCP servers can access external APIs and process data:

- Audit which servers handle sensitive data
- Ensure servers comply with your data residency requirements
- Document approved servers in your security policies
- Regularly review and update your allowlist

### [​](#recommendations-by-organization-size) Recommendations by Organization Size

#### [​](#small-teams-5–20-developers) Small Teams (5–20 developers)

- **Marketplace:** Open or lightly restricted with an allowlist
- **Remote Servers:** Push internal servers as needed
- **Personal Servers:** Allow with guidance
- **Review Cadence:** Quarterly allowlist review

#### [​](#medium-organizations-20–100-developers) Medium Organizations (20–100 developers)

- **Marketplace:** Restricted to an approved allowlist
- **Remote Servers:** Push internal servers with `alwaysEnabled`
- **Personal Servers:** Consider blocking (`blockPersonalRemoteMCPServers: true`)
- **Review Cadence:** Monthly allowlist review

#### [​](#large-enterprises-100+-developers) Large Enterprises (100+ developers)

- **Marketplace:** Strictly restricted to a vetted allowlist
- **Remote Servers:** All MCP access through organization-managed servers
- **Personal Servers:** Blocked (`blockPersonalRemoteMCPServers: true`)
- **Review Cadence:** Formal approval process for new servers with security review

## [​](#support-&-questions) Support & Questions

For help configuring MCP Marketplace policies:

- Review [Remote Configuration Overview](/enterprise-solutions/configuration/remote-configuration/overview)
- See [MCP Made Easy](/mcp/mcp-marketplace) for marketplace functionality details
- See [MCP Overview](/mcp/mcp-overview) for general MCP concepts
- Contact your Enterprise support representative
- Join our [Discord](https://discord.gg/cline) for community discussion

Was this page helpful?

YesNo

[YOLO Mode](/enterprise-solutions/configuration/infrastructure-configuration/control-other-cline-features/yolo-mode)[Overview](/enterprise-solutions/monitoring/overview)

⌘I

---

## Yolo Mode

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/infrastructure-configuration/control-other-cline-features/yolo-mode](https://docs.cline.bot/enterprise-solutions/configuration/infrastructure-configuration/control-other-cline-features/yolo-mode)*

YOLO Mode enables Cline to operate with complete autonomy, auto-approving all actions without user confirmation. For Enterprise administrators, this page covers how to control access to YOLO Mode across your organization.

For complete details about YOLO Mode functionality, risks, and best practices, see [YOLO Mode in Features](/features/yolo-mode).

## [​](#overview) Overview

When YOLO Mode is enabled, Cline automatically approves all operations including file changes, terminal commands, browser actions, and mode transitions. This provides maximum automation speed but removes all safety guardrails.

YOLO Mode is powerful but potentially dangerous. Administrators should carefully consider which teams or users should have access to this feature.

## [​](#enterprise-administrator-configuration) Enterprise Administrator Configuration

As an Enterprise administrator, you can control whether users in your organization can enable YOLO Mode through remote configuration.

### [​](#disabling-yolo-mode-for-all-users) Disabling YOLO Mode for All Users

Add the following to your remote configuration JSON:

```
{
  "yoloModeAllowed": false
}
```

When `yoloModeAllowed` is set to `false`:

- The YOLO Mode toggle is disabled in all user interfaces
- Users cannot enable YOLO Mode even in their local settings
- This policy applies immediately to all team members
- Enterprise policy takes precedence over individual preferences

### [​](#enabling-yolo-mode-for-all-users) Enabling YOLO Mode for All Users

```
{
  "yoloModeAllowed": true
}
```

When `yoloModeAllowed` is set to `true` or omitted:

- Users can enable or disable YOLO Mode in their local Cline settings
- Individual users make their own decisions about using YOLO Mode
- No organizational restrictions apply

## [​](#enterprise-policy-recommendations) Enterprise Policy Recommendations

### [​](#recommended-approach) Recommended Approach

Most organizations should **disable YOLO Mode by default** for the following reasons:

Security & Compliance

YOLO Mode removes all approval gates, potentially allowing:

- Unreviewed code changes to critical systems
- Execution of commands without oversight
- Automated actions that may violate compliance policies
- Risk of data exposure through unmonitored operations

Code Quality Control

Without approval prompts:

- Changes happen too quickly to review in real-time
- Mistakes can compound before detection
- Quality gates are bypassed
- Rollback becomes more complex

Audit Requirements

Many industries require:

- Documented approval trails for code changes
- Clear accountability for automated actions
- Traceable decision-making processes
- YOLO Mode may conflict with these requirements

### [​](#exceptions-when-to-allow-yolo-mode) Exceptions: When to Allow YOLO Mode

Consider enabling YOLO Mode for:
**Sandbox/Development Environments**

- Isolated testing environments
- Personal development machines
- Proof-of-concept projects
- Temporary exploratory work

**Specialized Roles**

- DevOps automation engineers (with proper monitoring)
- Research & development teams in sandboxed environments
- Teams with robust rollback and recovery procedures

**Controlled Use Cases**

- Scripted CI/CD pipelines with comprehensive logging
- Automated testing scenarios
- Demonstration or training environments

## [​](#enterprise-considerations) Enterprise Considerations

### [​](#security-implications) Security Implications

When YOLO Mode is enabled in your organization:
**Risk Factors:**

- All tool executions happen automatically without human review
- Potential for rapid propagation of mistakes across multiple files
- Reduced opportunity to catch security vulnerabilities before implementation
- Automated operations may bypass existing security controls

**Mitigations:**

- Implement comprehensive logging and monitoring
- Restrict YOLO Mode to non-production environments
- Require periodic security reviews for teams using YOLO Mode
- Ensure version control and rollback procedures are in place

### [​](#monitoring-requirements) Monitoring Requirements

When allowing YOLO Mode in your organization, implement:
**Mandatory Monitoring:**

1. **Real-time Activity Tracking**
   - Monitor which users enable YOLO Mode
   - Track when YOLO Mode is active
   - Log all automated actions taken
2. **Audit Trail Maintenance**
   - Preserve complete history of YOLO Mode sessions
   - Document what was automated and when
   - Maintain records for compliance purposes
3. **Anomaly Detection**
   - Alert on unusual patterns of automated actions
   - Flag high-risk operations performed automatically
   - Monitor for potential security incidents

### [​](#monitoring-yolo-mode-usage) Monitoring YOLO Mode Usage

When YOLO Mode is enabled (by policy), track usage through:
**Telemetry Events:**

- Captures when users toggle YOLO Mode on/off
- Records which tasks were executed with YOLO Mode enabled
- Provides aggregate usage statistics across your organization

**Task History:**

- Task metadata indicates whether YOLO Mode was active
- Complete action logs show automated approvals
- Enables post-action review and analysis

**Audit Logs:**

- Standard logging captures all automated decisions
- Tool executions are recorded with timestamps
- Provides compliance trail for regulated environments

## [​](#recommended-policies-by-organization-size) Recommended Policies by Organization Size

### [​](#small-teams-5-20-developers) Small Teams (5-20 developers)

- **Default:** Disabled
- **Exceptions:** Allow for individual sandbox environments
- **Monitoring:** Basic telemetry sufficient

### [​](#medium-organizations-20-100-developers) Medium Organizations (20-100 developers)

- **Default:** Disabled
- **Exceptions:** Permit for designated dev/test environments only
- **Monitoring:** Required telemetry + regular audit reviews

### [​](#large-enterprises-100+-developers) Large Enterprises (100+ developers)

- **Default:** Strictly disabled
- **Exceptions:** Require security approval for each use case
- **Monitoring:** Comprehensive telemetry + real-time alerting + compliance reporting

## [​](#technical-implementation) Technical Implementation

### [​](#configuration-management) Configuration Management

**Centralized Control through Remote Configuration:**

```
{
  "yoloModeAllowed": false,
  // Other policies...
}
```

This setting:

- Applies instantly to all connected clients
- Cannot be overridden by individual users
- Persists across Cline restarts
- Is synchronized across all team members

### [​](#policy-enforcement) Policy Enforcement

The enforcement mechanism:

1. Users authenticate with your enterprise configuration server
2. Remote configuration is downloaded and applied
3. Local UI respects enterprise policy settings
4. YOLO Mode toggle is disabled if policy forbids it
5. Users see a message explaining the enterprise restriction

## [​](#compliance-considerations) Compliance Considerations

For organizations in regulated industries:
**SOC 2 Compliance:**

- YOLO Mode may conflict with change management controls
- Document decision to allow/disallow in security policies
- Implement compensating controls if YOLO Mode is permitted

**GDPR/Data Protection:**

- Automated operations must still respect data handling policies
- Ensure YOLO Mode doesn’t bypass data protection safeguards
- Maintain audit trails of automated data processing

**Industry-Specific:**

- Financial services: Generally incompatible with Reg requirements
- Healthcare: May violate HIPAA audit trail requirements
- Government: Often conflicts with approval workflow mandates

## [​](#support-&-questions) Support & Questions

For help configuring YOLO Mode policies:

- Review [Remote Configuration Overview](/enterprise-solutions/configuration/remote-configuration/overview)
- See [Features: YOLO Mode](/features/yolo-mode) for detailed functionality
- Contact your Enterprise support representative
- Join our [Discord](https://discord.gg/cline) for community discussion

Was this page helpful?

YesNo

[Configure LiteLLM (Member)](/enterprise-solutions/configuration/remote-configuration/litellm/member-configuration)[MCP Marketplace](/enterprise-solutions/configuration/infrastructure-configuration/control-other-cline-features/mcp-marketplace)

⌘I

---

## Admin Configuration

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/anthropic/admin-configuration](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/anthropic/admin-configuration)*

As an administrator, you can add Anthropic as the organization-wide LLM provider for all Cline users through the hosted admin console. This centralized approach provides direct access to Anthropic’s Claude models, with an optional custom base URL for organizations that route traffic through a proxy.

## [​](#before-you-begin) Before You Begin

To get started with setting up Anthropic as your organization’s LLM provider, you’ll need a few items in place.
**Administrator access to the Cline Admin console**
You need admin privileges to enforce provider settings across your organization. If you can navigate to **Settings → Cline Settings** in the admin console at [app.cline.bot](https://app.cline.bot), you have the right access level.
**Anthropic API access**
Your organization needs an Anthropic account with API access to Claude models. Members will need individual API keys to authenticate.

If your organization requires routing API traffic through a proxy or custom endpoint, have the proxy URL ready before configuring.

## [​](#configuration-steps) Configuration Steps

1

Access Cline Settings

Navigate to [app.cline.bot](https://app.cline.bot) and sign in with your administrator account. Go to **Settings → Cline Settings**.

You should see the provider configuration options if you have the correct admin access level.

2

Enable Remote Provider Configuration

Toggle on **Enable settings** to reveal the remote provider configuration options. This allows you to enforce provider settings across your organization.

3

Select Anthropic as the API Provider

Open the **API Provider** dropdown menu and select **Anthropic**. This will open the Anthropic configuration panel where you’ll configure all your organization-wide settings.

4

Configure Anthropic Settings

The configuration panel includes settings that control how Anthropic works for your organization:

Base URL (optional)

By default, Cline connects directly to the Anthropic API (`https://api.anthropic.com`). If your organization routes API traffic through a proxy or custom endpoint, enter the base URL here.Use cases for a custom base URL:

- Corporate proxy that logs or filters API traffic
- Self-hosted API gateway for rate limiting or access control
- Regional routing requirements

Leave this empty to use the default Anthropic API endpoint.

If using a proxy, ensure it correctly forwards requests to the Anthropic API and preserves all required headers.

5

Save Configuration

After configuring your settings, close the provider configuration panel and click **Save** on the settings page to persist your changes.Once saved, all organization members signed into the Cline extension will automatically use Anthropic with your configured settings. They won’t be able to select other providers or switch to their personal Cline accounts.

Members can’t switch to personal Cline accounts or join other organizations once remote configuration is enabled. This ensures consistent provider usage across your team.

## [​](#verification) Verification

To verify the configuration:

1. Check that the provider shows as “Anthropic” in the Enabled provider field
2. Confirm the settings persist after refreshing the page
3. Test with a member account to ensure they see only Anthropic as a provider
4. Verify that Claude models are available in the model dropdown

## [​](#troubleshooting) Troubleshooting

**Members don’t see the configured provider**
Ensure you clicked Save after closing the configuration panel. Verify the member account belongs to the correct organization.
**Connection errors when using a custom base URL**
Verify the proxy URL is correct and accessible from your team’s development environments. Ensure the proxy correctly forwards requests to the Anthropic API.
**Configuration changes don’t persist**
Make sure to click the Save button on the main settings page, not just close the configuration panel.
**Need to change settings later**
You can update the base URL or other settings at any time. Changes take effect immediately for all organization members.
For further details, consult the [Anthropic API documentation](https://docs.anthropic.com/) and coordinate with your infrastructure team.

Was this page helpful?

YesNo

[Configure OpenAI Compatible (Member)](/enterprise-solutions/configuration/remote-configuration/openai-compatible/member-configuration)[Configure Anthropic (Member)](/enterprise-solutions/configuration/remote-configuration/anthropic/member-configuration)

⌘I

---

## Member Configuration

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/anthropic/member-configuration](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/anthropic/member-configuration)*

As a team member, you can connect your local development environment to your organization’s Anthropic provider setup. This guide walks you through configuring your API key in VS Code so you can start using Claude models through your organization’s configuration. Your administrator has already configured the provider settings — you just need to add your API key to get started.

## [​](#before-you-begin) Before You Begin

To successfully connect to your organization’s Anthropic provider, you’ll need a few things ready.
**Cline extension installed and configured**
The Cline extension must be installed in VS Code and you need to be signed into your organization account. If you haven’t installed Cline yet, follow our [installation guide](/getting-started/installing-cline).

**Quick Check**: Open the Cline panel in VS Code. If you see your organization name in the bottom left, you’re signed in correctly.

**Anthropic API key**
You need an API key from Anthropic to authenticate requests. Your organization may provide keys centrally or require you to create one through the [Anthropic Console](https://console.anthropic.com/).

If you’re unsure how to obtain an API key, check with your administrator about your organization’s key provisioning process.

## [​](#configuration-steps) Configuration Steps

1

Open Cline Settings

Open VS Code and access the Cline settings panel using either of these methods:

- Click the settings icon (⚙️) in the Cline panel
- Click on the API Provider dropdown located directly below the chat area

2

Enter Your API Key

1. Select or confirm the **Anthropic** provider is selected
2. Enter your Anthropic API key in the **API Key** field
3. If your administrator configured a custom base URL, it will already be set and locked
4. Click **Save** to store your credentials

API keys are stored locally and are only used by the Cline extension.

The base URL setting is controlled by your administrator. If a custom proxy URL is configured, your API requests will be routed through it automatically.

3

Verify Configuration

After entering your API key, administrator-controlled settings (such as base URL) will be locked (shown with a lock icon 🔒) as they’re managed by your organization.

4

Test the Connection

Send a test message in Cline to verify your API key works correctly with the configured Anthropic endpoint.

**Testing Recommendation**Try a simple test like “Hello” first to verify basic connectivity before starting development tasks.

## [​](#troubleshooting) Troubleshooting

**Anthropic not available as provider option**
Confirm you’re signed into the correct Cline organization. Verify your administrator has saved the Anthropic configuration and that you have the latest version of the Cline extension.
**Authentication errors (“Invalid API Key” or “Unauthorized”)**
Verify your API key is correct and active. Check the [Anthropic Console](https://console.anthropic.com/) to confirm your key status and that it has sufficient permissions.
**Connection errors or timeouts**
If your administrator configured a custom base URL (proxy), check with your IT team about network requirements. If using the default Anthropic endpoint, ensure you have internet access to `api.anthropic.com`.
**Models not available**
The available models depend on your Anthropic API plan and your organization’s configuration. Contact your administrator if expected models are not available.
**Rate limit errors**
Your API key may have rate limits configured by Anthropic. If you encounter rate limit errors during normal use, contact your administrator about adjusting limits or managing key usage across the team.

## [​](#security-best-practices) Security Best Practices

When working with your Anthropic API key:

- Keep your API key secure and do not share it
- Never store your API key in code or version control
- Report any suspected key compromise to your administrator immediately
- Regularly check the [Anthropic Console](https://console.anthropic.com/) for unusual usage patterns

For further details, consult the [Anthropic API documentation](https://docs.anthropic.com/) and coordinate with your organization’s administrator.

Was this page helpful?

YesNo

[Configure Anthropic (Admin)](/enterprise-solutions/configuration/remote-configuration/anthropic/admin-configuration)[Configure LiteLLM (Admin)](/enterprise-solutions/configuration/remote-configuration/litellm/admin-configuration)

⌘I

---

## Admin Configuration

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/aws-bedrock/admin-configuration](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/aws-bedrock/admin-configuration)*

As an administrator, you can add AWS Bedrock as the organization-wide LLM provider for all Cline users through the hosted admin console. This centralized approach ensures consistent access to Amazon’s AI models while maintaining your organization’s security and compliance requirements through region controls and basic configuration options.

## [​](#before-you-begin) Before You Begin

To get started with setting up AWS Bedrock as your organization’s LLM provider, you’ll need a few items in place.
**Administrator access to the Cline Admin console**
You need admin privileges to enforce provider settings across your organization. If you can navigate to **Settings → Cline Settings** in the admin console at [app.cline.bot](https://app.cline.bot), you have the right access level.
**AWS Bedrock account with the right permissions**
Your AWS account needs specific Bedrock permissions to work with Cline.

If you don’t have direct AWS access, coordinate with your cloud team to get these permissions set up before proceeding.

**Your preferred AWS region**
Choose your primary AWS region carefully since this will be enforced for all users.

Check which models are available in your region first. Some newer models might not be available in all regions yet.

## [​](#configuration-steps) Configuration Steps

1

Access Cline Settings

Navigate to [app.cline.bot](https://app.cline.bot) and sign in with your administrator account. Go to **Settings → Cline Settings**.

You should see the provider configuration options if you have the correct admin access level.

2

Enable Remote Provider Configuration

Toggle on **Enable settings** to reveal the remote provider configuration options. This allows you to enforce provider settings across your organization.

3

Select AWS Bedrock as the API Provider

Open the **API Provider** dropdown menu and select **Amazon Bedrock**. This will open the Bedrock configuration panel where you’ll configure all your organization-wide settings.

4

Configure Bedrock Settings

The configuration panel includes several settings that control how Bedrock works for your organization. Configure what you need:

Region (required)

Enter your preferred AWS region like `us-west-2` or `us-east-1`. This region will be enforced for all organization members.[View AWS Global Infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/)

For most organizations, `us-east-1` or `us-west-2` are recommended as they have the best model availability.

Custom VPC Endpoint (optional)

If your organization uses a private VPC endpoint for Bedrock, specify it here to ensure all API calls go through your network infrastructure.[Learn more about AWS PrivateLink](https://docs.aws.amazon.com/vpc/latest/userguide/endpoint-services-overview.html)

Cross-region Inference (optional)

Enable this to let Bedrock automatically route requests to other regions when your primary region has capacity constraints. Useful for maintaining availability during high-demand periods.[Learn more about Inference Profiles](https://docs.aws.amazon.com/bedrock/latest/userguide/inference-profiles-support.html)

Global Inference Profile (optional)

Turn this on to use AWS’s global inference routing, which automatically directs requests to the optimal region based on availability and latency.

Prompt Caching (optional)

Enable prompt caching to reduce costs and latency. Bedrock caches portions of prompts that remain consistent across requests, making repeated interactions faster and cheaper.[Learn more about Prompt Caching](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-caching.html)

5

Save Configuration

After configuring your settings, close the provider configuration panel and click **Save** on the settings page to persist your changes.Once saved, all organization members signed into the Cline extension will automatically use AWS Bedrock with your configured settings. They won’t be able to select other providers or switch to their personal Cline accounts.

Members can’t switch to personal Cline accounts or join other organizations once remote configuration is enabled. This ensures consistent provider usage across your team.

## [​](#verification) Verification

To verify the configuration:

1. Check that the provider shows as “Amazon Bedrock” in the Enabled provider field
2. Confirm the settings persist after refreshing the page
3. Test with a member account to ensure they see only Bedrock as a provider

## [​](#troubleshooting) Troubleshooting

**Members don’t see the configured provider**
Ensure you clicked Save after closing the configuration panel. Verify the member account belongs to the correct organization.
**Configuration changes don’t persist**
Make sure to click the Save button on the main settings page, not just close the configuration panel.
**Need to change regions later**
You can update the region at any time. Members will need to ensure their local AWS credentials have access to the new region. For more information, refer to the [AWS Bedrock Documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html).
For further details, consult the [AWS Bedrock Documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html) and coordinate with your internal cloud team.

Was this page helpful?

YesNo

[Overview](/enterprise-solutions/configuration/remote-configuration/overview)[Configure AWS Bedrock (Member)](/enterprise-solutions/configuration/remote-configuration/aws-bedrock/member-configuration)

⌘I

---

## Member Configuration

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/aws-bedrock/member-configuration](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/aws-bedrock/member-configuration)*

As a team member, you can connect your local development environment to your organization’s AWS Bedrock setup. This guide walks you through configuring your AWS credentials in VS Code so you can start using models through your organization’s Bedrock infrastructure. Your administrator has already configured the provider settings-you just need to add your credentials to get started.

## [​](#before-you-begin) Before You Begin

To successfully connect to your organization’s AWS Bedrock setup, you’ll need a few things ready.
**Cline extension installed and configured**
The Cline extension must be installed in VS Code and you need to be signed into your organization account. If you haven’t installed Cline yet, follow our [installation guide](/getting-started/installing-cline).

**Quick Check**: Open the Cline panel in VS Code. If you see your organization name in the bottom left, you’re signed in correctly.

**AWS credentials with Bedrock access**
You need AWS credentials that have permission to access Bedrock in your organization’s configured region.

If you don’t have AWS credentials yet, reach out to your IT or cloud team to get access keys or AWS CLI profiles configured with the necessary Bedrock permissions.

## [​](#configuration-steps) Configuration Steps

1

Open Cline Settings

Open VS Code and access the Cline settings panel using either of these methods:

- Click the settings icon (⚙️) in the Cline panel
- Click on the API Provider dropdown located directly below the chat area (it will display as `bedrock.anthropic.claude-sonnet-4-20250514-v1:0` or similar)

2

Select Your Authentication Method

Choose one of the following credential methods to authenticate with AWS Bedrock:

AWS Bedrock API Key

Use dedicated AWS access keys specifically for Bedrock access.[Learn more about AWS Bedrock API Keys](https://docs.aws.amazon.com/bedrock/latest/userguide/api-keys.html)

1. Select the **API Key** radio button
2. Enter your AWS Access Key ID and Secret Access Key
3. These credentials are stored locally and used only by the VS Code extension

AWS Profile

Use an existing AWS CLI profile configured on your machine.[Learn more about AWS CLI Profiles](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-profiles.html)

1. Select the **AWS Profile** radio button
2. Choose or enter the profile name from your `~/.aws/credentials` file
3. Cline will use the credentials associated with that profile

AWS Credentials

Use your default AWS credential chain (environment variables, EC2 instance roles, etc.).

1. Select the **AWS Credentials** radio button
2. Cline will automatically detect credentials from your environment using the standard AWS credential provider chain

The AWS Region is preconfigured by your administrator and does not need to be set in the extension.

3

Verify Configuration

After selecting your authentication method, the extension will display checkmarks for enabled features:

- ✓ Supports images
- ✓ Supports browser use
- ✓ Supports prompt caching

Additional settings like cross-region inference and global inference profile will be locked (shown with a lock icon 🔒) as they’re controlled by your administrator.

4

Test the Connection

Send a test message in Cline to verify your credentials work correctly with the configured Bedrock region.

**Testing Recommendation**It is recommended to test the connection in plan mode to verify everything works correctly before using it for actual tasks.

## [​](#troubleshooting) Troubleshooting

**Authentication errors (“Access Denied” or “Invalid Credentials”)**
Verify your chosen credential method has the necessary IAM permissions to call Bedrock in the configured region. Required permissions include `bedrock:InvokeModel` and `bedrock:InvokeModelWithResponseStream`. For more information, refer to [AWS Bedrock IAM Permissions](https://docs.aws.amazon.com/bedrock/latest/userguide/security-iam.html).
**Region-related errors or “model not available”**
Ask your administrator to confirm which region is configured for your organization. Ensure your AWS credentials have access to Bedrock in that specific region. [View AWS Global Infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/)
**Don’t see AWS Bedrock as an option**
Confirm you’re signed into the correct Cline organization. Verify your administrator has saved the Bedrock configuration. Try signing out and back into the extension.
**AWS Credentials option not finding credentials**
Verify AWS CLI is installed and configured with `aws configure` ([AWS CLI Installation Guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)). Check that credentials are present in `~/.aws/credentials`. For EC2/ECS environments, ensure IAM roles are properly attached. If using environment variables, set `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY`.

## [​](#security-best-practices) Security Best Practices

When configuring your AWS credentials, follow these security guidelines:

- Use IAM roles with minimum required permissions ([AWS IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html))
- Rotate access keys regularly if using the API Key method
- Never store credentials in code or version control
- Prefer AWS Profile method for better credential management
- Consider using AWS SSO/federated roles for enhanced security

Your organization administrator controls which models are available. The extension will automatically display available models based on your region’s Bedrock configuration. For more information about available models, refer to the [AWS Bedrock Model Access documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/model-access.html).
For further assistance, consult the [AWS Bedrock Documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html) and coordinate with your organization’s cloud administrator.

Was this page helpful?

YesNo

[Configure AWS Bedrock (Admin)](/enterprise-solutions/configuration/remote-configuration/aws-bedrock/admin-configuration)[Configure Google Vertex (Admin)](/enterprise-solutions/configuration/remote-configuration/google-vertex/admin-configuration)

⌘I

---

## Admin Configuration

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/google-vertex/admin-configuration](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/google-vertex/admin-configuration)*

As an administrator, you can add Google Vertex AI as the organization-wide LLM provider for all Cline users through the hosted admin console. This centralized approach ensures consistent access to Google’s Gemini models while maintaining your organization’s project boundaries and regional settings.

## [​](#before-you-begin) Before You Begin

To get started with setting up Google Vertex AI as your organization’s LLM provider, you’ll need a few items in place.
**Administrator access to the Cline Admin console**
You need admin privileges to enforce provider settings across your organization. If you can navigate to **Settings → Cline Settings** in the admin console at [app.cline.bot](https://app.cline.bot), you have the right access level.
**Google Cloud Project with Vertex AI enabled**
You need a Google Cloud project with the Vertex AI API enabled and appropriate models accessible.

If you haven’t set up Google Cloud or Vertex AI yet, work with your cloud team to enable the Vertex AI API and ensure necessary quotas are configured.

**Project configuration details**
You’ll need your Google Cloud project ID and preferred region for Vertex AI model access.

Service accounts should have the minimum IAM permissions needed for Vertex AI access to follow security best practices.

## [​](#configuration-steps) Configuration Steps

1

Access Cline Settings

Navigate to [app.cline.bot](https://app.cline.bot) and sign in with your administrator account. Go to **Settings → Cline Settings**.

You should see the provider configuration options if you have the correct admin access level.

2

Enable Remote Provider Configuration

Toggle on **Enable settings** to reveal the remote provider configuration options. This allows you to enforce provider settings across your organization.

3

Select Google Vertex AI as the API Provider

Open the **API Provider** dropdown menu and select **Google Vertex AI**. This will open the Vertex AI configuration panel where you’ll configure all your organization-wide settings.

4

Configure Vertex AI Settings

The configuration panel includes settings that control how Vertex AI works for your organization:

Project ID (required)

Enter your Google Cloud project ID where Vertex AI is enabled. This project will be used for all AI model requests from your organization members.

Use a dedicated project for AI workloads to better track usage and costs. Ensure the project has sufficient quotas for your team’s expected usage.

Region (required)

Select the Google Cloud region where your Vertex AI models should be accessed. Common options include `us-central1`, `us-east4`, or `europe-west4`.[View Google Cloud Regions](https://cloud.google.com/docs/geography-and-regions)

Choose a region close to your team’s location for optimal performance. Some models may not be available in all regions.

5

Save Configuration

After configuring your settings, close the provider configuration panel and click **Save** on the settings page to persist your changes.Once saved, all organization members signed into the Cline extension will automatically use Google Vertex AI with your configured settings. They won’t be able to select other providers or switch to their personal Cline accounts.

Members can’t switch to personal Cline accounts or join other organizations once remote configuration is enabled. This ensures consistent provider usage across your team.

## [​](#verification) Verification

To verify the configuration:

1. Check that the provider shows as “Google Vertex AI” in the Enabled provider field
2. Confirm the settings persist after refreshing the page
3. Test with a member account to ensure they see only Vertex AI as a provider
4. Verify that Gemini models are available in the model dropdown

## [​](#troubleshooting) Troubleshooting

**Members don’t see the configured provider**
Ensure you clicked Save after closing the configuration panel. Verify the member account belongs to the correct organization and that your Google Cloud project has Vertex AI API enabled.
**Project access errors**
Verify the project ID is correct and that Vertex AI API is enabled. Check that the project has appropriate billing configured and hasn’t exceeded quotas.
**Regional availability issues**
Confirm the selected region supports the Gemini models you want to use. Some newer models may only be available in specific regions.
**Configuration changes don’t persist**
Make sure to click the Save button on the main settings page, not just close the configuration panel.
**Need to change project or region later**
You can update these settings at any time. Members will need to ensure their local Google Cloud credentials have access to the new project/region.
For further details, consult the [Google Cloud Vertex AI Documentation](https://cloud.google.com/vertex-ai/docs) and coordinate with your internal cloud team.

Was this page helpful?

YesNo

[Configure AWS Bedrock (Member)](/enterprise-solutions/configuration/remote-configuration/aws-bedrock/member-configuration)[Configure Google Vertex (Member)](/enterprise-solutions/configuration/remote-configuration/google-vertex/member-configuration)

⌘I

---

## Member Configuration

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/google-vertex/member-configuration](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/google-vertex/member-configuration)*

As a team member, you can connect your local development environment to your organization’s Google Vertex AI setup. This guide walks you through configuring your Google Cloud credentials in VS Code so you can start using Vertex AI models through your organization’s configured project and regional settings. Your administrator has already configured the provider settings-you just need to add your credentials to get started.

## [​](#before-you-begin) Before You Begin

To successfully connect to your organization’s Google Vertex AI setup, you’ll need a few things ready.
**Cline extension installed and configured**
The Cline extension must be installed in VS Code and you need to be signed into your organization account. If you haven’t installed Cline yet, follow our [installation guide](/getting-started/installing-cline).

**Quick Check**: Open the Cline panel in VS Code. If you see your organization name in the bottom left, you’re signed in correctly.

**Google Cloud credentials with Vertex AI access**
You need Google Cloud credentials that have permission to access Vertex AI in your organization’s configured project and region.

If you’re unsure which method to use, check with your administrator or IT team about how your organization has configured Google Cloud access.

## [​](#configuration-steps) Configuration Steps

1

Open Cline Settings

Open VS Code and access the Cline settings panel using either of these methods:

- Click the settings icon (⚙️) in the Cline panel
- Click on the API Provider dropdown located directly below the chat area (it will display as `vertex_ai/gemini-pro` or similar)

2

Select Your Authentication Method

Choose one of the following credential methods to authenticate with Google Vertex AI:

Service Account Key

Use a service account JSON key file for Vertex AI access.[Learn more about Service Account Keys](https://cloud.google.com/iam/docs/service-accounts)

1. Select the **Service Account Key** authentication method
2. Upload or paste your service account JSON key content
3. The key should have `aiplatform.user` or similar Vertex AI permissions
4. These credentials are stored locally and used only by the VS Code extension

Google Cloud SDK

Use the Google Cloud SDK installed on your machine with your authenticated account.[Learn more about Google Cloud SDK](https://cloud.google.com/sdk/docs/install)

1. Select the **Google Cloud SDK** authentication method
2. Ensure you’ve authenticated with `gcloud auth login`
3. Verify your account has access to the organization’s Vertex AI project
4. Cline will use your default Google Cloud credentials automatically

Application Default Credentials

Use Google Cloud’s application default credentials (ADC) chain.

1. Select the **Application Default Credentials** method
2. Ensure ADC is properly configured in your environment
3. This works well for environments where Google Cloud credentials are managed centrally
4. Cline will automatically detect credentials from your environment

The Google Cloud Project ID and Region are preconfigured by your administrator and do not need to be set in the extension.

3

Verify Configuration

After selecting your authentication method, the extension will display checkmarks for enabled features:

- ✓ Supports images (for Gemini Pro Vision and similar models)
- ✓ Supports multimodal inputs
- ✓ Supports function calling (for supported models)

The project ID and region settings will be locked (shown with a lock icon 🔒) as they’re controlled by your administrator.

4

Test the Connection

Send a test message in Cline to verify your credentials work correctly with the configured Vertex AI project and region.

**Testing Recommendation**Try a simple test like “Hello” first to verify basic connectivity, then test multimodal capabilities if needed by sharing an image.

## [​](#model-usage) Model Usage

### [​](#available-model-families) Available Model Families

The models available through your organization’s Vertex AI setup typically include:
**Gemini Models:**

- **Gemini Pro**: Advanced reasoning, code generation, and multimodal capabilities
- **Gemini Pro Vision**: Image understanding and visual question answering
- **Gemini Ultra**: Most capable model for complex reasoning tasks

**PaLM Models:**

- **PaLM 2 for Text**: Text generation and completion
- **PaLM 2 for Chat**: Conversational AI interactions
- **Codey**: Specialized for code generation and explanation

**Specialized Models:**

- **Text Embedding**: For semantic search and similarity tasks
- **Custom Models**: Your organization’s fine-tuned variants (if available)

### [​](#model-selection-strategy) Model Selection Strategy

Choose models based on your development needs:

- **General tasks**: Use Gemini Pro for most text and reasoning tasks
- **Visual content**: Use Gemini Pro Vision when working with images
- **Code-heavy work**: Use Codey models for programming tasks
- **Complex reasoning**: Use Gemini Ultra for sophisticated problem-solving
- **Embedding tasks**: Use Text Embedding models for semantic operations

### [​](#multimodal-capabilities) Multimodal Capabilities

Take advantage of Vertex AI’s multimodal features:

- **Image Analysis**: Upload images directly in Cline for analysis
- **Visual Question Answering**: Ask questions about images
- **Code Screenshots**: Get explanations of code from screenshots
- **Document Processing**: Analyze charts, graphs, and visual data

## [​](#troubleshooting) Troubleshooting

**Google Vertex AI not available as provider option**
Confirm you’re signed into the correct Cline organization. Verify your administrator has saved the Vertex AI configuration and that you have the latest version of the Cline extension.
**Authentication errors (“Access Denied” or “Invalid Credentials”)**
Verify your chosen credential method has the necessary IAM permissions to access Vertex AI in the configured project and region. Required permissions include `aiplatform.endpoints.predict` and `aiplatform.models.predict`.
**Project access errors**
Ask your administrator to confirm which Google Cloud project is configured for your organization. Ensure your Google Cloud credentials have access to that specific project.
**Regional access errors**
Verify your credentials have access to Vertex AI in the configured region. Some models may not be available in all regions, so confirm with your administrator about the selected region.
**Google Cloud SDK authentication issues**
Ensure Google Cloud SDK is properly installed and authenticated:

```
gcloud auth login
gcloud config set project YOUR_PROJECT_ID
gcloud auth application-default login
```

**Service account key errors**
Verify the service account key is valid and hasn’t expired. Check that the service account has the proper Vertex AI permissions in your organization’s project. Ensure the JSON key file is properly formatted and contains all required fields.
**Model access errors or “model not found”**
Some models may not be enabled in your organization’s project or region. Contact your administrator if specific models are not available. Verify that your organization has enabled the models you’re trying to use in the Google Cloud Console.

## [​](#security-best-practices) Security Best Practices

When configuring your Google Cloud credentials, follow these security guidelines:

- Use service accounts with minimal required permissions for Vertex AI access
- Rotate service account keys regularly (every 90 days recommended)
- Never store credentials in code or version control
- Use Google Cloud SDK where possible for better credential management
- Consider using Workload Identity for containerized development environments
- Report any suspicious activity or unauthorized access attempts

Your organization administrator controls which models and regions are available. The extension will automatically display available models based on your project’s configuration and regional availability.
For more information about Google Cloud authentication and Vertex AI permissions, refer to the [Google Cloud IAM Documentation](https://cloud.google.com/iam/docs) and coordinate with your organization’s cloud administrator.

Was this page helpful?

YesNo

[Configure Google Vertex (Admin)](/enterprise-solutions/configuration/remote-configuration/google-vertex/admin-configuration)[Configure OpenAI Compatible (Admin)](/enterprise-solutions/configuration/remote-configuration/openai-compatible/admin-configuration)

⌘I

---

## Admin Configuration

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/litellm/admin-configuration](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/litellm/admin-configuration)*

As an administrator, you can add LiteLLM as the organization-wide LLM provider for all Cline users through the hosted admin console. This centralized approach provides unified access to multiple AI models through your LiteLLM proxy interface.

## [​](#before-you-begin) Before You Begin

To get started with setting up LiteLLM as your organization’s LLM provider, you’ll need a few items in place.
**Administrator access to the Cline Admin console**
You need admin privileges to enforce provider settings across your organization. If you can navigate to **Settings → Cline Settings** in the admin console at [app.cline.bot](https://app.cline.bot), you have the right access level.

**Quick Check**: Try accessing the settings page now. If you can see the provider configuration options, you’re good to go.

**LiteLLM proxy instance running**
You need a deployed LiteLLM proxy that your team can access. This can be self-hosted or managed through a cloud provider.

If you haven’t deployed LiteLLM yet, work with your infrastructure team to set up a LiteLLM proxy instance.

**LiteLLM endpoint details**
You’ll need the base URL of your LiteLLM proxy and optionally a master key if your deployment requires authentication.

Ensure your LiteLLM proxy is accessible from your team’s development environments and has the models you want to make available configured.

## [​](#configuration-steps) Configuration Steps

1

Access Cline Settings

Navigate to [app.cline.bot](https://app.cline.bot) and sign in with your administrator account. Go to **Settings → Cline Settings**.

You should see the provider configuration options if you have the correct admin access level.

2

Enable Remote Provider Configuration

Toggle on **Enable settings** to reveal the remote provider configuration options. This allows you to enforce provider settings across your organization.

3

Select LiteLLM as the API Provider

Open the **API Provider** dropdown menu and select **LiteLLM**. This will open the LiteLLM configuration panel where you’ll configure all your organization-wide settings.

4

Configure LiteLLM Settings

The configuration panel includes settings that control how LiteLLM works for your organization:

Base URL (required)

Enter your LiteLLM proxy endpoint URL. This should be the full URL where your LiteLLM proxy is accessible, such as `https://litellm.yourcompany.com` or `http://your-proxy:4000`.

Use HTTPS endpoints in production for security. Make sure the URL is accessible from your team’s development environments.

Master Key (optional)

If your LiteLLM proxy requires authentication, enter the master key here. This will be used to authenticate requests from all organization members.

**Centralized API Key Management**: By configuring the Master Key at the organization level, you enable centralized API key management. Organization members won’t need to manage their own individual API keys - access is fully managed through this centralized configuration.

The master key provides full access to your LiteLLM proxy. Only enter this if your proxy requires authentication and you want centralized key management.

5

Save Configuration

After configuring your settings, close the provider configuration panel and click **Save** on the settings page to persist your changes.Once saved, all organization members signed into the Cline extension will automatically use LiteLLM with your configured settings. They won’t be able to select other providers or switch to their personal Cline accounts.

Members can’t switch to personal Cline accounts or join other organizations once remote configuration is enabled. This ensures consistent provider usage across your team.

## [​](#verification) Verification

To verify the configuration:

1. Check that the provider shows as “LiteLLM” in the Enabled provider field
2. Confirm the settings persist after refreshing the page
3. Test with a member account to ensure they see only LiteLLM as a provider
4. Verify that the configured models are available in the model dropdown

## [​](#troubleshooting) Troubleshooting

**Members don’t see the configured provider**
Ensure you clicked Save after closing the configuration panel. Verify the member account belongs to the correct organization and that your LiteLLM proxy is accessible from their network.
**Connection errors to LiteLLM proxy**
Verify the Base URL is correct and accessible. Check that any firewalls or security groups allow access from your team’s IP addresses or development environments.
**Authentication failures**
If using a master key, verify it’s correctly entered and has proper permissions in your LiteLLM deployment. Check the LiteLLM proxy logs for authentication errors.
**Models not available**
Confirm the models are properly configured in your LiteLLM proxy deployment. The available models depend on how your LiteLLM proxy is configured.
**Configuration changes don’t persist**
Make sure to click the Save button on the main settings page, not just close the configuration panel.
**Need to change endpoint or key later**
You can update these settings at any time. Changes take effect immediately for all organization members.
For further details about LiteLLM deployment and configuration, consult the [LiteLLM Documentation](https://docs.litellm.ai/) and coordinate with your infrastructure team.

Was this page helpful?

YesNo

[Configure Anthropic (Member)](/enterprise-solutions/configuration/remote-configuration/anthropic/member-configuration)[Configure LiteLLM (Member)](/enterprise-solutions/configuration/remote-configuration/litellm/member-configuration)

⌘I

---

## Member Configuration

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/litellm/member-configuration](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/litellm/member-configuration)*

As a team member, you can connect your local development environment to your organization’s LiteLLM proxy setup. This guide walks you through configuring your connection in VS Code so you can start using multiple AI models through your organization’s unified proxy interface. Your administrator has already configured the provider settings-you just need to add your credentials to get started.

## [​](#before-you-begin) Before You Begin

To successfully connect to your organization’s LiteLLM proxy, you’ll need a few things ready.
**Cline extension installed and configured**
The Cline extension must be installed in VS Code and you need to be signed into your organization account. If you haven’t installed Cline yet, follow our [installation guide](/getting-started/installing-cline).

**Quick Check**: Open the Cline panel in VS Code. If you see your organization name in the bottom left, you’re signed in correctly.

**Access credentials for your organization’s LiteLLM proxy**
You need credentials to access your organization’s LiteLLM proxy. This might be an API key, or the proxy might be configured for open access within your network.

If you’re unsure about the credentials needed, check with your administrator or IT team about how to access your organization’s LiteLLM proxy.

## [​](#configuration-steps) Configuration Steps

1

Open Cline Settings

Open VS Code and access the Cline settings panel using either of these methods:

- Click the settings icon (⚙️) in the Cline panel
- Click on the API Provider dropdown located directly below the chat area (it will display as `LiteLLM` or show a specific model name)

2

Configure LiteLLM Connection

The LiteLLM configuration options depend on how your organization has set up the proxy:

API Key Authentication

If your organization requires API key authentication:

1. Select or confirm the **LiteLLM** provider is selected
2. Enter your assigned API key in the **API Key** field
3. The base URL should already be configured by your administrator
4. Click **Save** to store your credentials

API keys are stored locally in VS Code and are only used by the Cline extension.

Open Access (No Authentication)

If your LiteLLM proxy is configured for open access within your network:

1. Select or confirm the **LiteLLM** provider is selected
2. Leave the API key field empty
3. The extension will connect directly to the configured proxy endpoint
4. No additional authentication is required

Open access is common when the LiteLLM proxy is deployed within a secure network environment.

Custom Configuration

If your organization uses custom authentication or specific connection parameters:

1. Follow any custom instructions provided by your administrator
2. Contact your IT team if you encounter connection issues
3. Additional configuration may be needed outside of VS Code

Custom configurations might require specific network settings or additional authentication steps.

3

Select Available Models

Once connected, you’ll see the models available through your organization’s LiteLLM proxy:

- View available models in the model dropdown
- Models are determined by your administrator’s proxy configuration
- You can switch between models for different types of tasks
- Some models may be restricted based on your access level

**Model Selection**Choose models based on your task requirements:

- **Fast models** (like GPT-3.5-turbo) for quick responses
- **Powerful models** (like GPT-4) for complex reasoning
- **Specialized models** for code generation or specific domains

4

Test the Connection

Send a test message in Cline to verify your connection works correctly with the LiteLLM proxy.

**Testing Recommendation**Test the connection in plan mode first to verify everything works correctly before using it for actual development tasks.

## [​](#model-usage) Model Usage

### [​](#available-model-categories) Available Model Categories

The models available through your LiteLLM proxy typically include:
**Text Generation Models:**

- OpenAI GPT-4, GPT-3.5-turbo variants
- Anthropic Claude 3 Sonnet, Haiku, Opus
- Open source models like Llama 2, Mistral

**Code-Specific Models:**

- OpenAI GPT-4 for code
- CodeLlama variants
- Specialized code completion models

**Multimodal Models:**

- GPT-4 Vision for image analysis
- Claude 3 models with vision capabilities

### [​](#model-selection-strategy) Model Selection Strategy

Choose models based on your development needs:

- **Quick iterations**: Use faster, cost-effective models
- **Complex problems**: Use more powerful models
- **Code-heavy tasks**: Use code-specialized models
- **Visual content**: Use multimodal models when working with images

## [​](#troubleshooting) Troubleshooting

**LiteLLM not available as provider option**
Confirm you’re signed into the correct Cline organization. Verify your administrator has saved the LiteLLM configuration and that you have the latest version of the Cline extension.
**Connection errors or timeouts**
Verify your network can reach the LiteLLM proxy endpoint. Check with your IT team about firewall rules or VPN requirements. Ensure the proxy endpoint is accessible from your development environment.
**Authentication failures**
If using API key authentication, verify the key is correctly entered and hasn’t expired. Contact your administrator to confirm your key is active and has the proper permissions.
**Models not loading or are limited**
The available models depend on your organization’s LiteLLM configuration. Contact your administrator if you need access to specific models or if expected models aren’t available.
**Slow response times**
Response times depend on the models being used and proxy load. Try switching to faster models for routine tasks. Contact your administrator if performance is consistently poor.
**Error messages from specific models**
Some models may be temporarily unavailable or have specific limitations. Try alternative models or contact your administrator if specific models are consistently failing.

## [​](#security-best-practices) Security Best Practices

When working with your organization’s LiteLLM proxy:

- Keep your API credentials secure and don’t share them
- Use appropriate models for the sensitivity of your data
- Follow your organization’s usage guidelines
- Report any suspicious activity or unauthorized access attempts
- Regularly update the Cline extension for security patches

Your organization administrator controls which models are available and usage policies. The extension will automatically display available models based on your proxy configuration and access level.

Was this page helpful?

YesNo

[Configure LiteLLM (Admin)](/enterprise-solutions/configuration/remote-configuration/litellm/admin-configuration)[YOLO Mode](/enterprise-solutions/configuration/infrastructure-configuration/control-other-cline-features/yolo-mode)

⌘I

---

## Admin Configuration

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/openai-compatible/admin-configuration](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/openai-compatible/admin-configuration)*

As an administrator, you can add an OpenAI-compatible endpoint as the organization-wide LLM provider for all Cline users through the hosted admin console. This covers any provider that exposes an OpenAI-compatible API, including Azure Foundry (Azure OpenAI), self-hosted inference engines (vLLM, TGI), and other compatible services.

## [​](#before-you-begin) Before You Begin

To get started with setting up an OpenAI-compatible provider for your organization, you’ll need a few items in place.
**Administrator access to the Cline Admin console**
You need admin privileges to enforce provider settings across your organization. If you can navigate to **Settings → Cline Settings** in the admin console at [app.cline.bot](https://app.cline.bot), you have the right access level.
**An OpenAI-compatible API endpoint**
You need a running endpoint that implements the OpenAI chat completions API. This could be:

- Azure Foundry (Azure OpenAI Service)
- A self-hosted inference engine (vLLM, text-generation-inference, etc.)
- Any third-party service with an OpenAI-compatible API

If you’re using Azure Foundry, you’ll need your Azure OpenAI endpoint URL and optionally the API version. Work with your Azure administrator to ensure the endpoint is provisioned and accessible.

**Endpoint URL and authentication details**
You’ll need the base URL of your endpoint and any required authentication headers.

## [​](#configuration-steps) Configuration Steps

1

Access Cline Settings

Navigate to [app.cline.bot](https://app.cline.bot) and sign in with your administrator account. Go to **Settings → Cline Settings**.

You should see the provider configuration options if you have the correct admin access level.

2

Enable Remote Provider Configuration

Toggle on **Enable settings** to reveal the remote provider configuration options. This allows you to enforce provider settings across your organization.

3

Select OpenAI Compatible as the API Provider

Open the **API Provider** dropdown menu and select **OpenAI Compatible**. This will open the configuration panel where you’ll configure all your organization-wide settings.

4

Configure OpenAI Compatible Settings

The configuration panel includes settings that control how the provider works for your organization:

Base URL (required)

Enter the base URL of your OpenAI-compatible endpoint. Examples:

- **Azure Foundry**: `https://your-resource.openai.azure.com`
- **Self-hosted vLLM**: `https://inference.yourcompany.com/v1`
- **Other compatible services**: The provider’s API base URL

Use HTTPS endpoints in production for security. Ensure the URL is accessible from your team’s development environments.

Custom Headers (optional)

Add custom HTTP headers that will be included with every API request. This is useful for:

- Custom authentication schemes beyond API keys
- Routing headers for internal load balancers
- Organization or tenant identifiers required by your endpoint

Headers are configured as key-value pairs.

Azure API Version (optional — Azure Foundry only)

If you’re using Azure Foundry (Azure OpenAI), specify the API version string. For example: `2024-02-15-preview` or `2024-06-01`.This field is only needed for Azure OpenAI deployments. Leave it empty for non-Azure endpoints.

Check the [Azure OpenAI API version documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/reference) for available versions.

Azure Identity Authentication (optional — Azure Foundry only)

Enable this to use Azure Active Directory (Entra ID) token-based authentication instead of API keys. When enabled, members authenticate using their Azure AD credentials rather than a static API key.This field is only relevant for Azure Foundry deployments.

5

Save Configuration

After configuring your settings, close the provider configuration panel and click **Save** on the settings page to persist your changes.Once saved, all organization members signed into the Cline extension will automatically use the OpenAI Compatible provider with your configured settings. They won’t be able to select other providers or switch to their personal Cline accounts.

Members can’t switch to personal Cline accounts or join other organizations once remote configuration is enabled. This ensures consistent provider usage across your team.

## [​](#azure-foundry-configuration) Azure Foundry Configuration

For organizations using Azure Foundry (Azure OpenAI Service), use the following configuration:

1. **Base URL**: Your Azure OpenAI endpoint (e.g., `https://your-resource.openai.azure.com`)
2. **Azure API Version**: The API version to use (e.g., `2024-06-01`)
3. **Azure Identity Authentication**: Enable if your organization uses Azure AD for authentication instead of API keys

## [​](#verification) Verification

To verify the configuration:

1. Check that the provider shows as “OpenAI Compatible” in the Enabled provider field
2. Confirm the settings persist after refreshing the page
3. Test with a member account to ensure they see only the OpenAI Compatible provider
4. Verify that configured models are available in the model dropdown

## [​](#troubleshooting) Troubleshooting

**Members don’t see the configured provider**
Ensure you clicked Save after closing the configuration panel. Verify the member account belongs to the correct organization.
**Connection errors to the endpoint**
Verify the Base URL is correct and accessible from your team’s development environments. Check that any firewalls or security groups allow access from developer IP addresses.
**Azure authentication failures**
If using Azure Identity Authentication, verify that members’ Azure AD accounts have the appropriate role assignments on the Azure OpenAI resource. If using API keys, verify the key is correctly entered by the member.
**Configuration changes don’t persist**
Make sure to click the Save button on the main settings page, not just close the configuration panel.
**Need to change endpoint or settings later**
You can update these settings at any time. Changes take effect immediately for all organization members.
For Azure Foundry, consult the [Azure OpenAI Service documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/). For other OpenAI-compatible endpoints, refer to your provider’s documentation.

Was this page helpful?

YesNo

[Configure Google Vertex (Member)](/enterprise-solutions/configuration/remote-configuration/google-vertex/member-configuration)[Configure OpenAI Compatible (Member)](/enterprise-solutions/configuration/remote-configuration/openai-compatible/member-configuration)

⌘I

---

## Member Configuration

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/openai-compatible/member-configuration](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/openai-compatible/member-configuration)*

As a team member, you can connect your local development environment to your organization’s OpenAI-compatible endpoint. This guide walks you through configuring your credentials in VS Code so you can start using models through your organization’s configured endpoint. Your administrator has already configured the provider settings — you just need to add your API key to get started.

## [​](#before-you-begin) Before You Begin

To successfully connect to your organization’s OpenAI-compatible endpoint, you’ll need a few things ready.
**Cline extension installed and configured**
The Cline extension must be installed in VS Code and you need to be signed into your organization account. If you haven’t installed Cline yet, follow our [installation guide](/getting-started/installing-cline).

**Quick Check**: Open the Cline panel in VS Code. If you see your organization name in the bottom left, you’re signed in correctly.

**API key or credentials for your endpoint**
You need an API key or credentials to authenticate with your organization’s configured endpoint. For Azure Foundry deployments using Azure Identity Authentication, your Azure AD credentials may be used instead.

If you’re unsure what credentials to use, check with your administrator or IT team about how your organization has configured access.

## [​](#configuration-steps) Configuration Steps

1

Open Cline Settings

Open VS Code and access the Cline settings panel using either of these methods:

- Click the settings icon (⚙️) in the Cline panel
- Click on the API Provider dropdown located directly below the chat area

2

Configure Your Credentials

The authentication method depends on how your administrator configured the endpoint:

API Key Authentication

For most OpenAI-compatible endpoints:

1. Select or confirm the **OpenAI Compatible** provider is selected
2. Enter your API key in the **API Key** field
3. The base URL, custom headers, and other settings are preconfigured by your administrator
4. Click **Save** to store your credentials

API keys are stored locally and are only used by the Cline extension.

Azure Identity Authentication (Azure Foundry)

If your organization uses Azure AD authentication:

1. Select or confirm the **OpenAI Compatible** provider is selected
2. Ensure you are signed into Azure in your development environment
3. The extension will use your Azure AD credentials automatically
4. No API key is needed when Azure Identity Authentication is enabled

You may need the Azure Account extension or Azure CLI installed for credential resolution.

The Base URL, custom headers, Azure API version, and Azure Identity settings are preconfigured by your administrator and do not need to be set in the extension.

3

Verify Configuration

After configuring your credentials, administrator-controlled settings will be locked (shown with a lock icon 🔒) as they’re managed by your organization.

4

Test the Connection

Send a test message in Cline to verify your credentials work correctly with the configured endpoint.

**Testing Recommendation**Try a simple test like “Hello” first to verify basic connectivity before starting development tasks.

## [​](#troubleshooting) Troubleshooting

**OpenAI Compatible not available as provider option**
Confirm you’re signed into the correct Cline organization. Verify your administrator has saved the configuration and that you have the latest version of the Cline extension.
**Authentication errors (“Access Denied” or “Invalid API Key”)**
Verify your API key is correct and active. For Azure Foundry with Azure Identity Authentication, ensure you are signed into Azure in your development environment and that your account has the appropriate role assignments on the Azure OpenAI resource.
**Connection errors or timeouts**
The endpoint URL is configured by your administrator. If you experience connection issues, check with your IT team about network requirements (VPN, firewall rules, etc.).
**Models not available**
The available models depend on your organization’s endpoint configuration. Contact your administrator if expected models are not available in the model dropdown.
**Configuration changes don’t persist**
Make sure to save your credentials. The base URL and other admin-controlled settings cannot be changed locally.

## [​](#security-best-practices) Security Best Practices

When working with your API credentials:

- Keep your API key secure and do not share it
- Never store credentials in code or version control
- Report any suspected key compromise to your administrator immediately
- Follow your organization’s usage guidelines for the configured endpoint

Your organization administrator controls which endpoint, models, and settings are available. The extension will automatically apply the configured settings based on your organization’s remote configuration.
For Azure Foundry, refer to the [Azure OpenAI Service documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/). For other endpoints, consult your organization’s internal documentation or contact your administrator.

Was this page helpful?

YesNo

[Configure OpenAI Compatible (Admin)](/enterprise-solutions/configuration/remote-configuration/openai-compatible/admin-configuration)[Configure Anthropic (Admin)](/enterprise-solutions/configuration/remote-configuration/anthropic/admin-configuration)

⌘I

---

## Overview

*Source: [https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/overview](https://docs.cline.bot/enterprise-solutions/configuration/remote-configuration/overview)*

Remote Provider Configuration allows administrators to centrally configure inference providers for their entire organization through the Cline hosted admin console. This approach ensures consistent provider access, security policies, and cost management across all team members without requiring individual developer setup or infrastructure deployment.

## [​](#how-remote-configuration-works) How Remote Configuration Works

Remote configuration operates through Cline’s hosted service at [app.cline.bot](https://app.cline.bot), where administrators can:

## Centralized Setup

Configure providers once for the entire organization through the web-based admin console.

## Automatic Enforcement

Team members automatically receive the configured provider settings when signed into their organization.

## Simplified Onboarding

New team members get instant access to inference providers without complex individual configuration.

## Consistent Experience

Ensure all team members use the same models, regions, and settings organization-wide.

## [​](#supported-providers) Supported Providers

Cline supports remote configuration for the following inference providers:

| Provider | Use Case | Configuration | Member Setup |
| --- | --- | --- | --- |
| **Cline** | Organizations using Cline’s native provider with centralized API key management | API provider selection, model access | No individual API keys needed — fully managed by organization |
| **Amazon Bedrock** | Organizations using AWS infrastructure | Region selection, VPC endpoints, cross-region inference, global inference, prompt caching | AWS credential configuration (API key, CLI profile, or credential chain) |
| **Google Vertex AI** | Organizations using Google Cloud Platform | Project ID, region selection, model access | Google Cloud credential configuration (service account, SDK, or ADC) |
| **Azure Foundry** | Organizations using Azure OpenAI or Azure AI services | Base URL, Azure API version, Azure identity authentication, custom headers | API key configuration in the extension |
| **Anthropic** | Organizations using the Anthropic API directly | Optional custom base URL for proxy deployments, model access | API key configuration in the extension |
| **OpenAI Compatible** | Organizations using any OpenAI-compatible endpoint (self-hosted, vLLM, custom proxies) | Base URL, custom headers, model access | API key configuration in the extension |
| **LiteLLM** | Organizations requiring multi-model access through a unified proxy | Proxy endpoint, authentication, model routing | API key or endpoint configuration (or centralized with Master Key) |

**Azure Foundry** uses the OpenAI Compatible provider configuration with Azure-specific settings (API version, Azure identity authentication). See the [OpenAI Compatible admin configuration](/enterprise-solutions/configuration/remote-configuration/openai-compatible/admin-configuration) for setup instructions.

## [​](#configuration-process) Configuration Process

The typical remote configuration process follows these steps:

1

Administrator Setup

Access the Cline admin console and configure the desired inference provider with organization-wide settings.

2

Automatic Distribution

Provider configuration is automatically distributed to all organization members signed into Cline.

3

Member Credential Setup

Team members add their individual credentials (API keys, AWS profiles, etc.) to connect to the configured provider. For some providers like Cline and LiteLLM (with Master Key), no individual credentials are needed.

4

Immediate Access

Once credentials are configured, members can immediately start using the inference provider through Cline.

## [​](#benefits-of-remote-configuration) Benefits of Remote Configuration

### [​](#for-administrators) **For Administrators**

- **Centralized Control**: Manage all provider settings from one location
- **Security Compliance**: Ensure consistent security policies across the organization
- **Easy Updates**: Change provider settings organization-wide instantly

### [​](#for-team-members) **For Team Members**

- **Simplified Setup**: No need to research provider configuration options
- **Consistent Experience**: Same models and features available to everyone
- **Quick Onboarding**: Get started immediately with pre-configured providers
- **Focus on Development**: Spend time coding instead of configuring inference providers

## [​](#getting-started) Getting Started

To get started with provider remote configuration:

1. **Choose Your Provider**: Select the inference provider that best fits your organization’s needs and existing infrastructure
2. **Admin Configuration**: Follow the provider-specific admin configuration guide
3. **Member Onboarding**: Have team members complete the provider-specific member configuration
4. **Start Developing**: Begin using Cline with centrally managed inference provider access

Select your provider below to begin the configuration process:

## Amazon Bedrock

AWS-based AI models with enterprise security and compliance features.

## Google Vertex AI

Google Cloud’s AI platform with Gemini models and regional control.

## OpenAI Compatible

Any OpenAI-compatible endpoint, including Azure Foundry.

## Anthropic

Direct Anthropic API access with optional custom base URL configuration.

## LiteLLM

Unified proxy for accessing 100+ AI models through a single interface.

Was this page helpful?

YesNo

[Managing Members](/enterprise-solutions/team-management/managing-members)[Configure AWS Bedrock (Admin)](/enterprise-solutions/configuration/remote-configuration/aws-bedrock/admin-configuration)

⌘I

---

## Opentelemetry

*Source: [https://docs.cline.bot/enterprise-solutions/monitoring/opentelemetry](https://docs.cline.bot/enterprise-solutions/monitoring/opentelemetry)*

Cline includes opt-in OpenTelemetry support for exporting metrics and logs to your own observability infrastructure using the OpenTelemetry Protocol (OTLP).

OpenTelemetry integration is **optional** and intended for advanced users with existing observability infrastructure. Most users won’t need this feature.

## [​](#what-is-opentelemetry) What is OpenTelemetry?

[OpenTelemetry](https://opentelemetry.io/) is an industry-standard observability framework that provides a unified way to collect and export telemetry data (metrics, logs, and traces).
Cline’s OpenTelemetry support allows you to:

- Export telemetry to your own systems
- Integrate with observability platforms like Datadog, New Relic, Grafana Cloud, etc.
- Maintain full control over your monitoring data
- Use your organization’s existing monitoring infrastructure

## [​](#supported-features) Supported Features

Cline supports OpenTelemetry’s **OTLP (OpenTelemetry Protocol)** export with:

## Metrics Export

Export metrics about Cline usage, performance, and errors

## Logs Export

Export structured logs for debugging and analysis

### [​](#export-formats) Export Formats

Cline supports three OTLP export protocols:

- **gRPC** (default, recommended)
- **HTTP/protobuf**
- **HTTP/JSON**

## [​](#configuration) Configuration

OpenTelemetry is configured using [Remote Configuration](/enterprise-solutions/configuration/remote-configuration/overview#how-remote-configuration-works) from the [dashboard](https://app.cline.bot/dashboard/organization?tab=settings).

### [​](#basic-setup) Basic Setup

Enable OpenTelemetry, configure an OTLP endpoint and select a protocol:If you’re using gRPC, you can opt out of TLS.
Once the collector has been configured, you can enable logs and/or metrics collection. At least one of them needs to be enabled.
You only need to configure it further if you need an advanced configuration.

### [​](#advanced-configuration) Advanced Configuration

You can add custom protocols and endpoints for both, logs and metrics. You can also configure the metrics export interval, and the logs batch size, batch timeout and max queue size.**Custom headers for authentication:**
Finally, if your collector needs authentication headers, you can add key value pairs in the headers section.

## [​](#integration-examples) Integration Examples

### [​](#datadog) Datadog

Export to Datadog using their OTLP endpoint:

### [​](#new-relic) New Relic

Export to New Relic:

### [​](#grafana-cloud) Grafana Cloud

Export to Grafana Cloud:

## [​](#testing-configuration) Testing Configuration

To test your configuration, log in to your account, perform some actions in a task, wait for the export interval, and verify that the data has arrived at your collector.

## [​](#troubleshooting) Troubleshooting

If you aren’t getting any data in your collector, the easiest way to verify your integration is to enable the developer tools in your editor.
To do this, open the [webview developer tools](https://code.visualstudio.com/api/extension-guides/webview#inspecting-and-debugging-webviews).
Once you’ve done so, if you perform some actions that trigger metrics and/or logs (such as doing a task with Cline),
you will see error logs if any error occurs when sending the data to your collector.
If you don’t see any logs, enable [debug mode](#debug-mode).

### [​](#connection-errors) Connection Errors

1. **Verify endpoint is accessible:**

   ```
   curl -v https://your-otlp-endpoint:4317
   ```
2. **Check if insecure mode is needed** by opting out of TLS
3. **Verify authentication headers:**
   Double-check your API keys and authentication headers are correct

### [​](#debug-mode) Debug Mode

Enable debug logging to see detailed OpenTelemetry information:

```
TEL_DEBUG_DIAGNOSTICS=true code .
```

This will output detailed information about:

- Configuration being used
- Exporters being created
- Connection attempts
- Export successes/failures

## [​](#what-gets-exported) What Gets Exported

When OpenTelemetry is enabled, Cline exports:

### [​](#metrics) Metrics

- Feature usage counts
- Task execution metrics
- Error rates and types
- Performance measurements

### [​](#logs) Logs

- System events
- Error logs with context
- Operational information

Exported data is already anonymous and doesn’t include code content, file paths, or sensitive information. However, you’re responsible for securing the data once exported to your systems.

## [​](#limitations) Limitations

Current OpenTelemetry support in Cline:

- ✅ OTLP metrics export (gRPC, HTTP)
- ✅ OTLP logs export (gRPC, HTTP)
- ✅ Basic configuration via [Remote Configuration](/enterprise-solutions/configuration/remote-configuration/overview#how-remote-configuration-works)
- ❌ Distributed tracing (not yet implemented)
- ❌ Custom instrumentation API (not yet exposed)
- ❌ Sampling configuration (uses defaults)

## [​](#best-practices) Best Practices

1. **Test First**: Always test with console exporter before sending to production
2. **Secure Credentials**: Never hardcode API keys; use secure environment variable management
3. **Monitor Costs**: Be aware of data ingestion costs with your observability platform
4. **Start Simple**: Begin with metrics only, add logs if needed
5. **Use Compression**: OTLP supports compression; check if your endpoint requires it

## [​](#next-steps) Next Steps

## Event Reference

Complete catalog of all emitted OTel events

## Cline Telemetry

Configure simple built-in telemetry

## OpenTelemetry Docs

Learn more about OpenTelemetry

Was this page helpful?

YesNo

[Prompt Storage](/enterprise-solutions/monitoring/prompt-storage)[OTel Events](/enterprise-solutions/monitoring/opentelemetry-events)

⌘I

---

## Opentelemetry Events

*Source: [https://docs.cline.bot/enterprise-solutions/monitoring/opentelemetry-events](https://docs.cline.bot/enterprise-solutions/monitoring/opentelemetry-events)*

This page documents all OpenTelemetry log events currently instrumented in Cline. These events are emitted when OpenTelemetry integration is enabled and provide detailed insights into user behavior, task execution, and system operations.

Events are only emitted when OpenTelemetry is enabled. See [OpenTelemetry](/enterprise-solutions/monitoring/opentelemetry) for configuration instructions.

## [​](#event-categories) Event Categories

Cline emits events across several categories, each prefixed with a namespace:

## user.\*

Authentication, telemetry controls, extension lifecycle

## task.\*

Task execution, conversation turns, tool usage, tokens

## workspace.\*

Workspace initialization, VCS detection, path resolution

## ui.\*

User interface interactions and model selection

## hooks.\*

Hook discovery, execution, and context modification

## worktree.\*

Git worktree operations and merge handling

## host.\*

Host environment detection

## test.\*

Diagnostic and connection testing

## [​](#user-events) User Events

Events related to user authentication, telemetry preferences, and extension lifecycle.

| Event | Description | Key Attributes |
| --- | --- | --- |
| `user.opt_out` | User explicitly opts out of telemetry | user\_id, timestamp |
| `user.opt_in` | User explicitly opts into telemetry | user\_id, timestamp |
| `user.telemetry_enabled` | Telemetry service enabled/initialization signal | enabled, timestamp |
| `user.extension_activated` | Extension activation event | extension\_version, host\_type |
| `user.extension_storage_error` | Error while reading/writing extension storage state | error\_type, error\_message |
| `user.auth_started` | Authentication flow started | provider, timestamp |
| `user.auth_succeeded` | Authentication flow succeeded | provider, user\_id |
| `user.auth_failed` | Authentication flow failed | provider, error\_reason |
| `user.auth_logged_out` | User logged out | reason, provider |
| `user.onboarding_progress` | Onboarding step/action progress | step, action, completed |

### [​](#example-user-auth_succeeded) Example: user.auth\_succeeded

```
{
  "event": "user.auth_succeeded",
  "timestamp": "2026-03-05T10:30:00Z",
  "attributes": {
    "provider": "github",
    "user_id": "user_abc123",
    "session_id": "sess_xyz789"
  }
}
```

## [​](#workspace-events) Workspace Events

Events related to workspace initialization, version control detection, and multi-root operations.

| Event | Description | Key Attributes |
| --- | --- | --- |
| `workspace.initialized` | Workspace initialization completed | roots\_count, vcs\_type, duration\_ms |
| `workspace.init_error` | Workspace initialization failed | error\_type, fallback\_used |
| `workspace.vcs_detected` | Version control system detection event | vcs\_type, root\_path\_hash |
| `workspace.multi_root_checkpoint` | Multi-root checkpoint operation telemetry | operation, roots\_count, duration\_ms |
| `workspace.path_resolved` | Workspace path resolution | hint, fallback\_used, cross\_workspace |

### [​](#example-workspace-initialized) Example: workspace.initialized

```
{
  "event": "workspace.initialized",
  "timestamp": "2026-03-05T10:32:15Z",
  "attributes": {
    "roots_count": 2,
    "vcs_type": "git",
    "duration_ms": 145,
    "multi_root_enabled": true
  }
}
```

## [​](#task-events) Task Events

Core events tracking task lifecycle, conversation turns, tool usage, and execution details.

### [​](#task-lifecycle) Task Lifecycle

| Event | Description | Key Attributes |
| --- | --- | --- |
| `task.created` | New task/conversation started | task\_id, mode, model, provider |
| `task.restarted` | Existing task restarted/reopened | task\_id, time\_since\_last\_message |
| `task.completed` | Task completed | task\_id, duration\_ms, model, provider, tokens\_total |
| `task.feedback` | User feedback on task | task\_id, feedback\_type (thumbs\_up/thumbs\_down) |
| `task.historical_loaded` | Historical task loaded from storage | task\_id, age\_days |
| `task.retry_clicked` | User clicked retry on a failed action/request | task\_id, action\_type |

### [​](#conversation-&-tokens) Conversation & Tokens

| Event | Description | Key Attributes |
| --- | --- | --- |
| `task.conversation_turn` | Conversation turn event | role (user/assistant), provider, model, tokens\_in, tokens\_out |
| `task.tokens` | Token usage event | tokens\_in, tokens\_out, cached\_tokens, cost |
| `task.mode` | Plan/Act mode switch event | previous\_mode, new\_mode, task\_id |

### [​](#tool-usage) Tool Usage

| Event | Description | Key Attributes |
| --- | --- | --- |
| `task.tool_used` | Tool invocation and outcome telemetry | tool\_name, success, duration\_ms, auto\_approved |
| `task.mcp_tool_called` | MCP tool call lifecycle event | status (started/success/error), tool\_name, server\_name |
| `task.browser_tool_start` | Browser tool/session started | url, action |
| `task.browser_tool_end` | Browser tool/session ended with stats | duration\_ms, actions\_count, success |
| `task.browser_error` | Browser tool error event | error\_type, url |
| `task.terminal_execution` | Terminal execution capture success/failure event | success, command\_hash, duration\_ms |
| `task.terminal_output_failure` | Terminal output capture failed | reason |
| `task.terminal_user_intervention` | User intervention during terminal execution | intervention\_type |
| `task.terminal_hang` | Terminal hang/stuck detection event | duration\_ms, command\_hash |

### [​](#features-&-options) Features & Options

| Event | Description | Key Attributes |
| --- | --- | --- |
| `task.checkpoint_used` | Checkpoint action used | action (create/restore/compare), task\_id |
| `task.option_selected` | User selected one of AI-provided options | option\_index, total\_options |
| `task.options_ignored` | User ignored AI options and entered custom input | options\_count |
| `task.slash_command_used` | Slash command or MCP prompt command used | command\_name |
| `task.mention_used` | Mention resolution succeeded | mention\_type (file/url/folder/terminal/problems/git) |
| `task.mention_failed` | Mention resolution failed | mention\_type, error\_reason |
| `task.mention_search_results` | Mention search query result telemetry | query, results\_count |
| `task.workspace_search_pattern` | Workspace search strategy/pattern telemetry | pattern\_type, files\_scanned |

### [​](#advanced-features) Advanced Features

| Event | Description | Key Attributes |
| --- | --- | --- |
| `task.focus_chain_enabled` | Focus chain feature enabled | task\_id |
| `task.focus_chain_disabled` | Focus chain feature disabled | task\_id |
| `task.focus_chain_progress_first` | First focus-chain checklist/progress emitted | items\_count |
| `task.focus_chain_progress_update` | Subsequent focus-chain checklist/progress updates | items\_total, items\_completed |
| `task.focus_chain_incomplete_on_completion` | Task completed while focus-chain checklist still incomplete | items\_remaining |
| `task.focus_chain_list_opened` | Focus-chain markdown/list opened by user | task\_id |
| `task.focus_chain_list_written` | Focus-chain markdown/list written/saved | task\_id |
| `task.subagent_enabled` | Subagents feature enabled | task\_id |
| `task.subagent_disabled` | Subagents feature disabled | task\_id |
| `task.subagent_started` | Subagent execution started | subagent\_id, prompt\_length |
| `task.subagent_completed` | Subagent execution completed | subagent\_id, duration\_ms, success |
| `task.skill_used` | Skill invocation event | skill\_name, task\_id |

### [​](#auto-compact-&-context) Auto-Compact & Context

| Event | Description | Key Attributes |
| --- | --- | --- |
| `task.summarize_task` | Auto-compaction/summarize triggered for context pressure | conversation\_length, estimated\_tokens |
| `task.auto_condense_toggled` | Auto-condense setting toggled | enabled |

### [​](#settings-&-features) Settings & Features

| Event | Description | Key Attributes |
| --- | --- | --- |
| `task.feature_toggled` | Generic feature toggle changed | feature\_name, enabled |
| `task.rule_toggled` | Cline rule toggled on/off | rule\_name, enabled, is\_global |
| `task.yolo_mode_toggled` | YOLO mode toggled | enabled |
| `task.cline_web_tools_toggled` | Cline web tools setting toggled | enabled |

### [​](#api-&-performance) API & Performance

| Event | Description | Key Attributes |
| --- | --- | --- |
| `task.gemini_api_performance` | Gemini-specific API performance telemetry | duration\_ms, tokens, cache\_hit |
| `task.provider_api_error` | API provider error event | provider, model, error\_code, error\_message |
| `task.diff_edit_failed` | Diff/replace edit failed | file\_path\_hash, error\_type |
| `task.initialization` | Task initialization timing/metadata event | duration\_ms, mode |

### [​](#ai-output-feedback) AI Output Feedback

| Event | Description | Key Attributes |
| --- | --- | --- |
| `task.ai_output.accepted` | AI-generated file edit accepted | lines\_added, lines\_removed, file\_count |
| `task.ai_output.rejected` | AI-generated file edit rejected | lines\_added, lines\_removed, file\_count |

### [​](#example-task-tool_used) Example: task.tool\_used

```
{
  "event": "task.tool_used",
  "timestamp": "2026-03-05T10:35:22Z",
  "attributes": {
    "task_id": "task_1234567890",
    "tool_name": "write_to_file",
    "success": true,
    "duration_ms": 125,
    "auto_approved": false,
    "model": "claude-sonnet-4",
    "provider": "anthropic"
  }
}
```

## [​](#ui-events) UI Events

Events tracking user interface interactions.

| Event | Description | Key Attributes |
| --- | --- | --- |
| `ui.model_selected` | Model selected in UI | model, provider, previous\_model |
| `ui.model_favorite_toggled` | Model favorite toggled | model\_id, is\_favorited |
| `ui.button_clicked` | UI button click event | button\_id, context |
| `ui.rules_menu_opened` | Rules/skills menu/modal opened | menu\_type |

### [​](#example-ui-model_selected) Example: ui.model\_selected

```
{
  "event": "ui.model_selected",
  "timestamp": "2026-03-05T11:20:00Z",
  "attributes": {
    "model": "claude-sonnet-4",
    "provider": "anthropic",
    "previous_model": "gpt-4o",
    "mode": "act"
  }
}
```

## [​](#hooks-events) Hooks Events

Events related to hook discovery, execution lifecycle, and context modifications.

| Event | Description | Key Attributes |
| --- | --- | --- |
| `hooks.enabled` | Hooks feature enabled | user\_id |
| `hooks.disabled` | Hooks feature disabled | user\_id |
| `hooks.cancel_requested` | Hook requested cancellation | hook\_name, task\_id |
| `hooks.context_modified` | Hook modified context | hook\_name, modification\_type |
| `hooks.discovery_completed` | Hook discovery completed | hooks\_count, global\_count, workspace\_count |
| `hooks.execution` | Unified hook execution lifecycle | hook\_name, status (started/completed/failed/cancelled), duration\_ms |

### [​](#hook-execution-lifecycle) Hook Execution Lifecycle

The `hooks.execution` event tracks the complete lifecycle with a `status` attribute:

- **started**: Hook execution began
- **completed**: Hook finished successfully
- **failed**: Hook encountered an error
- **cancelled**: Hook was cancelled by user or system

### [​](#example-hooks-execution) Example: hooks.execution

```
{
  "event": "hooks.execution",
  "timestamp": "2026-03-05T10:40:15Z",
  "attributes": {
    "hook_name": "preToolUse",
    "status": "completed",
    "duration_ms": 234,
    "task_id": "task_1234567890",
    "context_modified": false
  }
}
```

## [​](#worktree-events) Worktree Events

Events related to Git worktree operations.

| Event | Description | Key Attributes |
| --- | --- | --- |
| `worktree.view_opened` | Worktree view opened | user\_id |
| `worktree.created` | Worktree create event | success, branch\_name, duration\_ms |
| `worktree.merge_attempted` | Worktree merge attempt event | has\_conflicts, delete\_option\_chosen |

### [​](#example-worktree-created) Example: worktree.created

```
{
  "event": "worktree.created",
  "timestamp": "2026-03-05T14:22:00Z",
  "attributes": {
    "success": true,
    "branch_name_hash": "abc123",
    "duration_ms": 1250,
    "parent_branch": "main"
  }
}
```

## [​](#host-events) Host Events

Events related to host environment detection.

| Event | Description | Key Attributes |
| --- | --- | --- |
| `host.detected` | Host environment detection event | host\_type (vscode/jetbrains/cli), version |

### [​](#example-host-detected) Example: host.detected

```
{
  "event": "host.detected",
  "timestamp": "2026-03-05T09:00:00Z",
  "attributes": {
    "host_type": "vscode",
    "version": "1.95.0",
    "platform": "darwin"
  }
}
```

## [​](#test-events) Test Events

Diagnostic and connection testing events.

| Event | Description | Key Attributes |
| --- | --- | --- |
| `cline.test.connection` | OTEL connection test event from “Test OTEL Connection” flow | success, exporter\_type, endpoint |

### [​](#example-cline-test-connection) Example: cline.test.connection

```
{
  "event": "cline.test.connection",
  "timestamp": "2026-03-05T15:30:00Z",
  "attributes": {
    "success": true,
    "exporter_type": "otlp",
    "endpoint": "https://api.datadoghq.com:4317",
    "protocol": "grpc"
  }
}
```

## [​](#event-attribute-guidelines) Event Attribute Guidelines

### [​](#common-attributes) Common Attributes

Most events include these standard attributes:

| Attribute | Type | Description |
| --- | --- | --- |
| `timestamp` | ISO 8601 | Event occurrence time |
| `user_id` | string | Anonymized user identifier (when authenticated) |
| `session_id` | string | Current session identifier |
| `extension_version` | string | Cline extension version |
| `host_type` | string | vscode, jetbrains, or cli |

### [​](#privacy-&-hashing) Privacy & Hashing

Sensitive information is hashed or anonymized:

- **File paths**: Hashed to preserve privacy
- **Command content**: Hashed, not logged verbatim
- **User identifiers**: Anonymized tokens
- **Branch names**: Hashed in worktree events

File paths, command arguments, and code content are **never** included in raw form. Only hashes or anonymized identifiers are used.

## [​](#task-event-deep-dive) Task Event Deep Dive

Task events are the most detailed category. Here’s a typical task execution flow:


### [​](#task-token-tracking) Task Token Tracking

Token events provide detailed cost and usage information:

```
{
  "event": "task.tokens",
  "timestamp": "2026-03-05T10:35:30Z",
  "attributes": {
    "task_id": "task_1234567890",
    "tokens_in": 2500,
    "tokens_out": 850,
    "cached_tokens": 1200,
    "cost": 0.0043,
    "model": "claude-sonnet-4",
    "provider": "anthropic"
  }
}
```

## [​](#using-events-for-analytics) Using Events for Analytics

**SQL syntax is illustrative only.** Attribute access varies by observability platform — for example, `JSON_EXTRACT(attributes, '$.model')` in BigQuery, `attributes['model']` in ClickHouse, or `@attributes.model` in Datadog. Adapt all queries below to your platform’s query language before use.

### [​](#query-patterns) Query Patterns

**Most used tools:**

```
SELECT attributes.tool_name, COUNT(*) as count
FROM otel_logs
WHERE event = 'task.tool_used'
  AND attributes.success = true
GROUP BY attributes.tool_name
ORDER BY count DESC
LIMIT 10
```

**Average task duration by model:**

```
SELECT
  attributes.model,
  AVG(attributes.duration_ms) as avg_duration_ms,
  COUNT(*) as task_count
FROM otel_logs
WHERE event = 'task.completed'
GROUP BY attributes.model
```

**Token usage by provider:**

```
SELECT
  attributes.provider,
  SUM(attributes.tokens_in) as total_tokens_in,
  SUM(attributes.tokens_out) as total_tokens_out,
  SUM(attributes.cost) as total_cost
FROM otel_logs
WHERE event = 'task.tokens'
  AND timestamp >= NOW() - INTERVAL '30 days'
GROUP BY attributes.provider
```

**Tool approval rates:**

```
SELECT
  attributes.tool_name,
  SUM(CASE WHEN attributes.auto_approved THEN 1 ELSE 0 END)::float / COUNT(*) as auto_approval_rate,
  COUNT(*) as total_uses
FROM otel_logs
WHERE event = 'task.tool_used'
GROUP BY attributes.tool_name
ORDER BY total_uses DESC
```

## [​](#integration-examples) Integration Examples

Query syntax below is illustrative. Attribute access varies by platform — for example, `JSON_EXTRACT(attributes, '$.model')` in BigQuery, `attributes['model']` in ClickHouse, or dot notation in Datadog. Adapt to your platform’s query language.

### [​](#datadog-dashboard) Datadog Dashboard

Create custom Datadog dashboards using these events:

```
{
  "widgets": [
    {
      "definition": {
        "type": "timeseries",
        "requests": [
          {
            "q": "sum:cline.task.completed{*}.as_count()",
            "display_type": "bars"
          }
        ],
        "title": "Tasks Completed Over Time"
      }
    },
    {
      "definition": {
        "type": "query_value",
        "requests": [
          {
            "q": "sum:cline.task.tokens{*}",
            "aggregator": "sum"
          }
        ],
        "title": "Total Tokens Used"
      }
    }
  ]
}
```

### [​](#grafana-queries) Grafana Queries

Example Loki query for tool usage:

```
{event="task.tool_used"}
| json
| line_format "{{.attributes_tool_name}}: {{.attributes_success}}"
```

### [​](#new-relic-nrql) New Relic NRQL

Query task completion rates:

```
SELECT count(*)
FROM Log
WHERE event = 'task.completed'
FACET attributes.model
SINCE 1 day ago
```

## [​](#event-schema-reference) Event Schema Reference

All events follow this structure:

```
interface OtelLogEvent {
  event: string              // Event name (e.g., "task.created")
  timestamp: string           // ISO 8601 timestamp
  attributes: {
    // Event-specific attributes
    [key: string]: string | number | boolean
  }
  resource: {
    service_name: "cline"
    service_version: string   // Extension version
    host_type: string         // vscode | jetbrains | cli
  }
}
```

## [​](#best-practices) Best Practices

## Filter Noise

Focus on events relevant to your use case. Not all events need dashboards.

## Set Alerts

Alert on error events and usage anomalies for proactive monitoring.

## Aggregate Metrics

Roll up events into metrics for long-term trend analysis.

## Respect Privacy

Remember events are already anonymized. Don’t attempt to de-anonymize.

## [​](#troubleshooting) Troubleshooting

### [​](#events-not-appearing) Events Not Appearing

If events aren’t showing up in your observability platform:

1. **Verify OTel is enabled** in remote configuration or environment variables
2. **Check endpoint configuration** - ensure URL and protocol are correct
3. **Validate credentials** - test with the “Test OTEL Connection” button
4. **Check exporter settings** - ensure logs exporter includes `otlp`
5. **Review platform-specific requirements** - some platforms need specific headers

### [​](#event-volume-concerns) Event Volume Concerns

If you’re seeing excessive event volume:

1. **Sample events** - Configure sampling in your OTel collector
2. **Filter events** - Use your platform’s filtering to drop noisy events
3. **Aggregate on collection** - Pre-aggregate metrics before export
4. **Adjust export intervals** - Increase `openTelemetryMetricExportInterval` and batch settings

## [​](#see-also) See Also

## OpenTelemetry Setup

Configure OTel integration

## Prompt Storage

Backup conversation history

## Telemetry

Basic telemetry overview

Was this page helpful?

YesNo

[OpenTelemetry](/enterprise-solutions/monitoring/opentelemetry)[OpenTelemetry Override](/enterprise-solutions/monitoring/opentelemetry_override)

⌘I

---

## Opentelemetry Override

*Source: [https://docs.cline.bot/enterprise-solutions/monitoring/opentelemetry_override](https://docs.cline.bot/enterprise-solutions/monitoring/opentelemetry_override)*

This is an **advanced configuration method**. Most users should use [Remote Configuration](/enterprise-solutions/monitoring/opentelemetry) via the dashboard instead.

Environment variables provide an alternative way to configure OpenTelemetry, useful for self-hosted deployments, local development, CI/CD pipelines, or when you need to override organization settings.

## [​](#when-to-use) When to Use

- **Self-hosted deployments** without dashboard access
- **Local development and testing** with your own collectors
- **CI/CD pipelines** that need observability
- **Override organization settings** with user-specific configuration

Environment variable configuration bypasses user telemetry settings and will export data regardless of individual preferences.

## [​](#environment-variables) Environment Variables

### [​](#core-configuration) Core Configuration

| Variable | Description | Values |
| --- | --- | --- |
| `CLINE_OTEL_TELEMETRY_ENABLED` | Enable OpenTelemetry export | `"true"` or `"false"` |
| `CLINE_OTEL_METRICS_EXPORTER` | Metrics exporters (comma-separated) | `"console"`, `"otlp"` |
| `CLINE_OTEL_LOGS_EXPORTER` | Logs exporters (comma-separated) | `"console"`, `"otlp"` |

### [​](#otlp-configuration) OTLP Configuration

| Variable | Description | Values |
| --- | --- | --- |
| `CLINE_OTEL_EXPORTER_OTLP_PROTOCOL` | OTLP protocol | `"grpc"`, `"http/json"`, or `"http/protobuf"` |
| `CLINE_OTEL_EXPORTER_OTLP_ENDPOINT` | OTLP collector endpoint (applies to both metrics and logs) | URL with optional port |
| `CLINE_OTEL_EXPORTER_OTLP_HEADERS` | Authentication headers (comma-separated `key=value` pairs) | `"key=value,key2=value2"` |
| `CLINE_OTEL_EXPORTER_OTLP_INSECURE` | Disable TLS for gRPC (local development only) | `"true"` |

### [​](#advanced-otlp-configuration) Advanced OTLP Configuration

For separate metrics and logs endpoints:

| Variable | Description |
| --- | --- |
| `CLINE_OTEL_EXPORTER_OTLP_METRICS_PROTOCOL` | Metrics-specific protocol override |
| `CLINE_OTEL_EXPORTER_OTLP_METRICS_ENDPOINT` | Metrics-specific endpoint |
| `CLINE_OTEL_EXPORTER_OTLP_LOGS_PROTOCOL` | Logs-specific protocol override |
| `CLINE_OTEL_EXPORTER_OTLP_LOGS_ENDPOINT` | Logs-specific endpoint |

### [​](#export-tuning) Export Tuning

| Variable | Description | Default |
| --- | --- | --- |
| `CLINE_OTEL_METRIC_EXPORT_INTERVAL` | Milliseconds between metric exports | 60000 |
| `CLINE_OTEL_LOG_BATCH_SIZE` | Maximum batch size for log records | 512 |
| `CLINE_OTEL_LOG_BATCH_TIMEOUT` | Maximum time before exporting logs (ms) | 5000 |
| `CLINE_OTEL_LOG_MAX_QUEUE_SIZE` | Maximum queue size for log records | 2048 |

## [​](#quick-start-examples) Quick Start Examples

### [​](#datadog-with-grpc) Datadog with gRPC

```
export CLINE_OTEL_TELEMETRY_ENABLED=true
export CLINE_OTEL_METRICS_EXPORTER=otlp
export CLINE_OTEL_LOGS_EXPORTER=otlp
export CLINE_OTEL_EXPORTER_OTLP_PROTOCOL=grpc
export CLINE_OTEL_EXPORTER_OTLP_ENDPOINT=https://api.datadoghq.com:4317
export CLINE_OTEL_EXPORTER_OTLP_HEADERS="dd-api-key=YOUR_API_KEY"

code .
```

The endpoint shown above is for Datadog’s **US1 region**. If you’re in a different region (EU, US3, US5, AP1, etc.), replace `api.datadoghq.com` with your region-specific hostname (e.g., `api.datadoghq.eu` for EU). See [Datadog’s OTLP documentation](https://docs.datadoghq.com/opentelemetry/) for your region’s endpoint.

### [​](#new-relic-with-http) New Relic with HTTP

```
export CLINE_OTEL_TELEMETRY_ENABLED=true
export CLINE_OTEL_METRICS_EXPORTER=otlp
export CLINE_OTEL_LOGS_EXPORTER=otlp
export CLINE_OTEL_EXPORTER_OTLP_PROTOCOL=http/protobuf
export CLINE_OTEL_EXPORTER_OTLP_ENDPOINT=https://otlp.nr-data.net:4318
export CLINE_OTEL_EXPORTER_OTLP_HEADERS="api-key=YOUR_LICENSE_KEY"

code .
```

### [​](#local-development-insecure) Local Development (Insecure)

```
export CLINE_OTEL_TELEMETRY_ENABLED=true
export CLINE_OTEL_METRICS_EXPORTER=otlp
export CLINE_OTEL_LOGS_EXPORTER=otlp
export CLINE_OTEL_EXPORTER_OTLP_PROTOCOL=grpc
export CLINE_OTEL_EXPORTER_OTLP_ENDPOINT=http://localhost:4317
export CLINE_OTEL_EXPORTER_OTLP_INSECURE=true

code .
```

### [​](#console-output-testing) Console Output (Testing)

```
export CLINE_OTEL_TELEMETRY_ENABLED=true
export CLINE_OTEL_METRICS_EXPORTER=console
export CLINE_OTEL_LOGS_EXPORTER=console

code .
```

## [​](#debugging) Debugging

Enable detailed OpenTelemetry diagnostic logging:

```
export TEL_DEBUG_DIAGNOSTICS=true
code .
```

This outputs:

- Configuration being used
- Exporters being created
- Connection attempts
- Export successes/failures

Check the VS Code Developer Tools Console (Help > Toggle Developer Tools) for diagnostic output.

## [​](#configuration-priority) Configuration Priority

When multiple configuration methods are present, Cline uses this priority order:

1. **Environment variables** (highest priority) - This method
2. **Remote Configuration** - Dashboard settings
3. **Default settings** - Built-in defaults

Environment variable configuration will override dashboard settings.

## [​](#see-also) See Also

## Dashboard Configuration

Configure OpenTelemetry via the web dashboard

## Remote Configuration

Learn about Remote Configuration system

Was this page helpful?

YesNo

[OTel Events](/enterprise-solutions/monitoring/opentelemetry-events)[API Reference](/enterprise-solutions/api-reference)

⌘I

---

## Overview

*Source: [https://docs.cline.bot/enterprise-solutions/monitoring/overview](https://docs.cline.bot/enterprise-solutions/monitoring/overview)*

Cline includes optional monitoring capabilities for organizations that want to track usage and integrate with their observability infrastructure.

## [​](#monitoring-options) Monitoring Options

## Cline Telemetry

Built-in anonymous usage tracking that helps improve Cline (opt-in)

## Prompt Storage

Backup conversation history to S3/R2 for compliance and analysis

## OpenTelemetry

Export metrics and logs to your own observability backends

## OpenTelemetry Override

Export to your own observability backends through environment variables (advanced)

## [​](#cline-telemetry) Cline Telemetry

Cline includes opt-in telemetry for anonymous usage tracking:

- Feature usage patterns
- Task completion rates
- Error occurrences
- Performance metrics

Users can enable or disable telemetry in Cline settings. All data is anonymous and does not include code content, file paths, or sensitive information.
See [Cline Telemetry](/enterprise-solutions/monitoring/telemetry) for configuration details.

## [​](#opentelemetry-integration) OpenTelemetry Integration

For advanced monitoring needs, Cline supports OpenTelemetry’s OTLP (OpenTelemetry Protocol) for exporting metrics and logs to your own infrastructure.
This allows you to:

- Export telemetry to your existing observability platforms
- Integrate with tools like Datadog, New Relic, or Grafana Cloud
- Maintain full control over your monitoring data
- Aggregate metrics across your organization

OpenTelemetry integration is **optional** and requires additional configuration. Most users don’t need this feature.

See [OpenTelemetry](/enterprise-solutions/monitoring/opentelemetry) for setup instructions.

## [​](#use-cases) Use Cases

### [​](#when-to-use-cline-telemetry) When to Use Cline Telemetry

- You want to help improve Cline through anonymous usage data
- No additional setup required
- Suitable for most users

### [​](#when-to-use-opentelemetry) When to Use OpenTelemetry

- You need granular metrics in your own systems
- You’re integrating with existing observability infrastructure
- You want detailed logs and metrics for debugging
- You need custom dashboards or alerting

## [​](#getting-started) Getting Started

1

Choose Your Approach

Decide whether basic telemetry or OpenTelemetry integration fits your needs

2

Enable Telemetry

For basic telemetry, enable it in Cline settings. For OpenTelemetry, see the configuration guide.

3

Verify Data Collection

Confirm telemetry is being collected as expected

## [​](#privacy-&-security) Privacy & Security

All Cline monitoring features are designed with privacy in mind:

## Anonymous

No personal information collected

## Optional

Users can disable at any time

## Local First

Code never leaves your machine

## Transparent

Open source - see what’s collected

## [​](#next-steps) Next Steps

## Configure Telemetry

Set up basic telemetry settings

## OpenTelemetry Setup

Advanced monitoring with OpenTelemetry

Was this page helpful?

YesNo

[MCP Marketplace](/enterprise-solutions/configuration/infrastructure-configuration/control-other-cline-features/mcp-marketplace)[Cline Telemetry](/enterprise-solutions/monitoring/telemetry)

⌘I

---

## Prompt Storage

*Source: [https://docs.cline.bot/enterprise-solutions/monitoring/prompt-storage](https://docs.cline.bot/enterprise-solutions/monitoring/prompt-storage)*

Prompt Storage allows enterprises to automatically back up Cline conversation history to cloud storage (AWS S3 or Cloudflare R2). This provides a centralized repository for compliance, audit trails, and usage analysis while maintaining local storage as the primary source of truth.

## [​](#overview) Overview

Every Cline task conversation is stored locally in `~/.cline/data/tasks/<taskId>/api_conversation_history.json`. When prompt storage is enabled, a background sync worker automatically uploads these conversation files to your configured S3 or R2 bucket.

## Compliance Ready

Maintain conversation records for regulatory requirements and internal policies.

## Audit Trail

Track AI interactions across your organization with timestamped conversation logs.

## Usage Analysis

Analyze conversation patterns, token usage, and model performance at scale.

## Disaster Recovery

Backup conversation history independent of local storage for business continuity.

## [​](#how-it-works) How It Works

1. **Local Storage First**: All conversations are written to local disk immediately
2. **Background Sync**: A worker process queues conversation files for upload
3. **Reliable Upload**: Automatic retry logic with configurable batch sizes
4. **Cloud Backup**: Files are stored in your S3/R2 bucket with the same path structure

## [​](#storage-architecture) Storage Architecture

### [​](#what-gets-stored) What Gets Stored

Prompt storage uploads the following files from each task:

| File | Content | Purpose |
| --- | --- | --- |
| `api_conversation_history.json` | Full conversation in Anthropic MessageParam format | Core conversation data for analysis |
| Task metadata | Task ID, timestamps, model info | Correlation and indexing |

### [​](#what’s-not-stored) What’s NOT Stored

Prompt storage **does not** include:

- ❌ Workspace files not accessed by Cline
- ❌ API keys or secrets
- ❌ User credentials or authentication tokens

Conversation history includes **all tool inputs and outputs**. This means code written via `write_to_file`, file contents read via `read_file`, and command outputs are included in the uploaded data. Review your compliance and data classification requirements before enabling.

### [​](#storage-path-pattern) Storage Path Pattern

Files are uploaded to your bucket following this structure:

```
s3://your-bucket/tasks/{taskId}/api_conversation_history.json
```

This mirrors the local storage structure, making it easy to correlate local and cloud data.

## [​](#configuration) Configuration

Prompt storage is configured through Remote Configuration in the `enterpriseTelemetry.promptUploading` section.

### [​](#schema) Schema

```
{
  "enterpriseTelemetry": {
    "promptUploading": {
      "enabled": true,
      "type": "s3_access_keys",
      "s3AccessSettings": {
        "bucket": "your-cline-prompts",
        "accessKeyId": "AKIAIOSFODNN7EXAMPLE",
        "secretAccessKey": "wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY",
        "region": "us-east-1",
        "intervalMs": 30000,
        "maxRetries": 5,
        "batchSize": 10,
        "maxQueueSize": 1000,
        "maxFailedAgeMs": 604800000,
        "backfillEnabled": false
      }
    }
  }
}
```

### [​](#configuration-fields) Configuration Fields

#### [​](#core-settings) Core Settings

| Field | Type | Required | Description |
| --- | --- | --- | --- |
| `enabled` | boolean | Yes | Enable/disable prompt storage |
| `type` | string | Yes | Storage type: `"s3_access_keys"` or `"r2_access_keys"` |

#### [​](#access-settings-s3/r2) Access Settings (S3/R2)

| Field | Type | Required | Description | Default |
| --- | --- | --- | --- | --- |
| `bucket` | string | Yes | S3/R2 bucket name | - |
| `accessKeyId` | string | Yes | AWS/Cloudflare access key ID | - |
| `secretAccessKey` | string | Yes | AWS/Cloudflare secret access key | - |
| `region` | string | S3 only | AWS region (e.g., `us-east-1`) | - |
| `endpoint` | string | R2 only | Cloudflare R2 endpoint URL | - |
| `accountId` | string | R2 only | Cloudflare account ID | - |

#### [​](#sync-worker-settings) Sync Worker Settings

| Field | Type | Description | Default |
| --- | --- | --- | --- |
| `intervalMs` | number | Milliseconds between sync attempts | 30000 (30s) |
| `maxRetries` | number | Maximum retries before giving up | 5 |
| `batchSize` | number | Items to process per interval | 10 |
| `maxQueueSize` | number | Maximum queue size before eviction | 1000 |
| `maxFailedAgeMs` | number | Time before discarding failed items | 604800000 (7 days) |
| `backfillEnabled` | boolean | Sync existing tasks on startup | false |

## [​](#setup-guides) Setup Guides

- AWS S3
- Cloudflare R2

### [​](#aws-s3-configuration) AWS S3 Configuration

1

Create S3 Bucket

Create a dedicated S3 bucket for Cline conversation storage:

```
aws s3 mb s3://your-cline-prompts --region us-east-1
```

Enable versioning and encryption:

```
aws s3api put-bucket-versioning \
  --bucket your-cline-prompts \
  --versioning-configuration Status=Enabled

aws s3api put-bucket-encryption \
  --bucket your-cline-prompts \
  --server-side-encryption-configuration '{
    "Rules": [{
      "ApplyServerSideEncryptionByDefault": {
        "SSEAlgorithm": "AES256"
      }
    }]
  }'
```

2

Create IAM Policy

Create an IAM policy with minimal required permissions:

```
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": [
        "s3:PutObject",
        "s3:PutObjectAcl",
        "s3:GetObject",
        "s3:DeleteObject"
      ],
      "Resource": "arn:aws:s3:::your-cline-prompts/*"
    },
    {
      "Effect": "Allow",
      "Action": [
        "s3:ListBucket"
      ],
      "Resource": "arn:aws:s3:::your-cline-prompts"
    }
  ]
}
```

Save this as `cline-prompt-storage-policy.json` and create the policy:

```
aws iam create-policy \
  --policy-name ClinePromptStorage \
  --policy-document file://cline-prompt-storage-policy.json
```

3

Create IAM User

Create a dedicated IAM user and attach the policy:

```
aws iam create-user --user-name cline-prompt-uploader

aws iam attach-user-policy \
  --user-name cline-prompt-uploader \
  --policy-arn arn:aws:iam::YOUR_ACCOUNT_ID:policy/ClinePromptStorage

aws iam create-access-key --user-name cline-prompt-uploader
```

Save the `AccessKeyId` and `SecretAccessKey` from the output.

4

Configure in Cline Dashboard

In the Cline admin console at [app.cline.bot](https://app.cline.bot):

1. Navigate to **Settings** → **Enterprise Telemetry**
2. Enable **Prompt Uploading**
3. Select **S3** as the storage type
4. Enter your bucket name, access key ID, secret key, and region
5. Configure sync worker settings (or use defaults)
6. Save configuration

5

Test Connection

Use the “Test Connection” button in the admin console to verify:

- Bucket access
- Write permissions
- Credential validity

A test file will be uploaded and deleted from your bucket.

### [​](#optional-lifecycle-policies) Optional: Lifecycle Policies

Configure retention policies for cost management:

```
{
  "Rules": [
    {
      "Id": "ArchiveOldPrompts",
      "Status": "Enabled",
      "Transitions": [
        {
          "Days": 90,
          "StorageClass": "GLACIER"
        }
      ]
    },
    {
      "Id": "DeleteOldPrompts",
      "Status": "Enabled",
      "Expiration": {
        "Days": 2555
      }
    }
  ]
}
```

### [​](#cloudflare-r2-configuration) Cloudflare R2 Configuration

1

Create R2 Bucket

1. Log in to the [Cloudflare Dashboard](https://dash.cloudflare.com)
2. Navigate to **R2** in the sidebar
3. Click **Create bucket**
4. Name your bucket (e.g., `cline-prompts`)
5. Select a location close to your users
6. Click **Create bucket**

2

Generate API Token

1. In the R2 dashboard, click **Manage R2 API Tokens**
2. Click **Create API token**
3. Configure permissions:
   - **Token name**: Cline Prompt Storage
   - **Permissions**: Object Read & Write
   - **Bucket**: Select your bucket or use All buckets
4. Click **Create API Token**
5. Save the **Access Key ID** and **Secret Access Key**
6. Note your **Account ID** (shown in the R2 overview)

3

Get R2 Endpoint

Your R2 endpoint follows this format:

```
https://<ACCOUNT_ID>.r2.cloudflarestorage.com
```

Find your account ID in the Cloudflare dashboard under R2 overview.

4

Configure in Cline Dashboard

In the Cline admin console at [app.cline.bot](https://app.cline.bot):

1. Navigate to **Settings** → **Enterprise Telemetry**
2. Enable **Prompt Uploading**
3. Select **R2** as the storage type
4. Enter:
   - Bucket name
   - Access key ID
   - Secret access key
   - Account ID
   - Endpoint URL
5. Configure sync worker settings (or use defaults)
6. Save configuration

5

Test Connection

Use the “Test Connection” button to verify:

- Bucket access with provided credentials
- Write permissions
- Endpoint connectivity

### [​](#cost-advantages) Cost Advantages

R2 offers significant cost advantages over S3:

- **No egress fees**: Download data at no cost
- **Lower storage costs**: ~0.015/GBvsS3′s 0.015/GB vs S3's ~0.015/GBvsS3′s 0.023/GB
- **Global edge access**: Fast access from anywhere

## [​](#sync-worker-behavior) Sync Worker Behavior

The background sync worker manages the upload queue with these characteristics:

### [​](#queue-management) Queue Management

- **FIFO ordering**: Files are uploaded in the order they were created
- **Automatic batching**: Processes up to `batchSize` items per interval
- **Queue size limits**: Evicts oldest items when `maxQueueSize` is exceeded
- **Retry logic**: Failed uploads are retried up to `maxRetries` times

### [​](#failure-handling) Failure Handling

When an upload fails:

1. **Immediate retry**: Item stays in queue for next sync interval
2. **Exponential backoff**: Retry attempts are spaced out
3. **Maximum retries**: After `maxRetries` attempts, item is marked as permanently failed
4. **Age-based cleanup**: Failed items older than `maxFailedAgeMs` are discarded
5. **No data loss**: Local files remain intact regardless of sync status

### [​](#backfill-mode) Backfill Mode

When `backfillEnabled` is set to `true`:

- On first startup, scans all existing tasks in `~/.cline/data/tasks/`
- Queues conversation files that haven’t been uploaded
- Useful for enabling prompt storage on an existing Cline deployment
- Can generate significant upload volume — monitor queue size

Enable backfill carefully on large deployments. Consider starting with `backfillEnabled: false` and monitoring the steady-state queue before enabling backfill.

## [​](#monitoring-&-observability) Monitoring & Observability

### [​](#integration-with-opentelemetry) Integration with OpenTelemetry

While prompt storage operates independently, it integrates with Cline’s observability system:

- **Task lifecycle events**: `task.created`, `task.completed` track when conversations are generated
- **Conversation events**: `task.conversation_turn`, `task.tokens` provide usage metrics
- **Local monitoring**: Sync worker status is logged but not yet exported as OTel events

See [OpenTelemetry](/enterprise-solutions/monitoring/opentelemetry) for configuring metrics export.

### [​](#cloudwatch-monitoring-s3) CloudWatch Monitoring (S3)

Monitor S3 upload activity with CloudWatch:

```
# View PutObject requests (uploads)
aws cloudwatch get-metric-statistics \
  --namespace AWS/S3 \
  --metric-name NumberOfObjects \
  --dimensions Name=BucketName,Value=your-cline-prompts \
  --start-time 2026-03-01T00:00:00Z \
  --end-time 2026-03-08T00:00:00Z \
  --period 3600 \
  --statistics Sum
```

### [​](#r2-analytics) R2 Analytics

Cloudflare R2 provides built-in analytics in the dashboard:

- Request counts and rates
- Storage usage over time
- Bandwidth utilization
- Error rates

## [​](#security-&-compliance) Security & Compliance

### [​](#encryption) Encryption

**At Rest:**

- S3: Enable server-side encryption (SSE-S3 or SSE-KMS)
- R2: Encryption enabled by default

**In Transit:**

- All uploads use HTTPS/TLS
- Credentials are never logged or exposed

### [​](#access-control) Access Control

**Recommended IAM policies:**

- Use dedicated IAM users/roles
- Limit permissions to write-only if read access isn’t needed
- Enable MFA for credential generation
- Rotate access keys regularly

**Bucket policies:**

```
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Deny",
      "Principal": "*",
      "Action": "s3:*",
      "Resource": [
        "arn:aws:s3:::your-cline-prompts/*",
        "arn:aws:s3:::your-cline-prompts"
      ],
      "Condition": {
        "Bool": {
          "aws:SecureTransport": "false"
        }
      }
    }
  ]
}
```

### [​](#audit-logging) Audit Logging

**S3 Server Access Logging:**

```
aws s3api put-bucket-logging \
  --bucket your-cline-prompts \
  --bucket-logging-status '{
    "LoggingEnabled": {
      "TargetBucket": "your-log-bucket",
      "TargetPrefix": "cline-prompts-access/"
    }
  }'
```

**CloudTrail for API Calls:**
Enable CloudTrail to track all S3 API operations on your bucket.

### [​](#data-retention) Data Retention

Implement retention policies based on your compliance requirements:

- **GDPR**: Consider right to erasure
- **SOC 2**: Maintain audit trails for required period
- **HIPAA**: Ensure appropriate retention and disposal

## [​](#troubleshooting) Troubleshooting

### [​](#common-issues) Common Issues

Queue size growing continuously

**Symptoms**: `maxQueueSize` limit reached, oldest items being evicted**Causes**:

- Upload rate slower than conversation creation rate
- Network connectivity issues
- Insufficient batch size or interval

**Solutions**:

1. Increase `batchSize` to process more items per interval
2. Decrease `intervalMs` to sync more frequently
3. Check network connectivity and credentials
4. Temporarily increase `maxQueueSize` while investigating

Uploads failing with 403 Forbidden

**Symptoms**: Repeated upload failures, items reaching `maxRetries`**Causes**:

- Invalid or expired credentials
- Insufficient IAM permissions
- Bucket policy denying access

**Solutions**:

1. Verify credentials are correct in remote config
2. Check IAM policy includes `s3:PutObject` permission
3. Review bucket policies for deny rules
4. Test with AWS CLI: `aws s3 cp test.txt s3://your-bucket/`

R2 endpoint connection timeout

**Symptoms**: Connection timeouts, failed uploads**Causes**:

- Incorrect endpoint URL
- Firewall blocking Cloudflare IPs
- Invalid account ID

**Solutions**:

1. Verify endpoint format: `https://<ACCOUNT_ID>.r2.cloudflarestorage.com`
2. Check firewall rules allow HTTPS to Cloudflare IPs
3. Confirm account ID in Cloudflare dashboard
4. Test with curl: `curl -I https://<ACCOUNT_ID>.r2.cloudflarestorage.com`

Backfill overwhelming upload queue

**Symptoms**: Queue at max size immediately after enabling backfill**Causes**:

- Large number of existing tasks
- Backfill queuing faster than upload processing

**Solutions**:

1. Disable backfill temporarily: `"backfillEnabled": false`
2. Let steady-state queue drain first
3. Increase `batchSize` and decrease `intervalMs`
4. Consider `maxQueueSize` increase during backfill period
5. Re-enable backfill once queue is stable

### [​](#debug-logging) Debug Logging

Enable debug logging to diagnose sync issues:

1. Check extension developer console (Help → Toggle Developer Tools)
2. Look for `[ClineBlobStorage]` and `[SyncWorker]` log entries
3. Failed uploads log error messages with details

### [​](#testing-configuration) Testing Configuration

Use the built-in test connection feature:

```
// Programmatic test (for custom integrations)
import { testPromptUploading } from '@/core/controller/state/testPromptUploading'

await testPromptUploading(controller)
// Returns: { success: boolean, message: string }
```

## [​](#data-format-reference) Data Format Reference

### [​](#conversation-file-schema) Conversation File Schema

Uploaded `api_conversation_history.json` files contain an array of messages:

```
[
  {
    "role": "user",
    "content": [
      {
        "type": "text",
        "text": "Create a React component for a todo list"
      }
    ]
  },
  {
    "role": "assistant",
    "content": [
      {
        "type": "text",
        "text": "I'll create a todo list component..."
      },
      {
        "type": "tool_use",
        "id": "toolu_123",
        "name": "write_to_file",
        "input": {
          "path": "TodoList.tsx",
          "content": "..."
        }
      }
    ]
  }
]
```

This follows the [Anthropic Messages API format](https://docs.anthropic.com/claude/reference/messages_post).

### [​](#metadata-schema) Metadata Schema

Task metadata includes:

```
{
  "taskId": "1234567890",
  "createdAt": "2026-03-05T10:30:00Z",
  "lastModified": "2026-03-05T11:45:00Z",
  "modelInfo": {
    "id": "claude-sonnet-4",
    "provider": "anthropic"
  },
  "tokensUsed": {
    "input": 1250,
    "output": 3400
  }
}
```

## [​](#best-practices) Best Practices

## Start Small

Test with a single team or project before rolling out organization-wide.

## Monitor Costs

Set up billing alerts and review storage usage monthly.

## Secure Credentials

Use dedicated IAM users with minimal permissions and rotate keys regularly.

## Plan Retention

Define and implement data retention policies based on compliance needs.

## [​](#see-also) See Also

## OpenTelemetry

Configure metrics and logs export for comprehensive observability

## Telemetry

Learn about Cline’s built-in anonymous usage tracking

## Remote Configuration

Understand the remote configuration system

Was this page helpful?

YesNo

[Cline Telemetry](/enterprise-solutions/monitoring/telemetry)[OpenTelemetry](/enterprise-solutions/monitoring/opentelemetry)

⌘I

---

## Telemetry

*Source: [https://docs.cline.bot/enterprise-solutions/monitoring/telemetry](https://docs.cline.bot/enterprise-solutions/monitoring/telemetry)*

Cline includes telemetry to help understand usage patterns and improve the product. Users can control whether to share this data.

## [​](#what-is-cline-telemetry) What is Cline Telemetry?

Telemetry captures anonymous usage events such as:

- Features used (which tools and commands)
- Task completion rates
- Error occurrences
- Performance metrics

All telemetry data is **anonymous** and does not include code content, file contents, or other sensitive information.

## [​](#user-controls) User Controls

### [​](#enabling/disabling-cline-telemetry) Enabling/Disabling Cline Telemetry

Individual users can control telemetry through Cline settings:

1. Open Cline settings
2. Find “Cline Telemetry” toggle
3. Enable or disable as preferred

Changes take effect immediately.

### [​](#what-gets-collected) What Gets Collected

When telemetry is enabled, Cline captures:

Feature Usage

- Tools executed (e.g., read\_file, execute\_command)
- Slash commands used
- Skills triggered
- Settings changed

Task Metrics

- Task started/completed events
- Mode switches (Plan/Act)
- Checkpoint usage
- Task duration

Error Events

- API failures
- Tool execution errors
- System errors
- Error types and frequencies

### [​](#what-doesn’t-get-collected) What Doesn’t Get Collected

Cline Telemetry **never** includes:

- Your code or file contents
- File paths or names
- Command arguments or parameters
- Conversation content
- Personal information
- API keys or credentials

## [​](#enterprise-configuration) Enterprise Configuration

Administrators can set default telemetry state through remote configuration:

```
{
  "telemetryEnabled": true
}
```

Even with enterprise configuration, individual users can still disable Cline Telemetry in their local settings.

## [​](#enterprise-monitoring-features) Enterprise Monitoring Features

For organizations with additional compliance or monitoring requirements, Cline provides:

### [​](#prompt-storage) Prompt Storage

Automatically backup conversation history to AWS S3 or Cloudflare R2 for:

- Compliance and audit trails
- Usage analysis and reporting
- Disaster recovery

See [Prompt Storage](/enterprise-solutions/monitoring/prompt-storage) for configuration details.

### [​](#opentelemetry-integration) OpenTelemetry Integration

Export detailed metrics and logs to your own observability platforms like Datadog, New Relic, or Grafana Cloud.
See [OpenTelemetry](/enterprise-solutions/monitoring/opentelemetry) for setup instructions.

## [​](#privacy) Privacy

Cline’s telemetry is designed with privacy in mind:

## Anonymous

No personal information is collected

## Optional

Users can disable at any time

## Local First

Code never leaves your machine

## Transparent

Open source - see exactly what’s collected

## [​](#why-telemetry-matters) Why Telemetry Matters

Anonymous usage data helps:

- **Identify bugs**: Discover issues affecting users
- **Prioritize features**: Focus on most-used capabilities
- **Improve performance**: Find and fix slow operations
- **Enhance reliability**: Track and reduce error rates

## [​](#related) Related

## OpenTelemetry

Enterprise monitoring and observability

## Event Details

See what data is collected

Was this page helpful?

YesNo

[Overview](/enterprise-solutions/monitoring/overview)[Prompt Storage](/enterprise-solutions/monitoring/prompt-storage)

⌘I

---

## Onboarding

*Source: [https://docs.cline.bot/enterprise-solutions/onboarding](https://docs.cline.bot/enterprise-solutions/onboarding)*

## [​](#overview) Overview

Cline Enterprise integrates with your existing identity provider (IdP) via WorkOS to deliver secure SSO and zero-touch user lifecycle management. In this guide, you’ll connect your IdP (Okta, Azure AD, Google Workspace, or any SAML/OIDC provider), enable just-in-time (JIT) provisioning so new users are created automatically on first sign-in, and configure role mapping so permissions stay aligned with your directory-no manual invites or seat reconciliations required.

## [​](#prerequisites) Prerequisites

- [Cline Enterprise License](https://cline.bot/contact-sales)
- Access to your identity provider (IdP) configuration (e.g., Okta, Azure AD, Google Workspace)
- Knowledge of your organization’s SSO requirements

## [​](#configuration-steps) Configuration Steps

### [​](#step-1-onboard-to-cline-enterprise-license) Step 1: Onboard to Cline Enterprise license

Your IdP administrator will receive an email with a link to register their organization with WorkOS during onboarding.

### [​](#step-2-configure-your-identity-provider) Step 2: Configure Your Identity Provider

For a short overview of where SSO configuration lives (Cline dashboard vs WorkOS vs your IdP), see [SSO Setup](/enterprise-solutions/sso-setup).

Connect your identity provider (IdP) to WorkOS:

1. In the WorkOS dashboard, go to **AuthKit → Connections**
2. Click **Add Connection**
3. Select your identity provider (e.g., Okta, Azure AD, Google Workspace, Generic SAML/OIDC)
4. Follow the provider-specific setup instructions

Each identity provider (IdP) will have its own setup process and required fields. Be sure to follow the specific instructions in the WorkOS dashboard for your chosen provider.
For more explicit instruction on connecting your IdP, refer to the [WorkOS SSO documentation](https://workos.com/docs/authkit/sso)

### [​](#step-3-configure-user-provisioning) Step 3: Configure User Provisioning

Cline Enterprise uses **just-in-time provisioning** that works automatically:

- **Organizations are created automatically**
- **Users gain access automatically** on their first SSO sign-in, once their credentials have been configured by the IdP administrator.
- **Roles sync automatically** from your IdP (Admin/Owner → Admin, Member → Member)
- **No manual user invites or seat management** required

No additional configuration is needed. Users are provisioned automatically when they sign in through SSO.

### [​](#step-4-configure-user-attributes-mapping) Step 4: Configure User Attributes Mapping

User roles are mapped automatically from your IdP:

- **Admin** in IdP → **Admin** role in Cline (Note: The first Owner of the org is created manually during onboarding)
- **Member** in IdP → **Member** role in Cline

For what each role can access, see the [Roles and Permissions](/enterprise-solutions/team-management/managing-members) page.

If needed, you can configure additional user attributes in the Cline Admin console:

1. Go to **Settings → Authentication → User Attributes**
2. Map attributes such as email and name based on your IdP configuration

For information about available user attributes, see the [WorkOS User Object Documentation](https://workos.com/docs/authkit/user-management).

### [​](#step-5-test-sso-connection) Step 5: Test SSO Connection

Before allowing users to sign in, test the SSO flow to ensure everything is configured correctly.
**To test the connection:**

1. In the WorkOS dashboard (or Cline Admin console if available), locate and click **Test SSO Connection**
2. You’ll be redirected to your IdP’s login page
3. Enter valid credentials for a test user
4. After successful authentication, you should be redirected back
5. Confirm that the user’s information (name, email, role) displays correctly

**Expected outcome:** The test user is authenticated, their account details are visible, and their role matches what’s configured in your IdP.
**If the test fails:** Double-check your IdP configuration (redirect URIs, SAML certificates, attribute mappings). See the [WorkOS SSO documentation](https://workos.com/docs/authkit/sso) for troubleshooting guidance.

### [​](#user-access) User Access

Once SSO is configured, users in your IdP can access Cline automatically without manual invites or account setup.
**First-time sign-in flow:**

1. User navigates to Cline and clicks **Sign in with SSO**
2. User authenticates via your organization’s IdP
3. Cline automatically creates their account in your Organization
4. Role is assigned based on their IdP role (see [Step 4](#step-4-configure-user-attributes-mapping))
5. User is redirected to Cline and can begin working

**What happens automatically:**

- Account creation with correct organization assignment
- Role and permission assignment
- Basic profile information (name, email) populated from IdP

**No action required:** Users don’t need to request access or wait for approval. Access is granted immediately upon successful IdP authentication.

### [​](#managing-access) Managing Access

All access management and revocation of users is currently handled by your IdP:

- Add users → access granted automatically on first login
- Change roles → updated on next login
- Remove users → access revoked automatically

Role changes sync automatically on the user’s next sign-in.

### [​](#changing-your-idp) Changing your IdP

In order to change to a different IdP, please contact support and we will guide you through this process.


---

## [​](#verification) Verification

Steps to verify successful configuration:

1. **Test User Sign-In**: Have a test user sign in through the SSO flow (access is granted automatically on first login)
2. **Verify User Provisioning**: Confirm that the user is automatically created and has appropriate role permissions
3. **Check User Attributes**: Verify that user information (name, email, organization) is correctly populated
4. **Test Role Changes**: Update a user’s role in your IdP and verify it syncs on their next login
5. **Test User Deprovisioning**: Remove a user from your IdP and verify they lose access to Cline on their next login attempt
6. **Review Audit Logs**: Check WorkOS audit logs to ensure authentication events are being recorded

---

Was this page helpful?

YesNo

[Overview](/enterprise-solutions/overview)[SSO Setup](/enterprise-solutions/sso-setup)

⌘I

---

## Overview

*Source: [https://docs.cline.bot/enterprise-solutions/overview](https://docs.cline.bot/enterprise-solutions/overview)*

Cline Enterprise brings centralized governance to the same open-source architecture that millions of developers already use. Your code stays in your environment, you use your own inference at your negotiated rates, and you get the security and observability capabilities that platform teams need for org-wide deployment.

## Learn More About Enterprise

Visit our website for detailed information about enterprise features, pricing, and deployment options.

## [​](#what-you-get) What You Get

It delivers five core capabilities that platform teams need for production deployment. Each addresses a specific requirement for scaling AI coding across your organization.

### [​](#security-by-design) Security by Design

Your code never leaves your environment. Cline processes everything locally - no uploads, no indexing, no training on your data.

## Client-side execution

All processing happens within your environment

## No data exfiltration

Code and context never transmitted externally

## No codebase indexing

Repositories are never indexed or cached

## No model training

Your code and prompts aren’t used for training

### [​](#bring-your-own-inference) Bring Your Own Inference

Use your existing cloud contracts and negotiated rates. Most AI tools force you to buy inference through them with markup. Cline connects directly to your providers.
Connect to any inference provider:

- AWS Bedrock
- Google Vertex AI
- Azure OpenAI
- Anthropic direct
- OpenAI direct
- Cerebras
- Any OpenAI-compatible endpoint

Switch models instantly as new ones release. Use Claude Sonnet 4.5 as your daily driver, GPT-5 for complex refactoring, open-source models for simple tasks. Your existing cloud credits and startup program contracts now cover AI coding. We handle the agent loop. You handle the inference. No markup, no vendor lock-in.

### [​](#governance-at-scale) Governance at Scale

Platform teams need central control when thousands of developers use AI. Individual API keys scattered across laptops create security risks and cost overruns.
Enterprise governance provides:

- **SSO authentication**: Corporate credentials instead of personal API keys
- **Role-based access control**: Three-tier hierarchy (Member/Admin/Owner) with organization-scoped permissions
- **Model and tool controls**: Govern which models and tools each team accesses
- **Remote configuration**: Manage settings for all developers from one dashboard
- **Usage tracking and observability**: OpenTelemetry integration for monitoring usage, costs, and performance with selective audit logging for administrative operations

Configure once, deploy everywhere. Developers work how they prefer while you maintain control.

### [​](#complete-observability) Complete Observability

Export logs to your existing observability stack. Track usage, costs, and performance across all teams.

- **OpenTelemetry export**: Direct integration with Datadog, Grafana, Splunk
- **Real-time analytics**: Track adoption, performance, and patterns
- **Cost breakdown**: See exactly what each team spends on which models
- **JSON output**: Build custom dashboards in your existing tools

The same observability standards you require for production systems.

## [​](#deployment) Deployment

Cline Enterprise connects securely to your infrastructure. Deploy in cloud environments. Configure to work with your existing security policies and compliance requirements.
Rolling out to your organization:

1. Configure Cline Core to connect to your infrastructure
2. Set SSO, RBAC, and governance policies
3. Deploy to developers via your existing software distribution
4. Monitor usage through your observability tools

## [​](#next-steps) Next Steps

- Review security architecture
- Configure [cloud provider setup](/provider-config/aws-bedrock/api-key) (AWS Bedrock, Vertex AI, Azure)
- Set up [MCP servers](/mcp/mcp-overview) for custom tooling
- Add [custom instructions](/customization/cline-rules) for your codebase

Schedule a walkthrough to see how Cline Enterprise fits your infrastructure. We’ll work with your security and compliance requirements to deploy in your environment.

Was this page helpful?

YesNo

[Onboarding](/enterprise-solutions/onboarding)

⌘I

---

## Sso Setup

*Source: [https://docs.cline.bot/enterprise-solutions/sso-setup](https://docs.cline.bot/enterprise-solutions/sso-setup)*

## [​](#overview) Overview

Cline Enterprise integrates with your identity provider (IdP) via **WorkOS AuthKit** for SSO.
This page describes, at a high level, how SSO is set up for Cline Enterprise using WorkOS AuthKit.
If you haven’t completed initial onboarding, start with [Onboarding](/enterprise-solutions/onboarding).

### [​](#video-walkthrough) Video Walkthrough

## [​](#where-setup-happens) Where setup happens

SSO setup spans two places:

1. **Cline Dashboard (app.cline.bot)**

- Where you sign in and verify SSO works for your organization.

2. **WorkOS dashboard**

- Where your IdP connection is configured (AuthKit → Connections). Your designated admin receives access to this during enterprise onboarding.

## [​](#using-the-cline-dashboard) Using the Cline Dashboard

Use the Cline Dashboard at <https://app.cline.bot> to:

- complete sign-in and onboarding flows
- verify users can authenticate via SSO

## [​](#configure-your-idp-connection-in-workos) Configure your IdP connection in WorkOS

During enterprise onboarding, your designated admin will receive an invitation email from WorkOS with a link to access your organization’s WorkOS dashboard.To connect your IdP to Cline Enterprise, configure your identity provider in **WorkOS AuthKit**:

1. In the WorkOS dashboard, go to **AuthKit → Connections**
2. Click **Add Connection**
3. Select your identity provider (e.g., Okta, Microsoft Entra ID/Azure AD, Google Workspace, Generic SAML/OIDC)
4. Follow the provider-specific instructions in WorkOS

WorkOS’s UI and required fields vary by provider. For details, follow WorkOS documentation:

- <https://workos.com/docs/authkit/sso>

## [​](#keycloak-note-idp-compatibility) Keycloak note (IdP compatibility)

Cline Enterprise’s default SSO integration is **via WorkOS**.
If you use **Keycloak** as your IdP, the supported path is to configure Keycloak in WorkOS as a **Generic SAML** or **Generic OIDC** provider (using the settings WorkOS requests for those provider types).

## [​](#verification) Verification

After configuring WorkOS:

1. Attempt an SSO sign-in from <https://app.cline.bot>.
2. Confirm the sign-in completes (you are redirected back successfully).

## [​](#troubleshooting) Troubleshooting

- **Redirect URI mismatch**: confirm the redirect/callback URL configured in WorkOS matches what was provided during your Cline Enterprise onboarding.

For additional troubleshooting guidance, refer to WorkOS documentation:

- <https://workos.com/docs/authkit/sso>

Was this page helpful?

YesNo

[Onboarding](/enterprise-solutions/onboarding)[Managing Members](/enterprise-solutions/team-management/managing-members)

⌘I

---

## Managing Members

*Source: [https://docs.cline.bot/enterprise-solutions/team-management/managing-members](https://docs.cline.bot/enterprise-solutions/team-management/managing-members)*

Effective member management is essential for maintaining security and enabling your team to work productively. This guide covers everything you need to know about roles, permissions, and day-to-day member administration.

## [​](#understanding-roles) Understanding Roles

Choose the right role for each team member to balance security with productivity. Here’s what each role is designed for:

## Owner

**Primary account holder**Unrestricted access to all settings including billing, security, and ownership transfer. Keep this limited to 1-2 key leaders.

## Admin

**Team leads & IT managers**Can manage users and configure providers. Ideal for trusted managers who need operational control without billing access.

## Member

**Developers & contributors**Can use Cline with shared resources but cannot change settings. The safest default for most team members.

## [​](#permissions-matrix) Permissions Matrix

Understand exactly what each role can do with this comprehensive permissions breakdown:

| Permission | Member | Admin | Owner |
| --- | --- | --- | --- |
| **General Usage** |  |  |  |
| Use Cline | ✅ | ✅ | ✅ |
| Access Shared API Providers | ✅ | ✅ | ✅ |
|  |  |  |  |
| **Member Management** |  |  |  |
| View Members | ❌ | ✅ | ✅ |
| Invite New Members | ❌ | ✅ | ✅ |
| Edit Member Roles | ❌ | ✅ | ✅ |
| Remove Members | ❌ | ✅ | ✅ |
| Remove Admins | ❌ | ❌ | ✅ |
|  |  |  |  |
| **Configuration** |  |  |  |
| Configure API Providers | ❌ | ✅ | ✅ |
| Manage Security Settings | ❌ | ❌ | ✅ |
|  |  |  |  |
| **Billing & Ownership** |  |  |  |
| View Billing Information | ❌ | ❌ | ✅ |
| Manage Subscription | ❌ | ❌ | ✅ |
| Transfer Ownership | ❌ | ❌ | ✅ |

**Quick Reference:** Most users should be **Members**. Grant **Admin** only to those managing users or configs. Reserve **Owner** for 1-2 account leaders.

## [​](#member-management-tasks) Member Management Tasks

- Adding Members
- Editing Roles
- Removing Members
- Revoking Invites

### [​](#inviting-new-team-members) Inviting New Team Members

1. **Navigate to Members**
   - Go to your organization dashboard at app.cline.bot
   - Click on “Members” in the sidebar
2. **Send Invitation**
   - Click “Invite Member”
   - Enter the user’s email address (must be from your verified domain)
   - Select the appropriate role (Member, Admin, or Owner)
   - Click “Send Invite”
3. **Invitation Status**
   - Invited users will receive an email with a join link
   - Pending invitations show in your member list with “Pending” status
   - Each pending invitation holds one seat from your license

**Bulk Invitations:** Need to add multiple users? Contact [support@cline.bot](mailto:support@cline.bot) for assistance with bulk invite CSV imports.

### [​](#changing-member-permissions) Changing Member Permissions

1. **Locate the Member**
   - Navigate to the Members page
   - Find the user you want to modify
2. **Change Role**
   - Click the dropdown next to their current role
   - Select the new role from the menu
   - Confirm the change
3. **Effective Immediately**
   - Role changes take effect instantly
   - The user may need to sign out and back in to see updated permissions

**Admin to Member:** Downgrading an Admin to Member will immediately revoke their ability to manage users and configurations. Ensure they no longer need these permissions.

### [​](#offboarding-team-members) Offboarding Team Members

1. **Access Member List**
   - Navigate to your organization’s Members page
   - Locate the user to remove
2. **Remove User**
   - Click the menu icon (⋮) next to their name
   - Select “Remove from Organization”
   - Confirm the removal
3. **Immediate Effects**
   - User loses access to the organization immediately
   - Their seat is freed and can be assigned to someone else
   - Audit logs are preserved for compliance

**Data Retention:** Removing a member does not delete their historical activity logs. All audit trails remain intact for compliance purposes.

### [​](#canceling-pending-invitations) Canceling Pending Invitations

If an invited user hasn’t accepted yet, you can revoke the invitation:

1. Find the pending invitation in your Members list
2. Click “Revoke Invitation”
3. The seat is immediately freed for another user

This is useful when:

- The wrong email was used
- The user no longer needs access
- You need to reassign the seat urgently

## [​](#identity-&-access-requirements) Identity & Access Requirements

For users to successfully join your organization, two conditions must be met:

1

Verified Identity Provider

Your organization must use a verified **Identity Provider (IDP)** such as:

- Microsoft Entra ID (Azure AD)
- Okta
- Google Workspace
- AWS IAM Identity Center

Users must authenticate through your IDP to access the organization.

2

Domain Verification

Your organization must have a **verified domain**. You’ll need to verify ownership of your domain through your domain provider (e.g., Google, Microsoft, Cloudflare).Only users with email addresses from verified domains can join.

These requirements ensure that only authenticated users from your company can access your Cline organization, preventing unauthorized access.

## [​](#seat-management) Seat Management

Understanding how seats work helps you manage your license effectively:

How Seats Are Calculated

- Each user (Owner, Admin, or Member) consumes **one seat**
- Pending invitations also hold one seat
- Removing a member or revoking an invite immediately frees the seat
- Your license determines the maximum number of seats available

When Seats Are Used

A seat is consumed when:

- You send an invitation (marked as “pending”)
- An invited user accepts and joins
- An existing user is granted access through SSO

Freeing Up Seats

To free a seat:

- Remove an active member from the organization
- Revoke a pending invitation
- Wait for a pending invite to expire (if configured)

Upgrading Your License

Need more seats?

- **Enterprise Plan:** Includes unlimited seats with no per-user restrictions. Contact your account manager or visit app.cline.bot/settings/billing to upgrade.

## [​](#security-best-practices) Security Best Practices

Follow these guidelines to maintain a secure organization:

## Principle of Least Privilege

Always assign the minimum role necessary. Most users should be Members. Only grant Admin or Owner privileges when required for job duties.

## Limit Owner Roles

Keep Owners to 1-2 key individuals who manage billing and security. This centralization prevents accidental or malicious changes to critical settings.

## Regular Audits

Review your member list quarterly. Remove inactive users promptly and verify that Admin/Owner roles are still appropriate for each user.

## Offboarding Process

Create a standard offboarding checklist: remove from Cline, revoke IDP access, document in audit log, and reassign any critical responsibilities.

**Owner Accountability:** Since Owners control billing and can transfer ownership, choose these individuals carefully and document the selection in your organization’s security policies.

## [​](#advanced-scenarios) Advanced Scenarios

Transferring Ownership

Only the current Owner can transfer ownership:

1. Navigate to Organization Settings
2. Go to the “Ownership” section
3. Select the new Owner from the member list
4. Confirm the transfer with your authentication
5. The new Owner receives immediate control

**Important:** This action cannot be undone by the previous Owner. The new Owner must initiate a reverse transfer if needed.

Managing Multiple Admins

When you have multiple Admins:

- Document each Admin’s area of responsibility
- Use audit logs to track configuration changes
- Consider creating rotation schedules for large teams
- Establish escalation paths for Owner-level decisions

Temporary Access

For contractors or temporary staff:

- Create them as Members with expiration calendar reminders
- Document their access period in your internal systems
- Set calendar reminders to remove them when the contract ends
- Consider using time-limited IDP accounts if your IDP supports it

## [​](#troubleshooting) Troubleshooting

User Can't Accept Invitation

**Common causes:**

- Email domain doesn’t match verified domain
- User’s IDP access hasn’t been granted yet
- Invitation link expired

**Solution:** Verify domain verification is complete and resend the invitation.

Can't Remove an Admin

**Cause:** Only Owners can remove Admins.**Solution:** Ask an Owner to perform the removal, or if you need to remove your organization’s sole Owner, contact [support@cline.bot](mailto:support@cline.bot).

Out of Seats

**When you’ve reached your license limit:**

- Remove inactive members to free seats
- Revoke pending invitations that are no longer needed
- Upgrade your license to add more seats

## [​](#next-steps) Next Steps

Now that you understand member management, proceed with configuring your organization:

## Configure Providers

Set up API providers for your team to use

## Monitor Usage

Track team activity and resource consumption

**Getting Started Fast?** The quickest path is: 1) Invite your team as Members, 2) Configure one API provider, 3) Let your team start using Cline. You can refine roles and settings later.

Was this page helpful?

YesNo

[SSO Setup](/enterprise-solutions/sso-setup)[Overview](/enterprise-solutions/configuration/remote-configuration/overview)

⌘I

---

## Auto Approve

*Source: [https://docs.cline.bot/features/auto-approve](https://docs.cline.bot/features/auto-approve)*

Auto Approve lets you decide which actions Cline can take without prompting you each time. It keeps you out of approval popups during routine work while letting you keep tight control over high-risk actions.
If you find yourself repeatedly clicking approve for the same safe operations, Auto Approve fixes that.

[](https://storage.googleapis.com/cline_public_images/autoapprove.mp4)

## [​](#how-it-works) How It Works

Auto Approve is evaluated per tool call. When Cline is about to read a file, edit a file, run a command, or use the browser, it checks your Auto Approve settings for that category.
A few details matter:

- **Workspace vs outside workspace**: “Read all files” and “Edit all files” only extend the base toggle. If the base toggle is off, the “all files” option does nothing.
- **Terminal commands**: Cline treats commands as either safe or requiring approval. “Execute safe commands” covers safe commands. “Execute all commands” extends to commands flagged as requiring approval.
- **Notifications**: If enabled, Cline sends OS-level notifications when approval is required, and when an auto-approved terminal command has been running for 30 seconds.

## [​](#permissions) Permissions

| Setting | What It Allows |
| --- | --- |
| Read project files | Read files, list files, search in your workspace |
| Read all files | Read files outside your workspace (requires base toggle) |
| Edit project files | Create and edit files in your workspace |
| Edit all files | Edit files outside your workspace (requires base toggle) |
| Execute safe commands | Run terminal commands marked safe |
| Execute all commands | Run commands requiring approval (requires base toggle) |
| Use the browser | Browser tool for web fetching and searching |
| Use MCP servers | MCP tools and resources |
| Enable notifications | Notifies you about long-running commands |

“Read all files” and “Edit all files” only matter if their base toggle is enabled. They extend access outside your workspace.

## [​](#safe-vs-approval-required-commands) Safe vs Approval-Required Commands

Cline does not use a fixed allowlist. The model marks each command with a `requires_approval` flag based on the command and arguments. These are examples, not guarantees.
**Commonly treated as safe:**

- `npm run build`, `npm test` - Build/test output
- `git status`, `ls -la`, `cat package.json` - Read-only commands

**Commonly requires approval:**

- `npm install <pkg>` - Modifies dependencies
- `rm -rf <path>` - Deletes files
- `mv <a> <b>` - Moves files (can overwrite)
- `sed -i ...` - In-place file edits

## [​](#recommendations) Recommendations

A good default setup:

- Enable **Read project files**
- Leave edits, commands, browser, and MCP off until you have a specific reason

If you enable edits, use [Checkpoints](/core-workflows/checkpoints) so you can roll back quickly.


---

## [​](#yolo-mode) YOLO Mode

YOLO mode is Auto Approve on steroids. Check the box and Cline auto-approves everything: file changes, terminal commands, browser actions, MCP tools, and mode transitions.

**Warning: This is dangerous.** YOLO mode disables all safety checks. Cline executes whatever it decides without asking permission.

### [​](#what-gets-auto-approved) What Gets Auto-Approved

When YOLO mode is enabled:

- All file operations anywhere on your system
- All terminal commands including potentially destructive ones
- Browser actions
- MCP server tools
- Mode transitions (Plan to Act)

### [​](#when-to-use-yolo-mode) When to Use YOLO Mode

**Rapid prototyping** where you want zero friction and don’t care about potential mistakes. Perfect for throwaway experiments.
**Trusted, repetitive tasks** where you’ve validated Cline’s approach and want to eliminate approval overhead.
**Demonstration purposes** where you want to show Cline’s capabilities without interruptions.

### [​](#what-could-go-wrong) What Could Go Wrong

Cline could:

- Delete important files without warning
- Execute commands that modify system settings
- Make network requests to external services
- Overwrite configuration files
- Install or uninstall packages
- Commit and push changes to version control

### [​](#best-practices-for-yolo-mode) Best Practices for YOLO Mode

- **Start with isolated environments.** Use throwaway projects or sandboxed environments first.
- **Be specific with requests.** Vague instructions + unlimited permissions = unpredictable results.
- **Monitor the output.** Cline still shows what it’s doing. Watch the terminal and file changes.
- **Keep version control handy.** Git becomes your safety net.

### [​](#enabling-yolo-mode) Enabling YOLO Mode

Navigate to Cline Settings, then Features, and check “YOLO Mode.” No confirmation dialogs. Once enabled, Cline auto-approves all actions immediately. Uncheck to disable.

Was this page helpful?

YesNo

[Memory Bank](/best-practices/memory-bank)[Jupyter Notebooks](/features/jupyter-notebooks)

⌘I

---

## Auto Compact

*Source: [https://docs.cline.bot/features/auto-compact](https://docs.cline.bot/features/auto-compact)*

When your conversation approaches the model’s context window limit, Cline automatically summarizes it to free up space and keep working.

## [​](#how-it-works) How It Works

Cline monitors token usage during your conversation. When you’re getting close to the limit, it:

1. Creates a comprehensive summary of everything that’s happened
2. Preserves all technical details, code changes, and decisions
3. Replaces the conversation history with the summary
4. Continues exactly where it left off

You’ll see a summarization tool call when this happens, showing the cost like any other API call.

## [​](#why-this-matters) Why This Matters

Previously, Cline would truncate older messages when hitting context limits, losing important context.
Now with summarization:

- All technical decisions and code patterns are preserved
- File changes and project context remain intact
- Cline remembers everything it’s done
- You can work on much larger projects without interruption

Auto Compact works especially well for long-running tasks. Structured task lists can help maintain progress across summarizations so Cline can stay on track across multiple context windows.

## [​](#cost-considerations) Cost Considerations

Summarization leverages your existing prompt cache from the conversation, so it costs about the same as any other tool call.
Since most input tokens are already cached, you’re primarily paying for summary generation (output tokens), making it cost-effective.

With other models, Cline falls back to standard rule-based context truncation, even if Auto Compact is enabled.

## [​](#restoring-context) Restoring Context

You can use [checkpoints](/core-workflows/checkpoints) to restore your task state from before a summarization occurred. You never truly lose context since you can always roll back.
Editing a message before a summarization tool call works similarly, restoring the conversation to that point.

Was this page helpful?

YesNo

⌘I

---

## Jupyter Notebooks

*Source: [https://docs.cline.bot/features/jupyter-notebooks](https://docs.cline.bot/features/jupyter-notebooks)*

Cline provides comprehensive support for Jupyter notebooks (`.ipynb` files), enabling AI-assisted editing with full cell-level context awareness. This feature was developed in collaboration with Amazon to bring AI coding assistance to data science workflows.

## [​](#getting-started) Getting Started

Jupyter notebook support is a built-in feature of Cline. To use it, you just need to have the Jupyter notebook extension enabled in VS Code. Once you open any `.ipynb` file, you’ll see AI-assisted buttons in your notebook interface.

## [​](#how-to-use) How to Use

### [​](#generate-cell) Generate Cell

Click the sparkle icon in the notebook toolbar to generate new cells with AI assistance.The AI receives context from surrounding cells, so it understands the variables and imports already in scope. This means you can reference existing DataFrames, functions, and other objects without re-explaining them.
**Example prompt:** “Create a visualization showing the correlation matrix of numeric columns with a heatmap”
The cell is inserted with proper notebook JSON structure, preserving metadata and ready to execute.

### [​](#explain-cell) Explain Cell

Click the Explain button in any cell’s title bar to get a detailed explanation of what the cell does.
This is useful for:

- Revisiting old notebooks
- Onboarding to a teammate’s analysis
- Understanding complex transformations

Cline extracts the full cell context, including outputs, so explanations can reference actual results like column names, row counts, and computed values.

### [​](#improve-cell) Improve Cell

Click the Improve button in any cell’s title bar to enhance existing cells with AI suggestions.Use this to:

- Optimize slow pandas operations
- Add error handling
- Refactor for clarity
- Convert loops to vectorized operations

Cline suggests improvements while preserving the cell’s position and metadata in the notebook structure. The AI explains what was changed and why.

## [​](#how-cell-context-works) How Cell Context Works

Unlike traditional file editing, Jupyter notebooks are JSON documents containing arrays of cells. Each cell has its own type, source content, metadata, execution count, and outputs.
When you use a Jupyter command, Cline extracts structured context that includes:

- **Cell type** (code, markdown, or raw)
- **Source content** as an array of lines
- **Cell metadata** and configuration
- **Execution count** for code cells
- **Outputs** including data, text, and error traces

This structured representation allows the AI to understand not just the code, but its context within the notebook and its actual output.

### [​](#json-structure-preservation) JSON Structure Preservation

Cline is designed to work carefully with the cell JSON structure, aiming to:

- Keep cell boundaries intact
- Preserve execution counts
- Maintain cell metadata
- Keep outputs associated with their source cells

The AI is specifically prompted to preserve notebook structure, though you should always review changes to ensure your notebook format remains correct.

## [​](#keyboard-shortcuts) Keyboard Shortcuts

You can bind any of these commands to keyboard shortcuts for faster access:

1. Open VS Code keyboard shortcuts (Cmd/Ctrl + K, Cmd/Ctrl + S)
2. Search for `cline.jupyterGenerateCell`, `cline.jupyterExplainCell`, or `cline.jupyterImproveCell`
3. Assign your preferred key combinations

## [​](#tips-for-best-results) Tips for Best Results

**For Generate Cell:**

- Be specific about what you want the cell to do
- Reference existing variables by name (the AI can see them)
- Mention preferred libraries if you have a preference (e.g., “use seaborn” or “use plotly”)

**For Explain Cell:**

- Works best on cells that have been executed (outputs provide additional context)
- Good for complex chained operations like pandas groupby/merge sequences

**For Improve Cell:**

- Mention what aspect you want to improve (performance, readability, error handling)
- The AI will explain the changes it suggests

## [​](#limitations) Limitations

- Notebook support requires the Jupyter notebook extension to be enabled in VS Code
- Cell context extraction depends on VS Code’s notebook API
- Very large notebooks may require more context than some models can handle efficiently

## [​](#related) Related

- [All Cline Tools](/tools-reference/all-cline-tools) - Overview of all Cline tools
- [Cline provider](/getting-started/cline-provider) - Fastest way to get started with built-in provider setup

Was this page helpful?

YesNo

[Auto Approve](/features/auto-approve)[Multi-Root Workspaces](/features/multiroot-workspace)

⌘I

---

## Multiroot Workspace

*Source: [https://docs.cline.bot/features/multiroot-workspace](https://docs.cline.bot/features/multiroot-workspace)*

Cline works with VSCode’s multi-root workspaces, letting you manage multiple project folders or repositories in a single window. Whether you’re working with a monorepo or separate Git repositories, Cline can read files, write code, and run commands across all of them.

[](https://storage.googleapis.com/cline_public_images/multiworkspace.mp4)

Multi-root workspaces have two limitations:

- **Cline rules** only work in the primary workspace folder
- **[Checkpoints](/core-workflows/checkpoints)** are disabled (restored when you return to a single folder)

See [Current Limitations](#current-limitations) for details.

## [​](#understanding-multi-root-workspaces) Understanding Multi-Root Workspaces

Before diving in, it helps to understand the two common patterns for organizing related projects.

### [​](#why-use-multi-root-workspaces) Why Use Multi-Root Workspaces?

Cline can complete tasks that span multiple projects or repositories:

- **Refactoring**: Update an API contract and fix all consumers across repos
- **Feature development**: Implement a feature that touches frontend, backend, and shared code
- **Dependency updates**: Coordinate version bumps across related projects
- **Documentation**: Generate docs that reference code from multiple repositories

**Example prompt:**

```
Update the User type in the contracts repo, then update both the frontend
and backend to use the new fields. Make sure the API validates the new
required field.
```

## [​](#setting-up-a-multi-root-workspace) Setting Up a Multi-Root Workspace

### [​](#monorepos-vs-multiple-repositories) Monorepos vs Multiple Repositories

**Monorepo**: One Git repository containing multiple projects or packages. All code shares the same version history.

**Multiple Repositories**: Separate Git repositories, each with their own history, opened together in one VSCode workspace.

```
~/projects/
├── fullstack.code-workspace   # Workspace config file
├── frontend/                  # git@github.com:acme/frontend.git
│   └── .git/
├── backend/                   # git@github.com:acme/backend.git
│   └── .git/
└── contracts/                 # git@github.com:acme/api-contracts.git
    └── .git/
```

Cline supports both patterns, as well as hybrid setups where some folders are Git repositories and others are not. The key difference: with multiple repositories, each folder has its own `.git` directory and Cline tracks them independently.

### [​](#adding-folders-to-your-workspace) Adding Folders to Your Workspace

You can add folders to your workspace in several ways:

- **File menu**: Use `File > Add Folder to Workspace` in VSCode
- **Drag and drop**: Drag folders directly into VSCode’s file explorer
- **Workspace file**: Create a `.code-workspace` file (recommended for teams)
- **Command palette**: Run `Workspaces: Add Folder to Workspace`

For detailed instructions, see [Microsoft’s multi-root workspace guide](https://code.visualstudio.com/docs/editor/multi-root-workspaces).

## [​](#working-with-multiple-repositories) Working with Multiple Repositories

When you open separate Git repositories in one workspace, Cline treats each as an independent project with its own version control.

### [​](#what-cline-tracks-per-repository) What Cline Tracks Per Repository

For each workspace folder, Cline detects:

| Property | Description |
| --- | --- |
| **Path** | Absolute path to the folder |
| **Name** | Derived from folder name or workspace file |
| **VCS Type** | Git, Mercurial, or None |
| **Commit Hash** | Current HEAD commit (for Git/Mercurial repos) |

This means Cline understands that your frontend and backend might be at different commits, on different branches, or even use different version control systems.

While Cline detects VCS information for all workspace folders, certain features only use the **primary workspace** (the first folder): [Cline rules](/customization/cline-rules), [skills](/customization/skills#triggering-skills-with-slash-commands), and [Git-related features](/core-workflows/working-with-files) like `@git` mentions.

## [​](#referencing-files-across-workspaces) Referencing Files Across Workspaces

### [​](#natural-language-references) Natural Language References

Cline understands natural references to your workspaces:

```
"Read the package.json in the frontend folder"
```

```
"Compare the user model in backend with the TypeScript types in contracts"
```

```
"Search for TODO comments across all workspaces"
```

### [​](#workspace-hints-syntax) Workspace Hints Syntax

For explicit references, use the `@workspace:path` syntax:

| Syntax | Description |
| --- | --- |
| `@frontend:src/App.tsx` | File in the “frontend” workspace |
| `@backend:server.ts` | File in the “backend” workspace |
| `@contracts:types/` | Folder in the “contracts” workspace |

This syntax is especially useful when:

- Multiple workspaces have files with the same name
- You want to be explicit about which project you mean
- Cline needs to resolve ambiguity

### [​](#how-workspace-names-work) How Workspace Names Work

Workspace names are derived from:

1. The `name` field in your `.code-workspace` file (if specified)
2. The folder name (default)

If two folders have the same name, append numbers or use the workspace file to give them unique names.

## [​](#common-configurations) Common Configurations

### [​](#monorepo-development) Monorepo Development

```
~/projects/my-app/
├── my-app.code-workspace      # Workspace config file
├── web/          (React frontend)
├── api/          (Node.js backend)
├── mobile/       (React Native)
└── shared/       (Common utilities)
```

All folders share one Git history. Changes across packages are atomic.
**Example prompt:** *“Update the API endpoint in both web and mobile apps to match the new backend route”*

### [​](#microservices-with-separate-repos) Microservices with Separate Repos

```
~/projects/services/
├── services.code-workspace    # Workspace config file
├── user-service/       (git: github.com/acme/user-service)
├── payment-service/    (git: github.com/acme/payment-service)
├── gateway/            (git: github.com/acme/api-gateway)
└── proto/              (git: github.com/acme/service-protos)
```

Each service has its own repository. Cline can update the proto definitions and regenerate clients across all services.
**Example prompt:** *“Add a new field to the UserProfile message in proto, then update user-service and gateway to handle it”*

### [​](#full-stack-with-shared-contracts) Full-Stack with Shared Contracts

```
~/projects/fullstack/
├── fullstack.code-workspace   # Workspace config file
├── client/         (git: github.com/acme/web-client)
├── server/         (git: github.com/acme/api-server)
└── types/          (git: github.com/acme/shared-types)
```

The types repository defines interfaces used by both client and server. When you update a type, Cline can fix both consumers.

### [​](#hybrid-setup) Hybrid Setup

```
~/projects/project/
├── project.code-workspace     # Workspace config file
├── main-app/       (git: github.com/acme/main-app)
├── vendor/         (no VCS - vendored dependencies)
└── scripts/        (no VCS - local automation)
```

Mix of repositories and plain folders. Cline adapts to each folder’s configuration.

## [​](#current-limitations) Current Limitations

Two features have limitations in multi-root workspace mode:

### [​](#cline-rules) Cline Rules

[Cline rules](/customization/cline-rules) (`.clinerules/` directory) only work in the **primary workspace** (the first folder in your workspace). Rules in other workspace folders are ignored.
**Workaround:** Place shared rules in the primary workspace, or use global rules (`~/Documents/Cline/Rules/`) which apply everywhere.

### [​](#checkpoints) Checkpoints

[Checkpoints](/core-workflows/checkpoints) are disabled in multi-root workspace mode. Cline displays a warning when this happens.
**Why:** Checkpoints use a shadow Git repository to track changes. With multiple repositories, coordinating checkpoints across independent Git histories adds complexity that isn’t yet supported.
**Workaround:** Use your normal Git workflow. Commit frequently, or create branches for experimental work.
Both limitations are restored when you return to a single-folder workspace.

## [​](#best-practices) Best Practices

### [​](#organizing-your-workspaces) Organizing Your Workspaces

1. **Group related projects** that often need coordinated changes
2. **Use a workspace file** for reproducible setups across your team
3. **Name folders clearly** so workspace hints are intuitive
4. **Consider the primary workspace** for Cline rules placement

### [​](#effective-prompting) Effective Prompting

- **Be specific** when it matters: *“Update the user model in the backend workspace”*
- **Reference relationships**: *“The frontend uses types from the contracts workspace”*
- **Describe cross-workspace changes**: *“This needs to update both web and mobile”*
- **Scope searches** for large codebases: *“Search for ‘TODO’ only in the frontend workspace”*

### [​](#working-with-large-workspaces) Working with Large Workspaces

- Break large tasks into workspace-specific operations when possible
- Use [Plan mode](/core-workflows/plan-and-act) to let Cline understand structure first
- Add a `.clineignore` file to reduce noise, speed up scanning, and keep Cline focused on source code:

```
# Dependencies
**/node_modules/

# Build outputs
**/dist/
**/build/

# VCS metadata
**/.git/
```

For more patterns and gotchas, see the [.clineignore File Guide](/customization/clineignore).

Was this page helpful?

YesNo

[Jupyter Notebooks](/features/jupyter-notebooks)[Networking & Proxies](/troubleshooting/networking-and-proxies)

⌘I

---

## Subagents

*Source: [https://docs.cline.bot/features/subagents](https://docs.cline.bot/features/subagents)*

Subagents let Cline spawn focused research agents that run in parallel. Each subagent gets its own prompt and context window, explores the codebase independently, and returns a detailed report to the main agent. This keeps the main agent’s context clean while gathering broad information fast.

Subagents is an experimental feature. Behavior may change in future releases.

## [​](#how-it-works) How It Works

When Cline uses the `use_subagents` tool, it launches independent agents simultaneously. Each one:

- Gets its own prompt describing what to investigate
- Runs with a separate context window and token budget
- Can read files, search code, list directories, run read-only commands, and use skills
- Cannot edit files, use the browser, access MCP servers, or spawn nested subagents
- Returns a result focused on the most relevant file paths for the main agent to read next

Subagent costs (tokens and API spend) are tracked separately per subagent and rolled into the task’s total cost. You can see per-subagent stats (tool calls, tokens, cost) in the chat UI as they run.

## [​](#enabling-subagents) Enabling Subagents

Subagents are enabled by default. Cline decides when parallel research is worth the overhead — you don’t need to opt in or call them out in your prompt. To turn subagents off, disable the `use_subagents` tool in Settings → Features → Agent.
This setting applies across all editors (VS Code, JetBrains, CLI).

## [​](#using-subagents) Using Subagents

When subagents are enabled, Cline picks them up on its own when a task benefits from parallel exploration. You can also nudge it explicitly by asking for parallel research in your prompt.
Example prompts:

- “Use subagents to explore how authentication works and where the database models are defined”
- “Spin up subagents to investigate the API routes, the test setup, and the deployment config”
- “I’m new to this codebase. Use subagents to map out the main entry points, the routing layer, and the data access patterns”

Each subagent prompt should describe a focused research question. Cline will run them in parallel and synthesize the results.
You can also run only one subagent when the task is small enough that parallel discovery would be unnecessary overhead.

## [​](#auto-approve-behavior) Auto-Approve Behavior

Subagents follow the **Read project files** auto-approve permission. If you have “Read project files” enabled in [Auto Approve](/features/auto-approve), subagent launches will be auto-approved.
If auto-approve is off, Cline will ask for your approval before launching subagents, showing you the prompts it plans to send.

## [​](#what-subagents-can-do) What Subagents Can Do

Subagents are read-only research agents. Here is what they have access to:

| Tool | Purpose |
| --- | --- |
| `read_file` | Read file contents |
| `list_files` | List directory contents |
| `search_files` | Regex search across files |
| `list_code_definition_names` | List top-level classes, functions, and methods |
| `execute_command` | Run read-only commands (`ls`, `grep`, `git log`, `git diff`, etc.) |
| `use_skill` | Load and activate skills |

Subagents cannot write files, apply patches, use the browser, access MCP servers, or perform web searches. They also cannot spawn their own subagents.

Commands run by subagents execute in the background and are restricted to read-only operations. Subagents will not run commands that modify files or system state.
Subagents also benefit from command pipelines and filters to narrow output quickly before reading files, for example `rg ... | sort | uniq`.

## [​](#when-to-use-subagents) When to Use Subagents

Subagents work best when you need broad context from multiple areas of a codebase at once:

- **Onboarding to an unfamiliar project**: Ask subagents to map out the architecture, key entry points, and data flow in parallel.
- **Investigating cross-cutting concerns**: Have separate subagents trace authentication, logging, and error handling simultaneously.
- **Pre-edit research**: Before making changes, use subagents to gather context from related files so the main agent can make informed edits without burning through its context window.
- **Large codebases**: When reading many files sequentially would consume too much of the main agent’s context, subagents let you explore broadly without that tradeoff.

For small, focused tasks where you already know which files to look at, subagents add unnecessary overhead. Just ask Cline directly.

Was this page helpful?

YesNo

[Agent Teams](/cli/agent-teams)[Memory Bank](/best-practices/memory-bank)

⌘I

---

## Yolo Mode

*Source: [https://docs.cline.bot/features/yolo-mode](https://docs.cline.bot/features/yolo-mode)*

Auto Approve lets you decide which actions Cline can take without prompting you each time. It keeps you out of approval popups during routine work while letting you keep tight control over high-risk actions.
If you find yourself repeatedly clicking approve for the same safe operations, Auto Approve fixes that.

[](https://storage.googleapis.com/cline_public_images/autoapprove.mp4)

## [​](#how-it-works) How It Works

Auto Approve is evaluated per tool call. When Cline is about to read a file, edit a file, run a command, or use the browser, it checks your Auto Approve settings for that category.
A few details matter:

- **Workspace vs outside workspace**: “Read all files” and “Edit all files” only extend the base toggle. If the base toggle is off, the “all files” option does nothing.
- **Terminal commands**: Cline treats commands as either safe or requiring approval. “Execute safe commands” covers safe commands. “Execute all commands” extends to commands flagged as requiring approval.
- **Notifications**: If enabled, Cline sends OS-level notifications when approval is required, and when an auto-approved terminal command has been running for 30 seconds.

## [​](#permissions) Permissions

| Setting | What It Allows |
| --- | --- |
| Read project files | Read files, list files, search in your workspace |
| Read all files | Read files outside your workspace (requires base toggle) |
| Edit project files | Create and edit files in your workspace |
| Edit all files | Edit files outside your workspace (requires base toggle) |
| Execute safe commands | Run terminal commands marked safe |
| Execute all commands | Run commands requiring approval (requires base toggle) |
| Use the browser | Browser tool for web fetching and searching |
| Use MCP servers | MCP tools and resources |
| Enable notifications | Notifies you about long-running commands |

“Read all files” and “Edit all files” only matter if their base toggle is enabled. They extend access outside your workspace.

## [​](#safe-vs-approval-required-commands) Safe vs Approval-Required Commands

Cline does not use a fixed allowlist. The model marks each command with a `requires_approval` flag based on the command and arguments. These are examples, not guarantees.
**Commonly treated as safe:**

- `npm run build`, `npm test` - Build/test output
- `git status`, `ls -la`, `cat package.json` - Read-only commands

**Commonly requires approval:**

- `npm install <pkg>` - Modifies dependencies
- `rm -rf <path>` - Deletes files
- `mv <a> <b>` - Moves files (can overwrite)
- `sed -i ...` - In-place file edits

## [​](#recommendations) Recommendations

A good default setup:

- Enable **Read project files**
- Leave edits, commands, browser, and MCP off until you have a specific reason

If you enable edits, use [Checkpoints](/core-workflows/checkpoints) so you can roll back quickly.


---

## [​](#yolo-mode) YOLO Mode

YOLO mode is Auto Approve on steroids. Check the box and Cline auto-approves everything: file changes, terminal commands, browser actions, MCP tools, and mode transitions.

**Warning: This is dangerous.** YOLO mode disables all safety checks. Cline executes whatever it decides without asking permission.

### [​](#what-gets-auto-approved) What Gets Auto-Approved

When YOLO mode is enabled:

- All file operations anywhere on your system
- All terminal commands including potentially destructive ones
- Browser actions
- MCP server tools
- Mode transitions (Plan to Act)

### [​](#when-to-use-yolo-mode) When to Use YOLO Mode

**Rapid prototyping** where you want zero friction and don’t care about potential mistakes. Perfect for throwaway experiments.
**Trusted, repetitive tasks** where you’ve validated Cline’s approach and want to eliminate approval overhead.
**Demonstration purposes** where you want to show Cline’s capabilities without interruptions.

### [​](#what-could-go-wrong) What Could Go Wrong

Cline could:

- Delete important files without warning
- Execute commands that modify system settings
- Make network requests to external services
- Overwrite configuration files
- Install or uninstall packages
- Commit and push changes to version control

### [​](#best-practices-for-yolo-mode) Best Practices for YOLO Mode

- **Start with isolated environments.** Use throwaway projects or sandboxed environments first.
- **Be specific with requests.** Vague instructions + unlimited permissions = unpredictable results.
- **Monitor the output.** Cline still shows what it’s doing. Watch the terminal and file changes.
- **Keep version control handy.** Git becomes your safety net.

### [​](#enabling-yolo-mode) Enabling YOLO Mode

Navigate to Cline Settings, then Features, and check “YOLO Mode.” No confirmation dialogs. Once enabled, Cline auto-approves all actions immediately. Uncheck to disable.

Was this page helpful?

YesNo

[Memory Bank](/best-practices/memory-bank)[Jupyter Notebooks](/features/jupyter-notebooks)

⌘I

---

## Authorizing With Cline

*Source: [https://docs.cline.bot/getting-started/authorizing-with-cline](https://docs.cline.bot/getting-started/authorizing-with-cline)*

Cline connects to AI models through a **provider**. You have two paths:

- **Cline Provider** (recommended): sign in with Google/GitHub/email, no API key setup.
- **Bring Your Own Key (BYOK)**: use your own provider credentials (cloud or local runtimes).

## [​](#menu) Menu

- [IDE Setup](#ide-setup)
- [CLI Setup](#cli-setup)

## [​](#ide-setup) IDE Setup

1

Open Cline Settings

Click the settings icon (⚙️) in the Cline panel.

2

Select Provider

Choose your desired provider from the **API Provider** dropdown.

3

Authenticate

- **Cline Provider:** Click **Sign In** and complete OAuth.
- **BYOK cloud provider:** Paste your API key into the **API Key** field.
- **Local runtime (Ollama/LM Studio):** no key needed; ensure runtime is running.

4

Select Model

Choose your desired Claude model from the **Model** dropdown.

## [​](#provider-options) Provider Options

### [​](#cline-provider) Cline Provider

- One sign-in, no key management
- Built-in billing and free model options
- Access to multiple providers from one account

Add credits in Cline settings or at [app.cline.bot/dashboard](https://app.cline.bot/dashboard).

### [​](#byok-cloud-+-local) BYOK (cloud + local)

### [​](#cloud-providers) Cloud Providers

| Provider | Best For | Setup Guide |
| --- | --- | --- |
| **OpenRouter** | Multiple models, competitive pricing | [Setup](/provider-config/openrouter) |
| **Anthropic** | Direct Claude access | [Setup](/provider-config/anthropic) |
| **Claude Code** | Claude Max/Pro subscription | [Setup](/provider-config/anthropic) |
| **OpenAI** | GPT models | [Setup](/provider-config/openai) |
| **Google Gemini** | Gemini models | [Setup](/provider-config/google-gemini) |
| **AWS Bedrock** | Enterprise | [Setup](/provider-config/aws-bedrock/api-key) |
| **DeepSeek** | Great value | [Setup](/provider-config/deepseek) |

### [​](#local-models) Local Models

Run models on your own hardware for complete privacy and zero per-request costs.

| Provider | Best For | Setup Guide |
| --- | --- | --- |
| **Ollama** | CLI-based local runtime | [Setup](/running-models-locally/overview#runtime-options) |
| **LM Studio** | GUI-based local runtime | [Setup](/running-models-locally/overview#runtime-options) |

Local models require sufficient hardware (especially GPU memory). See [Running Models Locally](/running-models-locally/overview) for requirements.

## [​](#cli-setup) CLI Setup

```
# Authenticate from the terminal
cline auth

# Shorthand
cline a
```

Runs the same auth flow as IDE setup.

## [​](#troubleshooting) Troubleshooting

| Issue | Fix |
| --- | --- |
| ”Unauthorized: Please sign in” | Session expired. Click **Sign In** to re-authenticate. |
| Browser doesn’t open | Check default browser settings. Copy the URL from the Cline output panel manually. |
| Frequent re-authentication | Check org security policies. Ensure you’re not clearing IDE secrets. Try a full sign-out/sign-in. |
| Can’t access organization | Verify membership at [app.cline.bot](https://app.cline.bot). Ask your admin about permissions. Sign out and back in. |

Was this page helpful?

YesNo

[Installing Cline](/getting-started/installing-cline)[Cline provider](/getting-started/cline-provider)

⌘I

---

## Cline Provider

*Source: [https://docs.cline.bot/getting-started/cline-provider](https://docs.cline.bot/getting-started/cline-provider)*

The **Cline provider** is the simplest way to get started with Cline.
Instead of managing separate API keys across multiple vendors, you sign in once and select from available models directly in Cline.

## [​](#why-use-cline-provider) Why use Cline provider

- **Fastest setup**: no manual API key copy/paste
- **One account**: sign in once with Google, GitHub, or email
- **Unified billing**: one balance across supported models
- **Free options**: look for models tagged **FREE** in the selector

## [​](#setup) Setup

1

Open Cline Settings

Click the settings icon in the Cline panel.

2

Choose Provider

Set **API Provider** to **Cline**.

3

Sign In

Click **Sign In** and complete authentication in your browser.

4

Select a Model

Choose a model from the **Model** dropdown.

5

Verify

Send a test message. If Cline responds, setup is complete.

## [​](#credits-and-usage) Credits and usage

- Add credits from your [Cline dashboard](https://app.cline.bot/dashboard)
- View usage in Cline Settings → **View Usage**
- Switch organizations in Cline Settings → **Switch Organization**

## [​](#related) Related

- [Authorization](/getting-started/authorizing-with-cline)
- [Local models](/running-models-locally/overview)
- [Provider setup guides](/provider-config/openrouter)

Was this page helpful?

YesNo

[Authorization](/getting-started/authorizing-with-cline)[Local models](/running-models-locally/overview)

⌘I

---

## Config

*Source: [https://docs.cline.bot/getting-started/config](https://docs.cline.bot/getting-started/config)*

Cline configuration lives in two scopes:

- **Global configuration** in `~/.cline/` (applies globally across all Cline applications, including IDE, CLI, and SDK)
- **Project configuration** in `.cline/` (applies only to the current workspace)

## [​](#configuration-directory-layout) Configuration Directory Layout

Cline stores shared configuration across a few well-known locations. The primary root is `~/.cline/`, with structured app state under `~/.cline/data/`:

```
~/.cline/
  data/
    settings/
      providers.json           # API keys and provider configuration
      global-settings.json     # Global settings
      cline_mcp_settings.json  # MCP settings
    teams/                     # Team state
    sessions/                  # Session data
    db/                        # SQLite databases (for example cron.db)
    workflows/                 # Global workflows
  rules/                       # Global rules
  hooks/                       # Global hooks
  skills/                      # Global skills
  agents/                      # Global agent definitions
  plugins/                     # Global plugins (.js, .ts)
  cron/                        # Global cron specs
```

Additional global search paths supported by the code:

```
~/Documents/Cline/
  Rules/                       # Additional global rules
  Hooks/                       # Additional global hooks
  Plugins/                     # Additional global plugins
  Workflows/                   # Additional global workflows
```

Project-level configuration lives in `.cline/` at your repository root:

```
.cline/
  rules/                       # Project rules
  skills/                      # Project skills
  hooks/                       # Lifecycle hooks
  agents/                      # Project agent definitions
  plugins/                     # Project plugins
  cron/                        # Workspace cron specs
```

Notes:

- Global provider settings, global settings, and MCP settings are stored under `~/.cline/data/settings/`.
- Global workflows resolve from `~/.cline/data/workflows/`.
- Global rules, hooks, skills, agents, plugins, and cron specs resolve directly under `~/.cline/`.
- Rules, hooks, plugins, and workflows may also be discovered from `~/Documents/Cline/` for compatibility.

## [​](#what-goes-where) What Goes Where?

- Use **global (`~/.cline/`)** for defaults shared across all Cline applications (IDE, CLI, SDK) on your machine.
- Use **project (`.cline/`)** for team-shared behavior that should travel with the repo.

Commit `.cline/` files you want to share with your team. Keep secrets out of the repo.

## [​](#configure-through-the-cli) Configure Through the CLI

Use the interactive config UI:

```
cline config
```

From there, you can view/edit:

- Settings (global + workspace)
- Rules
- Skills
- Hooks

## [​](#useful-configuration-commands) Useful Configuration Commands

Use a custom configuration directory:

```
cline --config /path/to/custom/config "your task"
```

Or via environment variable:

```
export CLINE_DATA_DIR=/custom/path/to/cline
cline "your task"
```

View CLI logs when troubleshooting:

```
cline dev log
```

## [​](#environment-variables) Environment Variables

| Variable | Description |
| --- | --- |
| `CLINE_DATA_DIR` | Custom data directory (replaces `~/.cline/data/`) |
| `CLINE_HUB_ADDRESS` | Override hub address (default: `127.0.0.1:25463`) |
| `CLINE_SESSION_BACKEND_MODE` | Force backend mode (`local`, `hub`, `remote`, `auto`) |
| `CLINE_SANDBOX` | Enable sandbox mode |
| `CLINE_SANDBOX_DATA_DIR` | Sandbox session storage directory |
| `CLINE_HOOKS_DIR` | Additional hooks directory |
| `CLINE_COMMAND_PERMISSIONS` | JSON policy restricting shell commands |

### [​](#cline_data_dir) CLINE\_DATA\_DIR

```
export CLINE_DATA_DIR=/custom/path/to/cline
cline "your task"
```

### [​](#cline_command_permissions) CLINE\_COMMAND\_PERMISSIONS

Restrict which shell commands Cline can execute:

```
export CLINE_COMMAND_PERMISSIONS='{"allow": ["npm *", "git *"], "deny": ["rm -rf *"]}'
```

Format:

```
{
  "allow": ["pattern1", "pattern2"],
  "deny": ["pattern3"],
  "allowRedirects": true
}
```

Rules:

- `deny` overrides `allow`
- If `allow` is set, commands not matching `allow` are denied
- `allowRedirects` controls shell redirects (`>`, `>>`, `<`), default `false`

## [​](#related-docs) Related Docs

- [CLI Configuration](/cli/configuration)
- [Rules](/customization/cline-rules)
- [Skills](/customization/skills)
- [Hooks](/customization/hooks)
- [Plugins](/customization/plugins)
- [.clineignore](/customization/clineignore)

## [​](#security-notes) Security Notes

Only use rules, hooks, skills, and plugins from sources you trust.

Hooks and plugins can execute code. Review them like any other executable artifact before adding them globally or to a project.

Was this page helpful?

YesNo

[Other 30+ Providers](/provider-config/other-30-plus-providers)[IDE](/usage/ide)

⌘I

---

## Installing Cline

*Source: [https://docs.cline.bot/getting-started/installing-cline](https://docs.cline.bot/getting-started/installing-cline)*

## [​](#choose-your-install-path) Choose Your Install Path

- [IDE Extension](#ide-extension) — VS Code, Cursor, JetBrains, Windsurf, VSCodium, Antigravity
- [CLI](#cli) — terminal workflows
- [Kanban](#kanban) (preview) — easily manage through multiple agents through a kanban board
- [SDK](#sdk) — build with `@cline/sdk`

## [​](#ide-extension) IDE Extension

Use this if you want Cline inside your editor UI.

- VS Code / Cursor / Windsurf / VSCodium / Antigravity
- JetBrains

1

Open Extensions

Press `Ctrl/Cmd + Shift + X`.

2

Search for Cline

Type `Cline`.

3

Install

Click **Install** on the Cline extension.

4

Open Cline

Use the Cline activity bar icon, or run `Cline: Open In New Tab` from Command Palette.

5

Authorize with Cline

After installing the extension, complete provider setup in Cline settings.[Authorize with Cline](/getting-started/authorizing-with-cline)

Windsurf and VSCodium use Open VSX. The install flow is the same.

1

Open Plugins Marketplace

**Settings** → **Plugins** → **Marketplace**.

2

Install Cline

Search `Cline`, click **Install**, then restart the IDE.

3

Open Cline

**View** → **Tool Windows** → **Cline**.

4

Authorize with Cline

After installing the extension, complete provider setup in Cline settings.[Authorize with Cline](/getting-started/authorizing-with-cline)

Alternative: install from the [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/28247-cline).

## [​](#cli) CLI

Use this if you want Cline in terminal workflows (interactive + automation).

1

Install Node.js

Install Node.js 20+ (22 recommended).

2

Install CLI

```
npm install -g cline
```

3

Authenticate

```
cline auth
```

4

Run Cline

```
cline
# or
cline "your task"
```

More details: [CLI Installation & Setup](/usage/cli-overview)

## [​](#kanban) Kanban

Use this if you want task-board workflows with agent execution.

1

Install Node.js

Install Node.js 18+.

2

Launch Kanban

```
npx kanban
```

More details: [Kanban](/usage/kanban)

## [​](#sdk) SDK

Use this if you are building your own app/agent on top of Cline.

1

Create project

```
mkdir my-agent && cd my-agent
npm init -y
```

2

Install SDK

```
npm install @cline/sdk
```

3

Build and run

Browse SDK examples to run your first agent.

Start here: [SDK Examples](/sdk/examples)

## [​](#need-help) Need Help?

- [Troubleshooting](/troubleshooting/networking-and-proxies)
- [Discord community](https://discord.gg/cline)

Was this page helpful?

YesNo

[Cline Overview](/cline-overview)[Authorization](/getting-started/authorizing-with-cline)

⌘I

---

## Core Workflow

*Source: [https://docs.cline.bot/kanban/core-workflow](https://docs.cline.bot/kanban/core-workflow)*

This guide walks through the typical Kanban workflow from start to finish.

## [​](#1-create-tasks) 1. Create Tasks

There are two ways to add tasks to the board:

- **Manually** — click the add button and write a task description
- **Via sidebar chat** — open the sidebar chat and ask the agent to break down a piece of work into tasks. The agent can create cards, link them together, and start work directly on the board.

Each card on the board represents a discrete unit of work for an agent to complete.

## [​](#2-link-tasks) 2. Link Tasks

Link cards together to create dependency chains:

- **⌘ + click** (Mac) / **Ctrl + click** (Windows/Linux) a card to link it to another task
- When a linked card completes and is moved to trash, the next linked task **automatically starts**

Combined with auto-commit, this enables fully autonomous chains where one task’s output feeds into the next without manual intervention.

## [​](#3-start-tasks) 3. Start Tasks

Hit the **play button** on a card to start it. Here’s what happens:

1. Kanban creates an **ephemeral git worktree** for the task — an isolated copy of your repo where the agent can make changes without affecting your main working directory or other tasks
2. Gitignored files like `node_modules` are **symlinked** from your main repo into the worktree, avoiding slow reinstalls for each task
3. The agent starts working in its own terminal within that worktree
4. The card displays the agent’s **latest message or tool call** so you can monitor progress from the board

Multiple tasks run in parallel, each in their own worktree, so agents never create merge conflicts with each other.

Symlinks work well for gitignored files that agents don’t need to modify (like `node_modules`). If your workflow requires agents to modify gitignored files, be aware that changes will affect the symlink target (your main repo’s copy).

## [​](#4-review-changes) 4. Review Changes

Click a card to open the detail view, which shows:

- **The agent’s TUI** — the full text interface showing the agent’s conversation and actions
- **A diff of all changes** in that worktree compared to your base branch

The diff viewer includes a **checkpoint system** — you can see diffs scoped to specific message ranges, not just the full cumulative diff. This makes it easier to understand what changed and when.

### [​](#inline-comments) Inline Comments

Click on any line in the diff to leave a comment. Comments are sent back to the agent as feedback, letting you steer its work without rewriting the task description. This is useful for corrections like “use a different approach here” or “this edge case isn’t handled.”

## [​](#5-ship-it) 5. Ship It

When you’re satisfied with the changes, you have two options:

- **Commit** — merges the worktree changes into a commit on your base branch
- **Open PR** — creates a new branch and opens a pull request

In both cases, Kanban sends a dynamic prompt to the agent to handle the operation. The agent converts the worktree into the appropriate git action and **intelligently handles merge conflicts** if the base branch has moved since the worktree was created.

## [​](#6-clean-up) 6. Clean Up

After shipping, move the card to **trash** to clean up the ephemeral worktree and free disk space.

If you need to resume work on a trashed card later, Kanban provides a **resume ID** for each task. You can use this to pick up where you left off.

## [​](#workflow-summary) Workflow Summary

| Step | Action | What Happens |
| --- | --- | --- |
| Create | Add card or use sidebar chat | Task card appears on the board |
| Link | ⌘ + click to connect cards | Dependency chain is established |
| Start | Hit play on a card | Ephemeral worktree is created, agent begins work |
| Monitor | Watch card status on board | Latest agent message/tool call shown on card |
| Review | Click card to see diff | Full diff with checkpoints and inline commenting |
| Ship | Click Commit or Open PR | Agent handles merge into base branch or creates PR |
| Clean up | Move to trash | Worktree is removed, resume ID saved |

Was this page helpful?

YesNo

[Overview](/usage/kanban)[Remote Access](/kanban/remote-access)

⌘I

---

## Remote Access

*Source: [https://docs.cline.bot/kanban/remote-access](https://docs.cline.bot/kanban/remote-access)*

By default, Kanban binds to `127.0.0.1:3484` and is only accessible from the machine it’s running on. This guide shows how to enable remote access for mobile devices, remote machines, or team collaboration.

When exposing Kanban beyond localhost, ensure you trust all devices and users with access. Kanban provides full access to your git repository and terminal.

## [​](#local-network-access) Local Network Access

To make Kanban accessible to other devices on your local network (like a phone or tablet on the same WiFi), bind to `0.0.0.0` instead of `127.0.0.1`.

### [​](#using-cli-flag) Using CLI Flag

```
kanban --host 0.0.0.0
```

This makes Kanban available at `http://<your-machine-ip>:3484` from any device on your network.

### [​](#using-environment-variable) Using Environment Variable

```
KANBAN_RUNTIME_HOST=0.0.0.0 cline
```

When you run `cline`, it will launch Kanban bound to `0.0.0.0`.

**Security Note**: Binding to `0.0.0.0` exposes Kanban to your entire local network. Only use this on networks you trust, such as your home WiFi.

## [​](#tailscale-recommended-for-remote-access) Tailscale (Recommended for Remote Access)

Tailscale provides secure remote access without exposing ports to the internet. Once configured, you can access Kanban from your phone while on the road, from a coffee shop, or anywhere else.

### [​](#setup) Setup

1. **Install Tailscale** on both your development machine and your phone/remote device
2. **Sign in** to the same Tailscale account on both devices
3. **Launch Kanban** with network binding:

```
KANBAN_RUNTIME_HOST=0.0.0.0 cline
```

4. **Access from your phone**: Navigate to your machine’s Tailscale hostname on port 3484:

```
http://your-machine-name.tail1234.ts.net:3484
```

Your Tailscale hostname is visible in the Tailscale app or admin console.

Tailscale creates a secure mesh VPN, so your connection is encrypted and doesn’t require opening any firewall ports. This is the safest option for remote access.

## [​](#docker-deployment) Docker Deployment

Run Kanban in a Docker container for isolated deployments or server environments.

### [​](#dockerfile) Dockerfile

```
FROM node:22

WORKDIR /app

EXPOSE 3484

CMD ["npx", "--yes", "kanban@latest", "--host", "0.0.0.0"]
```

### [​](#build-and-run) Build and Run

```
docker build -t npx-kanban .
docker run -it -p 3484:3484 npx-kanban
```

Then navigate to `http://localhost:3484` from your browser.

To access the Kanban container from other machines on your network, use `http://<docker-host-ip>:3484`.

## [​](#ssh-tunnel) SSH Tunnel

SSH tunneling creates a secure connection between your local machine and a remote server. This requires SSH access to the remote machine where Kanban is running.

### [​](#setup-2) Setup

**On the remote machine**, run Kanban normally (it can bind to `127.0.0.1`):

```
kanban
```

**On your local machine**, create an SSH tunnel:

```
ssh -L 3484:localhost:3484 user@remote-hostname
```

Then navigate to `http://localhost:3484` in your local browser. The SSH tunnel securely forwards the connection to the remote machine.

Replace `user` with your SSH username and `remote-hostname` with the IP address or hostname of your remote machine. If using SSH keys, add `-i /path/to/key.pem` before the username.

## [​](#ngrok) Ngrok

Ngrok creates a public HTTPS URL that tunnels to your local Kanban instance. Useful for quick demos or sharing with collaborators.

### [​](#setup-3) Setup

```
# Install ngrok (macOS)
brew install ngrok

# Add your auth token (create a free account at ngrok.com)
ngrok config add-authtoken $YOUR_AUTHTOKEN

# Start Kanban
kanban

# In another terminal, create the tunnel
ngrok http 3484
```

Ngrok will display a public URL like `https://1234-5678-9012.ngrok-free.app`. Share this URL to give others access to your Kanban board.

Ngrok URLs are publicly accessible on the internet. Anyone with the URL can access your Kanban board. Only use this for temporary access and stop the tunnel when finished.

## [​](#cloudflare-tunnels) Cloudflare Tunnels

Cloudflare Tunnels provide production-grade remote access with custom domains, access controls, and HTTPS.

### [​](#setup-4) Setup

Follow the [Cloudflare Tunnel guide](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/get-started/create-remote-tunnel/) to create a tunnel. Then configure your application route with these settings:

- **Hostname.subdomain**: Choose any subdomain (e.g., `kanban`)
- **Hostname.Domain**: Your domain configured with Cloudflare
- **Hostname.Path**: Leave empty
- **Service.Type**: `HTTP`
- **Service.URL**: `localhost:3484`

### [​](#aws-cdk-example) AWS CDK Example

Deploy Kanban on EC2 with Cloudflare Tunnel using AWS CDK:

```
import * as cdk from "aws-cdk-lib/core";
import * as ec2 from "aws-cdk-lib/aws-ec2";
import * as iam from "aws-cdk-lib/aws-iam";
import { Construct } from "constructs";

export class KanbanEc2Stack extends cdk.Stack {
    constructor(scope: Construct, id: string, props?: cdk.StackProps) {
        super(scope, id, props);

        // Tunnel token from env or CDK context
        const tunnelToken =
            process.env.TUNNEL_TOKEN || this.node.tryGetContext("tunnelToken");
        if (!tunnelToken) {
            throw new Error(
                "Missing tunnel token. Set TUNNEL_TOKEN env var or pass -c tunnelToken=xxx",
            );
        }

        // VPC + Security Group
        const vpc = ec2.Vpc.fromLookup(this, "DefaultVpc", { isDefault: true });

        const sg = new ec2.SecurityGroup(this, "KanbanSg", {
            vpc,
            allowAllOutbound: true,
            description: "Kanban EC2 security group",
        });
        sg.addIngressRule(ec2.Peer.myIp(), ec2.Port.tcp(22), "SSH access");

        // User data script
        const userData = ec2.UserData.forLinux();
        userData.addCommands(
            "set -x",
            "exec > >(tee /var/log/user-data.log) 2>&1",

            // 1) Install git and cloudflared first for tunnel connectivity
            "sudo dnf install -y git",
            "curl -L --output /tmp/cloudflared.rpm https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-x86_64.rpm",
            "sudo yum localinstall -y /tmp/cloudflared.rpm",

            // 2) Start cloudflared tunnel so the instance is reachable
            `sudo cloudflared service install ${tunnelToken}`,

            // 3) Install Node.js 22 via NodeSource
            "curl -fsSL https://rpm.nodesource.com/setup_22.x | sudo bash -",
            "sudo dnf install -y nodejs",

            // 4) Clone and build the app
            "git clone -b main https://github.com/cline/kanban.git /opt/kanban",

            // 5) Create systemd service for the kanban app
            `cat > /etc/systemd/system/kanban.service << 'UNIT'
[Unit]
Description=Kanban App
After=network.target

[Service]
Type=simple
WorkingDirectory=/opt/kanban
ExecStart=/usr/bin/kanban
Restart=always
RestartSec=5
Environment=NODE_ENV=production
Environment=HOME=/root
Environment=PATH=/usr/bin:/usr/local/bin

[Install]
WantedBy=multi-user.target
UNIT`,
            "systemctl daemon-reload",
            "systemctl enable --now kanban.service",
        );

        // IAM role with SSM access
        const role = new iam.Role(this, "KanbanInstanceRole", {
            assumedBy: new iam.ServicePrincipal("ec2.amazonaws.com"),
            managedPolicies: [
                iam.ManagedPolicy.fromAwsManagedPolicyName(
                    "AmazonSSMManagedInstanceCore",
                ),
            ],
        });

        // EC2 Instance
        const instance = new ec2.Instance(this, "KanbanInstance", {
            vpc,
            instanceType: ec2.InstanceType.of(
                ec2.InstanceClass.T3,
                ec2.InstanceSize.SMALL,
            ),
            machineImage: ec2.MachineImage.latestAmazonLinux2023(),
            securityGroup: sg,
            vpcSubnets: { subnetType: ec2.SubnetType.PUBLIC },
            associatePublicIpAddress: true,
            userData,
            role,
        });

        // Outputs
        new cdk.CfnOutput(this, "InstanceId", { value: instance.instanceId });
        new cdk.CfnOutput(this, "PublicIp", {
            value: instance.instancePublicIp,
        });
    }
}
```

Deploy with:

```
TUNNEL_TOKEN=<your_tunnel_token> cdk deploy
```

## [​](#summary) Summary

| Method | Security | Complexity | Use Case |
| --- | --- | --- | --- |
| **Local Network** | Low (LAN only) | Easy | Phone/tablet on same WiFi |
| **Tailscale** | High (encrypted VPN) | Easy | Remote access from anywhere |
| **Docker** | Medium (isolated) | Medium | Server deployments |
| **SSH Tunnel** | High (encrypted) | Medium | Secure remote access |
| **Ngrok** | Low (public URL) | Easy | Temporary demos/sharing |
| **Cloudflare** | High (custom domain) | Complex | Production deployments |

For personal remote access, **Tailscale** offers the best balance of security and ease of use. For production team access, consider **Cloudflare Tunnels** with access controls.

Was this page helpful?

YesNo

[Core Workflow](/kanban/core-workflow)[Tools](/tools-reference/all-cline-tools)

⌘I

---

## Mcp Marketplace

*Source: [https://docs.cline.bot/mcp/mcp-marketplace](https://docs.cline.bot/mcp/mcp-marketplace)*

MCP (Model Context Protocol) lets Cline use external tools and data sources through MCP servers.

## [​](#what-mcp-gives-you) What MCP gives you

- Connect Cline to external APIs and services
- Add custom tools beyond built-in Cline tools
- Use either local servers or remote hosted servers

## [​](#quick-start) Quick start

1. Open **MCP Servers** in Cline
2. Add a server (from Marketplace or manually)
3. Configure credentials/environment variables
4. Verify tools appear and test one tool call

## [​](#add-servers) Add servers

### [​](#option-1-marketplace) Option 1: Marketplace

Use Cline’s MCP Marketplace for one-click install when available.

1. In the Cline panel, click the MCP Servers icon (stacked server icon in the top toolbar).
2. Open the Marketplace tab.

### [​](#option-2-manual-config) Option 2: Manual config

Edit your MCP config file and add either:

- **CLI:** `~/.cline/mcp.json`
- **IDE extensions:**
  1. In the Cline panel, click the **MCP Servers** icon (stacked server icon in the top toolbar).
  2. Open the **Configure** tab.
  3. Click **Configure MCP Servers** (button near the bottom).
  4. This opens the MCP settings JSON used by the extension; add/update entries under `mcpServers`.
  - If you’re adding a hosted endpoint (instead of editing JSON directly), use the **Remote Servers** tab:
    1. Enter **Server Name** (any unique label).
    2. Enter **Server URL** (full endpoint URL).
    3. Choose **Transport Type**:
       - **Streamable HTTP** (recommended)
       - **SSE (Legacy)**
    4. Click **Add Server**.
  - Server config shape:
    - **Local (STDIO)** server using `command` + `args`
    - **Remote (HTTP/SSE)** server using `url`

### [​](#cli-mcp-wizard) CLI MCP wizard

From CLI, run:

```
cline mcp
```

The wizard supports:

| Action | Description |
| --- | --- |
| List servers | Show configured servers and enabled/disabled status |
| Add server | Create a new MCP server entry |
| Edit server | Modify an existing server |
| Enable/Disable | Toggle a server without deleting it |
| Delete server | Remove a server permanently |

When adding a server, the CLI prompts for server name, transport type, command/args (for stdio), or URL/headers (for remote transports).

## [​](#configuration-examples) Configuration examples

### [​](#local-server-stdio) Local server (STDIO)

```
{
  "mcpServers": {
    "local-server": {
      "command": "node",
      "args": ["/path/to/server.js"],
      "env": {
        "API_KEY": "your_api_key"
      },
      "disabled": false,
      "autoApprove": []
    }
  }
}
```

### [​](#remote-server-http/sse) Remote server (HTTP/SSE)

```
{
  "mcpServers": {
    "remote-server": {
      "url": "https://example.com/mcp",
      "headers": {
        "Authorization": "Bearer your-token"
      },
      "disabled": false,
      "autoApprove": []
    }
  }
}
```

## [​](#transport-types) Transport types

- **STDIO**: local process, lower latency, simpler local setup
- **Remote HTTP/SSE**: hosted endpoint, centralized deployment, supports multi-client usage

Use STDIO for local tools and remote transport for shared hosted services.

## [​](#managing-servers) Managing servers

In MCP settings you can:

- Enable/disable servers
- Restart unresponsive servers
- Set request timeouts
- Remove servers

## [​](#security-basics) Security basics

- Only install servers you trust
- Store secrets in environment variables
- Limit `autoApprove` to safe tools
- Review tool calls before approval

## [​](#troubleshooting) Troubleshooting

| Issue | Fix |
| --- | --- |
| Server won’t connect | Verify command/URL, server process status, and port |
| Missing tools | Confirm server started successfully and tools are exposed |
| Auth errors | Re-check API keys/tokens and required headers |
| Timeout errors | Increase MCP timeout and test server response directly |

## [​](#cli) CLI

MCP also works in Cline CLI. Configure servers in CLI MCP settings and use the same server definitions.
You can also list servers non-interactively:

```
cline config mcp
cline config mcp --json
```

Was this page helpful?

YesNo

[Plugins](/customization/plugins)[Hooks](/customization/hooks)

⌘I

---

## Mcp Overview

*Source: [https://docs.cline.bot/mcp/mcp-overview](https://docs.cline.bot/mcp/mcp-overview)*

MCP (Model Context Protocol) lets Cline use external tools and data sources through MCP servers.

## [​](#what-mcp-gives-you) What MCP gives you

- Connect Cline to external APIs and services
- Add custom tools beyond built-in Cline tools
- Use either local servers or remote hosted servers

## [​](#quick-start) Quick start

1. Open **MCP Servers** in Cline
2. Add a server (from Marketplace or manually)
3. Configure credentials/environment variables
4. Verify tools appear and test one tool call

## [​](#add-servers) Add servers

### [​](#option-1-marketplace) Option 1: Marketplace

Use Cline’s MCP Marketplace for one-click install when available.

1. In the Cline panel, click the MCP Servers icon (stacked server icon in the top toolbar).
2. Open the Marketplace tab.

### [​](#option-2-manual-config) Option 2: Manual config

Edit your MCP config file and add either:

- **CLI:** `~/.cline/mcp.json`
- **IDE extensions:**
  1. In the Cline panel, click the **MCP Servers** icon (stacked server icon in the top toolbar).
  2. Open the **Configure** tab.
  3. Click **Configure MCP Servers** (button near the bottom).
  4. This opens the MCP settings JSON used by the extension; add/update entries under `mcpServers`.
  - If you’re adding a hosted endpoint (instead of editing JSON directly), use the **Remote Servers** tab:
    1. Enter **Server Name** (any unique label).
    2. Enter **Server URL** (full endpoint URL).
    3. Choose **Transport Type**:
       - **Streamable HTTP** (recommended)
       - **SSE (Legacy)**
    4. Click **Add Server**.
  - Server config shape:
    - **Local (STDIO)** server using `command` + `args`
    - **Remote (HTTP/SSE)** server using `url`

### [​](#cli-mcp-wizard) CLI MCP wizard

From CLI, run:

```
cline mcp
```

The wizard supports:

| Action | Description |
| --- | --- |
| List servers | Show configured servers and enabled/disabled status |
| Add server | Create a new MCP server entry |
| Edit server | Modify an existing server |
| Enable/Disable | Toggle a server without deleting it |
| Delete server | Remove a server permanently |

When adding a server, the CLI prompts for server name, transport type, command/args (for stdio), or URL/headers (for remote transports).

## [​](#configuration-examples) Configuration examples

### [​](#local-server-stdio) Local server (STDIO)

```
{
  "mcpServers": {
    "local-server": {
      "command": "node",
      "args": ["/path/to/server.js"],
      "env": {
        "API_KEY": "your_api_key"
      },
      "disabled": false,
      "autoApprove": []
    }
  }
}
```

### [​](#remote-server-http/sse) Remote server (HTTP/SSE)

```
{
  "mcpServers": {
    "remote-server": {
      "url": "https://example.com/mcp",
      "headers": {
        "Authorization": "Bearer your-token"
      },
      "disabled": false,
      "autoApprove": []
    }
  }
}
```

## [​](#transport-types) Transport types

- **STDIO**: local process, lower latency, simpler local setup
- **Remote HTTP/SSE**: hosted endpoint, centralized deployment, supports multi-client usage

Use STDIO for local tools and remote transport for shared hosted services.

## [​](#managing-servers) Managing servers

In MCP settings you can:

- Enable/disable servers
- Restart unresponsive servers
- Set request timeouts
- Remove servers

## [​](#security-basics) Security basics

- Only install servers you trust
- Store secrets in environment variables
- Limit `autoApprove` to safe tools
- Review tool calls before approval

## [​](#troubleshooting) Troubleshooting

| Issue | Fix |
| --- | --- |
| Server won’t connect | Verify command/URL, server process status, and port |
| Missing tools | Confirm server started successfully and tools are exposed |
| Auth errors | Re-check API keys/tokens and required headers |
| Timeout errors | Increase MCP timeout and test server response directly |

## [​](#cli) CLI

MCP also works in Cline CLI. Configure servers in CLI MCP settings and use the same server definitions.
You can also list servers non-interactively:

```
cline config mcp
cline config mcp --json
```

Was this page helpful?

YesNo

[Plugins](/customization/plugins)[Hooks](/customization/hooks)

⌘I

---

## Anthropic

*Source: [https://docs.cline.bot/provider-config/anthropic](https://docs.cline.bot/provider-config/anthropic)*

**Website:** <https://www.anthropic.com/>

## [​](#choose-an-anthropic-path) Choose an Anthropic Path

- **[Anthropic API (key-based)](#getting-an-api-key):** Use an Anthropic API key.
- **[Claude Code (subscription-based)](#claude-code-subscription):** Use your Claude Max/Pro subscription through the Claude CLI.

## [​](#anthropic-api-key-based) Anthropic API (key-based)

### [​](#getting-an-api-key) Getting an API Key

1. **Sign Up/Sign In:** Go to the [Anthropic Console](https://console.anthropic.com/). Create an account or sign in.
2. **Navigate to API Keys:** Go to the [API keys](https://console.anthropic.com/settings/keys) section.
3. **Create a Key:** Click “Create Key”. Give your key a descriptive name (e.g., “Cline”).
4. **Copy the Key:** **Important:** Copy the API key *immediately*. You will not be able to see it again. Store it securely.

### [​](#configuration-in-cline) Configuration in Cline

> See [Authorization & Model Selection](/getting-started/authorizing-with-cline#menu).

1. **Open Cline Settings:** Click the settings icon (⚙️) in the Cline panel.
2. **Select Provider:** Choose “Anthropic” from the “API Provider” dropdown.
3. **Enter API Key:** Paste your Anthropic API key into the “Anthropic API Key” field.
4. **Select Model:** Choose your desired Claude model from the “Model” dropdown.
5. **(Optional) Custom Base URL:** If you need to use a custom base URL for the Anthropic API, check “Use custom base URL” and enter the URL. Most users won’t need to adjust this setting.

## [​](#claude-code-subscription) Claude Code (Subscription)

Use this path if you already have Claude Max/Pro and want to use subscription-based access in Cline.

1. Install and authenticate Claude CLI via Anthropic docs: [Claude Code setup](https://docs.anthropic.com/en/docs/claude-code/setup).
2. In Cline settings, select **Claude Code** as provider.
3. Set the Claude CLI path (usually `claude` if available in PATH).

Find Claude path:

- macOS / Linux / WSL / Git Bash: `which claude`
- Windows Command Prompt: `where claude`

Notes:

- Uses your Claude subscription limits instead of API token billing.
- Responses may not stream token-by-token.
- Image uploads and prompt caching are limited in this mode.

### [​](#extended-thinking) Extended Thinking

Anthropic models offer an “Extended Thinking” feature, designed to give them enhanced reasoning capabilities for complex tasks. This feature allows the model to output its step-by-step thought process before delivering a final answer, providing transparency and enabling more thorough analysis for challenging prompts.
When extended thinking is in Cline, the model generates `thinking` content blocks that detail its internal reasoning. These insights are then incorporated into its final response.
Cline users can leverage this by checking the `Enable Extended Thinking` box below the model selection menu after selecting a Claude Model from any provider.
**Key Aspects of Extended Thinking:**

- **Summarized Thinking (Claude 3.7+):** For Claude 3.7+ models, the API returns a summary of the full thinking process to balance insight with efficiency and prevent misuse. You are billed for the full thinking tokens, not just the summary.
- **Streaming:** Extended thinking responses, including the `thinking` blocks, can be streamed.
- **Tool Use & Prompt Caching:** Extended thinking interacts with tool use (requiring thinking blocks to be passed back) and prompt caching (with specific behaviors around cache invalidation and context).

For comprehensive details on how extended thinking works, including API examples, interaction with tool use, prompt caching, and pricing, please refer to the [official Anthropic documentation on Extended Thinking](https://docs.anthropic.com/en/docs/build-with-claude/extended-thinking).

### [​](#tips-and-notes) Tips and Notes

- **Prompt Caching:** Claude 3 models support [prompt caching](https://docs.anthropic.com/en/docs/build-with-claude/prompt-caching), which can significantly reduce costs and latency for repeated prompts.
- **Context Window:** Claude models have large context windows (200,000 tokens), allowing you to include a significant amount of code and context in your prompts.
- **Pricing:** Refer to the [Anthropic Pricing](https://www.anthropic.com/pricing) page for the latest pricing information.
- **Rate Limits:** Anthropic has strict rate limits based on [usage tiers](https://docs.anthropic.com/en/api/rate-limits#requirements-to-advance-tier). If you’re repeatedly hitting rate limits, consider contacting Anthropic sales or accessing Claude through a different provider like [OpenRouter](/provider-config/openrouter) or [Requesty](/provider-config/other-30-plus-providers#requesty).

Was this page helpful?

YesNo

[Alibaba Qwen](/provider-config/qwen)[API Key](/provider-config/aws-bedrock/api-key)

⌘I

---

## Api Key

*Source: [https://docs.cline.bot/provider-config/aws-bedrock/api-key](https://docs.cline.bot/provider-config/aws-bedrock/api-key)*

### [​](#overview) Overview

- **AWS Bedrock:** A fully managed service that offers access to leading generative AI models (e.g., Anthropic Claude, Amazon Nova) through AWS.
  [Learn more about AWS Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html).
- **Cline:** A VS Code extension that acts as a coding assistant by integrating with AI models-empowering developers to generate code, debug, and analyze data.
- **Developer Focus:** This guide is tailored for individual developers that want to enable access to frontier models via AWS Bedrock with a simplified setup using API Keys.

---

### [​](#step-1-prepare-your-aws-environment) Step 1: Prepare Your AWS Environment

#### [​](#1-1-individual-user-setup-create-a-bedrock-api-key) 1.1 Individual user setup - Create a Bedrock API Key

For more detailed instructions check the [documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/api-keys.html).

1. **Sign in to the AWS Management Console:**
   [AWS Console](https://aws.amazon.com/console/)
2. **Access Bedrock Console:**
   - [Bedrock Console](https://console.aws.amazon.com/bedrock)
   - Create a new Long Lived API Key. This API Key will have by default the `AmazonBedrockLimitedAccess` IAM policy
     [View AmazonBedrockLimitedAccess Policy Details](https://docs.aws.amazon.com/bedrock/latest/userguide/security-iam.html)

#### [​](#1-2-create-or-modify-the-policy) 1.2 Create or Modify the Policy

To ensure Cline can interact with AWS Bedrock, your IAM user or role needs specific permissions. While the `AmazonBedrockLimitedAccess` managed policy provides comprehensive access, for a more restricted and secure setup adhering to the principle of least privilege, the following minimal permissions are sufficient for Cline’s core model invocation functionality:

- `bedrock:InvokeModel`
- `bedrock:InvokeModelWithResponseStream`
- `bedrock:CallWithBearerToken`

You can create a custom IAM policy with these permissions and attach it to your IAM user or role.

1. In the AWS IAM console, create a new policy.
2. Use the JSON editor to add the following policy document:

   ```
   {
   	"Version": "2012-10-17",
   	"Statement": [
   		{
   			"Effect": "Allow",
   			"Action": ["bedrock:InvokeModel", "bedrock:InvokeModelWithResponseStream", "bedrock:CallWithBearerToken"],
   			"Resource": "*" // For enhanced security, scope this to specific model ARNs if possible.
   		}
   	]
   }
   ```
3. Name the policy (e.g., `ClineBedrockInvokeAccess`) and attach it to the IAM user associated with the key you created. The IAM user and the API key have the same prefix.

**Important Considerations:**

- **Model Listing in Cline:** The minimal permissions (`bedrock:InvokeModel`, `bedrock:InvokeModelWithResponseStream`) are sufficient for Cline to *use* a model if you specify the model ID directly in Cline’s settings. If you rely on Cline to dynamically list available Bedrock models, you might need additional permissions like `bedrock:ListFoundationModels`.
- **AWS Marketplace Subscriptions:** For third-party models (e.g., Anthropic Claude), the **`AmazonBedrockLimitedAccess`** policy grants you the necessary permissions to subscribe via the AWS Marketplace. There is no explicit access to be enabled. For Anthropic models you are still required to submit a First Time Use (FTU) form via the Console. If you get the following message in the Cline chat `[ERROR] Failed to process response: Model use case details have not been submitted for this account. Fill out the Anthropic use case details form before using the model.` then open the [Playground in the AWS Bedrock Console](https://console.aws.amazon.com/bedrock/home?#/text-generation-playground), select any Anthropic model and fill in the form (you might need to send a prompt first)

---

### [​](#step-2-verify-regional-access) Step 2: Verify Regional Access

#### [​](#2-1-choose-and-confirm-a-region) 2.1 Choose and Confirm a Region

1. **Select a Region:**
   AWS Bedrock is available in multiple regions (e.g., US East, Europe, Asia Pacific). Choose the region that meets your latency and compliance needs.
   [AWS Global Infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/)
2. **Verify Model Access:**
   - **Note:** Some models are only accessible via an [Inference Profile](https://docs.aws.amazon.com/bedrock/latest/userguide/inference-profiles-support.html). In such case check the box “Cross Region Inference”.

---

### [​](#step-3-configure-the-cline-vs-code-extension) Step 3: Configure the Cline VS Code Extension

#### [​](#3-1-install-and-open-cline) 3.1 Install and Open Cline

1. **Install VS Code:**
   Download from the [VS Code website](https://code.visualstudio.com/).
2. **Install the Cline Extension:**
   - Open VS Code.
   - Go to the Extensions Marketplace (`Ctrl+Shift+X` or `Cmd+Shift+X`).
   - Search for **Cline** and install it.

#### [​](#3-2-configure-cline-settings) 3.2 Configure Cline Settings

1. **Open Cline Settings:**
   - Click on the settings ⚙️ to select your API Provider.
2. **Select AWS Bedrock as the API Provider:**
   - From the API Provider dropdown, choose **AWS Bedrock**.
3. **Enter Your AWS API Key:**
   - Input your **API Key**
   - Specify the correct **AWS Region** (e.g., `us-east-1` or your enterprise-approved region).
4. **Select a Provider Model:**
5. **Save and Test:**
   - Click **Done/Save** to apply your settings.
   - Test the integration by sending a simple prompt (e.g., “Generate a Python function to check if a number is prime.”).

---

### [​](#step-4-security-monitoring-and-best-practices) Step 4: Security, Monitoring, and Best Practices

1. **Secure Access:**
   - Prefer AWS SSO/federated roles over long-lived API Key when possible.
   - [AWS IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)
2. **Enhance Network Security:**
   - Consider setting up [AWS PrivateLink](https://docs.aws.amazon.com/vpc/latest/userguide/endpoint-services-overview.html) to securely connect to Bedrock.
3. **Monitor and Log Activity:**
   - Enable AWS CloudTrail to log Bedrock API calls.
   - Use CloudWatch to monitor metrics like invocation count, latency, and token usage.
   - Set up alerts for abnormal activity.
4. **Handle Errors and Manage Costs:**
   - Implement exponential backoff for throttling errors.
   - Use AWS Cost Explorer and set billing alerts to track usage.
     [AWS Cost Management](https://docs.aws.amazon.com/cost-management/latest/userguide/what-is-aws-cost-management.html)
5. **Regular Audits and Compliance:**
   - Periodically review IAM roles and CloudTrail logs.
   - Follow internal data privacy and governance policies.

---

Was this page helpful?

YesNo

[Anthropic / Claude Code](/provider-config/anthropic)[IAM Credentials](/provider-config/aws-bedrock/iam-credentials)

⌘I

---

## Cli Profile

*Source: [https://docs.cline.bot/provider-config/aws-bedrock/cli-profile](https://docs.cline.bot/provider-config/aws-bedrock/cli-profile)*

### [​](#overview) Overview

Cline offers the option of utilizing AWS credentials or AWS profiles to access AWS Bedrock services. SSO/Federated roles are suggested over Legacy IAM configuration; this guide describes how to configure your environment so that Cline uses SSO roles for authentication.


---

### [​](#configuration-steps) Configuration Steps

1. Install the [latest version](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html) of AWS CLI
   - Follow the AWS docs to install your OS-specific version of AWS CLI
2. [Configure IAM authentication](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-sso.html) with the AWS CLI
   - If you do not already have AWS access through the IAM Identity Center, follow the [IAM User Guide](https://docs.aws.amazon.com/singlesignon/latest/userguide/getting-started.html) to set up IAM users and roles. Ensure you have a `PowerUserAccess` role.
   - If you have access to AWS through your employer, open your AWS access portal and find the appropriate account. Ensure you have `PowerUserAccess` permissions.
   - Open the `Access keys` link and note the `SSO start URL` and `SSO region`, which are needed in the next step
3. Continue configuring your profile using [the `aws configure sso` CLI wizard](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-sso.html#cli-configure-sso-configure)
   - Once configured, use the following command to authenticate the AWS CLI: `aws sso login --profile <AWS-profile-name>`
   - Note which profile name you attach to your AWS account, this is needed to configure Cline in the following steps
4. If you haven’t already done so, install VSCode and the Cline extension. Consult the [Getting Started](/getting-started/installing-cline) page for guidance.
5. Open the Cline extension, then click on the settings button ⚙️ to select your API Provider.
   - From the API Provider dropdown, select AWS Bedrock
   - Select the AWS Profile radio button, then enter the AWS Profile Name from step 3
   - Select your AWS Region from the dropdown menu
   - Selecting the cross-region inference checkbox is required for some models

Was this page helpful?

YesNo

[IAM Credentials](/provider-config/aws-bedrock/iam-credentials)[DeepSeek](/provider-config/deepseek)

⌘I

---

## Iam Credentials

*Source: [https://docs.cline.bot/provider-config/aws-bedrock/iam-credentials](https://docs.cline.bot/provider-config/aws-bedrock/iam-credentials)*

### [​](#overview) Overview

- **AWS Bedrock:** A fully managed service that offers access to leading generative AI models (e.g., Anthropic Claude, Amazon Nova) through AWS.
  [Learn more about AWS Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html).
- **Cline:** A VS Code extension that acts as a coding assistant by integrating with AI models-empowering developers to generate code, debug, and analyze data.
- **Enterprise Focus:** This guide is tailored for organizations with established AWS environments (using IAM roles, AWS SSO, AWS Organizations, etc.) to ensure secure and compliant usage.

---

### [​](#step-1-prepare-your-aws-environment) Step 1: Prepare Your AWS Environment

#### [​](#1-1-create-or-use-an-iam-role/user) 1.1 Create or Use an IAM Role/User

1. **Sign in to the AWS Management Console:**
   [AWS Console](https://aws.amazon.com/console/)
2. **Access IAM:**
   - Search for **IAM (Identity and Access Management)** in the AWS Console.
   - Either create a new IAM user or use your enterprise’s AWS SSO to assume a dedicated role for Bedrock access.
   - [AWS IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)

#### [​](#1-2-attach-the-required-policies) 1.2 Attach the Required Policies

To ensure Cline can interact with AWS Bedrock, your IAM user or role needs specific permissions. While the `AmazonBedrockLimitedAccess` managed policy provides comprehensive access, for a more restricted and secure setup adhering to the principle of least privilege, the following minimal permissions are sufficient for Cline’s core model invocation functionality:

- `bedrock:InvokeModel`
- `bedrock:InvokeModelWithResponseStream`

You can create a custom IAM policy with these permissions and attach it to your IAM user or role.
**Option 1: Minimal Permissions (Recommended for Production & Least Privilege)**

1. In the AWS IAM console, create a new policy.
2. Use the JSON editor to add the following policy document:

   ```
   {
   	"Version": "2012-10-17",
   	"Statement": [
   		{
   			"Effect": "Allow",
   			"Action": ["bedrock:InvokeModel", "bedrock:InvokeModelWithResponseStream"],
   			"Resource": "*" // For enhanced security, scope this to specific model ARNs if possible.
   		}
   	]
   }
   ```
3. Name the policy (e.g., `ClineBedrockInvokeAccess`) and attach it to your IAM user or role.

**Option 2: Using a Managed Policy (Simpler Initial Setup)**

- Alternatively, you can attach the AWS managed policy **`AmazonBedrockLimitedAccess`**. This grants broader permissions, including the ability to list models, manage provisioning, and other Bedrock features. This might be simpler for initial setup or if you require these wider capabilities.
  [View AmazonBedrockLimitedAccess Policy Details](https://docs.aws.amazon.com/bedrock/latest/userguide/security-iam.html)

**Important Considerations:**

- **Model Listing in Cline:** The minimal permissions (`bedrock:InvokeModel`, `bedrock:InvokeModelWithResponseStream`) are sufficient for Cline to *use* a model if you specify the model ID directly in Cline’s settings. If you rely on Cline to dynamically list available Bedrock models, you might need additional permissions like `bedrock:ListFoundationModels`.
- **AWS Marketplace Subscriptions:** For third-party models (e.g., Anthropic Claude), ensure you have active AWS Marketplace subscriptions. This is typically managed in the AWS Bedrock console under “Model access” and might require `aws-marketplace:Subscribe` permissions if not already handled.
- *Enterprise Tip:* Always apply least-privilege practices. Where possible, scope resource ARNs in your IAM policies to specific models or regions. Utilize [Service Control Policies (SCPs)](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_scps.html) for overarching governance in AWS Organizations.

---

### [​](#step-2-verify-regional-access) Step 2: Verify Regional Access

#### [​](#2-1-choose-and-confirm-a-region) 2.1 Choose and Confirm a Region

1. **Select a Region:**
   AWS Bedrock is available in multiple regions (e.g., US East, Europe, Asia Pacific). Choose the region that meets your latency and compliance needs.
   [AWS Global Infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/)
2. **Verify Model Access:**
   - In the AWS Bedrock console, confirm that the models your team requires (e.g., Anthropic Claude, Amazon Nova) are marked as “Access granted.”
   - **Note:** Some advanced models might require an [Inference Profile](https://docs.aws.amazon.com/bedrock/latest/userguide/inference-profiles-support.html) if not available on-demand.

#### [​](#2-2-set-up-aws-marketplace-subscriptions-if-needed) 2.2 Set Up AWS Marketplace Subscriptions (if needed)

1. **Subscribe to Third-Party Models:**
   - Navigate to the AWS Bedrock console and locate the model subscription section.
   - For models from third-party providers (e.g., Anthropic), accept the terms to subscribe.
   - [AWS Marketplace](https://aws.amazon.com/marketplace/)
2. **Enterprise Tip:**
   - Model subscriptions are often managed centrally. Confirm with your cloud team if a standard subscription process is in place.

---

### [​](#step-3-configure-the-cline-vs-code-extension) Step 3: Configure the Cline VS Code Extension

#### [​](#3-1-install-and-open-cline) 3.1 Install and Open Cline

1. **Install VS Code:**
   Download from the [VS Code website](https://code.visualstudio.com/).
2. **Install the Cline Extension:**
   - Open VS Code.
   - Go to the Extensions Marketplace (`Ctrl+Shift+X` or `Cmd+Shift+X`).
   - Search for **Cline** and install it.

#### [​](#3-2-configure-cline-settings) 3.2 Configure Cline Settings

1. **Open Cline Settings:**
   - Click on the settings ⚙️ to select your API Provider.
2. **Select AWS Bedrock as the API Provider:**
   - From the API Provider dropdown, choose **AWS Bedrock**.
3. **Enter Your AWS Credentials:**
   - Input your **Access Key** and **Secret Key** (or use temporary credentials if using AWS SSO).
   - Specify the correct **AWS Region** (e.g., `us-east-1` or your enterprise-approved region).
4. **Select a Provider Model:**
5. **Save and Test:**
   - Click **Done/Save** to apply your settings.
   - Test the integration by sending a simple prompt (e.g., “Generate a Python function to check if a number is prime.”).

---

### [​](#step-4-security-monitoring-and-best-practices) Step 4: Security, Monitoring, and Best Practices

1. **Secure Access:**
   - Prefer AWS SSO/federated roles over long-lived IAM credentials.
   - [AWS IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)
2. **Enhance Network Security:**
   - Consider setting up [AWS PrivateLink](https://docs.aws.amazon.com/vpc/latest/userguide/endpoint-services-overview.html) to securely connect to Bedrock.
3. **Monitor and Log Activity:**
   - Enable AWS CloudTrail to log Bedrock API calls.
   - Use CloudWatch to monitor metrics like invocation count, latency, and token usage.
   - Set up alerts for abnormal activity.
4. **Handle Errors and Manage Costs:**
   - Implement exponential backoff for throttling errors.
   - Use AWS Cost Explorer and set billing alerts to track usage.
     [AWS Cost Management](https://docs.aws.amazon.com/cost-management/latest/userguide/what-is-aws-cost-management.html)
5. **Regular Audits and Compliance:**
   - Periodically review IAM roles and CloudTrail logs.
   - Follow internal data privacy and governance policies.

---

Was this page helpful?

YesNo

[API Key](/provider-config/aws-bedrock/api-key)[CLI Profile (SSO)](/provider-config/aws-bedrock/cli-profile)

⌘I

---

## Deepseek

*Source: [https://docs.cline.bot/provider-config/deepseek](https://docs.cline.bot/provider-config/deepseek)*

**Website:** <https://platform.deepseek.com/>

### [​](#get-api-credentials) Get API Credentials

1. **Sign Up/Sign In:** Go to the [DeepSeek Platform](https://platform.deepseek.com/). Create an account or sign in.
2. **Navigate to API Keys:** Find your API keys in the [API keys](https://platform.deepseek.com/api_keys) section of the platform.
3. **Create a Key:** Click “Create new API key”. Give your key a descriptive name (e.g., “Cline”).
4. **Copy the Key:** **Important:** Copy the API key *immediately*. You will not be able to see it again. Store it securely.

### [​](#configuration-in-cline) Configuration in Cline

> See [Authorization & Model Selection](/getting-started/authorizing-with-cline#menu).

1. **Open Cline Settings:** Click the ⚙️ icon in the Cline panel.
2. **Select Provider:** Choose “DeepSeek” from the “API Provider” dropdown.
3. **Enter API Key:** Paste your DeepSeek API key into the “DeepSeek API Key” field.
4. **Select Provider Model:** Choose your desired model from the “Model” dropdown.

### [​](#tips-and-notes) Tips and Notes

Was this page helpful?

YesNo

[CLI Profile (SSO)](/provider-config/aws-bedrock/cli-profile)[Google Gemini](/provider-config/google-gemini)

⌘I

---

## Google Gemini

*Source: [https://docs.cline.bot/provider-config/google-gemini](https://docs.cline.bot/provider-config/google-gemini)*

Google Gemini is Google’s family of multimodal AI models, offering some of the largest context windows available and strong performance across coding, reasoning, and document analysis tasks.
**Website:** <https://ai.google.dev/>

### [​](#get-api-credentials) Get API Credentials

1. **Sign Up/Sign In:** Go to [Google AI Studio](https://aistudio.google.com/). Sign in with your Google account.
2. **Get API Key:** Navigate to [aistudio.google.com/apikey](https://aistudio.google.com/apikey).
3. **Create a Key:** Click “Create API Key” and select or create a Google Cloud project.
4. **Copy the Key:** Copy the API key immediately and store it securely.

### [​](#configuration-in-cline) Configuration in Cline

> See [Authorization & Model Selection](/getting-started/authorizing-with-cline#menu).

1. **Open Cline Settings:** Click the settings icon (⚙️) in the Cline panel.
2. **Select Provider:** Choose “Google Gemini” from the “API Provider” dropdown.
3. **Enter API Key:** Paste your Google AI API key into the “Gemini API Key” field.
4. **Select Provider Model:** Choose your desired model from the “Model” dropdown.

### [​](#tips-and-notes) Tips and Notes

- **Pricing:** Refer to the [Google AI pricing page](https://ai.google.dev/gemini-api/docs/models/gemini) for the latest information.

Was this page helpful?

YesNo

[DeepSeek](/provider-config/deepseek)[MiniMax](/provider-config/minimax)

⌘I

---

## Minimax

*Source: [https://docs.cline.bot/provider-config/minimax](https://docs.cline.bot/provider-config/minimax)*

MiniMax provides AI models with large context windows and competitive pricing, featuring the MiniMax-M2 series.
**Website:** <https://www.minimax.io/>

### [​](#get-api-credentials) Get API Credentials

1. **Sign Up/Sign In:** Go to the [MiniMax Platform](https://www.minimax.io/platform). Create an account or sign in.
2. **Navigate to API Keys:** Access the API key section.
3. **Create a Key:** Generate a new API key.
4. **Copy the Key:** Copy the API key immediately and store it securely.

### [​](#configuration-in-cline) Configuration in Cline

> See [Authorization & Model Selection](/getting-started/authorizing-with-cline#menu).

1. **Open Cline Settings:** Click the settings icon (⚙️) in the Cline panel.
2. **Select Provider:** Choose “MiniMax” from the “API Provider” dropdown.
3. **Enter API Key:** Paste your MiniMax API key.
4. **Select Provider Model:** Choose your desired model from the “Model” dropdown.

### [​](#tips-and-notes) Tips and Notes

- **Large Context:** All models support 192K token context windows.
- **Reasoning Support:** M2.7 and M2.5 support extended thinking/reasoning for complex tasks.
- **Pricing:** Check the [MiniMax pricing page](https://www.minimax.io/platform/document/pricing) for current rates.

Was this page helpful?

YesNo

[Google Gemini](/provider-config/google-gemini)[OpenAI (Codex)](/provider-config/openai)

⌘I

---

## Openai

*Source: [https://docs.cline.bot/provider-config/openai](https://docs.cline.bot/provider-config/openai)*

Cline supports accessing models directly through the official OpenAI API.

## [​](#choose-an-openai-path) Choose an OpenAI Path

- **[OpenAI API (key-based)](#get-api-credentials):** Use your OpenAI API key.
- **[OpenAI Codex (Subscription OAuth)](#openai-codex-oauth):** Sign in with OpenAI account, using OAI subscriptions (no key management).

**Website:** <https://openai.com/>

## [​](#openai-api-key-based) OpenAI API (key-based)

### [​](#get-api-credentials) Get API Credentials

1. **Sign Up/Sign In:** Visit the [OpenAI Platform](https://platform.openai.com/). You’ll need to create an account or sign in if you already have one.
2. **Navigate to API Keys:** Once logged in, go to the [API keys section](https://platform.openai.com/api-keys) of your account.
3. **Create a Key:** Click on “Create new secret key”. It’s good practice to give your key a descriptive name (e.g., “Cline API Key”).
4. **Copy the Key:** **Crucial:** Copy the generated API key immediately. For security reasons, OpenAI will not show it to you again. Store this key in a safe and secure location.

### [​](#configuration-in-cline) Configuration in Cline

> See [Authorization & Model Selection](/getting-started/authorizing-with-cline#menu).

1. **Open Cline Settings:** Click the settings gear icon (⚙️) in the Cline panel.
2. **Select Provider:** Choose “OpenAI” from the “API Provider” dropdown menu.
3. **Enter API Key:** Paste your OpenAI API key into the “OpenAI API Key” field.
4. **Select Provider Model:** Choose your desired model from the “Model” dropdown list.
5. **(Optional) Base URL:** If you need to use a proxy or a custom base URL for the OpenAI API, you can enter it here. Most users will not need to change this from the default.

### [​](#tips-and-notes) Tips and Notes

- **Pricing:** Be sure to review the [OpenAI Pricing page](https://openai.com/pricing) for detailed information on the costs associated with different models.
- **Azure OpenAI Service:** If you are looking to use the Azure OpenAI service, please note that specific documentation for Azure OpenAI with Cline may be found separately, or you might need to configure it as an OpenAI-compatible endpoint if such functionality is supported by Cline for custom configurations.

## [​](#openai-codex-oauth) OpenAI Codex (OAuth)

1. Open Cline settings.
2. Select **OpenAI Codex** from **API Provider**.
3. Click **Sign in with OpenAI** and complete browser OAuth.
4. Return to Cline and choose a model.

Notes:

- No API key entry required.
- Available models depend on your OpenAI plan.

Was this page helpful?

YesNo

[MiniMax](/provider-config/minimax)[OpenAI Compatible](/provider-config/openai-compatible)

⌘I

---

## Openai Compatible

*Source: [https://docs.cline.bot/provider-config/openai-compatible](https://docs.cline.bot/provider-config/openai-compatible)*

Cline supports a wide range of AI model providers that offer APIs compatible with the OpenAI API standard. This allows you to use models from providers *other than* OpenAI, while still utilizing a familiar API interface. This includes providers such as:

- **Local models** running through tools like Ollama and LM Studio (which are covered in their respective sections).
- **Cloud providers** like Perplexity, Together AI, Anyscale, and many others.
- **Any other provider** that offers an OpenAI-compatible API endpoint.

This document focuses on setting up providers *other than* the official OpenAI API (which has its own [dedicated configuration page](/provider-config/openai)).

### [​](#general-configuration) General Configuration

The key to using an OpenAI-compatible provider with Cline is to configure these main settings:

1. **Base URL:** This is the API endpoint specific to the provider. It will *not* be `https://api.openai.com/v1` (that URL is for the official OpenAI API).
2. **API Key:** This is the secret key you obtain from your chosen provider. (or **Use Azure Identity Authentication**)
3. **Model ID:** This is the specific name or identifier for the model you wish to use.

You’ll find these settings in the Cline settings panel (click the ⚙️ icon):

- **API Provider:** Select “OpenAI Compatible”.
- **Base URL:** Enter the base URL provided by your chosen provider. **This is a crucial step.**
- **API Key:** Enter your API key from the provider.
- **Model:** Choose or enter the model ID.
- **Use Azure Identity Authentication:** Check the box to authenticate with your Azure managed identity (Note that this will not trigger the authentication, it will use the existing one (e.g., “az login”))
- **Model Configuration:** This section allows you to customize advanced parameters for the model, such as:
  - Max Output Tokens
  - Context Window size
  - Image Support capabilities
  - Computer Use (e.g., for models with tool/function calling)
  - Input Price (per token/million tokens)
  - Output Price (per token/million tokens)

**Note:** If you are using a different OpenAI-compatible provider (such as Together AI, Anyscale, etc.), the available model IDs will differ. Always refer to your specific provider’s documentation for their supported model names and any unique configuration details.

### [​](#v0-vercel-sdk-in-cline) v0 (Vercel SDK) in Cline:

- For developers working with v0, their [AI SDK documentation](https://vercel.com/docs/v0/cline) provides valuable insights and examples for integrating various models, many of which are OpenAI-compatible. This can be a helpful resource for understanding how to structure calls and manage configurations when using Cline with services deployed on or integrated with Vercel.
- v0 can be used in Cline with the OpenAI Compatible provider.
- ### [​](#quickstart) Quickstart
- 1. With the OpenAI Compatible provider selected, set the Base URL to <https://api.v0.dev/v1>.
- 2. Paste in your v0 API Key
- 3. Set the Model ID: v0-1.0-md
- 4. Click Verify to confirm the connection.

### [​](#troubleshooting) Troubleshooting

- **“Invalid API Key”:** Double-check that you’ve entered the API key correctly and that it’s for the correct provider.
- **“Model Not Found”:** Ensure you’re using a valid model ID for your chosen provider and that it’s available at the specified Base URL.
- **Connection Errors:** Verify the Base URL is correct, that your provider’s API is accessible from your machine, and that there are no firewall or network issues.
- **Unexpected Results:** If you’re getting unexpected outputs, try a different model or double-check all configuration parameters.

By using an OpenAI-compatible provider, you can leverage the flexibility of Cline with a wider array of AI models. Remember to always consult your provider’s documentation for the most accurate and up-to-date information.

Was this page helpful?

YesNo

[OpenAI (Codex)](/provider-config/openai)[OpenRouter](/provider-config/openrouter)

⌘I

---

## Openrouter

*Source: [https://docs.cline.bot/provider-config/openrouter](https://docs.cline.bot/provider-config/openrouter)*

OpenRouter is an AI platform that provides access to a wide variety of language models from different providers, all through a single API. This can simplify setup and allow you to easily experiment with different models.
**Website:** <https://openrouter.ai/>

### [​](#get-api-credentials) Get API Credentials

1. **Sign Up/Sign In:** Go to the [OpenRouter website](https://openrouter.ai/). Sign in with your Google or GitHub account.
2. **Get an API Key:** Go to the [keys page](https://openrouter.ai/keys). You should see an API key listed. If not, create a new key.
3. **Copy the Key:** Copy the API key.

### [​](#configuration-in-cline) Configuration in Cline

> See [Authorization & Model Selection](/getting-started/authorizing-with-cline#menu).

1. **Open Cline Settings:** Click the settings icon (⚙️) in the Cline panel.
2. **Select Provider:** Choose “OpenRouter” from the “API Provider” dropdown.
3. **Enter API Key:** Paste your OpenRouter API key into the “OpenRouter API Key” field.
4. **Select Provider Model:** Choose your desired model from the “Model” dropdown.
5. **(Optional) Custom Base URL:** If you need to use a custom base URL for the OpenRouter API, check “Use custom base URL” and enter the URL. Leave this blank for most users.

### [​](#tips-and-notes) Tips and Notes

- **Pricing:** OpenRouter charges based on the underlying model’s pricing. See the [OpenRouter Models page](https://openrouter.ai/models) for details.
  - OpenRouter passes caching requests to underlying models that support it. Check the [OpenRouter Models page](https://openrouter.ai/models) to see which models offer caching.
  - For most models, caching should activate automatically if supported by the model itself (similar to how Requesty works).
  - **Exception for Gemini Models via OpenRouter:** Due to potential response delays sometimes observed with Google’s caching mechanism when accessed via OpenRouter, a manual activation step is required *specifically for Gemini models*.
  - If using a **Gemini model** via OpenRouter, you **must manually check** the “Enable Prompt Caching” box in the provider settings to activate caching for that model. This checkbox serves as a temporary workaround. For non-Gemini models on OpenRouter, this checkbox is not necessary for caching.

Was this page helpful?

YesNo

[OpenAI Compatible](/provider-config/openai-compatible)[Z AI (Zhipu AI)](/provider-config/zai)

⌘I

---

## Other 30 Plus Providers

*Source: [https://docs.cline.bot/provider-config/other-30-plus-providers](https://docs.cline.bot/provider-config/other-30-plus-providers)*

Use this page for providers that follow the same setup pattern.

## [​](#menu) Menu

- [Shared Configuration in Cline](#shared-configuration-in-cline)
- [Providers](#providers)
  - [AIHubMix](#aihubmix)
  - [AskSage](#asksage)
  - [Baseten](#baseten)
  - [Cerebras](#cerebras)
  - [Dify.ai](#difyai)
  - [Doubao](#doubao)
  - [Fireworks AI](#fireworks-ai)
  - [GCP Vertex AI](#gcp-vertex-ai)
  - [Groq](#groq)
  - [Hicap](#hicap)
  - [Huawei Cloud MaaS](#huawei-cloud-maas)
  - [Hugging Face](#hugging-face)
  - [Mistral](#mistral)
  - [Moonshot](#moonshot)
  - [Nebius AI Studio](#nebius-ai-studio)
  - [Nous Research](#nous-research)
  - [Oracle Code Assist](#oracle-code-assist)
  - [Qwen Code](#qwen-code)
  - [Requesty](#requesty)
  - [SambaNova](#sambanova)
  - [SAP AI Core](#sap-ai-core)
  - [Together](#together)
  - [Vercel AI Gateway](#vercel-ai-gateway)
  - [VS Code Language Model API](#vs-code-language-model-api)
  - [xAI (Grok)](#xai-grok)

## [​](#shared-configuration-in-cline) Shared Configuration in Cline

1. Open Cline settings (⚙️).
2. Select your provider from **API Provider**.
3. Paste your API key/token in the matching credential field.
4. Choose a model from **Model**.

For the full auth flow (IDE + CLI), see [Authorization & Model Selection](/getting-started/authorizing-with-cline#menu).

## [​](#providers) Providers

### [​](#aihubmix) AIHubMix

AIHubMix is an OpenAI-compatible model aggregator that gives you one API surface for multiple model backends.
**Website:** <https://aihubmix.com/>

#### [​](#basic-setup) Basic Setup

1. Create/sign in to your AIHubMix account.
2. Generate an API key from the dashboard.
3. In Cline, choose **AIHubMix** and paste the key.

### [​](#asksage) AskSage

AskSage is focused on enterprise and government AI access with compliance-oriented controls.
**Website:** <https://www.asksage.ai/>

#### [​](#basic-setup-2) Basic Setup

1. Sign in to AskSage and create API credentials.
2. Confirm your workspace/organization has model access enabled.
3. In Cline, select **AskSage** and enter the key.

### [​](#baseten) Baseten

Baseten provides hosted model APIs and deployment infrastructure for production inference.
**Website:** <https://www.baseten.co/products/model-apis/>

#### [​](#basic-setup-3) Basic Setup

1. Create a Baseten account and open the API keys section.
2. Generate an API key with the required permissions.
3. In Cline, choose **Baseten** and paste the key.

### [​](#cerebras) Cerebras

Cerebras offers very fast hosted inference for supported model families.
**Website:** <https://cloud.cerebras.ai/>

#### [​](#basic-setup-4) Basic Setup

1. Sign in to Cerebras Cloud.
2. Create or retrieve your API key.
3. In Cline, select **Cerebras** and enter the key.

### [​](#dify-ai) Dify.ai

Dify.ai is a workflow-centric AI platform with app and pipeline capabilities.
**Website:** <https://dify.ai/>

#### [​](#basic-setup-5) Basic Setup

1. Create a Dify workspace and API credential.
2. Confirm your Dify endpoint/provider settings are active.
3. In Cline, select **Dify.ai** and paste your key.

### [​](#doubao) Doubao

Doubao is ByteDance’s model family, typically accessed through Volcengine services.
**Website:** <https://www.volcengine.com/>

#### [​](#basic-setup-6) Basic Setup

1. Sign in to Volcengine and enable model access.
2. Generate API credentials for Doubao endpoints.
3. In Cline, select **Doubao** and paste credentials.

### [​](#fireworks-ai) Fireworks AI

Fireworks AI provides hosted inference for open models and performance-focused deployment.
**Website:** <https://fireworks.ai/>

#### [​](#basic-setup-7) Basic Setup

1. Create a Fireworks account.
2. Generate an API key in your project/account settings.
3. In Cline, choose **Fireworks AI** and enter the key.

### [​](#gcp-vertex-ai) GCP Vertex AI

Vertex AI is Google Cloud’s enterprise model platform with IAM and project-level governance.
**Website:** <https://cloud.google.com/vertex-ai>

#### [​](#basic-setup-8) Basic Setup

1. Set up a GCP project with Vertex AI enabled.
2. Configure authentication (service account or application default credentials).
3. In Cline, select **GCP Vertex AI** and provide required config values.

### [​](#groq) Groq

Groq is a low-latency inference provider for supported model families.
**Website:** <https://groq.com/>

#### [​](#basic-setup-9) Basic Setup

1. Sign in to Groq Console.
2. Create an API key.
3. In Cline, select **Groq** and paste the key.

### [​](#hicap) Hicap

Hicap provides OpenAI-compatible access with multimodal support.
**Website:** <https://hicap.ai>

#### [​](#basic-setup-10) Basic Setup

1. Create your Hicap account.
2. Generate an API key/token.
3. In Cline, choose **Hicap** and enter the credential.

### [​](#huawei-cloud-maas) Huawei Cloud MaaS

Huawei Cloud MaaS provides model-as-a-service access within Huawei Cloud.
**Website:** <https://www.huaweicloud.com/>

#### [​](#basic-setup-11) Basic Setup

1. Sign in to Huawei Cloud and open MaaS services.
2. Create API credentials for model access.
3. In Cline, select **Huawei Cloud MaaS** and add credentials.

### [​](#hugging-face) Hugging Face

Hugging Face provides hosted inference access for open-source models.
**Website:** <https://huggingface.co/>

#### [​](#basic-setup-12) Basic Setup

1. Sign in to Hugging Face.
2. Create an access token with inference permissions.
3. In Cline, select **Hugging Face** and paste the token.

### [​](#mistral) Mistral

Mistral provides direct API access to its model lineup.
**Website:** <https://mistral.ai/>

#### [​](#basic-setup-13) Basic Setup

1. Create/sign in to Mistral platform account.
2. Generate an API key.
3. In Cline, choose **Mistral** and paste the key.

### [​](#moonshot) Moonshot

Moonshot provides API access to Kimi model families.
**Website:** <https://platform.moonshot.ai/>

#### [​](#basic-setup-14) Basic Setup

1. Sign in to Moonshot platform.
2. Create an API key in account settings.
3. In Cline, select **Moonshot** and enter the key.

### [​](#nebius-ai-studio) Nebius AI Studio

Nebius AI Studio offers managed hosted model APIs.
**Website:** <https://studio.nebius.com/>

#### [​](#basic-setup-15) Basic Setup

1. Create/sign in to Nebius AI Studio.
2. Generate API credentials.
3. In Cline, choose **Nebius AI Studio** and provide the credential.

### [​](#nous-research) Nous Research

Nous Research provides access to Hermes-family model offerings.
**Website:** <https://nousresearch.com/>

#### [​](#basic-setup-16) Basic Setup

1. Get provider access/credentials for Nous-hosted endpoints.
2. Confirm available model IDs for your account.
3. In Cline, select **NousResearch** and add credentials.

### [​](#oracle-code-assist) Oracle Code Assist

Oracle Code Assist provides AI-powered coding assistance through Oracle Cloud Infrastructure (OCI) Generative AI service.
**Website:** <https://www.oracle.com/application-development/code-assist/>

#### [​](#basic-setup-17) Basic Setup

1. **OCI Account:** You need an Oracle Cloud Infrastructure account.
2. **Enable Generative AI:** Enable the OCI Generative AI service in your tenancy.
3. **Get Credentials:** Configure OCI authentication (API key, config file, or instance principal).

### [​](#qwen-code) Qwen Code

Qwen Code provides coding-oriented access to Qwen models.
**Website:** <https://chat.qwen.ai/>

#### [​](#basic-setup-18) Basic Setup

1. Sign in to Qwen platform.
2. Obtain API access credentials.
3. In Cline, select **Qwen Code** and enter the credential.

### [​](#requesty) Requesty

Requesty provides multi-provider routing behind a single API surface.
**Website:** <https://www.requesty.ai/>

#### [​](#basic-setup-19) Basic Setup

1. Create/sign in to Requesty.
2. Generate an API key.
3. In Cline, select **Requesty** and paste the key.

### [​](#sambanova) SambaNova

SambaNova offers hosted inference and enterprise AI platform capabilities.
**Website:** <https://sambanova.ai/>

#### [​](#basic-setup-20) Basic Setup

1. Create/sign in to SambaNova account.
2. Create an API key/token.
3. In Cline, choose **SambaNova** and enter credentials.

### [​](#sap-ai-core) SAP AI Core

SAP AI Core is SAP’s enterprise AI platform for model integration and governance.
**Website:** <https://help.sap.com/docs/sap-ai-core/sap-ai-core-service-guide/what-is-sap-ai-core>

#### [​](#basic-setup-21) Basic Setup

1. Set up SAP AI Core / generative AI hub access.
2. Configure your service key/endpoint credentials.
3. In Cline, select **SAP AI Core** and provide required values.

### [​](#together) Together

Together provides hosted inference for many popular open models.
**Website:** <https://together.ai/>

#### [​](#basic-setup-22) Basic Setup

1. Create/sign in to Together account.
2. Generate an API key.
3. In Cline, choose **Together** and paste the key.

### [​](#vercel-ai-gateway) Vercel AI Gateway

Vercel AI Gateway gives one API for multiple upstream model providers.
**Website:** <https://vercel.com/>

#### [​](#basic-setup-23) Basic Setup

1. Sign in to Vercel and open AI Gateway.
2. Create a Gateway API key.
3. In Cline, select **Vercel AI Gateway** and add the key.

### [​](#vs-code-language-model-api) VS Code Language Model API

VS Code Language Model API support lets Cline use models exposed by the VS Code host environment.
**Website:** <https://code.visualstudio.com/api/extension-guides/language-model>

#### [​](#basic-setup-24) Basic Setup

1. Use VS Code with LM API-compatible model access configured.
2. Ensure the language model integration is available in your environment.
3. In Cline, select **VS Code Language Model API**.

### [​](#xai-grok) xAI (Grok)

xAI provides Grok models through its API platform.
**Website:** <https://x.ai/>

#### [​](#basic-setup-25) Basic Setup

1. Sign in to xAI platform.
2. Generate an API key.
3. In Cline, choose **xAI (Grok)** and paste the key.

Was this page helpful?

YesNo

[Z AI (Zhipu AI)](/provider-config/zai)[Config](/getting-started/config)

⌘I

---

## Qwen

*Source: [https://docs.cline.bot/provider-config/qwen](https://docs.cline.bot/provider-config/qwen)*

**Website:** <https://bailian.console.aliyun.com/>

### [​](#get-api-credentials) Get API Credentials

1. **Sign Up/Sign In:** Go to the [Alibaba Cloud Bailian Console](https://bailian.console.aliyun.com/). Create an account or sign in.
2. **Navigate to API Keys:** Access the API key management section.
3. **Create a Key:** Generate a new API key for your application.
4. **Copy the Key:** Copy the API key immediately and store it securely.

### [​](#configuration-in-cline) Configuration in Cline

> See [Authorization & Model Selection](/getting-started/authorizing-with-cline#menu).

1. **Open Cline Settings:** Click the settings icon (⚙️) in the Cline panel.
2. **Select Provider:** Choose “Alibaba Qwen” from the “API Provider” dropdown.
3. **Select Region:** Choose “International” or “China” based on your location.
4. **Enter API Key:** Paste your Qwen API key into the “Qwen API Key” field.
5. **Select Provider Model:** Choose your desired model from the “Model” dropdown.

### [​](#tips-and-notes) Tips and Notes

- **Vision Support:** VL (Vision-Language) models support image inputs for multimodal tasks.
- **Pricing:** Check the [Alibaba Cloud Bailian Console](https://bailian.console.aliyun.com/) for current pricing.

Was this page helpful?

YesNo

[Local models](/running-models-locally/overview)[Anthropic / Claude Code](/provider-config/anthropic)

⌘I

---

## Zai

*Source: [https://docs.cline.bot/provider-config/zai](https://docs.cline.bot/provider-config/zai)*

Z AI (formerly Zhipu AI) offers the GLM model series, featuring hybrid reasoning capabilities and agentic AI design. These models excel in unified reasoning, coding, and intelligent agent applications while maintaining open-source accessibility under MIT license.
**Website:** <https://z.ai/model-api> (International) | <https://open.bigmodel.cn/> (China)

### [​](#getting-an-api-key) Getting an API Key

#### [​](#international-users) International Users

1. **Sign Up/Sign In:** Go to <https://z.ai/model-api>. Create an account or sign in.
2. **Navigate to API Keys:** Access your account dashboard and find the API keys section.
3. **Create a Key:** Generate a new API key for your application.
4. **Copy the Key:** Copy the API key immediately and store it securely.

#### [​](#china-mainland-users) China Mainland Users

1. **Sign Up/Sign In:** Go to <https://open.bigmodel.cn/>. Create an account or sign in.
2. **Navigate to API Keys:** Access your account dashboard and find the API keys section.
3. **Create a Key:** Generate a new API key for your application.
4. **Copy the Key:** Copy the API key immediately and store it securely.

**Note:** Pricing differs between International and China regions. China region pricing is approximately 50% lower.

### [​](#configuration-in-cline) Configuration in Cline

> See [Authorization & Model Selection](/getting-started/authorizing-with-cline#menu).

1. **Open Cline Settings:** Click the settings icon (⚙️) in the Cline panel.
2. **Select Provider:** Choose “Z AI” from the “API Provider” dropdown.
3. **Select Region:** Choose your region:
   - “International” for global access
   - “China” for mainland China access
4. **Enter API Key:** Paste your Z AI API key into the “Z AI API Key” field.
5. **Select Model:** Choose your desired model from the “Model” dropdown.

### [​](#glm-coding-plans) GLM Coding Plans

Z AI offers subscription plans specifically designed for coding applications. These plans provide cost-effective access to GLM series models through a prompt-based structure rather than traditional API usage billing.

#### [​](#setting-up-glm-coding-plans) Setting up GLM Coding Plans

To use the GLM Coding Plans with Cline:

1. **Subscribe:** Go to <https://z.ai/subscribe> and choose your plan.
2. **Create API Key:** After subscribing, log into your zAI dashboard and create an API key for your coding plan.
3. **Configure in Cline:** Open Cline settings, select “Z AI” as your provider, and paste your API key into the “Z AI API Key” field.

The setup connects your subscription directly to Cline, giving you access to GLM-4.5’s tool-calling capabilities optimized for coding workflows.

### [​](#regional-optimization) Regional Optimization

#### [​](#api-endpoints) API Endpoints

- **International:** Uses `https://api.z.ai/api/paas/v4`
- **China:** Uses `https://open.bigmodel.cn/api/paas/v4`

#### [​](#model-availability) Model Availability

The region setting determines both API endpoint and available models, with automatic filtering to ensure compatibility with your selected region.

Was this page helpful?

YesNo

[OpenRouter](/provider-config/openrouter)[Other 30+ Providers](/provider-config/other-30-plus-providers)

⌘I

---

## Overview

*Source: [https://docs.cline.bot/running-models-locally/overview](https://docs.cline.bot/running-models-locally/overview)*

Run Cline with local inference on your machine.

## [​](#quick-start) Quick Start

1. Install a local runtime (**Ollama** or **LM Studio**)
2. Start the local server
3. In Cline Settings, select the matching provider
4. Select a local model
5. Enable **Use Compact Prompt** in Cline Settings → Features

## [​](#hardware-requirements) Hardware Requirements

| RAM | Typical local setup |
| --- | --- |
| 16-32GB | Small/quantized models |
| 32-64GB | Mid-size coding models |
| 64GB+ | Larger models and bigger context windows |

## [​](#runtime-options) Runtime Options

- Ollama
- LM Studio

### [​](#1-install) 1) Install

- Download from [ollama.com](https://ollama.com)
- Install for your OS

### [​](#2-find-popular-local-models) 2) Find popular local models

- Browse the Ollama model catalog: [ollama.com/search](https://ollama.com/search)
- Sort/filter by popularity, model size, and latest updates
- Open any model page and copy the `ollama pull` command

### [​](#3-pull-and-run-a-model) 3) Pull and run a model

```
ollama pull <model-name>
ollama run <model-name>
```

### [​](#4-configure-cline) 4) Configure Cline

1. Open Cline Settings
2. Select provider: **Ollama**
3. Base URL: `http://localhost:11434`
4. Select your model from the dropdown

### [​](#5-troubleshooting) 5) Troubleshooting

- Make sure Ollama is running before sending prompts
- If connection fails, verify `http://localhost:11434`
- If model is missing, run `ollama pull <model-name>`

### [​](#1-install-2) 1) Install

- Download from [lmstudio.ai](https://lmstudio.ai)
- Install and launch the app

### [​](#2-find-local-models) 2) Find local models

- Browse the LM Studio model catalog: [lmstudio.ai/models](https://lmstudio.ai/models)
- Filter by model family, size, and capabilities
- Pick a model that matches your hardware

### [​](#3-download-a-model) 3) Download a model

- Open **Discover** and download a model

### [​](#4-start-server) 4) Start server

- Open **Developer** tab
- Start server (default: `http://localhost:1234`)

### [​](#5-configure-cline) 5) Configure Cline

1. Open Cline Settings
2. Select provider: **LM Studio**
3. Keep Base URL as `http://localhost:1234`
4. Select your model from the dropdown

### [​](#6-troubleshooting) 6) Troubleshooting

- Ensure LM Studio server is running
- Ensure a model is loaded
- If connection fails, verify `http://localhost:1234`

## [​](#recommended-cline-settings-for-local-inference) Recommended Cline Settings for Local Inference

- Enable **Use Compact Prompt**
- Keep tasks focused (smaller context = faster responses)
- Start a new task when context gets too large

Was this page helpful?

YesNo

[Cline provider](/getting-started/cline-provider)[Alibaba Qwen](/provider-config/qwen)

⌘I

---

## Hub Spoke

*Source: [https://docs.cline.bot/sdk/architecture/hub-spoke](https://docs.cline.bot/sdk/architecture/hub-spoke)*

The SDK uses a hub-spoke architecture for production deployments. A background daemon (the hub) coordinates session state and event routing, spoke workers execute the agent loop, and clients (CLI, VS Code, JetBrains, etc.) attach as peers over WebSocket.

## [​](#why-hub-spoke) Why Hub-Spoke?

A single-process architecture works for simple scripts, but breaks down when you need:

- Sessions that survive when a window closes or the CLI exits
- Multiple clients viewing and controlling the same session
- Scheduled agents that run when no client is connected
- Process isolation so a runaway agent doesn’t freeze the UI

The hub-spoke model solves all of these by separating coordination from execution, and both from the client UI.

## [​](#three-roles) Three Roles

## Hub

Singleton daemon per machine. Coordinates sessions, routes events and approvals, manages schedules, brokers capabilities between clients. Does not run the agent loop.

## Spoke

Worker process running `@cline/core`. Executes the agent loop, calls tools, streams output. Reports events back to the hub. Owned by the daemon, not by any client.

## Client

CLI, VS Code, JetBrains, or any custom app. Discovers the hub, registers over WebSocket, attaches to sessions, sends user input, receives streamed events.

The single rule that keeps it clean: clients participate, spokes execute, the hub coordinates. No two roles should overlap.

## [​](#communication-flow) Communication Flow

Clients connect to the hub over WebSocket. The hub routes commands and streams events. Spokes report back to the hub, never directly to clients.

1

Client discovers or starts the hub

The hub is a singleton daemon per machine. If one isn’t running, `ClineCore` starts it automatically. Discovery uses lock files at `~/.cline/locks/hub/owners/`.

2

Client registers and attaches to a session

The client sends a `client.register` command over WebSocket, advertising its capabilities (shell access, file editing, diff viewing, etc.). It then creates or attaches to a session.

3

Hub assigns a spoke to execute

The hub spawns or assigns a spoke worker to run the agent loop. The spoke executes tools, streams partial output, and handles abort/cancel.

4

Hub fans out events to all attached clients

As the spoke produces events (text deltas, tool calls, usage), the hub relays them to every client attached to that session. Clients can come and go without interrupting execution.

5

Client disconnects, session keeps running

If the CLI exits or a window closes, the spoke continues executing. Another client can attach to the same session and pick up the event stream mid-flight.

## [​](#backend-modes) Backend Modes

`ClineCore` selects the execution mode based on configuration:

```
const cline = await ClineCore.create({
  clientName: "my-app",
  backendMode: "auto",
})
```

| Mode | Behavior |
| --- | --- |
| `auto` | Prefers a compatible local hub when available, falls back to local in-process execution when not. This is the default. |
| `hub` | Requires a compatible WebSocket hub. Throws if one is not reachable. |
| `remote` | Requires an explicit remote WebSocket hub endpoint. For deployments where the hub doesn’t live on the user’s machine. |
| `local` | Always uses local in-process execution with local SQLite/file storage. No hub, no shared sessions. |

### [​](#when-to-use-each-mode) When to Use Each Mode

Use `local` for:

- Simple scripts and one-off tasks
- Testing and development
- Environments where a background process isn’t appropriate

Use `hub` (or `auto`) for:

- Session persistence across client restarts
- Multiple clients sharing the same session
- Scheduled agents
- Connector integrations (Telegram, Slack, etc.)

Use `remote` for:

- Cloud deployments where the hub runs on a server
- Team-shared hub instances

## [​](#capability-brokerage) Capability Brokerage

When multiple clients are attached to a session, the hub routes capability requests to whichever client can handle them. Clients advertise their capabilities at registration.
For example, VS Code might register `open-file`, `reveal-diff`, and `run-build` capabilities. The CLI might register `shell` and `run-tests`. When the agent needs to open a diff, the hub routes the request to VS Code. When it needs to run a shell command, the hub routes to the CLI.
This means a session gets richer as more clients join. A CLI session can later be enriched by VS Code attaching — an IDE selection can be sent into a running terminal session, or a diff created by one client can be opened by another.

## [​](#session-persistence) Session Persistence

Sessions are stored with full conversation history, tool call records, and metadata. The hub maintains a SQLite index for efficient listing and JSON snapshots as the source of truth for each session’s state.

```
~/.cline/data/sessions/
  sessions.db                    # SQLite index
  [session-id].json              # Authoritative session record
```

Sessions can have multiple participants, each tracked with a role (`creator`, `participant`, `observer`). The session persists independently of any single client’s lifecycle.

## [​](#managing-the-hub) Managing the Hub

The hub starts automatically when `ClineCore` needs it. You can also manage it manually:

```
cline hub start      # Start the hub daemon
cline hub stop       # Stop it
cline hub status     # Check if running
cline hub ensure     # Start if not running, return URL
```

The hub listens on `127.0.0.1:25463` by default and logs to `~/.cline/logs/hub-daemon.log`.

## [​](#multi-client-access) Multi-Client Access

Multiple clients can connect to the same hub and attach to the same session simultaneously:

```
# Terminal 1: start a task
cline "Work on feature X"

# Terminal 2: attach to the same session from VS Code or another CLI

# Terminal 3: Telegram connector
cline connect telegram -k $TOKEN

# All three share the same hub and can access the same sessions
```

## [​](#process-isolation) Process Isolation

If a client crashes, the hub and its running spokes are unaffected. The session continues executing in the spoke worker. When the client reconnects (or a different client attaches), it receives the full session history and resumes the live event stream.
The spoke also has a process boundary from the hub itself. A runaway model call in a spoke doesn’t degrade the hub’s ability to coordinate other sessions, route approvals, or fan out events.

Was this page helpful?

YesNo

[Packages](/sdk/architecture/overview)[Building an Agent](/sdk/guides/building-an-agent)

⌘I

---

## Overview

*Source: [https://docs.cline.bot/sdk/architecture/overview](https://docs.cline.bot/sdk/architecture/overview)*

The SDK is split into layered packages. Dependencies flow downward: `core` depends on `agents`, `llms`, and `shared`; `agents` depends on `llms` and `shared`; `llms` depends on `shared`.

## [​](#package-stack) Package Stack

```
Your application / CLI / VS Code / JetBrains
          │
          ▼
@cline/core
Sessions, storage, built-in tools, hub, automation, telemetry
          │
          ├── @cline/agents
          │   Browser-compatible AgentRuntime / Agent loop
          │
          ├── @cline/llms
          │   Provider handlers, gateway, model catalogs
          │
          └── @cline/shared
              Types, schemas, tools, hooks, extension contracts
```

## [​](#packages) Packages

### [​](#@cline/core) @cline/core

Node runtime/orchestration layer.
Key exports include:

| Export | Description |
| --- | --- |
| `ClineCore` | Main runtime entry point |
| `ClineCoreOptions` | Constructor options |
| `ClineCoreStartInput` | Session start input |
| `CoreSessionConfig` | Session configuration |
| `SessionRecord` | Persisted session metadata |
| `AgentPlugin` | Public plugin type |
| `createTool` | Re-export from shared |

Capabilities include:

- local/hub/remote runtime backends
- session manifests and message artifacts
- built-in tools
- tool approvals
- automation/scheduling services
- telemetry hooks
- plugin/extension loading
- team/sub-agent tools

Depends on: `@cline/shared`, `@cline/llms`, `@cline/agents`.

### [​](#@cline/agents) @cline/agents

Browser-compatible agent execution loop.
Key exports include:

| Export | Description |
| --- | --- |
| `AgentRuntime` | Core runtime class |
| `Agent` | Alias for `AgentRuntime` |
| `createAgentRuntime`, `createAgent` | Factory functions |
| `AgentRuntimeConfig` | Constructor config union |
| `AgentRunInput`, `AgentEventListener` | Runtime helper types |
| `createTool` | Re-export from `@cline/shared` |

Methods on `AgentRuntime` include `run`, `continue`, `abort`, `subscribe`, `restore`, and `snapshot`.
Depends on: `@cline/shared`, `@cline/llms`.

### [​](#@cline/llms) @cline/llms

Provider and model layer.
Key exports include:

| Export | Description |
| --- | --- |
| `DefaultGateway`, `createGateway` | Gateway for creating provider-backed agent models |
| `createHandler`, `createHandlerAsync` | Provider handler factories |
| `getAllProviders`, `getProviderIds`, `getModelsForProvider` | Catalog helpers |
| `registerProvider`, `registerModel` | Runtime registry extension |
| `ModelInfo`, `ProviderInfo` | Provider/model metadata |

Depends on: `@cline/shared`.

### [​](#@cline/shared) @cline/shared

Foundation package for shared contracts and utilities.
Key exports include:

| Export | Description |
| --- | --- |
| `createTool` | Helper for creating typed tools |
| `AgentTool`, `AgentToolContext`, `ToolPolicy` | Tool interfaces |
| `AgentEvent`, `AgentResult`, `AgentConfig` | Host-facing agent types |
| `AgentRuntimeEvent`, `AgentRunResult` | Runtime-facing agent types |
| `HookEngine`, `HookStage`, `HookPolicies` | Hook contracts and engine |
| `ContributionRegistry`, `AgentExtensionApi` | Extension registration contracts |
| `ModelInfo`, `Message`, `ContentBlock` | Model/message types |
| `BasicLogger`, `noopBasicLogger` | Logging contracts |

No higher-layer dependencies.

## [​](#install) Install

```
npm install @cline/sdk
```

`@cline/sdk` re-exports everything from `@cline/core`. Install `@cline/agents` or `@cline/llms` directly only if you need lower-level control.

## [​](#design-principles) Design Principles

### [​](#strict-dependency-direction) Strict dependency direction

Dependencies flow downward only. Lower layers stay embeddable without pulling in the full runtime.

### [​](#browser-compatible-agent-loop) Browser-compatible agent loop

`@cline/agents` exposes a browser-compatible runtime. It does not own session storage, built-in file/shell tools, hub transports, or Node-specific orchestration.

### [​](#core-as-orchestration-layer) Core as orchestration layer

`@cline/core` owns Node runtime integration: session persistence, built-in tools, automation, hub/remote transports, telemetry, and extension loading.

Was this page helpful?

YesNo

[ClineCore](/sdk/clinecore)[Hub & Spoke](/sdk/architecture/hub-spoke)

⌘I

---

## Clinecore

*Source: [https://docs.cline.bot/sdk/clinecore](https://docs.cline.bot/sdk/clinecore)*

`ClineCore` is the full Cline harness as a programmable runtime. It gives you everything Cline ships out of the box: built-in tools for files, shell, search, and web; session persistence and message history; tool approval callbacks; local, hub, and remote backends; scheduling and automation APIs; and plugin support.
Under the hood, `ClineCore` uses the `Agent` class from `@cline/agents`. You can use `Agent` directly if you want to skip the harness and wire everything yourself: your own tools, your own persistence, your own lifecycle.

## [​](#when-to-use-which) When to use which

| Need | Use |
| --- | --- |
| Sessions, persistence, message history | `ClineCore` |
| Built-in tools for files, shell, search, web fetch | `ClineCore` |
| Hub/remote runtime | `ClineCore` |
| Scheduling or event automation | `ClineCore` |
| Multi-agent teams | `ClineCore` |
| Browser-compatible or lightweight in-process agent | `Agent` |
| Custom tools only, no built-ins | `Agent` |
| Full control over persistence and lifecycle | `Agent` |

## [​](#clinecore) ClineCore

`ClineCore` wraps runtime execution with application features:

- session manifests and message artifacts
- built-in tools
- tool approval callbacks
- local, hub, and remote backends
- automation/scheduling APIs
- optional plugin paths and extensions

```
import { ClineCore } from "@cline/sdk"

const cline = await ClineCore.create({
  clientName: "my-app",
  backendMode: "auto",
})

const session = await cline.start({
  prompt: "Set up GitHub Actions for this repo",
  config: {
    providerId: "anthropic",
    modelId: "claude-sonnet-4-6",
    apiKey: process.env.ANTHROPIC_API_KEY,
    systemPrompt: "You are a helpful coding assistant.",
    cwd: "/path/to/project",
    workspaceRoot: "/path/to/project",
    enableTools: true,
    enableSpawnAgent: false,
    enableAgentTeams: false,
  },
})

console.log(session.sessionId)
console.log(session.result?.finishReason)
```

### [​](#methods) Methods

| Method | Purpose |
| --- | --- |
| `ClineCore.create(options)` | Create the runtime |
| `start(input)` | Start a session |
| `send({ sessionId, prompt })` | Send a follow-up message |
| `subscribe(listener, options?)` | Listen to session events |
| `list(limit?, options?)` | List sessions with history metadata |
| `get(sessionId)` | Read session metadata |
| `readMessages(sessionId)` | Read session messages |
| `getAccumulatedUsage(sessionId)` | Read session token/cost totals |
| `abort(sessionId, reason?)` | Abort current work |
| `stop(sessionId)` | Stop a session |
| `delete(sessionId)` | Delete a session |
| `dispose(reason?)` | Clean up runtime resources |

See [ClineCore reference](/sdk/reference/cline-core) for exact signatures.

## [​](#backend-modes) Backend Modes

| Mode | Behavior |
| --- | --- |
| `auto` | Prefer a compatible local hub, otherwise use local execution |
| `hub` | Require a compatible WebSocket hub |
| `remote` | Connect to a configured remote hub |
| `local` | Always use local in-process execution and local storage |

For process topology, see [Hub & Spoke](/sdk/architecture/hub-spoke).

## [​](#session-artifacts) Session Artifacts

`ClineCore` stores session manifests and messages as files. A session result includes:

| Field | Meaning |
| --- | --- |
| `sessionId` | Session identifier |
| `manifest` | Parsed session manifest |
| `manifestPath` | Path to the session manifest JSON |
| `messagesPath` | Path to persisted message JSON |
| `result` | Final `AgentResult`, when available |

## [​](#tool-approval) Tool Approval

Use tool policies for simple cases:

```
await cline.start({
  prompt: "Audit this repo",
  config: {
    providerId: "anthropic",
    modelId: "claude-sonnet-4-6",
    apiKey: process.env.ANTHROPIC_API_KEY,
    systemPrompt: "You are a helpful coding assistant.",
    cwd: process.cwd(),
    workspaceRoot: process.cwd(),
    enableTools: true,
    enableSpawnAgent: false,
    enableAgentTeams: false,
  },
  toolPolicies: {
    read_files: { autoApprove: true },
    search_codebase: { autoApprove: true },
    run_commands: { autoApprove: false },
    editor: { autoApprove: false },
  },
})
```

Use `requestToolApproval` when your application needs to decide dynamically:

```
const cline = await ClineCore.create({
  clientName: "my-app",
  capabilities: {
    requestToolApproval: async (request) => {
      return { approved: request.toolName !== "run_commands" }
    },
  },
})
```

For tool behavior and policies, see [Tools](/sdk/tools).

## [​](#using-agent-directly) Using Agent directly

`Agent` (also exported as `AgentRuntime`) is the stateless primitive that `ClineCore` builds on. Use it directly when you want full control or don’t need the harness.
`Agent` is an alias for `AgentRuntime`. Use `Agent` when constructing from provider/model IDs. Use `AgentRuntime` when supplying a pre-built `AgentModel`.
`Agent` runs the core loop:

```
run() or continue()
  -> model request
  -> tool calls, if any
  -> tool results
  -> repeat until complete
```

```
import { Agent } from "@cline/sdk"

const agent = new Agent({
  providerId: "anthropic",
  modelId: "claude-sonnet-4-6",
  apiKey: process.env.ANTHROPIC_API_KEY,
  systemPrompt: "You are a helpful coding assistant.",
  tools: [myTool],
})

agent.subscribe((event) => {
  if (event.type === "assistant-text-delta") {
    process.stdout.write(event.text ?? "")
  }
})

const result = await agent.run("Review this diff")
console.log(result.outputText)
```

### [​](#agent-methods) Agent Methods

| Method | Purpose |
| --- | --- |
| `run(input)` | Start a run with user input |
| `continue(input?)` | Continue with optional new input |
| `abort(reason?)` | Abort the active run |
| `subscribe(listener)` | Listen to `AgentRuntimeEvent` events |
| `restore(messages)` | Replace conversation history |
| `snapshot()` | Read runtime state |

See [Agent reference](/sdk/reference/agent) for exact signatures.

### [​](#multi-turn-conversations) Multi-Turn Conversations

`AgentRuntime` keeps message state internally. Use `continue()` after the first run:

```
await agent.run("What does this project do?")
await agent.continue("Now identify risky files")
```

If you persist messages externally, restore them with `restore(messages)` before continuing.

Was this page helpful?

YesNo

[Model Providers](/sdk/model-providers)[Packages](/sdk/architecture/overview)

⌘I

---

## Events

*Source: [https://docs.cline.bot/sdk/events](https://docs.cline.bot/sdk/events)*

The SDK exposes two related event surfaces:

- `AgentRuntimeEvent` from `@cline/agents`, delivered through `agent.subscribe(listener)`.
- `AgentEvent` / `CoreSessionEvent` from `@cline/core`, delivered through core session adapters and `cline.subscribe(listener)`.

Use this page for event handling patterns. For event shapes, see [Events reference](/sdk/reference/events).

## [​](#agentruntime-events) AgentRuntime Events

```
const unsubscribe = agent.subscribe((event) => {
  if (event.type === "assistant-text-delta") {
    process.stdout.write(event.text ?? "")
  }
})

await agent.run("Explain this codebase")
unsubscribe()
```

`AgentRuntimeEvent` is the low-level event stream from the browser-compatible runtime.

## [​](#core-/-host-facing-agent-events) Core / Host-Facing Agent Events

`AgentEvent` is the host-facing event shape used by `@cline/core` session orchestration. For direct `Agent` usage, prefer `agent.subscribe(...)` and `AgentRuntimeEvent`.
Common host-facing event categories:

| Category | Events | Use for |
| --- | --- | --- |
| Content | `content_start`, `content_update`, `content_end` | Text/reasoning/tool UI |
| Iterations | `iteration_start`, `iteration_end` | Progress tracking |
| Usage | `usage` | Token/cost tracking |
| Notices | `notice` | Recovery and status updates |
| Completion | `done`, `error` | Final state and failure handling |

## [​](#clinecore-session-events) ClineCore Session Events

Use `cline.subscribe()` for session-level events:

```
const unsubscribe = cline.subscribe((event) => {
  console.log(event.type, event.sessionId)
})

await cline.start({ /* ... */ })
unsubscribe()
```

Pass a `sessionId` filter when you only want one session:

```
const unsubscribe = cline.subscribe(listener, { sessionId })
```

## [​](#streaming-ui-pattern) Streaming UI Pattern

Subscribe to events to build real-time UIs:

```
agent.subscribe((event) => {
  switch (event.type) {
    case "assistant-text-delta":
      onUpdate({ type: "text", content: event.text ?? "" })
      break
    case "tool-started":
      onUpdate({ type: "tool_start", content: event.toolCall.toolName })
      break
    case "tool-finished":
      onUpdate({ type: "tool_end", content: event.toolCall.toolName })
      break
    case "run-finished":
      onUpdate({ type: "done", content: event.result.status })
      break
  }
})
```

For a complete working example of streaming agent events to a browser via SSE, see the [multi-agent example](https://github.com/cline/cline/tree/main/apps/examples/multi-agent). It spawns multiple agents in parallel and streams each agent’s events to separate UI cards.

## [​](#usage-tracking-pattern) Usage Tracking Pattern

```
let totalTokens = 0

agent.subscribe((event) => {
  if (event.type === "usage-updated") {
    totalTokens = event.usage.inputTokens + event.usage.outputTokens
  }
})
```

## [​](#runtime-state-snapshots) Runtime State Snapshots

Call `snapshot()` when you need the current state:

```
const snapshot = agent.snapshot()
console.log(snapshot.status, snapshot.iteration, snapshot.usage)
```

Was this page helpful?

YesNo

[Scheduled Agents](/sdk/guides/scheduled-agents)[Model Providers](/sdk/model-providers)

⌘I

---

## Examples

*Source: [https://docs.cline.bot/sdk/examples](https://docs.cline.bot/sdk/examples)*

This tutorial walks through the [code-review-bot example](https://github.com/cline/cline/tree/main/apps/examples/code-review-bot) from the SDK repository. By the end, you’ll understand how to combine custom tools, system prompts, completion lifecycle, and event streaming into a real application.

## [​](#what-it-builds) What It Builds

A code review agent that:

1. Reads a git diff from the local repo
2. Optionally reads full file contents for context
3. Produces structured review comments with severity levels
4. Ends the run with a summary and approve/reject decision

## [​](#prerequisites) Prerequisites

- Node.js 22+
- An Anthropic API key
- A git repository with at least one commit

## [​](#get-the-code) Get the Code

```
git clone https://github.com/cline/cline.git
cd cline/apps/examples/code-review-bot
bun install
```

Or read along with the [source on GitHub](https://github.com/cline/cline/blob/main/apps/examples/code-review-bot/src/index.ts).

## [​](#how-it-works) How It Works

### [​](#defining-tools-with-zod-schemas) Defining Tools with Zod Schemas

The bot uses `createTool` with zod schemas for type-safe tool definitions. Here’s the review comment tool:

```
createTool({
  name: "add_review_comment",
  description: "Add a review comment on a specific file and line.",
  inputSchema: z.object({
    file: z.string().describe("File path"),
    line: z.number().describe("Line number (approximate is fine)"),
    severity: z.enum(["critical", "warning", "suggestion"]),
    comment: z.string().describe("The review comment"),
  }),
  async execute(input) {
    reviews.push(input)
    return `Comment added (${reviews.length} total)`
  },
})
```

Key points:

- `z.enum` constrains severity to valid values, which improves model accuracy
- `.describe()` on each field tells the model what to provide
- The tool accumulates results in an array for post-run processing

### [​](#completion-tools) Completion Tools

The `submit_review` tool uses `lifecycle: { completesRun: true }` to signal that the agent’s work is done:

```
createTool({
  name: "submit_review",
  description: "Submit the completed review with a summary.",
  inputSchema: z.object({
    summary: z.string().describe("Brief overall assessment of the changes"),
    approve: z.boolean().describe("Whether the changes look good to merge"),
  }),
  lifecycle: { completesRun: true },
  async execute(input) {
    return JSON.stringify({ summary: input.summary, approve: input.approve })
  },
})
```

Without this, the agent would keep looping until `maxIterations`. With it, the agent calls `submit_review` when it’s done and the run ends cleanly.

### [​](#system-prompt) System Prompt

The system prompt gives the agent a structured workflow to follow:

```
const agent = new Agent({
  systemPrompt: `You are a senior code reviewer. Analyze the git diff provided and leave review comments using the add_review_comment tool. Focus on:
- Bugs and logic errors (critical)
- Security issues (critical)
- Performance problems (warning)
- Style and readability improvements (suggestion)

When you are done reviewing, call submit_review with a brief summary.`,
  // ...
})
```

Telling the agent exactly which tools to use and when keeps the workflow predictable.

### [​](#event-streaming) Event Streaming

The bot subscribes to events to show progress as the agent works:

```
agent.subscribe((event) => {
  switch (event.type) {
    case "assistant-text-delta":
      process.stdout.write(event.text ?? "")
      break
    case "tool-started":
      if (event.toolCall.toolName === "add_review_comment") {
        const input = event.toolCall.input
        console.log(`  [${input.severity}] ${input.file}:${input.line} - ${input.comment}`)
      }
      break
  }
})
```

This prints review comments as they’re made, so you see results streaming rather than waiting for the full run to finish.

### [​](#post-run-processing) Post-Run Processing

After the run, the bot groups comments by severity and prints a summary:

```
const result = await agent.run(`Review this git diff:\n\n\`\`\`diff\n${diff}\n\`\`\``)

const critical = reviews.filter((r) => r.severity === "critical")
const warnings = reviews.filter((r) => r.severity === "warning")
const suggestions = reviews.filter((r) => r.severity === "suggestion")
```

The tool calls accumulate structured data during the run, and the application processes it after. This pattern is useful any time you want the agent to produce structured output.

## [​](#run-it) Run It

```
ANTHROPIC_API_KEY=sk-ant-... bun dev        # review last commit
ANTHROPIC_API_KEY=sk-ant-... bun dev main   # review against main
```

## [​](#extending-further) Extending Further

From here, you could:

- Add a tool that posts review comments back to GitHub via the API
- Use `continue()` for follow-up questions about specific findings
- Add a `checkstyle` tool that runs linters on the changed files
- Connect it to a webhook for automatic PR reviews

## [​](#more-examples) More Examples

## CLI Agent

Interactive terminal chat with tools and multi-turn conversation.

## Multi-Agent

Parallel agents streaming to a web UI.

See [Creating Custom Tools](/sdk/guides/creating-custom-tools) and [Writing Plugins](/sdk/guides/writing-plugins) for more on extending agent capabilities.

Was this page helpful?

YesNo

[Hub & Spoke](/sdk/architecture/hub-spoke)[Permission Handling](/sdk/guides/permission-handling)

⌘I

---

## Building An Agent

*Source: [https://docs.cline.bot/sdk/guides/building-an-agent](https://docs.cline.bot/sdk/guides/building-an-agent)*

This tutorial walks through the [code-review-bot example](https://github.com/cline/cline/tree/main/apps/examples/code-review-bot) from the SDK repository. By the end, you’ll understand how to combine custom tools, system prompts, completion lifecycle, and event streaming into a real application.

## [​](#what-it-builds) What It Builds

A code review agent that:

1. Reads a git diff from the local repo
2. Optionally reads full file contents for context
3. Produces structured review comments with severity levels
4. Ends the run with a summary and approve/reject decision

## [​](#prerequisites) Prerequisites

- Node.js 22+
- An Anthropic API key
- A git repository with at least one commit

## [​](#get-the-code) Get the Code

```
git clone https://github.com/cline/cline.git
cd cline/apps/examples/code-review-bot
bun install
```

Or read along with the [source on GitHub](https://github.com/cline/cline/blob/main/apps/examples/code-review-bot/src/index.ts).

## [​](#how-it-works) How It Works

### [​](#defining-tools-with-zod-schemas) Defining Tools with Zod Schemas

The bot uses `createTool` with zod schemas for type-safe tool definitions. Here’s the review comment tool:

```
createTool({
  name: "add_review_comment",
  description: "Add a review comment on a specific file and line.",
  inputSchema: z.object({
    file: z.string().describe("File path"),
    line: z.number().describe("Line number (approximate is fine)"),
    severity: z.enum(["critical", "warning", "suggestion"]),
    comment: z.string().describe("The review comment"),
  }),
  async execute(input) {
    reviews.push(input)
    return `Comment added (${reviews.length} total)`
  },
})
```

Key points:

- `z.enum` constrains severity to valid values, which improves model accuracy
- `.describe()` on each field tells the model what to provide
- The tool accumulates results in an array for post-run processing

### [​](#completion-tools) Completion Tools

The `submit_review` tool uses `lifecycle: { completesRun: true }` to signal that the agent’s work is done:

```
createTool({
  name: "submit_review",
  description: "Submit the completed review with a summary.",
  inputSchema: z.object({
    summary: z.string().describe("Brief overall assessment of the changes"),
    approve: z.boolean().describe("Whether the changes look good to merge"),
  }),
  lifecycle: { completesRun: true },
  async execute(input) {
    return JSON.stringify({ summary: input.summary, approve: input.approve })
  },
})
```

Without this, the agent would keep looping until `maxIterations`. With it, the agent calls `submit_review` when it’s done and the run ends cleanly.

### [​](#system-prompt) System Prompt

The system prompt gives the agent a structured workflow to follow:

```
const agent = new Agent({
  systemPrompt: `You are a senior code reviewer. Analyze the git diff provided and leave review comments using the add_review_comment tool. Focus on:
- Bugs and logic errors (critical)
- Security issues (critical)
- Performance problems (warning)
- Style and readability improvements (suggestion)

When you are done reviewing, call submit_review with a brief summary.`,
  // ...
})
```

Telling the agent exactly which tools to use and when keeps the workflow predictable.

### [​](#event-streaming) Event Streaming

The bot subscribes to events to show progress as the agent works:

```
agent.subscribe((event) => {
  switch (event.type) {
    case "assistant-text-delta":
      process.stdout.write(event.text ?? "")
      break
    case "tool-started":
      if (event.toolCall.toolName === "add_review_comment") {
        const input = event.toolCall.input
        console.log(`  [${input.severity}] ${input.file}:${input.line} - ${input.comment}`)
      }
      break
  }
})
```

This prints review comments as they’re made, so you see results streaming rather than waiting for the full run to finish.

### [​](#post-run-processing) Post-Run Processing

After the run, the bot groups comments by severity and prints a summary:

```
const result = await agent.run(`Review this git diff:\n\n\`\`\`diff\n${diff}\n\`\`\``)

const critical = reviews.filter((r) => r.severity === "critical")
const warnings = reviews.filter((r) => r.severity === "warning")
const suggestions = reviews.filter((r) => r.severity === "suggestion")
```

The tool calls accumulate structured data during the run, and the application processes it after. This pattern is useful any time you want the agent to produce structured output.

## [​](#run-it) Run It

```
ANTHROPIC_API_KEY=sk-ant-... bun dev        # review last commit
ANTHROPIC_API_KEY=sk-ant-... bun dev main   # review against main
```

## [​](#extending-further) Extending Further

From here, you could:

- Add a tool that posts review comments back to GitHub via the API
- Use `continue()` for follow-up questions about specific findings
- Add a `checkstyle` tool that runs linters on the changed files
- Connect it to a webhook for automatic PR reviews

## [​](#more-examples) More Examples

## CLI Agent

Interactive terminal chat with tools and multi-turn conversation.

## Multi-Agent

Parallel agents streaming to a web UI.

See [Creating Custom Tools](/sdk/guides/creating-custom-tools) and [Writing Plugins](/sdk/guides/writing-plugins) for more on extending agent capabilities.

Was this page helpful?

YesNo

[Hub & Spoke](/sdk/architecture/hub-spoke)[Permission Handling](/sdk/guides/permission-handling)

⌘I

---

## Creating Custom Tools

*Source: [https://docs.cline.bot/sdk/guides/creating-custom-tools](https://docs.cline.bot/sdk/guides/creating-custom-tools)*

Custom tools extend what your agent can do. A tool is a function with a name, a description the LLM reads, a schema for inputs, and an execute function that does the actual work.

## [​](#basic-tool) Basic Tool

Use `createTool` with a zod schema for the simplest approach:

```
import { createTool } from "@cline/sdk"
import { z } from "zod"

const getCurrentTime = createTool({
  name: "get_current_time",
  description: "Get the current date and time. Optionally specify a timezone.",
  inputSchema: z.object({
    timezone: z.string().optional().describe("IANA timezone (e.g., 'America/New_York'). Defaults to UTC."),
  }),
  async execute(input) {
    const tz = input.timezone ?? "UTC"
    const date = new Date()
    return {
      iso: date.toISOString(),
      timezone: tz,
      formatted: date.toLocaleString("en-US", { timeZone: tz }),
    }
  },
})
```

The SDK converts the zod schema to JSON Schema automatically. Input is fully typed in the `execute` function.
For working examples of tools in real agents, see the [cli-agent](https://github.com/cline/cline/tree/main/apps/examples/cli-agent) (shell tool with zod) and [code-review-bot](https://github.com/cline/cline/tree/main/apps/examples/code-review-bot) (multiple tools with completion lifecycle).

## [​](#anatomy-of-a-tool) Anatomy of a Tool

Every tool has four parts:

| Field | Purpose |
| --- | --- |
| `name` | Unique identifier (snake\_case recommended) |
| `description` | LLM reads this to decide when to use the tool |
| `inputSchema` | Zod schema or JSON Schema defining accepted arguments |
| `execute` | Function that does the work |

### [​](#the-name) The Name

Use `snake_case`. Keep it descriptive but concise:

- `search_database`, not `db` or `performDatabaseSearchOperation`
- `send_email`, not `email` or `handleEmailSending`

### [​](#the-description) The Description

This is the most important field for tool call accuracy. The LLM uses it to decide when and how to use the tool.

```
// Weak: model won't know when to use this
description: "Handles data."

// Strong: model knows exactly what this does and when to use it
description: "Search the PostgreSQL database by executing a read-only SQL query. Returns matching rows as JSON. Use this when you need to look up user records, order history, or product data. Maximum 100 rows per query."
```

Include:

- What the tool does
- What it returns
- When to use it (and when not to)
- Constraints (rate limits, read-only, max results, etc.)

### [​](#the-input-schema) The Input Schema

With zod, use `.describe()` on every field:

```
inputSchema: z.object({
  query: z.string().describe("Search query. Supports wildcards (*) and exact phrases."),
  limit: z.number().min(1).max(100).optional().describe("Maximum results. Default: 10."),
  status: z.enum(["active", "archived", "deleted"]).optional().describe("Filter by record status."),
})
```

Use `z.enum` for fields with a fixed set of values. This dramatically improves accuracy.

## [​](#using-agenttoolcontext) Using AgentToolContext

The `execute` function receives a context object with execution metadata:

```
const longProcess = createTool({
  name: "long_process",
  description: "Process data in batches.",
  inputSchema: z.object({}),
  async execute(_input, context) {
    console.log(`Agent: ${context.agentId}, Iteration: ${context.iteration}`)

    for (const batch of batches) {
      if (context.signal?.aborted) {
        return { status: "cancelled", processed: count }
      }
      await processBatch(batch)
    }

    return { status: "complete" }
  },
})
```

## [​](#error-handling) Error Handling

Return errors as structured data rather than throwing:

```
const apiTool = createTool({
  name: "call_api",
  description: "Make an authenticated API call.",
  inputSchema: z.object({
    endpoint: z.string().describe("API endpoint path"),
  }),
  async execute(input) {
    try {
      const response = await fetch(`https://api.example.com${input.endpoint}`, {
        headers: { Authorization: `Bearer ${process.env.API_TOKEN}` },
      })

      if (!response.ok) {
        return {
          output: { error: `API returned ${response.status}` },
          isError: true,
        }
      }

      return await response.json()
    } catch (err) {
      return {
        output: { error: `Network error: ${(err as Error).message}` },
        isError: true,
      }
    }
  },
})
```

When a tool returns an error, the agent sees it and can adjust its approach. When a tool throws, it counts as a “mistake” and increments the consecutive mistake counter.

## [​](#completion-tools) Completion Tools

Mark a tool with `lifecycle: { completesRun: true }` to make it end the agent loop when called successfully:

```
const submitResult = createTool({
  name: "submit_result",
  description: "Submit the final result and end the run.",
  inputSchema: z.object({
    summary: z.string(),
    approve: z.boolean(),
  }),
  lifecycle: { completesRun: true },
  async execute(input) {
    return JSON.stringify(input)
  },
})
```

See the [code-review-bot example](https://github.com/cline/cline/tree/main/apps/examples/code-review-bot) for this pattern in a complete application.

## [​](#testing-tools) Testing Tools

Test your tools in isolation before giving them to an agent:

```
import { describe, it, expect } from "vitest"

describe("get_current_time", () => {
  it("returns ISO timestamp", async () => {
    const result = await getCurrentTime.execute(
      { timezone: "UTC" },
      {
        agentId: "test",
        runId: "run_test",
        iteration: 1,
        toolCallId: "tool_test",
        snapshot: {} as never,
        emitUpdate: () => {},
      }
    )

    expect(result.iso).toMatch(/^\d{4}-\d{2}-\d{2}T/)
  })
})
```

## [​](#registering-tools) Registering Tools

- Cline Core
- Agent
- Via Plugin

```
await cline.start({
  prompt: "Get the current time",
  config: {
    // ...
    extraTools: [getCurrentTime],
  },
})
```

```
const agent = new Agent({
  tools: [searchDatabase, getCurrentTime],
  // ...
})
```

```
const myPlugin: AgentPlugin = {
  name: "my-tools",
  manifest: { capabilities: ["tools"] },
  setup(api) {
    api.registerTool(searchDatabase)
    api.registerTool(getCurrentTime)
  },
}
```

## [​](#tool-design-rules) Tool Design Rules

Good tools are specific and predictable.

- Use action-oriented names: `get_pull_request`, `search_database`, `deploy_service`.
- Describe what the tool does, when to use it, and what it returns.
- Put constraints in the description: rate limits, read-only behavior, required permissions.
- Add descriptions for every input property.
- Return structured JSON instead of prose when possible.
- Respect `context.abortSignal` in long-running tools.

Was this page helpful?

YesNo

[Tools](/sdk/tools)[Scheduled Agents](/sdk/guides/scheduled-agents)

⌘I

---

## Going To Production

*Source: [https://docs.cline.bot/sdk/guides/going-to-production](https://docs.cline.bot/sdk/guides/going-to-production)*

Moving from development to production means handling the things that don’t matter during prototyping: errors, costs, observability, and security. This guide covers the patterns that production agent deployments need.

## [​](#error-handling) Error Handling

### [​](#agent-level-errors) Agent-Level Errors

The direct `AgentRuntime` result reports `status`; the host-facing `AgentResult` used by core reports `finishReason`.

```
const result = await agent.run("Do something complex")

if (result.status === "failed") {
  // Log the error and alert
  logger.error("Agent run failed", {
    iterations: result.iterations,
    error: result.error,
  })
}
```

### [​](#tool-errors) Tool Errors

Tools should return errors as data rather than throwing. This lets the agent see the error and adjust:

```
const apiTool: AgentTool<{ payload: unknown }, { success: boolean; data?: unknown; error?: string }> = {
  name: "call_service",
  // ...
  execute: async (input) => {
    try {
      const result = await service.call(input)
      return { output: { success: true, data: result } }
    } catch (err) {
      return {
        output: { success: false, error: err.message },
        isError: true,
      }
    }
  },
}
```

### [​](#mistake-limits) Mistake Limits

Core sessions can track consecutive recoverable mistakes and stop with `finishReason: "mistake_limit"`. Direct runtime runs report failure through `status` and `error`.

### [​](#loop-detection) Loop Detection

Loop detection is available through core/session execution settings.

## [​](#observability) Observability

### [​](#opentelemetry-integration) OpenTelemetry Integration

The SDK integrates with OpenTelemetry for traces, metrics, and logs:

```
const cline = await ClineCore.create({
  clientName: "production-app",
  telemetry: myTelemetryService,
  logger: myLogger,
})
```

Events emitted include:

- `agent_created` — agent initialized with config
- `tool_usage` — tool called with name, duration, success/failure
- `model_api_call` — LLM API call with model, tokens, latency
- `session_ended` — session completed with finish reason, total tokens

### [​](#custom-metrics-via-plugins) Custom Metrics via Plugins

```
const productionMetrics: AgentPlugin = {
  name: "production-metrics",
  manifest: { capabilities: ["hooks"] },

  onRunEnd({ result }) {
    metrics.histogram("agent.duration_ms", result.durationMs)
    metrics.counter("agent.tokens.input", result.usage.inputTokens)
    metrics.counter("agent.tokens.output", result.usage.outputTokens)
    metrics.counter(`agent.finish.${result.finishReason}`, 1)
  },

  onToolCall({ call }) {
    metrics.counter(`agent.tool.${call.name}`, 1)
  },

  onError({ error, recoverable }) {
    metrics.counter("agent.errors", 1, {
      recoverable: String(recoverable),
      type: error.constructor.name,
    })
  },
}
```

### [​](#structured-logging) Structured Logging

```
import pino from "pino"

const logger = pino({ level: "info" })

const agent = new Agent({
  // ...config
})

agent.subscribe((event) => {
  if (event.type === "run-finished") {
    logger.info({
      event: "agent_complete",
      status: event.result.status,
      iterations: event.result.iterations,
      tokens: event.result.usage,
    })
  }
  if (event.type === "run-failed") {
    logger.error({
      event: "agent_error",
      message: event.error.message,
    })
  }
})
```

## [​](#cost-control) Cost Control

### [​](#set-token-limits) Set Token Limits

```
const agent = new Agent({
  // ...config
  maxTokensPerTurn: 4096,
  maxIterations: 20,
})
```

### [​](#track-spending) Track Spending

```
type ModelPricing = {
  inputPerMillion: number
  outputPerMillion: number
}

function estimateCost(
  usage: { inputTokens: number; outputTokens: number; totalCost?: number },
  pricing: ModelPricing,
) {
  if (usage.totalCost != null) {
    return usage.totalCost
  }

  return (
    (usage.inputTokens / 1_000_000) * pricing.inputPerMillion +
    (usage.outputTokens / 1_000_000) * pricing.outputPerMillion
  )
}

let sessionCost = 0

const providerId = "anthropic"
const modelId = "claude-sonnet-4-6"
// Load current USD-per-million-token pricing from configuration or a pricing service.
const pricing = loadModelPricing(providerId, modelId)

const agent = new Agent({
  providerId,
  modelId,
  // ...
})

agent.subscribe((event) => {
  if (event.type === "usage-updated") {
    sessionCost = estimateCost(event.usage, pricing)

    if (sessionCost > 1.0) {
      agent.abort("Cost limit exceeded ($1.00)")
    }
  }
})
```

### [​](#use-cheaper-models-for-simple-tasks) Use Cheaper Models for Simple Tasks

```
// Quick lookup: use a fast, cheap model
const lookupAgent = new Agent({
  providerId: "anthropic",
  modelId: "claude-haiku-4-5",
  // ...
})

// Complex work: use a more capable model
const workAgent = new Agent({
  providerId: "anthropic",
  modelId: "claude-sonnet-4-6",
  // ...
})
```

## [​](#security) Security

### [​](#sandbox-tool-execution) Sandbox Tool Execution

Never let an agent run arbitrary shell commands on a production server without constraints:

```
const sandboxedBash: AgentTool<{ command: string }, { error?: string; result?: unknown }> = {
  name: "run_commands",
  description: "Execute a shell command in a sandboxed environment.",
  inputSchema: {
    type: "object",
    properties: {
      command: { type: "string", description: "Shell command to execute" },
    },
    required: ["command"],
  },
  execute: async (input) => {
    const blocked = ["rm -rf", "sudo", "curl | sh", "wget | sh", "> /dev/"]
    if (blocked.some((b) => input.command.includes(b))) {
      return { output: { error: "Command blocked by security policy" }, isError: true }
    }

    // Execute in a container, chroot, or restricted shell
    return { output: { result: await executeInSandbox(input.command) } }
  },
}
```

### [​](#validate-tool-inputs) Validate Tool Inputs

Don’t trust tool inputs any more than you’d trust user input:

```
const fileTool = createTool({
  name: "read_files",
  // ...
  execute: async (input) => {
    const resolved = path.resolve(input.path)

    // Prevent path traversal
    if (!resolved.startsWith(ALLOWED_DIRECTORY)) {
      return { error: "Access denied: path outside allowed directory" }
    }

    return await fs.readFile(resolved, "utf-8")
  },
})
```

### [​](#rotate-api-keys) Rotate API Keys

Use environment variables for API keys, not hardcoded values:

```
// Good
const agent = new Agent({
  apiKey: process.env.ANTHROPIC_API_KEY,
  // ...
})

// Never do this
const agent = new Agent({
  apiKey: "sk-ant-api03-...",
  // ...
})
```

## [​](#deployment-patterns) Deployment Patterns

### [​](#stateless-worker) Stateless Worker

For request/response workflows (API endpoints, webhook handlers):

```
async function handleRequest(prompt: string): Promise<string> {
  const agent = new Agent({
    providerId: "anthropic",
    modelId: "claude-sonnet-4-6",
    apiKey: process.env.ANTHROPIC_API_KEY,
    systemPrompt: "You are a helpful assistant.",
    tools: [myTool],
    maxIterations: 10,
  })

  const result = await agent.run(prompt)
  // Agent has no explicit shutdown method
  return result.outputText
}
```

### [​](#persistent-service) Persistent Service

For long-running services with session management:

```
const cline = await ClineCore.create({
  clientName: "my-service",
  backendMode: "hub",
})

// Sessions persist across restarts
// Connectors, schedules, and team state all managed by the hub

process.on("SIGTERM", async () => {
  await cline.dispose("Shutting down")
  process.exit(0)
})
```

Was this page helpful?

YesNo

[Multi-Agent Teams](/sdk/guides/multi-agent-teams)[ClineCore](/sdk/reference/cline-core)

⌘I

---

## Multi Agent Teams

*Source: [https://docs.cline.bot/sdk/guides/multi-agent-teams](https://docs.cline.bot/sdk/guides/multi-agent-teams)*

Multi-agent teams let you break complex work across multiple agents that coordinate through a shared task board. One agent acts as the coordinator, delegating subtasks to specialist agents and merging their results.

## [​](#enabling-teams) Enabling Teams

Teams are a ClineCore feature. Enable them in the session config:

```
import { ClineCore } from "@cline/sdk"

const cline = await ClineCore.create({ clientName: "team-app" })

const session = await cline.start({
  prompt: "Plan and implement a user authentication module with tests",
  config: {
    providerId: "anthropic",
    modelId: "claude-sonnet-4-6",
    apiKey: process.env.ANTHROPIC_API_KEY,
    systemPrompt: "You are a coordinator for a multi-agent coding team.",
    cwd: "/path/to/project",
    workspaceRoot: "/path/to/project",
    enableTools: true,
    enableSpawnAgent: true,
    enableAgentTeams: true,
    teamName: "auth-sprint",
  },
})
```

## [​](#how-teams-work) How Teams Work

When teams are enabled, the coordinator agent gets additional tools:

| Tool | Description |
| --- | --- |
| `team_spawn_teammate` | Create a new agent with a specific role and task |
| `team_delegate_task` | Assign a task to an existing teammate |
| `team_check_status` | Check the status of delegated tasks |
| `team_get_result` | Retrieve the result of a completed task |

The coordinator decides how to split work, which agents to create, and how to combine results.

## [​](#team-persistence) Team Persistence

Team state persists across sessions:

```
~/.cline/data/teams/[team-name]/
  task-board.json      # Current tasks and their status
  mailbox.json         # Inter-agent messages
  mission-log.json     # Team activity history
```

Resume a team’s work in a new session:

```
cline --team-name auth-sprint "Continue -- pick up incomplete tasks"
```

## [​](#via-cli) Via CLI

```
# Start a new team
cline --team-name auth-sprint "Plan and implement user auth with tests"

# Resume work
cline --team-name auth-sprint "What's the status? Continue with unfinished tasks."

# Different team for a different workstream
cline --team-name perf-sprint "Profile the API endpoints and optimize the slowest 3"
```

## [​](#sub-agents-vs-teams) Sub-Agents vs Teams

The SDK offers two levels of multi-agent coordination:

| Feature | Sub-Agents | Teams |
| --- | --- | --- |
| Enable with | `enableSpawnAgent: true` | `enableAgentTeams: true` |
| Persistence | Within session only | Across sessions |
| Coordination | Parent-child | Peer-to-peer with task board |
| Shared state | None | Task board, mailbox, mission log |
| Best for | One-off delegation | Complex, multi-session projects |

Sub-agents are lighter weight. The parent agent spawns a child, waits for its result, and continues. No persistent state, no task board.

```
// Sub-agents: simple delegation within a single session
const session = await cline.start({
  config: {
    enableSpawnAgent: true,  // Agent can spawn sub-agents
    // ...
  },
  // ...
})
```

Teams are for bigger efforts where work spans multiple sessions and agents need to coordinate asynchronously.

## [​](#when-to-use-teams) When to Use Teams

Teams add overhead. Use them when:

- The task naturally decomposes into independent subtasks
- Different subtasks benefit from different system prompts or specializations
- Work spans multiple sessions or days
- You want a persistent record of task delegation and completion

For simpler cases, a single agent with good tools is usually more efficient than a team.

Was this page helpful?

YesNo

[Permission Handling](/sdk/guides/permission-handling)[Going to Production](/sdk/guides/going-to-production)

⌘I

---

## Permission Handling

*Source: [https://docs.cline.bot/sdk/guides/permission-handling](https://docs.cline.bot/sdk/guides/permission-handling)*

Tool policies control whether tools are enabled and whether they run without approval. Tool names not listed in `toolPolicies` default to enabled and auto-approved, so set policies explicitly for tools that need review.

## [​](#tool-policies) Tool Policies

The simplest way to manage permissions is through tool policies. Set them per-tool when creating an agent:

```
const agent = new Agent({
  // ...config
  tools: [readFileTool, writeFileTool, bashTool, searchTool],
  toolPolicies: {
    read_files: { autoApprove: true },     // Always run without asking
    search_codebase: { autoApprove: true },         // Always run without asking
    write_file: { autoApprove: false },    // Always ask before running
    run_commands: { autoApprove: false },          // Always ask before running
  },
})
```

### [​](#policy-options) Policy Options

| Policy | Effect |
| --- | --- |
| `{ autoApprove: true }` | Tool executes immediately without approval |
| `{ autoApprove: false }` | Tool waits for approval before executing |
| `{ enabled: false }` | Tool is completely disabled (model won’t see it) |
| No policy set | Defaults to enabled and auto-approved |

## [​](#auto-approve-everything) Auto-Approve Everything

For trusted environments (CI pipelines, sandboxed containers, development scripts):

```
const agent = new Agent({
  // ...config
  tools: allTools,
  toolPolicies: Object.fromEntries(
    allTools.map((t) => [t.name, { autoApprove: true }])
  ),
})
```

Or with ClineCore:

```
const session = await cline.start({
  config: {
    enableTools: true,
  },
  toolPolicies: {
    run_commands: { autoApprove: true },
    editor: { autoApprove: true },
    read_files: { autoApprove: true },
    apply_patch: { autoApprove: true },
    search_codebase: { autoApprove: true },
    fetch_web_content: { autoApprove: true },
  },
  capabilities: {
    requestToolApproval: async () => ({ approved: true }),
  },
  // ...
})
```

Auto-approving all tools means the agent can execute any shell command, modify any file, and make network requests without your review. Only use this in environments where the agent’s actions are either sandboxed or fully trusted.

## [​](#interactive-approval) Interactive Approval

For applications that need human oversight, implement a custom approval handler:

```
import { ClineCore } from "@cline/sdk"
import * as readline from "readline"

const rl = readline.createInterface({ input: process.stdin, output: process.stdout })
const ask = (q: string) => new Promise<string>((res) => rl.question(q, res))

const cline = await ClineCore.create({
  clientName: "interactive-app",
  capabilities: {
    requestToolApproval: async (request) => {
      console.log(`\nTool: ${request.toolName}`)
      console.log(`Input: ${JSON.stringify(request.input, null, 2)}`)

      const answer = await ask("Approve? (y/n): ")
      return { approved: answer.toLowerCase() === "y" }
    },
  },
})
```

## [​](#tiered-permissions) Tiered Permissions

A practical middle ground: auto-approve read-only operations, require approval for writes:

```
const READ_TOOLS = new Set(["read_files", "search_codebase", "fetch_web_content"])
const WRITE_TOOLS = new Set(["run_commands", "editor", "apply_patch"])

const toolPolicies: Record<string, { autoApprove: boolean }> = {}

for (const tool of READ_TOOLS) {
  toolPolicies[tool] = { autoApprove: true }
}
for (const tool of WRITE_TOOLS) {
  toolPolicies[tool] = { autoApprove: false }
}
```

## [​](#conditional-approval-logic) Conditional Approval Logic

Approve based on what the tool is actually doing, not just which tool it is:

```
const cline = await ClineCore.create({
  clientName: "smart-approval",
  capabilities: {
    requestToolApproval: async (request) => {
      // Auto-approve non-destructive shell commands
      if (request.toolName === "run_commands") {
        const cmd = JSON.stringify(request.input)
        const safeCommands = ["ls", "cat", "grep", "find", "git status", "git log", "git diff"]
        if (safeCommands.some((safe) => cmd.startsWith(safe))) {
          return { approved: true }
        }
      }

      // Auto-approve reads to specific directories
      if (request.toolName === "read_files") {
        const path = request.input.path as string
        if (path.startsWith("/src/") || path.startsWith("/tests/")) {
          return { approved: true }
        }
      }

      // Everything else requires manual approval
      console.log(`Approval needed: ${request.toolName}`)
      console.log(`Input: ${JSON.stringify(request.input)}`)
      return { approved: false }
    },
  },
})
```

## [​](#what-happens-when-a-tool-is-rejected) What Happens When a Tool is Rejected

When approval is denied, the agent receives a rejection message and can adjust its approach. It might:

- Ask the user for clarification
- Try a different tool to accomplish the same goal
- Modify its approach and try again with different parameters
- Give up on that subtask and move on

The agent does not get stuck in a loop. The rejection counts as a response, and the agent proceeds with its next iteration.

Was this page helpful?

YesNo

[Building an Agent](/sdk/guides/building-an-agent)[Multi-Agent Teams](/sdk/guides/multi-agent-teams)

⌘I

---

## Scheduled Agents

*Source: [https://docs.cline.bot/sdk/guides/scheduled-agents](https://docs.cline.bot/sdk/guides/scheduled-agents)*

The SDK supports running agents on cron schedules. Scheduled agents persist across process restarts and run independently of any client application.

## [​](#how-scheduling-works) How Scheduling Works

1. You define a schedule (cron expression + prompt + config)
2. The SDK stores the schedule and manages execution
3. At each trigger time a new session is created and the agent is run
4. Results are stored and can be routed to connectors (Slack, email, etc.)

Scheduled agents rely on the [hub-spoke architecture](/sdk/architecture/hub-spoke) that is part of `ClineCore`. The hub runs as a background process on your machine. It starts automatically when needed and persists schedules across restarts.

## [​](#creating-schedules-programmatically-with-cline-sdk) Creating Schedules Programmatically with Cline SDK

```
import { ClineCore } from "@cline/sdk"

const cline = await ClineCore.create({
  clientName: "scheduler",
  automation: true,
})

await cline.automation.start()

// Use cline.automation to reconcile specs, ingest events, and list runs.
```

## [​](#schedule-wizard-with-cline-cli) Schedule Wizard with Cline CLI

An easy way to schedule task is to use Cline CLI for scheduling task, if you’ve already installed via `npm i -g cline`
Run `cline schedule` to open an interactive menu for creating and managing schedules, browsing execution history, and viewing performance statistics.

## [​](#creating-schedules-with-flags) Creating Schedules with Flags

```
# Daily at 9 AM on weekdays
cline schedule create "PR summary" \
  --cron "0 9 * * MON-FRI" \
  --prompt "List all open PRs, their review status, and any that have been open more than 3 days" \
  --workspace /path/to/repo \
  --model anthropic/claude-sonnet-4-6

# Every 6 hours
cline schedule create "Health check" \
  --cron "0 */6 * * *" \
  --prompt "Run the test suite and report any failures" \
  --workspace /path/to/project

# Monday mornings
cline schedule create "Weekly digest" \
  --cron "0 8 * * MON" \
  --prompt "Summarize last week's commits, PRs merged, and issues closed"
```

## [​](#managing-schedules) Managing Schedules

```
# List all schedules
cline schedule list

# Trigger a schedule immediately (without waiting for cron)
cline schedule trigger <schedule-id>

# Pause a schedule
cline schedule pause <schedule-id>

# Resume a paused schedule
cline schedule resume <schedule-id>

# Delete a schedule
cline schedule delete <schedule-id>

# View execution history
cline schedule executions <schedule-id>
```

## [​](#cron-expression-reference) Cron Expression Reference

| Expression | Schedule |
| --- | --- |
| `0 9 * * MON-FRI` | 9 AM, Monday through Friday |
| `0 */6 * * *` | Every 6 hours |
| `0 8 * * MON` | 8 AM every Monday |
| `30 17 * * *` | 5:30 PM every day |
| `0 0 1 * *` | Midnight on the 1st of each month |
| `*/30 * * * *` | Every 30 minutes |

## [​](#use-cases) Use Cases

### [​](#daily-standup-summary) Daily Standup Summary

```
cline schedule create "Standup prep" \
  --cron "0 8 * * MON-FRI" \
  --prompt "Summarize: (1) PRs merged yesterday, (2) PRs currently in review, (3) open issues assigned to team members. Format as a brief standup update." \
  --workspace /path/to/repo
```

### [​](#automated-dependency-updates) Automated Dependency Updates

```
cline schedule create "Dependency check" \
  --cron "0 10 * * MON" \
  --prompt "Check for outdated npm dependencies. For any with security vulnerabilities, create a branch with the update and open a PR." \
  --workspace /path/to/project
```

### [​](#codebase-health-report) Codebase Health Report

```
cline schedule create "Code health" \
  --cron "0 6 * * MON" \
  --prompt "Analyze the codebase for: (1) files with no test coverage, (2) TODO/FIXME comments older than 30 days, (3) functions longer than 100 lines. Produce a health report." \
  --workspace /path/to/project
```

## [​](#concurrency-and-resource-limits) Concurrency and Resource Limits

The scheduler enforces limits to prevent resource exhaustion:

- Schedules have configurable concurrency limits
- If a previous execution is still running when the next trigger fires, the new execution is queued or skipped (configurable)
- The hub monitors resource usage and can pause schedules if the system is under load

## [​](#routing-results) Routing Results

Combine scheduled agents with [connectors](/cli/connectors) in CLI to route results to messaging platforms:

```
# Start a Telegram connector
cline connect telegram -k $BOT_TOKEN

# Schedule an agent whose output gets sent to Telegram
cline schedule create "Morning briefing" \
  --cron "0 8 * * *" \
  --prompt "Summarize overnight activity in the repo"
```

Was this page helpful?

YesNo

[Creating Custom Tools](/sdk/guides/creating-custom-tools)[Events](/sdk/events)

⌘I

---

## Writing Plugins

*Source: [https://docs.cline.bot/sdk/guides/writing-plugins](https://docs.cline.bot/sdk/guides/writing-plugins)*

Plugins are the primary way to package reusable agent capabilities. This guide walks through building a production-quality plugin from scratch.

## [​](#what-you’ll-build) What You’ll Build

A GitHub integration plugin that:

- Registers tools for interacting with GitHub (list issues, create PRs, post comments)
- Logs all tool calls for auditing
- Tracks token usage per session

## [​](#step-1-define-the-plugin-structure) Step 1: Define the Plugin Structure

```
// github-plugin.ts
import { type AgentPlugin } from "@cline/sdk"
import { createTool } from "@cline/sdk"

interface GitHubConfig {
  token: string
  owner: string
  repo: string
}

export function createGitHubPlugin(config: GitHubConfig): AgentPlugin {
  let totalTokens = 0

  return {
    name: "github-integration",
    manifest: {
      capabilities: ["tools", "hooks"],
    },

    setup(api, ctx) {
      // Register tools in the setup phase
      api.registerTool(createListIssuesTool(config))
      api.registerTool(createCreateIssueTool(config))
      api.registerTool(createPostCommentTool(config))
    },

    hooks: {
      beforeRun() {
        console.log(`[github] Run started`)
      },

      beforeTool(context) {
        console.log(`[github] Tool: ${context.toolCall.name}(${JSON.stringify(context.input).slice(0, 100)})`)
      },

      afterRun(context) {
        const usage = context.result.usage
        totalTokens += (usage?.inputTokens ?? 0) + (usage?.outputTokens ?? 0)
        console.log(`[github] Run complete. Session tokens so far: ${totalTokens}`)
      },
    },
  }
}
```

## [​](#step-2-create-the-tools) Step 2: Create the Tools

```
function createListIssuesTool(config: GitHubConfig) {
  return createTool({
    name: "list_github_issues",
    description: `List open issues in ${config.owner}/${config.repo}. Returns issue numbers, titles, labels, and assignees.`,
    inputSchema: {
      type: "object",
      properties: {
        state: {
          type: "string",
          enum: ["open", "closed", "all"],
          description: "Issue state filter. Default: open.",
        },
        labels: {
          type: "string",
          description: "Comma-separated label names to filter by (e.g., 'bug,priority:high').",
        },
        limit: {
          type: "number",
          description: "Maximum issues to return. Default: 10, max: 100.",
        },
      },
    },
    execute: async (input) => {
      const params = new URLSearchParams({
        state: input.state ?? "open",
        per_page: String(Math.min(input.limit ?? 10, 100)),
      })
      if (input.labels) params.set("labels", input.labels)

      const response = await fetch(
        `https://api.github.com/repos/${config.owner}/${config.repo}/issues?${params}`,
        { headers: { Authorization: `token ${config.token}` } }
      )

      const issues = await response.json()
      return {
        issues: issues.map((i: Record<string, unknown>) => ({
          number: i.number,
          title: i.title,
          state: i.state,
          labels: (i.labels as Array<{ name: string }>).map((l) => l.name),
          assignee: (i.assignee as { login: string } | null)?.login,
          createdAt: i.created_at,
        })),
        total: issues.length,
      }
    },
  })
}

function createCreateIssueTool(config: GitHubConfig) {
  return createTool({
    name: "create_github_issue",
    description: `Create a new issue in ${config.owner}/${config.repo}.`,
    inputSchema: {
      type: "object",
      properties: {
        title: { type: "string", description: "Issue title" },
        body: { type: "string", description: "Issue body (Markdown supported)" },
        labels: {
          type: "array",
          items: { type: "string" },
          description: "Labels to apply",
        },
      },
      required: ["title"],
    },
    execute: async (input) => {
      const response = await fetch(
        `https://api.github.com/repos/${config.owner}/${config.repo}/issues`,
        {
          method: "POST",
          headers: {
            Authorization: `token ${config.token}`,
            "Content-Type": "application/json",
          },
          body: JSON.stringify({
            title: input.title,
            body: input.body,
            labels: input.labels,
          }),
        }
      )

      const issue = await response.json()
      return { number: issue.number, url: issue.html_url }
    },
  })
}

function createPostCommentTool(config: GitHubConfig) {
  return createTool({
    name: "post_github_comment",
    description: `Post a comment on an issue or PR in ${config.owner}/${config.repo}.`,
    inputSchema: {
      type: "object",
      properties: {
        issueNumber: { type: "number", description: "Issue or PR number" },
        body: { type: "string", description: "Comment body (Markdown supported)" },
      },
      required: ["issueNumber", "body"],
    },
    execute: async (input) => {
      const response = await fetch(
        `https://api.github.com/repos/${config.owner}/${config.repo}/issues/${input.issueNumber}/comments`,
        {
          method: "POST",
          headers: {
            Authorization: `token ${config.token}`,
            "Content-Type": "application/json",
          },
          body: JSON.stringify({ body: input.body }),
        }
      )

      const comment = await response.json()
      return { id: comment.id, url: comment.html_url }
    },
  })
}
```

## [​](#step-3-use-the-plugin) Step 3: Use the Plugin

```
import { Agent } from "@cline/sdk"
import { createGitHubPlugin } from "./github-plugin"

const agent = new Agent({
  providerId: "anthropic",
  modelId: "claude-sonnet-4-6",
  apiKey: process.env.ANTHROPIC_API_KEY,
  systemPrompt: "You are a project manager assistant with access to GitHub.",
  plugins: [
    createGitHubPlugin({
      token: process.env.GITHUB_TOKEN,
      owner: "my-org",
      repo: "my-project",
    }),
  ],
})

await agent.run("List all open bugs and create a summary issue with the count")
```

## [​](#distributing-as-a-file-plugin) Distributing as a File Plugin

To load this plugin from a file in ClineCore, pass its path in `pluginPaths`:

```
// /absolute/path/to/github.ts
import { type AgentPlugin, createTool } from "@cline/sdk"

const plugin: AgentPlugin = {
  name: "github",
  manifest: { capabilities: ["tools"] },
  setup(api, ctx) {
    api.registerTool(
      createTool({
        name: "list_github_issues",
        // ... tool definition
      })
    )
  },
}

export default plugin
```

Then include it in session config:

```
import { ClineCore } from "@cline/sdk"

const cline = await ClineCore.create({ clientName: "my-app" })

await cline.start({
  config: {
    systemPrompt: "Use the GitHub plugin",
    // ...model/runtime config
    pluginPaths: ["/absolute/path/to/github.ts"],
  },
})
```

## [​](#distributing-via-cli-install) Distributing via CLI Install

Single-file plugins can be installed directly from a file URL:

```
cline plugin install https://github.com/your-org/your-repo/blob/main/plugins/github-plugin.ts
```

Single-file plugins can only import Node builtins and `@cline/*`. As soon as you need an npm dependency (`zod`, an HTTP client, etc.) you must ship as a package: a directory with a `package.json` that declares a `cline` field for entry points and your runtime `dependencies`. Dependencies under the `@cline/` scope are provided by the host runtime — the installer strips these and runs `npm install` for the rest, so declare any `@cline/*` package you import as an optional peer dependency:

```
{
  "cline": {
    "plugins": [{ "paths": ["./github-plugin.ts"], "capabilities": ["tools", "hooks"] }]
  },
  "dependencies": {
    "@octokit/rest": "^21.0.0"
  },
  "peerDependencies": {
    "@cline/sdk": "*"
  },
  "peerDependenciesMeta": {
    "@cline/sdk": {
      "optional": true
    }
  }
}
```

Users can also install package plugins from git, npm, or a local path:

```
cline plugin install https://github.com/your-org/cline-github-plugin.git
```

## [​](#bundling-skills) Bundling Skills

Package plugins can include skills by adding a top-level `skills/` directory next to `package.json`:

```
cline-github-plugin/
  package.json
  github-plugin.ts
  skills/
    triage/
      SKILL.md
```

Each bundled skill follows the same directory format as any other [Cline skill](/customization/skills). When the plugin is installed or loaded through `pluginPaths`, Cline discovers those skills automatically.
See [Plugins](/customization/plugins) for the full manifest format, directory layout, and the [typescript-lsp-plugin](https://github.com/cline/typescript-lsp-plugin) for a complete working example.

## [​](#plugin-design-guidelines) Plugin Design Guidelines

1. Use factory functions (like `createGitHubPlugin`) when the plugin needs configuration. Export the plugin object directly when it doesn’t.
2. Keep `setup()` synchronous and fast. It runs before the first LLM call, so any async initialization delays the agent.
3. Register all tools in `setup()`, not in lifecycle hooks. Tools must be available before the first iteration.
4. Use lifecycle hooks for observation (logging, metrics, auditing), not for modifying agent behavior. If you need to modify behavior, consider using the `beforeRun` or `beforeModel` hooks to adjust the system prompt or context.
5. Handle errors gracefully in hooks. A thrown error in `beforeTool` will count as a tool failure. If your hook is purely observational, catch errors internally.

Was this page helpful?

YesNo

[Installing Plugins](/sdk/plugin-install)[Plugin Examples](/sdk/plugin-examples)

⌘I

---

## Model Providers

*Source: [https://docs.cline.bot/sdk/model-providers](https://docs.cline.bot/sdk/model-providers)*

The `@cline/llms` package provides provider registries, model catalogs, handlers, and a gateway. `@cline/agents` and `@cline/core` use this layer internally.

## [​](#configure-a-provider) Configure a Provider

```
const agent = new Agent({
  providerId: "anthropic",
  modelId: "claude-sonnet-4-6",
  apiKey: process.env.ANTHROPIC_API_KEY,
  // ...
})
```

Provider config can include `apiKey`, `baseUrl`, `headers`, and provider-specific settings through core/provider config types.
Common environment variables:

| Provider | Environment variable |
| --- | --- |
| Anthropic | `ANTHROPIC_API_KEY` |
| OpenAI | `OPENAI_API_KEY` |
| Google | `GOOGLE_API_KEY` or `GOOGLE_APPLICATION_CREDENTIALS` |
| AWS Bedrock | `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`, `AWS_SESSION_TOKEN` |
| Mistral | `MISTRAL_API_KEY` |

## [​](#openai-compatible-providers) OpenAI-Compatible Providers

Use `openai-compatible` for providers that expose an OpenAI-compatible API:

```
const agent = new Agent({
  providerId: "openai-compatible",
  modelId: "your-model-name",
  apiKey: process.env.PROVIDER_API_KEY,
  baseUrl: "https://your-provider.com/v1",
})
```

## [​](#aws-bedrock) AWS Bedrock

Bedrock uses AWS credentials from the standard environment/SDK chain and provider-specific config:

```
const agent = new Agent({
  providerId: "bedrock",
  modelId: "anthropic.claude-sonnet-4-6",
  providerConfig: {
    awsRegion: "us-east-1",
  },
})
```

## [​](#gateway-api) Gateway API

Use `DefaultGateway` or `createGateway` when you need direct provider/model access:

```
import { DefaultGateway } from "@cline/llms"

const gateway = new DefaultGateway()

const providers = gateway.listProviders()
const model = gateway.createAgentModel({
  providerId: "anthropic",
  modelId: "claude-sonnet-4-6",
})
```

The package also exports registry helpers such as `getAllProviders`, `getProviderIds`, `getModelsForProvider`, `registerProvider`, and `registerModel`.
See [Gateway reference](/sdk/reference/gateway) for exact APIs.

## [​](#model-metadata) Model Metadata

Models expose metadata for selection and cost calculations:

```
interface ModelInfo {
  id: string
  name?: string
  contextWindow?: number
  maxTokens?: number
  pricing?: {
    input?: number
    output?: number
    cacheCreation?: number
    cacheRead?: number
  }
  capabilities?: Record<string, unknown>
}
```

## [​](#cost-tracking) Cost Tracking

Agent results and usage events include token usage:

```
const result = await agent.run("Analyze this codebase")

console.log(result.usage.inputTokens)
console.log(result.usage.outputTokens)
console.log(result.usage.totalCost)
```

Was this page helpful?

YesNo

[Events](/sdk/events)[ClineCore](/sdk/clinecore)

⌘I

---

## Overview

*Source: [https://docs.cline.bot/sdk/overview](https://docs.cline.bot/sdk/overview)*

The Cline SDK is an open source framework for building agentic applications, and is the same harness used in the Cline IDE extensions and CLI. It uses a plugin architecture that makes it easy to customize and comes with all the features you expect from agents like checkpoints, web fetch, MCPs, cron jobs, subagents, and more.
Use the Cline SDK to run agents from CI/CD pipelines, create automations for end-to-end workflows, or embed agents directly inside your products.

## [​](#install) Install

```
npm install @cline/sdk
```

`@cline/sdk` exports all SDK packages: `@cline/core` for the full agent harness, `@cline/agents` for the stateless agent loop, `@cline/llms` for control over the model gateway, and `@cline/shared` for common utilities.
Requires Node.js 22 or later.

## [​](#sdk-skill) SDK Skill

If you use a coding agent (Claude Code, Codex, Cline, etc.), install the [Cline SDK skill](https://github.com/cline/sdk-skill) to give your agent context on the SDK’s APIs and best practices to help you build with the Cline SDK.

```
npx skills add cline/sdk-skill
```

Prompt it to scaffold agents, create custom tools, wire up plugins, configure providers, and more.

## [​](#your-first-agent) Your First Agent

```
import { Agent } from "@cline/sdk"

const agent = new Agent({
  providerId: "anthropic",
  modelId: "claude-sonnet-4-6",
  apiKey: process.env.ANTHROPIC_API_KEY,
  maxIterations: 1,
})

agent.subscribe((event) => {
  if (event.type === "assistant-text-delta") {
    process.stdout.write(event.text ?? "")
  }
})

const result = await agent.run("Explain what an SDK is in two sentences.")
```

Here is a complete [quickstart example](https://github.com/cline/cline/tree/main/apps/examples/quickstart). Clone it and run `bun dev` to try it.

## [​](#packages) Packages

| Package | Purpose |
| --- | --- |
| `@cline/sdk` | Public SDK surface (re-exports `@cline/core`) |
| `@cline/core` | Node runtime for sessions, built-in tools, persistence, hub support, automation |
| `@cline/agents` | Browser-compatible stateless agent execution loop |
| `@cline/llms` | Provider gateway and model catalogs |
| `@cline/shared` | Types, schemas, tool helpers, hooks, storage helpers |

See [Packages](/sdk/architecture/overview) for package boundaries and exports.

## [​](#next-steps) Next Steps

## Examples

Browse complete, runnable SDK examples.

## Plugins

Extend Cline’s functionality.

## Tools

Add actions the model can call.

## Building an Agent

Build a complete SDK agent from a tutorial.

Was this page helpful?

YesNo

[Examples](/sdk/examples)

⌘I

---

## Plugin Examples

*Source: [https://docs.cline.bot/sdk/plugin-examples](https://docs.cline.bot/sdk/plugin-examples)*

The [SDK repository](https://github.com/cline/cline/tree/main/sdk) includes installable plugin examples under [`examples/plugins/`](https://github.com/cline/cline/tree/main/sdk/examples/plugins). Use them as starting points for tools, lifecycle hooks, message rewriting, policy enforcement, background jobs, and multi-agent workflows.

## [​](#examples) Examples

| Example | What it shows |
| --- | --- |
| [`weather-metrics.ts`](https://github.com/cline/cline/blob/main/sdk/examples/plugins/weather-metrics.ts) | Tool registration plus lifecycle metrics hooks. Best starting point. |
| [`mac-notify.ts`](https://github.com/cline/cline/blob/main/sdk/examples/plugins/mac-notify.ts) | macOS Notification Center alert from an `afterRun` hook. |
| [`custom-compaction.ts`](https://github.com/cline/cline/blob/main/sdk/examples/plugins/custom-compaction.ts) | Provider-message compaction with `registerMessageBuilder`. |
| [`background-terminal.ts`](https://github.com/cline/cline/blob/main/sdk/examples/plugins/background-terminal.ts) | Detached shell jobs with persisted logs and optional session steering. |
| [`automation-events.ts`](https://github.com/cline/cline/blob/main/sdk/examples/plugins/automation-events.ts) | Plugin-emitted automation events. |
| [`gitignore-read-files-guard.ts`](https://github.com/cline/cline/blob/main/sdk/examples/plugins/gitignore-read-files-guard.ts) | Runtime hook policy that blocks file access outside workspace `.gitignore` boundaries. |
| [`web-search.ts`](https://github.com/cline/cline/blob/main/sdk/examples/plugins/web-search.ts) | `web_search` tool backed by an Exa API key. |
| [`typescript-lsp/`](https://github.com/cline/cline/tree/main/sdk/examples/plugins/typescript-lsp) | `goto_definition` tool powered by the TypeScript Language Service. |
| [`agents-squad/`](https://github.com/cline/cline/tree/main/sdk/examples/plugins/agents-squad) | Multi-agent team with subagents that have their own models and personalities. |

## [​](#try-a-file-plugin-with-the-cli) Try a File Plugin with the CLI

The CLI auto-discovers plugins from `.cline/plugins` in the workspace, `~/.cline/plugins`, and the system plugins folder.

```
cline plugin install https://github.com/cline/cline/blob/main/sdk/examples/plugins/weather-metrics.ts --cwd .
cline -i "What's the weather like in Tokyo and Paris?"
```

Swap `weather-metrics.ts` for any other single-file plugin example.

## [​](#block-ignored-file-access) Block Ignored File Access

Use `gitignore-read-files-guard.ts` to block tools from reading or editing files ignored by workspace `.gitignore` files:

```
cline plugin install https://github.com/cline/cline/blob/main/sdk/examples/plugins/gitignore-read-files-guard.ts --cwd .
cline -i "Read the ignored .env file"
```

The guard uses the `beforeTool` runtime hook. When a `read_files`, `editor`, or `apply_patch` call targets an ignored workspace file, the hook returns `{ skip: true }`, so the tool records a policy error and does not access the file.

## [​](#install-a-directory-plugin) Install a Directory Plugin

For a plugin that lives in a directory with its own `package.json`, use `cline plugin install`:

```
cline plugin install ./examples/plugins/agents-squad
```

See [Installing Plugins](/sdk/plugin-install) for more install options.

## [​](#add-web-search) Add Web Search

The `web-search.ts` plugin registers a `web_search` tool backed by Exa. Use `web_search` to discover relevant URLs, then use `fetch_web_content` when the agent needs to inspect a specific page.

```
cline plugin install https://github.com/cline/cline/blob/main/sdk/examples/plugins/web-search.ts --cwd .

export EXA_API_KEY=...
export OPENROUTER_API_KEY=...

cline auth --provider openrouter --apikey "$OPENROUTER_API_KEY" --modelid anthropic/claude-sonnet-4.6
cline -P openrouter -m anthropic/claude-sonnet-4.6 "Search the web for recent Bun release notes, then fetch the most relevant page"
```

`EXA_API_KEY` authenticates the search backend. The CLI still needs a normal model provider key or saved provider auth for inference.

## [​](#custom-message-compaction) Custom Message Compaction

Use `registerMessageBuilder` when a plugin needs to rewrite the provider-bound message list before the model call.

| Example | Extension point | Best for |
| --- | --- | --- |
| [`custom-compaction.ts`](https://github.com/cline/cline/blob/main/sdk/examples/plugins/custom-compaction.ts) | `api.registerMessageBuilder()` | Reusable, plugin-owned compaction policies. |
| [`custom-compaction-hook.example.ts`](https://github.com/cline/cline/blob/main/sdk/examples/hooks/custom-compaction-hook.example.ts) | `hooks.beforeModel` | Runtime hook logic that needs runtime hook context or direct request mutation. |

Prefer the message-builder version for normal compaction. It runs in the core message pipeline before the built-in safety builder, multiple builders run in registration order, and the final pass enforces provider-safe truncation.

## [​](#background-terminal-plugin) Background Terminal Plugin

`background-terminal.ts` registers three tools for long-running shell jobs:

| Tool | Purpose |
| --- | --- |
| `start_background_command` | Starts a detached shell command, returns a job ID immediately, and captures stdout/stderr under Cline’s data directory. |
| `get_background_command` | Reads job status plus recent stdout/stderr tails. |
| `delete_background_command` | Deletes saved job metadata and optionally deletes captured logs. |

When `notifyParent` is true, the plugin emits a `steer_message` after the command exits, pushing a completion summary back into the active session so the agent can react to long-running commands without blocking the original tool call.

Was this page helpful?

YesNo

[Writing Plugins](/sdk/guides/writing-plugins)[Tools](/sdk/tools)

⌘I

---

## Plugin Install

*Source: [https://docs.cline.bot/sdk/plugin-install](https://docs.cline.bot/sdk/plugin-install)*

The Cline CLI provides a `plugin install` command to install plugins from various sources. You can also load plugins programmatically via session config.

## [​](#cli-installation) CLI Installation

Use the `cline plugin install` command to install plugins from file URLs, npm, git repositories, or local paths.

```
cline plugin install <source> [options]
```

The shorthand `cline plugin i` works as well.

### [​](#install-from-a-file-url) Install from a File URL

```
cline plugin install https://github.com/cline/cline/blob/main/sdk/examples/plugins/weather-metrics.ts
cline plugin install https://raw.githubusercontent.com/cline/cline/main/sdk/examples/plugins/weather-metrics.ts
```

Installs a single `.ts` or `.js` plugin file from an HTTPS URL. GitHub `blob` URLs are normalized to raw file downloads automatically.

### [​](#install-from-npm) Install from npm

```
cline plugin install --npm @scope/plugin-name
```

Installs the package from the npm registry into the Cline plugin directory.

### [​](#install-from-git) Install from Git

```
cline plugin install --git https://github.com/owner/repo.git
cline plugin install --git github.com/owner/repo
```

Clones the repository (shallow, with blobless filter for speed) and installs its dependencies. The `.git` directory is excluded from the final install.

### [​](#install-from-local-source) Install from Local Source

```
cline plugin install ./path/to/plugin.ts     # Single file
cline plugin install /absolute/path/to/dir   # Directory with package.json
```

Supports both files and directories. Local installs copy the source, filter out `.git` and `node_modules`, and run `npm install` to resolve dependencies.

### [​](#options) Options

| Option | Description |
| --- | --- |
| `--npm` | Treat the source as an npm package name |
| `--git` | Treat the source as a git repository URL |
| `--force` | Overwrite an existing plugin at the same path |
| `--json` | Output results as JSON (useful for scripting) |
| `--cwd` | Install to `<path>/.cline/plugins` and resolve relative local paths from `<path>` |

### [​](#examples) Examples

```
# Install a local plugin directory
cline plugin install ./my-custom-plugin

# Install a single plugin file from GitHub
cline plugin install https://github.com/cline/cline/blob/main/sdk/examples/plugins/weather-metrics.ts

# Install an npm package as a plugin
cline plugin install --npm @cline/plugin-sql

# Install from a GitHub repo
cline plugin install --git https://github.com/my-org/my-plugin.git

# Force reinstall an existing plugin
cline plugin install --force --npm @scope/plugin-name

# Use shorthand
cline plugin i --git github.com/owner/repo
```

### [​](#listing-installed-plugins) Listing Installed Plugins

Installed plugins appear in the `plugins` section of your CLI config:

```
cline config
```

### [​](#find-all-your-plugins-from-your-file-system) Find All Your Plugins from your file system

Project-scoped plugins live in the `.cline/plugins/` folder at your workspace root. The CLI auto-discovers plugins from this folder when you run Cline in that project.

```
your-project/
├── .cline/
│   └── plugins/
│       ├── my-plugin.ts
│       └── another-plugin/
└── ...
```

To add a single-file plugin to a project, install it with `--cwd`:

```
cline plugin install https://github.com/owner/repo/blob/main/plugins/my-plugin.ts --cwd .
```

Global plugins are discovered from `~/.cline/plugins/`, and Cline may also discover plugins from the system Plugins folder. Use `--cwd .` when you want plugins to stay with a specific project.

## [​](#programmatic-installation) Programmatic Installation

### [​](#using-pluginpaths-clinecore) Using `pluginPaths` (ClineCore)

In SDK code, load plugins from file paths using the `pluginPaths` session config option:

```
import { ClineCore } from "@cline/sdk"

const cline = await ClineCore.create({ clientName: "my-app" })

await cline.start({
  config: {
    systemPrompt: "Analyze this project",
    // ...model/runtime config
    pluginPaths: ["/absolute/path/to/plugin.ts"],
  },
})
```

Plugin files must export an `AgentPlugin` as the default export. `pluginPaths` also accepts a package directory — the SDK reads `package.json` and follows the `cline.plugins` entries, so you can `npm install` once inside a package and iterate without re-running `cline plugin install` on every edit.

### [​](#using-plugins-agent-runtime) Using `plugins` (Agent Runtime)

When using the `Agent` or `AgentRuntime` directly, pass plugin instances in the `plugins` array:

```
import { Agent } from "@cline/sdk"
import { myPlugin } from "./my-plugin"

const agent = new Agent({
  providerId: "anthropic",
  modelId: "claude-sonnet-4-6",
  plugins: [myPlugin],
})
```

### [​](#using-extensions-clinecore) Using `extensions` (ClineCore)

With `ClineCore`, use the `extensions` config array instead:

```
import { ClineCore } from "@cline/sdk"

const cline = await ClineCore.create({ clientName: "my-app" })

await cline.start({
  config: {
    systemPrompt: "Analyze customer records",
    extensions: [myPlugin],
  },
})
```

## [​](#next-steps) Next Steps

- **Learn about [Plugins](/sdk/plugins)** — Understand what plugins are and their benefits.
- **Follow the [Writing Plugins](/sdk/guides/writing-plugins) guide** — Build and distribute your own plugin.
- Explore [Plugin Examples](/sdk/plugin-examples) to install ready-to-run plugin examples from the SDK repository.

Was this page helpful?

YesNo

[Plugins](/sdk/plugins)[Writing Plugins](/sdk/guides/writing-plugins)

⌘I

---

## Plugins

*Source: [https://docs.cline.bot/sdk/plugins](https://docs.cline.bot/sdk/plugins)*

Plugins are packages of reusable agent capabilities. They let you bundle tools, lifecycle hooks, commands, and configuration into a single module that can be shared across projects or published for others to use.

## [​](#benefits-of-plugins) Benefits of Plugins

| Benefit | Description |
| --- | --- |
| **Modularity** | Encapsulate related tools and hooks in a single unit. No more scattered logic. |
| **Reusability** | Share plugins across agents, projects, or teams. Publish to npm or distribute via git. |
| **Packaging** | Bundle tools, hooks, commands, message builders, and providers together. |
| **Observability** | Hook into every stage of the agent lifecycle — run start/end, model calls, tool calls, errors. |
| **Composability** | Combine multiple plugins in a single agent. Each plugin handles its own domain. |

## [​](#extension-glossary) Extension Glossary

| Extension point | What it does |
| --- | --- |
| **Tool** | Lets the model call an action (query a DB, call an API, etc.) |
| **Command** | Register slash commands to allow actions to be manually triggered |
| **Hook** | Runs lifecycle logic or policy checks at specific stages |
| **Rules** | Prompts that steer the agent and will be included in every session |
| **Events** | Register external events that will trigger agent actions |
| **Plugin** | Packages tools, hooks, commands, rules, and automation events together |

| If you need to… | Use a… |
| --- | --- |
| Allow the model to query a database, call an API, run a domain action | **Tool** |
| Register a user triggered action (slash command) | **Command** |
| Log runs, collect metrics, enforce policy | **Hook** handler |
| Block dangerous tool calls | **Hook** or approval policy |
| Provide consistent guidance to the model via prompts | **Rule** |
| Trigger agent action on an external event (new PR, Slack message, etc) | **Event** |
| Bundle several tools into a reusable module | **Plugin** |

## [​](#what-is-a-plugin) What is a Plugin?

A plugin is an `AgentPlugin` — an object that implements the SDK’s extension interface. It can register tools, hook into agent lifecycle events, and provide configuration defaults.

```
import { type AgentPlugin } from "@cline/sdk"

const myPlugin: AgentPlugin = {
  name: "my-plugin",
  manifest: {
    capabilities: ["tools", "hooks"],
  },
  setup(api, ctx) {
    // Register tools, commands, providers via api.registerTool(), etc.
  },
  hooks: {
    beforeTool(context) {
      // Observe or audit tool calls before they execute
    },
    afterRun(context) {
      // Log metrics, cleanup, notify after a run completes
    },
  },
}
```

Hooks are defined inside the `hooks` object, not directly on the extension. The available lifecycle hooks are `beforeRun`, `afterRun`, `beforeModel`, `afterModel`, `beforeTool`, `afterTool`, and `onEvent`.

## [​](#next-steps) Next Steps

Register with `ClineCore`:

```
await cline.start({
  prompt: "Analyze customer records",
  config: {
    // ...model/runtime config
    extensions: [databasePlugin],
  },
})
```

## [​](#file-based-plugins) File-Based Plugins

`ClineCore` supports plugin module paths via `pluginPaths` in session config:

```
await cline.start({
  prompt: "Analyze this project",
  config: {
    // ...model/runtime config
    pluginPaths: ["/absolute/path/to/plugin.ts"],
  },
})
```

Plugin files export an `AgentPlugin`.

## [​](#installing-plugins-via-cli) Installing Plugins via CLI

Plugins can also be installed from file URLs, npm, git, or local paths using `cline plugin install`. See [Plugins](/customization/plugins) for install commands, the manifest format, and directory layout.

## [​](#hook-stages) Hook Stages

Hook stages include:

```
input
runtime_event
session_start
run_start
iteration_start
turn_start
before_agent_start
tool_call_before
tool_call_after
turn_end
stop_error
iteration_end
run_end
session_shutdown
error
```

Common stages:

| Stage | Use for |
| --- | --- |
| `before_agent_start` | Inject context or modify prompt/messages |
| `run_start` | Logging, timers, rate limits |
| `tool_call_before` | Audit or block tool calls |
| `tool_call_after` | Log results, trigger side effects |
| `run_end` | Metrics, notifications, cleanup |
| `error` | Error reporting |

## [​](#hook-policies) Hook Policies

Hook policies control execution behavior:

| Field | Meaning |
| --- | --- |
| `mode` | `"blocking"` or `"async"` |
| `timeoutMs` | Hook timeout |
| `retries` | Retry count |
| `retryDelayMs` | Delay between retries |
| `failureMode` | `"fail_open"` or `"fail_closed"` |
| `maxConcurrency` | Concurrent hook executions |
| `queueLimit` | Queue size before dropping |

Use `fail_closed` for policy-enforcement hooks where bypassing the hook is unsafe.

## [​](#build-a-plugin) Build a Plugin

For a step-by-step plugin tutorial, see [Writing Plugins](/sdk/guides/writing-plugins).

## [​](#sdk-examples) SDK Examples

The [SDK repository](https://github.com/cline/cline/tree/main/sdk) includes ready-to-run plugin examples under [`examples/plugins/`](https://github.com/cline/cline/tree/main/sdk/examples/plugins), including tool registration, lifecycle metrics, notifications, custom compaction, policy guards, web search, background jobs, TypeScript LSP tools, and multi-agent teams.
See [Plugin Examples](/sdk/plugin-examples) for the full list and usage commands.

Was this page helpful?

YesNo

[Examples](/sdk/examples)[Installing Plugins](/sdk/plugin-install)

⌘I

---

## Agent

*Source: [https://docs.cline.bot/sdk/reference/agent](https://docs.cline.bot/sdk/reference/agent)*

`Agent` is an alias for `AgentRuntime` from `@cline/agents`.

```
import { Agent, AgentRuntime, createAgent, createAgentRuntime } from "@cline/sdk"
```

## [​](#constructor) Constructor

```
new Agent(config: AgentRuntimeConfig)
```

`AgentRuntimeConfig` accepts either:

- a prebuilt `model: AgentModel`, or
- `providerId`, `modelId`, and optional provider credentials (`apiKey`, `baseUrl`, `headers`).

Common fields:

| Field | Type | Required | Description |
| --- | --- | --- | --- |
| `providerId` | `string` | Yes, unless `model` supplied | Provider ID |
| `modelId` | `string` | Yes, unless `model` supplied | Model ID |
| `apiKey` | `string` | No | Provider API key |
| `baseUrl` | `string` | No | Custom provider base URL |
| `systemPrompt` | `string` | No | System instructions |
| `tools` | `AgentTool[]` | No | Tools available to the runtime |
| `initialMessages` | `AgentMessage[]` | No | Preloaded conversation |
| `toolPolicies` | `Record<string, ToolPolicy>` | No | Per-tool enablement/approval |
| `hooks` | `AgentRuntimeHooks` | No | Runtime lifecycle hooks |

## [​](#methods) Methods

### [​](#run-input) `run(input)`

```
const result = await agent.run("Analyze this codebase")
```

Starts a run with input.

### [​](#continue-input) `continue(input?)`

```
const result = await agent.continue("Now inspect the auth module")
```

Continues with optional new input.

### [​](#abort-reason) `abort(reason?)`

```
agent.abort("User cancelled")
```

Aborts the active run.

### [​](#subscribe-listener) `subscribe(listener)`

```
const unsubscribe = agent.subscribe((event) => {
  console.log(event.type)
})
```

Subscribes to `AgentRuntimeEvent` events.

### [​](#restore-messages) `restore(messages)`

```
agent.restore(savedMessages)
```

Replaces conversation history and resets runtime state while preserving tools, hooks, model, agent identity, and subscribers.

### [​](#snapshot) `snapshot()`

```
const state = agent.snapshot()
```

Returns an `AgentRuntimeStateSnapshot`.

## [​](#agentrunresult) AgentRunResult

```
interface AgentRunResult {
  agentId: string
  agentRole?: string
  runId: string
  status: "completed" | "aborted" | "failed"
  iterations: number
  outputText: string
  messages: readonly AgentMessage[]
  usage: AgentUsage
  error?: Error
}
```

## [​](#factories) Factories

```
const agent = createAgent(config)
const runtime = createAgentRuntime(config)
```

Was this page helpful?

YesNo

[ClineCore](/sdk/reference/cline-core)[Gateway](/sdk/reference/gateway)

⌘I

---

## Cline Core

*Source: [https://docs.cline.bot/sdk/reference/cline-core](https://docs.cline.bot/sdk/reference/cline-core)*

```
import { ClineCore } from "@cline/sdk"
```

## [​](#clinecore-create-options) `ClineCore.create(options)`

```
const cline = await ClineCore.create({
  clientName: "my-app",
  backendMode: "auto",
})
```

Common options:

| Option | Type | Description |
| --- | --- | --- |
| `clientName` | `string` | Human-readable SDK client name |
| `distinctId` | `string` | Stable telemetry/user identifier |
| `backendMode` | `"auto" | "local" | "hub" | "remote"` | Runtime backend selection |
| `hub` | `HubOptions` | Local hub connection options |
| `remote` | `RemoteOptions` | Remote hub options |
| `capabilities` | `RuntimeCapabilities` | Client-owned tool executors and approval callbacks |
| `toolPolicies` | `Record<string, ToolPolicy>` | Default tool approval policies |
| `automation` | `boolean | ClineCoreAutomationOptions` | Enable automation APIs |
| `fetch` | `typeof fetch` | Custom fetch for local provider calls |

## [​](#start-input) `start(input)`

```
const session = await cline.start({
  prompt: "Summarize this repo",
  config: {
    providerId: "anthropic",
    modelId: "claude-sonnet-4-6",
    apiKey: process.env.ANTHROPIC_API_KEY,
    systemPrompt: "You are a helpful coding assistant.",
    cwd: process.cwd(),
    workspaceRoot: process.cwd(),
    enableTools: true,
    enableSpawnAgent: false,
    enableAgentTeams: false,
  },
})
```

### [​](#clinecorestartinput) ClineCoreStartInput

| Field | Type | Required | Description |
| --- | --- | --- | --- |
| `prompt` | `string` | No | Initial prompt |
| `config` | `CoreSessionConfig` | Yes | Session model/runtime config |
| `source` | `SessionSource` | No | Session source label |
| `interactive` | `boolean` | No | Whether session expects interaction |
| `sessionMetadata` | `Record<string, unknown>` | No | Metadata persisted with session |
| `initialMessages` | `Message[]` | No | Preloaded messages |
| `toolPolicies` | `Record<string, ToolPolicy>` | No | Per-session tool policies |
| `capabilities` | `RuntimeCapabilities` | No | Per-session tool executors and approval callbacks |

### [​](#startsessionresult) StartSessionResult

```
interface StartSessionResult {
  sessionId: string
  manifest: SessionManifest
  manifestPath: string
  messagesPath: string
  result?: AgentResult
}
```

## [​](#send-input) `send(input)`

```
const result = await cline.send({
  sessionId,
  prompt: "Continue with tests",
})
```

Returns `AgentResult | undefined`.

## [​](#session-apis) Session APIs

| Method | Description |
| --- | --- |
| `subscribe(listener, options?)` | Subscribe to `CoreSessionEvent` events |
| `list(limit?, options?)` | List session history records |
| `listHistory(options?)` | List session history records |
| `get(sessionId)` | Get session metadata |
| `readMessages(sessionId)` | Read persisted messages |
| `getAccumulatedUsage(sessionId)` | Read accumulated token/cost usage |
| `update(sessionId, updates)` | Update prompt/title/metadata |
| `abort(sessionId, reason?)` | Abort active work |
| `stop(sessionId)` | Stop session |
| `delete(sessionId)` | Delete session |
| `restore(input)` | Restore from checkpoint |
| `dispose(reason?)` | Dispose runtime resources |

## [​](#automation-api) Automation API

When `automation` is enabled, use `cline.automation` to start/stop automation services, reconcile specs, ingest events, and list events/specs/runs.

Was this page helpful?

YesNo

[Going to Production](/sdk/guides/going-to-production)[Agent](/sdk/reference/agent)

⌘I

---

## Events

*Source: [https://docs.cline.bot/sdk/reference/events](https://docs.cline.bot/sdk/reference/events)*

The SDK exposes multiple event surfaces.

## [​](#agentruntimeevent) AgentRuntimeEvent

Direct `AgentRuntime` usage emits low-level runtime events through `agent.subscribe(listener)`.

```
const unsubscribe = agent.subscribe((event) => {
  console.log(event.type)
})
```

Common runtime events include model events, tool execution events, run lifecycle events, and failure events. Runtime results use `AgentRunResult.status` rather than `finishReason`.

## [​](#agentevent) AgentEvent

Core/host-facing agent events are emitted through `AgentConfig.onEvent` and core adapters.

| Event | Description |
| --- | --- |
| `content_start` | Text/reasoning/tool content begins |
| `content_update` | Tool progress update |
| `content_end` | Text/reasoning/tool content completes |
| `iteration_start` | Loop iteration begins |
| `iteration_end` | Loop iteration completes |
| `usage` | Token/cost usage update |
| `notice` | Runtime status/recovery notice |
| `done` | Agent completed/aborted/failed |
| `error` | Error occurred |

## [​](#done-event) Done Event

```
interface AgentDoneEvent {
  type: "done"
  reason: "completed" | "max_iterations" | "aborted" | "mistake_limit" | "error"
  text: string
  iterations: number
  usage?: LegacyAgentUsage
}
```

## [​](#usage-event) Usage Event

```
interface AgentUsageEvent {
  type: "usage"
  inputTokens: number
  outputTokens: number
  cacheReadTokens?: number
  cacheWriteTokens?: number
  cost?: number
  totalInputTokens: number
  totalOutputTokens: number
  totalCacheReadTokens?: number
  totalCacheWriteTokens?: number
  totalCost?: number
}
```

## [​](#coresessionevent) CoreSessionEvent

`ClineCore.subscribe(listener, options?)` emits session-level events from the runtime host.

```
const unsubscribe = cline.subscribe((event) => {
  console.log(event.type, event.sessionId)
}, { sessionId })
```

Was this page helpful?

YesNo

[Tools API](/sdk/reference/tools-api)[Types](/sdk/reference/types)

⌘I

---

## Gateway

*Source: [https://docs.cline.bot/sdk/reference/gateway](https://docs.cline.bot/sdk/reference/gateway)*

`DefaultGateway` creates provider-backed `AgentModel` instances and exposes provider/model catalog helpers.

```
import { DefaultGateway, createGateway } from "@cline/llms"
```

## [​](#constructor) Constructor

```
const gateway = new DefaultGateway({
  providerConfigs: [
    { providerId: "anthropic", apiKey: process.env.ANTHROPIC_API_KEY },
  ],
})
```

Or:

```
const gateway = createGateway({ providerConfigs: [...] })
```

## [​](#methods) Methods

### [​](#registerprovider-registration) `registerProvider(registration)`

```
gateway.registerProvider(registration)
```

Registers a `GatewayProviderRegistration`.

### [​](#configureprovider-config) `configureProvider(config)`

```
gateway.configureProvider({
  providerId: "anthropic",
  apiKey: process.env.ANTHROPIC_API_KEY,
})
```

Configures credentials/defaults for a provider.

### [​](#listproviders) `listProviders()`

```
const providers = gateway.listProviders()
```

Returns registered provider manifests.

### [​](#listmodels-providerid) `listModels(providerId?)`

```
const allModels = gateway.listModels()
const anthropicModels = gateway.listModels("anthropic")
```

Returns model metadata.

### [​](#createagentmodel-selection-options) `createAgentModel(selection, options?)`

```
const model = gateway.createAgentModel({
  providerId: "anthropic",
  modelId: "claude-sonnet-4-6",
})
```

Returns an `AgentModel` that can be passed to `AgentRuntime`.

### [​](#stream-request) `stream(request)`

```
const stream = await gateway.stream({
  providerId: "anthropic",
  modelId: "claude-sonnet-4-6",
  messages,
  tools: [],
})
```

Returns `AsyncIterable<AgentModelEvent>`.

## [​](#registry-helpers) Registry Helpers

`@cline/llms` also exports:

- `getAllProviders`
- `getProviderIds`
- `getProvider`
- `getModelsForProvider`
- `registerProvider`
- `registerModel`
- `createHandler`
- `createHandlerAsync`

## [​](#built-in-provider-families) Built-In Provider Families

The runtime includes built-in registrations for provider families including Anthropic, OpenAI, Gemini, Vertex, Bedrock, Mistral, Claude Code, OpenAI Codex, OpenCode, Dify, and OpenAI-compatible providers.

Was this page helpful?

YesNo

[Agent](/sdk/reference/agent)[Tools API](/sdk/reference/tools-api)

⌘I

---

## Tools Api

*Source: [https://docs.cline.bot/sdk/reference/tools-api](https://docs.cline.bot/sdk/reference/tools-api)*

## [​](#createtool-config) `createTool(config)`

```
import { createTool } from "@cline/sdk"
```

Creates a typed tool. Also re-exported from `@cline/agents` and `@cline/core`.

```
const tool = createTool({
  name: "get_current_time",
  description: "Return the current time as ISO string.",
  inputSchema: { type: "object", properties: {} },
  execute: async (_input, context) => {
    return { now: new Date().toISOString() }
  },
})
```

`inputSchema` can be either JSON Schema or a Zod schema.

## [​](#agenttool) AgentTool

```
interface AgentTool<TInput = unknown, TOutput = unknown> {
  name: string
  description: string
  inputSchema: Record<string, unknown>
  execute: (input: TInput, context: AgentToolContext, onChange?: (update: unknown) => void) => Promise<TOutput>
  timeoutMs?: number
  retryable?: boolean
  maxRetries?: number
}
```

Defaults from `createTool`:

| Field | Default |
| --- | --- |
| `timeoutMs` | `30000` |
| `retryable` | `true` |
| `maxRetries` | `3` |

## [​](#agenttoolcontext) AgentToolContext

```
interface AgentToolContext {
  agentId: string
  conversationId: string
  iteration: number
  abortSignal?: AbortSignal
  metadata?: Record<string, unknown>
}
```

## [​](#toolpolicy) ToolPolicy

```
interface ToolPolicy {
  enabled?: boolean
  autoApprove?: boolean
}
```

Tool names not listed in a policy map default to enabled and auto-approved.

## [​](#toolcallrecord) ToolCallRecord

```
interface ToolCallRecord {
  id: string
  name: string
  input: unknown
  output: unknown
  error?: string
  durationMs: number
  startedAt: Date
  endedAt: Date
}
```

Was this page helpful?

YesNo

[Gateway](/sdk/reference/gateway)[Events](/sdk/reference/events)

⌘I

---

## Types

*Source: [https://docs.cline.bot/sdk/reference/types](https://docs.cline.bot/sdk/reference/types)*

Most common types are exported from `@cline/shared`; runtime entry-point packages re-export selected helpers.

## [​](#agentruntime-types) AgentRuntime Types

```
import type {
  AgentMessage,
  AgentMessagePart,
  AgentRunResult,
  AgentRuntimeEvent,
  AgentRuntimeStateSnapshot,
  AgentUsage,
} from "@cline/sdk"
```

`AgentRunResult` is returned by direct `AgentRuntime` / `Agent` runs:

```
interface AgentRunResult {
  agentId: string
  agentRole?: string
  runId: string
  status: "completed" | "aborted" | "failed"
  iterations: number
  outputText: string
  messages: readonly AgentMessage[]
  usage: AgentUsage
  error?: Error
}
```

## [​](#host-facing-agent-types) Host-Facing Agent Types

```
import type {
  AgentConfig,
  AgentEvent,
  AgentResult,
  AgentPlugin,
  AgentTool,
  AgentToolContext,
  ToolPolicy,
} from "@cline/sdk"
```

`AgentResult` is the host/core-facing result shape:

```
interface AgentResult {
  text: string
  usage: LegacyAgentUsage
  messages: MessageWithMetadata[]
  toolCalls: ToolCallRecord[]
  iterations: number
  finishReason: "completed" | "max_iterations" | "aborted" | "mistake_limit" | "error"
  model: { id: string; provider: string; info?: ModelInfo }
  startedAt: Date
  endedAt: Date
  durationMs: number
}
```

## [​](#clinecore-types) ClineCore Types

```
import type {
  ClineCoreOptions,
  ClineCoreStartInput,
  CoreSessionConfig,
  SessionRecord,
} from "@cline/sdk"
```

## [​](#tool-types) Tool Types

```
interface ToolPolicy {
  enabled?: boolean
  autoApprove?: boolean
}
```

See [Tools API](/sdk/reference/tools-api) for the full tool surface.

Was this page helpful?

YesNo

[Events](/sdk/reference/events)

⌘I

---

## Tools

*Source: [https://docs.cline.bot/sdk/tools](https://docs.cline.bot/sdk/tools)*

Tools are functions the model can call during execution. Tools consist of a name, description, and schema which the SDK sends to the model. Then the model can direct the SDK to execute tool functions and send results back into the conversation.

## [​](#built-in-tools) Built-In Tools

`ClineCore` can enable the built-in tool suite:

| Tool | Description |
| --- | --- |
| `read_files` | Read one or more files |
| `search_codebase` | Search the workspace |
| `run_commands` | Execute shell commands |
| `fetch_web_content` | Fetch web content |
| `apply_patch` | Apply patch/diff edits |
| `editor` | Edit files |
| `skills` | Invoke configured skills |
| `ask_question` | Ask the user for input |
| `submit_and_exit` | Submit a final answer and stop |

If you need more control you can use the `Agents` package directly. This does not include built-in tools. You pass in only the tools you want when constructing the agent.

## [​](#custom-tools-with-createtool) Custom Tools with createTool

One of the most powerful features of the SDK is the ability to create and register custom tools. This allows you to add and share capabilities that are context efficient and behave deterministically because they are implemented in code rather than prompts.

### [​](#quick-example) Quick Example

Use `createTool` with a zod schema for type-safe tools:

```
import { createTool } from "@cline/sdk"
import { z } from "zod"

const searchDatabase = createTool({
  name: "search_database",
  description: "Search the application database. Returns matching records as JSON.",
  inputSchema: z.object({
    query: z.string().describe("Search query"),
    limit: z.number().optional().describe("Maximum results to return"),
  }),
  async execute(input) {
    const results = await db.search(input.query, input.limit ?? 10)
    return { results, count: results.length }
  },
})
```

`createTool` also accepts raw JSON Schema if you prefer:

```
const searchDatabase = createTool({
  name: "search_database",
  description: "Search the application database.",
  inputSchema: {
    type: "object",
    properties: {
      query: { type: "string", description: "Search query" },
      limit: { type: "number", description: "Maximum results to return" },
    },
    required: ["query"],
  },
  async execute(input) {
    return await db.search(input.query, input.limit ?? 10)
  },
})
```

For complete examples of tools in action, see the [cli-agent](https://github.com/cline/cline/tree/main/apps/examples/cli-agent) (shell tool) and [code-review-bot](https://github.com/cline/cline/tree/main/apps/examples/code-review-bot) (multiple tools with completion lifecycle).
For a full tutorial, see [Creating Custom Tools](/sdk/guides/creating-custom-tools). For exact types, see [Tools API](/sdk/reference/tools-api).

## [​](#registering-tools) Registering Tools

With `ClineCore`, custom tools are passed as `extraTools` in session config:

```
await cline.start({
  prompt: "Analyze customer records",
  config: {
    // ...
    extraTools: [searchDatabase],
  },
})
```

With `Agent`, you pass all tools into the constructor:

```
const agent = new Agent({
  tools: [searchDatabase, myOtherTool],
  // ...
})
```

Tools are more easily shared via plugins/extensions:

```
const plugin: AgentPlugin = {
  name: "database-tools",
  manifest: { capabilities: ["tools"] },
  setup(api) {
    api.registerTool(searchDatabase)
  },
}
```

See [Plugins](/sdk/plugins) for more info.

## [​](#tool-policies) Tool Policies

You can control how tools are used through Tool Policies. These control whether a tool is visible and whether it requires approval.

```
const agent = new Agent({
  tools: [readTool, writeTool, deleteTool],
  toolPolicies: {
    read_data: { autoApprove: true },
    write_data: { autoApprove: false },
    delete_data: { enabled: false },
  },
  // ...
})
```

| Policy | Effect |
| --- | --- |
| `{ autoApprove: true }` | Run without asking |
| `{ autoApprove: false }` | Ask before running |
| `{ enabled: false }` | Hide/disable the tool |

Tool names not listed in `toolPolicies` default to enabled and auto-approved.

## [​](#mcp-tools) MCP Tools

Tools work along side MCP. `ClineCore` can load MCP settings through its runtime/config extension path. MCP tools are registered alongside built-in and custom tools when MCP support is enabled for the session.

Was this page helpful?

YesNo

[Plugin Examples](/sdk/plugin-examples)[Creating Custom Tools](/sdk/guides/creating-custom-tools)

⌘I

---

## All Cline Tools

*Source: [https://docs.cline.bot/tools-reference/all-cline-tools](https://docs.cline.bot/tools-reference/all-cline-tools)*

Cline tools are executable functions the model can call while working. The model decides which tool to call, Cline runs it, then returns results back to the model.

## [​](#built-in-tools-clinecore) Built-In Tools (ClineCore)

When running through `ClineCore`, these built-ins are available:

| Tool | Description |
| --- | --- |
| `bash` | Execute shell commands |
| `editor` | View and edit files |
| `read_files` | Batch read multiple files |
| `apply_patch` | Apply unified diffs to files |
| `search` | Ripgrep-powered codebase search |
| `fetch_web` | HTTP requests with HTML-to-markdown conversion |
| `ask_question` | Ask the user for input |

`Agent` from `@cline/agents` does not include built-ins by default. You provide tools explicitly.

## [​](#tool-categories) Tool Categories

- **Codebase operations**: `editor`, `read_files`, `apply_patch`, `search`
- **Execution**: `bash`
- **External retrieval**: `fetch_web`
- **Human-in-the-loop controls**: `ask_question`

## [​](#approval-and-policy-controls) Approval and Policy Controls

Cline can run tools with approval or auto-approval, depending on settings/policies. Typical patterns:

- Require approval for risky tools (for example `bash`, write/edit operations)
- Auto-approve low-risk tools (for example read/search operations)
- Disable specific tools entirely when needed

For policy examples, see [SDK Tools](/sdk/tools) and [Permission Handling](/sdk/guides/permission-handling).

## [​](#mcp-tools) MCP Tools

Cline can also call tools discovered from MCP servers configured in `.cline/mcp.json`.
MCP tools are loaded alongside built-ins, so Cline can use both local tools and external integrations in one task.
See [MCP Overview](/mcp/mcp-overview) and [SDK Tools → MCP Tools](/sdk/tools#mcp-tools).

## [​](#custom-tools) Custom Tools

This feature currently only applies to Cline SDK, CLI, and Kanban. This feature is not applicable on VSCode and JetBrains Extension for now.

Beyond built-ins and MCP, you can create custom tools and add them through plugins.

- Define tool behavior and input schema in plugin code
- Register tools during plugin setup
- Expose those tools to agents alongside built-ins

See:

- [SDK Plugins](/sdk/plugins)
- [Writing Plugins (examples)](/sdk/guides/writing-plugins)
- [SDK Tools: Creating Custom Tools](/sdk/tools#creating-custom-tools)

## [​](#legacy-tool-names-vs-current-runtime-tools) Legacy Tool Names vs Current Runtime Tools

Some older docs/examples reference XML-style names like `read_file`, `replace_in_file`, or `execute_command`. Current SDK/ClineCore runtime uses the built-in tool names listed above (`read_files`, `apply_patch`, `bash`, etc.).

## [​](#related) Related

- [SDK Tools](/sdk/tools)
- [Tools API Reference](/sdk/reference/tools-api)
- [MCP Overview](/mcp/mcp-overview)

Was this page helpful?

YesNo

[Remote Access](/kanban/remote-access)[Rules](/customization/cline-rules)

⌘I

---

## Networking And Proxies

*Source: [https://docs.cline.bot/troubleshooting/networking-and-proxies](https://docs.cline.bot/troubleshooting/networking-and-proxies)*

If you’re working behind a corporate proxy or firewall, you’ll need to configure
proxy settings for Cline to connect to AI providers. The configuration varies
depending on which version of Cline you’re using.

## [​](#vscode-extension) VSCode Extension

The VSCode extension automatically uses VSCode’s built-in proxy settings. See
[Network Connections in Visual Studio Code, Proxy server support](https://code.visualstudio.com/docs/setup/network#_proxy-server-support)
for instructions on how to set up proxies in VSCode. No additional configuration
is needed for Cline itself.

## [​](#cli) CLI

The Cline CLI uses standard HTTP proxy environment variables. Configure these before running `cline` commands.

### [​](#basic-configuration) Basic Configuration

**Windows (Command Prompt)**

```
set https_proxy=http://proxy.company.com:8080
set http_proxy=http://proxy.company.com:8080
cline start
```

**Windows (PowerShell)**

```
$env:https_proxy="http://proxy.company.com:8080"
$env:http_proxy="http://proxy.company.com:8080"
cline start
```

**macOS/Linux**

```
export https_proxy=http://proxy.company.com:8080
export http_proxy=http://proxy.company.com:8080
cline start
```

### [​](#proxy-with-authentication) Proxy with Authentication

If your proxy requires authentication, include credentials in the URL:

```
export https_proxy=http://username:password@proxy.company.com:8080
export http_proxy=http://username:password@proxy.company.com:8080
```

Storing credentials in environment variables can be a security risk.

### [​](#bypass-proxy-for-localhost) Bypass Proxy for Localhost

To prevent localhost traffic from going through the proxy, set the `no_proxy` environment variable:
**Windows**

```
set no_proxy=localhost,127.0.0.1,.local
```

**macOS/Linux**

```
export no_proxy=localhost,127.0.0.1,.local
```

### [​](#custom-certificate-authority) Custom Certificate Authority

If your proxy uses a custom CA certificate:
**Windows**

```
set NODE_EXTRA_CA_CERTS=C:\path\to\ca-certificate.crt
cline start
```

**macOS/Linux**

```
export NODE_EXTRA_CA_CERTS=/path/to/ca-certificate.pem
cline start
```

### [​](#permanent-configuration) Permanent Configuration

To avoid setting these variables every time, add them to your shell profile or system environment variables.
**macOS/Linux** (add to `~/.bashrc`, `~/.zshrc`, or `~/.profile`):

```
# Proxy configuration
export https_proxy=http://proxy.company.com:8080
export http_proxy=http://proxy.company.com:8080
export no_proxy=localhost,127.0.0.1,.local
export NODE_EXTRA_CA_CERTS=/path/to/ca-certificate.pem
```

**Windows** (System Environment Variables):

1. Search for “Environment Variables” in Windows Settings
2. Add the variables under “User variables” or “System variables”
3. Restart your terminal or IDE

### [​](#known-limitations) Known Limitations

Cline CLI only supports HTTP proxies. It does not support SOCKS proxies,
proxy autoconfiguration (PAC) scripts, or HTTP proxies which require
authentication beyond a basic username and password.

## [​](#jetbrains-ides) JetBrains IDEs

The JetBrains plugin uses the IDE’s HTTP proxy settings.

### [​](#configure-jetbrains-proxy) Configure JetBrains Proxy

1. Open Settings/Preferences:
   - **Windows/Linux**: File > Settings
   - **macOS**: IntelliJ IDEA > Preferences
   - Or press `Ctrl+Alt+S` (Windows/Linux) or `Cmd+,` (macOS)
2. Navigate to:

   ```
   Appearance & Behavior > System Settings > HTTP Proxy
   ```
3. Select “Manual proxy configuration”
4. Configure your proxy:
   - **Host name**: `proxy.company.com`
   - **Port number**: `8080`
   - **No proxy for**: `localhost,127.0.0.1`
   - Check “Proxy authentication” if required
   - Enter your username and password
5. Click “Check connection” to verify the settings
6. Click “OK” to apply
7. Restart the IDE

### [​](#test-connection) Test Connection

After configuring the proxy, test that Cline can connect to your AI provider:

1. Open the Cline panel
2. Try sending a simple message
3. If connection fails, check the IDE’s Event Log for error messages

### [​](#custom-certificate-authority-2) Custom Certificate Authority

If your proxy uses a custom CA:

1. Add the certificate to your system’s trust store, or
2. Import it into the JetBrains IDE:
   - Settings > Tools > Server Certificates
   - Click ”+” to add your certificate

### [​](#known-limitations-2) Known Limitations

Cline in JetBrains only supports HTTP proxies. It does not support SOCKS
proxies, proxy autoconfiguration (PAC) scripts, or HTTP proxies which require
authentication beyond a basic username and password.
Cline does not pick up changed proxy settings dynamically. After changing proxy
settings, restart the IDE for Cline to use the new settings.

## [​](#troubleshooting) Troubleshooting

### [​](#connection-timeouts) Connection Timeouts

If you’re experiencing connection timeouts:

1. Verify your proxy address and port are correct
2. Check if the proxy requires authentication
3. Ensure the AI provider’s API endpoints aren’t blocked by your firewall

### [​](#ssl/tls-certificate-errors) SSL/TLS Certificate Errors

If you see certificate-related errors:

1. Check that `NODE_EXTRA_CA_CERTS` points to the correct certificate file
2. Ensure the certificate file is in PEM format
3. Use curl to verify the certificate works, for example, `curl -x proxy.corp.example:8080 --cacert /path/to/ca-cert.pem -o - -vv https://api.cline.bot/`
4. Consider disabling `http.proxyStrictSSL` in VSCode (not recommended for production)

### [​](#testing-proxy-configuration) Testing Proxy Configuration

If you encounter problems with Cline networking, first verify your proxy
configuration works using curl:

```
# Linux/macOS
export https_proxy=http://proxy.company.com:8080
curl -vv https://api.anthropic.com

# Windows PowerShell
$env:https_proxy="http://proxy.company.com:8080"
curl.exe -vv https://api.anthropic.com
```

Use `--cacert $NODE_EXTRA_CA_CERTS` to specify a certificate if necessary.
Next, check ~/.cline/cline-core-service.log (CLI, JetBrains) for log messages
confirming your proxy configuration and any network-related errors.

## [​](#common-proxy-patterns) Common Proxy Patterns

### [​](#authenticated-https-proxy) Authenticated HTTPS Proxy

```
export https_proxy=http://username:password@proxy.company.com:8080
export NODE_EXTRA_CA_CERTS=/path/to/ca-cert.pem
```

### [​](#proxy-with-no-authentication) Proxy with No Authentication

```
export https_proxy=http://proxy.company.com:8080
export http_proxy=http://proxy.company.com:8080
```

### [​](#proxy-with-bypass-rules) Proxy with Bypass Rules

```
export https_proxy=http://proxy.company.com:8080
export no_proxy=localhost,127.0.0.1,.company.local,192.168.0.0/16
```

Was this page helpful?

YesNo

[Multi-Root Workspaces](/features/multiroot-workspace)

⌘I

---

## Cli Overview

*Source: [https://docs.cline.bot/usage/cli-overview](https://docs.cline.bot/usage/cli-overview)*

## [​](#prerequisites) Prerequisites

- Cline CLI installed (install via `npm i -g cline`)
- Provider authenticated (`cline auth`) ([Authorization Guide](/getting-started/authorizing-with-cline#cli-setup))

## [​](#quick-start) Quick Start

```
# Interactive session
cline

# Run one task immediately
cline "refactor this module to use async/await"

# Structured output for scripts
cline --json "list TODO comments"
```

## [​](#headless-mode) Headless mode

Use headless mode for scripts/automation and processable output.
Headless is triggered when using flags like `--json`, when stdin is piped, or when output is redirected.

#### [​](#when-headless-activates) When headless activates

| Invocation | Reason |
| --- | --- |
| `cline --json "task"` | JSON output mode |
| `cat file | cline "task"` | stdin is piped |
| `cline "task" > output.txt` | stdout is redirected |

```
# CI/script style execution
git diff | cline "review these changes"

# JSON for parsing
cline --json "summarize this changelog" | jq -r '.text'
```

See: [Headless Mode](#headless-mode)

### [​](#autonomous-execution) Autonomous execution

For fully unattended runs, use auto-approval:

```
cline --auto-approve true "run tests and fix failures"
```

Mode selection also works in headless runs:

```
# plan-first
cline -p "design migration plan"

# act immediately (default)
cline "apply migration"
```

Autonomous execution can modify files and run commands without further prompts. Use a clean branch and review results.

## [​](#high-value-commands) High-Value Commands

```
cline --help
cline <command> --help
```

| Command | Purpose |
| --- | --- |
| `cline` | Start interactive mode or run a prompt |
| `cline auth` | Authenticate and set provider/model |
| `cline config` | Open the interactive config view |
| `cline mcp` | Manage MCP servers |
| `cline doctor` | Diagnose/fix configuration issues |
| `cline history` | Show and manage task history |
| `cline schedule` | Manage scheduled tasks |
| `cline hub` | Manage local hub daemon |
| `cline kanban` | Launch Kanban app |

## [​](#most-used-global-flags) Most-Used Global Flags

Source of truth: [CLI Reference](/cli/cli-reference)

| Flag | Purpose |
| --- | --- |
| `-p, --plan` | Start in Plan mode |
| `--auto-approve <boolean>` | Global tool auto-approval (`true`/`false`, default `true`) |
| `-m, --model <model>` | Override model for this run |
| `-P, --provider <id>` | Override provider for this run |
| `-c, --cwd <path>` | Set working directory |
| `--config <dir>` | Use config directory |
| `--data-dir <dir>` | Use isolated local state |
| `--json` | Output newline-delimited JSON messages |
| `--thinking <level>` | Set reasoning effort: `none|low|medium|high|xhigh` (default `medium`) |
| `-t, --timeout <seconds>` | Set task timeout |

## [​](#automation-patterns) Automation Patterns

### [​](#pipe-context-in) Pipe context in

```
cat README.md | cline "summarize key setup steps"
git diff | cline "review for potential regressions"
```

### [​](#chain-tasks) Chain tasks

```
git diff | cline "explain these changes" | cline "write a commit message"
```

### [​](#restrict-command-execution) Restrict command execution

```
export CLINE_COMMAND_PERMISSIONS='{"allow": ["npm *", "git *"], "deny": ["rm -rf *", "sudo *"]}'
```

### [​](#include-images-in-tasks) Include images in tasks

```
cline -i "fix the layout issue shown in @./screenshot.png"

# or reference inline
cline "fix the UI shown in @./design-mockup.png"
```

### [​](#set-execution-timeout) Set execution timeout

```
cline --timeout 600 "run full test suite"
```

## [​](#json-output-schema) JSON Output Schema

When using `--json`, each line is a JSON message object.

```
{"type":"say","text":"I'll create the file now.","ts":1760501486669,"say":"text"}
```

| Field | Type | Description |
| --- | --- | --- |
| `type` | `"ask"` or `"say"` | Message category |
| `text` | `string` | Message content |
| `ts` | `number` | Unix timestamp in milliseconds |
| `say` | `string` | Subtype when `type` is `"say"` |
| `ask` | `string` | Subtype when `type` is `"ask"` |
| `reasoning` | `string` | Optional model reasoning |
| `partial` | `boolean` | Streaming flag |

## [​](#next-steps) Next Steps

- [CLI Reference](/cli/cli-reference)

Was this page helpful?

YesNo

[TUI](/usage/tui)[CLI Reference](/cli/cli-reference)

⌘I

---

## Ide

*Source: [https://docs.cline.bot/usage/ide](https://docs.cline.bot/usage/ide)*

## [​](#prerequisites) Prerequisites

Before starting, make sure you have:

- Cline installed in your editor ([Install Guide](/getting-started/installing-cline))
- An AI model connected ([Model Setup](/getting-started/authorizing-with-cline))

If you haven’t done these yet, complete them first and come back here.

## [​](#step-1-open-a-project-folder) Step 1: Open a Project Folder

Cline needs a workspace, which is a folder on your computer where it can create and edit files. You’ll open an empty folder so Cline has a clean place to build your todo app.

- VS Code / Cursor / Windsurf
- JetBrains

1. Go to **File → Open Folder** in the top menu bar
2. Create a new folder on your computer (for example, name it `todo-app` on your Desktop)
3. Select that folder and click **Open**

Your editor should now show the folder name in the top of the sidebar on the left. The file explorer (left panel) will be empty since the folder is new.

1. Go to **File → Open** in the top menu bar
2. Create a new folder on your computer (for example, name it `todo-app` on your Desktop)
3. Select that folder and click **OK**

Your editor should now show the folder name in the Project panel on the left. It will be empty since the folder is new.

If you skip this step and don’t have a folder open, Cline won’t know where to create files. Always open a folder before starting a task.

## [​](#step-2-open-the-cline-panel) Step 2: Open the Cline Panel

The Cline panel is a chat interface where you communicate with Cline. You need to open it before you can give Cline any instructions.

- VS Code / Cursor / Windsurf
- JetBrains

Look at the **Activity Bar**, the vertical strip of icons on the far left (or far right) of your editor. Find the **Cline icon** (it looks like a small robot) and click it.A panel will open showing the Cline chat interface. You’ll see:

- A **text input box** at the bottom where you type messages
- A **chat area** above it where Cline’s responses will appear
- A **settings gear icon** in the top-right corner of the panel

**Can’t find the Cline icon?** Open the Command Palette with `Cmd+Shift+P` (Mac) or `Ctrl+Shift+P` (Windows/Linux), type **“Cline: Open In New Tab”**, and press Enter. This opens Cline in a full editor tab, which also gives it more screen space.

Go to **View → Tool Windows → Cline** in the top menu bar. The Cline panel will open on the right side of your editor.You’ll see:

- A **text input box** at the bottom where you type messages
- A **chat area** above it where Cline’s responses will appear
- A **settings gear icon** in the top-right corner of the panel

## [​](#step-3-give-cline-a-task) Step 3: Give Cline a Task

Now you’ll tell Cline what to build. You communicate with Cline by typing messages in the text input box, just like a chat app.

1. **Click on the text input box** at the bottom of the Cline panel
2. **Paste (or type) the following prompt** into the text input box:

```
Build a todo app in a single HTML file. Include:
- Input field to add new tasks
- List that displays all tasks
- Checkbox to mark tasks complete (with strikethrough styling)
- Button to delete individual tasks
- Clean, modern design with CSS
- All JavaScript inline in the same file
```

3. **Press Enter** on your keyboard (or click the **Send** button) to send the message

Cline will now read your message and start working on a response. You’ll see text appearing in the chat area as Cline thinks through your request.

## [​](#step-4-understand-plan-mode-vs-act-mode) Step 4: Understand Plan Mode vs Act Mode

When Cline receives your task, it may start in one of two modes. Look at the **bottom of the Cline panel**. You’ll see a toggle button that says either **“Plan”** or **“Act”**.

### [​](#if-cline-is-in-plan-mode) If Cline is in Plan Mode

In Plan mode, Cline **only talks**. It analyzes your request and discusses the approach, but it does **not** create or modify any files. You’ll see Cline describe what it plans to build, but nothing will change in your project folder yet.
This is useful for complex tasks where you want to discuss the approach first. You can:

- Ask Cline questions about its plan
- Suggest changes to the approach
- Clarify your requirements

**When you’re ready for Cline to start writing code**, click the toggle button at the bottom of the panel to switch from **“Plan”** to **“Act”**. Cline will then begin proposing actual file changes.

### [​](#if-cline-is-in-act-mode) If Cline is in Act Mode

In Act mode, Cline will start creating files and writing code right away (but it still asks for your approval before making any changes, see the next step).

For this tutorial, you want to be in **Act mode** so Cline creates the todo app. If you see “Plan” at the bottom, click it to switch to “Act”. Learn more about when to use each mode in the [Plan and Act guide](/core-workflows/plan-and-act).

## [​](#step-5-approve-the-changes) Step 5: Approve the Changes

Cline **never** modifies your files without your permission. Before creating or editing any file, Cline will show you exactly what it wants to do and wait for you to approve.
Here’s what you’ll see in the chat:

1. **Cline proposes a file change.** You’ll see a section in the chat showing the file path (e.g., `index.html`) and the code Cline wants to write. New lines of code are highlighted in **green**.
2. **Approve or Reject buttons appear.** Directly below the proposed change, you’ll see two buttons:
   - **Approve** (checkmark): Click this to let Cline create or edit the file. The file will be written to your project folder.
   - **Reject** (X): Click this to stop Cline and provide different instructions instead.
3. **Click Approve** to let Cline create the `index.html` file.

After you approve, Cline writes the file to your project folder. You should see `index.html` appear in your editor’s file explorer (the left panel).

Every file creation, file edit, and terminal command requires your explicit approval. You are always in control of what changes in your project. Once you’re comfortable with Cline, you can enable [auto-approve](/features/auto-approve) to skip confirmations for specific actions.

## [​](#step-6-view-any-created-app) Step 6: View Any Created App

With the previous prompt, Cline has created the `index.html` file in your project folder. Now let’s open it in a web browser to see the app.

- macOS
- Windows
- Linux

**Option A: Use the terminal**If Cline ran a terminal command to open the file, it may have already opened. Otherwise, you can open a terminal in your editor (`` Ctrl+` `` or **Terminal → New Terminal** from the menu) and type:

```
open index.html
```

**Option B: Use Finder**Right-click `index.html` in your editor’s file explorer (left panel) and select **“Reveal in Finder”**. Then double-click the file in Finder to open it in your default browser.

**Option A: Use the terminal**Open a terminal in your editor (`` Ctrl+` `` or **Terminal → New Terminal** from the menu) and type:

```
start index.html
```

**Option B: Use File Explorer**Right-click `index.html` in your editor’s file explorer (left panel) and select **“Reveal in File Explorer”**. Then double-click the file to open it in your default browser.

**Option A: Use the terminal**Open a terminal in your editor (`` Ctrl+` `` or **Terminal → New Terminal** from the menu) and type:

```
xdg-open index.html
```

**Option B: Use your file manager**Right-click `index.html` in your editor’s file explorer (left panel) and select **“Open Containing Folder”**. Then double-click the file to open it in your default browser.

**Option C: Live Server (any OS)**
If you have the Live Server extension installed in VS Code, right-click `index.html` in the file explorer and select **“Open with Live Server”**. This opens the app in your browser and automatically refreshes when files change.
Try out your new todo app: add a few tasks, check them off, and delete them. The app runs entirely in your browser with no server or backend needed.

## [​](#step-7-iterate-on-your-project) Step 7: Iterate on Your Project

One of Cline’s most powerful features is that it remembers your entire conversation. You can ask for changes and Cline will modify the existing code rather than starting over.
**In the same Cline chat** (don’t start a new conversation), click the text input box at the bottom and type a follow-up request. Here are some ideas to try:
**Add persistence:**

```
Add local storage so tasks persist when I refresh the page
```

**Change the design:**

```
Switch to a dark theme with purple accent colors
```

**Add a feature:**

```
Add a filter to show all, active, or completed tasks
```

When you send a follow-up message, Cline will:

1. Read your current `index.html` file to understand the existing code
2. Propose specific changes (shown as a diff with green for added lines and red for removed lines)
3. Wait for your approval before modifying the file

Click **Approve** to apply the changes, then refresh your browser to see the updated app.

## [​](#step-8-undo-mistakes-with-checkpoints) Step 8: Undo Mistakes with Checkpoints

Cline automatically saves a **checkpoint** after each change it makes. If something breaks or you don’t like a modification, you can go back to any previous state.

### [​](#how-to-find-checkpoints) How to find checkpoints

Scroll through your conversation in the Cline panel. Next to each step where Cline made a change, you’ll see two small buttons:

- **Compare**: Click this to see exactly what files changed at that step (a before/after diff)
- **Restore**: Click this to roll back your project to how it was at that point

### [​](#how-to-restore) How to restore

When you click **Restore**, you’ll see three options:

| Option | What it does | When to use it |
| --- | --- | --- |
| **Restore Task and Workspace** | Resets both your files and conversation to that point | You want to completely go back and start over from that step |
| **Restore Task Only** | Keeps your current files but reverts the conversation context | Rarely needed |
| **Restore Workspace Only** | Resets files to that point but keeps the full conversation | You want to try a different approach but keep the conversation history |

**Recommended for beginners:** Use **“Restore Workspace Only”** when you want to undo a change but keep chatting with Cline about what to do differently.

Checkpoints are separate from Git. They won’t affect your commits, branches, or any version control you have set up.

Learn more in the [Checkpoints guide](/core-workflows/checkpoints).

## [​](#what-you-learned) What You Learned

You just completed the core Cline workflow:

1. **Opened a project folder** so Cline has a workspace
2. **Opened the Cline panel** and typed a task in the chat input
3. **Understood Plan vs Act mode** and how to switch between them
4. **Approved file changes** before Cline wrote anything to disk
5. **Iterated** by sending follow-up messages in the same conversation
6. **Used checkpoints** to undo mistakes and try different approaches

These same patterns work for any project, from simple scripts to full applications. The more context you give Cline about what you want, the better the results.

## [​](#next-steps) Next Steps

- [Core Workflows](/core-workflows/task-management): Learn the patterns you’ll use daily with Cline
- [Working with Files](/core-workflows/working-with-files): Use `@` mentions to reference files, folders, and URLs in your prompts
- [Cline provider](/getting-started/cline-provider): Fastest setup with built-in authentication and unified billing
- [Cline Rules](/customization/cline-rules): Customize how Cline behaves in your projects

## [​](#need-help) Need Help?

- **Start a fresh conversation**: Type `/new` in the chat input to begin a new task
- **Report issues**: Use `/reportbug` to help us improve
- **Get support**: Join our [Discord community](https://discord.gg/cline)

Was this page helpful?

YesNo

[Config](/getting-started/config)[TUI](/usage/tui)

⌘I

---

## Kanban

*Source: [https://docs.cline.bot/usage/kanban](https://docs.cline.bot/usage/kanban)*

Kanban is a **research preview**. Some features described here use experimental capabilities. Expect changes.

## [​](#prerequisites) Prerequisites

- Node.js 18+
- A git repository (run from repo root)
- Kanban launcher available (`npx kanban`)

## [​](#quick-start) Quick Start

```
cd /path/to/your/repo
npx kanban
```

This starts a local server and opens the board in your browser.

## [​](#core-workflow) Core Workflow

1. **Create tasks** on the board (manually or from sidebar chat).
2. **Start tasks** with play — each card gets an isolated git worktree + terminal.
3. **Monitor progress** from card status and latest agent output.
4. **Review diffs** in card detail view and leave inline comments.
5. **Ship changes** via Commit or Open PR.
6. **Clean up** by moving cards to trash (worktrees are removed).

## [​](#key-capabilities) Key Capabilities

- **Parallel execution:** each task runs in a separate worktree to avoid conflicts.
- **Task linking:** dependency chains can auto-start next tasks.
- **Inline review loop:** comment directly on diff lines to steer agent work.
- **Auto-commit / Auto-PR:** optional automation from settings.
- **Sidebar chat orchestration:** ask an agent to break work into cards and start flows.

## [​](#agent-compatibility) Agent Compatibility

Kanban is designed for CLI-style coding agents and currently works with Cline CLI, Claude Code, Codex, OpenCode, and related runtimes available in settings.

## [​](#next-steps) Next Steps

- [Kanban Core Workflow](/kanban/core-workflow)
- [Kanban Remote Access](/kanban/remote-access)

Was this page helpful?

YesNo

[ACP: Editor Integrations](/cli/acp-editor-integrations)[Core Workflow](/kanban/core-workflow)

⌘I

---

## Tui

*Source: [https://docs.cline.bot/usage/tui](https://docs.cline.bot/usage/tui)*

## [​](#what-is-the-tui) What is the TUI?

The TUI is Cline’s interactive terminal interface. It is designed for conversational, in-terminal work: ask questions, review plans, approve actions, and iterate quickly.

## [​](#prerequisites) Prerequisites

Install the CLI:

```
npm install -g cline
```

## [​](#launch-the-tui) Launch the TUI

```
# default interactive launch
cline

# explicit TUI mode
cline -i
```

## [​](#core-tui-actions) Core TUI Actions

- `Tab` to toggle Plan/Act
- `Shift+Tab` to toggle auto-approve all
- `Ctrl+C` to abort a running turn; press again to exit
- `Ctrl+D` to exit when the prompt is empty and idle
- `Ctrl+L` to clear the chat view or current conversation
- `/settings`, `/model`, `/account`, `/mcp`, `/compact`, `/undo`, `/clear`, `/history`, `/help`, `/quit`
- `@file` mentions for workspace context

The status area shows the active model, context usage, cost, workspace/branch, git diff stats, Plan/Act state, and whether auto-approve all is enabled.

## [​](#when-to-use-tui-vs-headless) When to Use TUI vs Headless

- Use **TUI** when you want collaboration and approvals.
- Use **headless** (`--json`, piped stdin/stdout, CI scripts) for automation.

See: [CLI Headless Mode](/usage/cli-overview#headless-mode)

## [​](#next-steps) Next Steps

- [CLI Overview](/usage/cli-overview)
- [CLI Reference](/cli/cli-reference)

Was this page helpful?

YesNo

[IDE](/usage/ide)[CLI Overview](/usage/cli-overview)

⌘I
