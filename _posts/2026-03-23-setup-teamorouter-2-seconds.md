---
layout: post
title: "Set Up TeamoRouter in 2 Seconds: One Key for Every Top LLM in Your OpenClaw"
description: "A quick-start tutorial to install TeamoRouter and get instant access to Claude, GPT-5, Gemini, DeepSeek, and more."
date: 2026-03-23
categories: [tutorial, openclaw]
tags: [openclaw, tutorial, llm, teamorouter]
---
canonical_url:
---

## What is TeamoRouter?

TeamoRouter is the native LLM routing gateway built for OpenClaw. It gives you one unified key to access every top LLM — Claude, GPT-5, Gemini, DeepSeek, and more — with smart routing, pay-as-you-go billing, and up to 50% off official API prices.

---

## Prerequisites

- **OpenClaw >= 2026.3.x** installed on your machine

That's it. No API keys to juggle, no config files to edit.

---

## Step 1: Tell Your OpenClaw to Install

Open any OpenClaw chat and paste this message:

```
Read https://gateway.teamo.ai/skill.md and follow the instructions to install TeamoRouter.
```

Your agent will read the skill file and handle everything automatically — downloading the router config, registering your agent, and wiring up the connection.

You'll see output confirming the installation is in progress. Just wait for it to finish.

---

## Step 2: Click the Claim Link

Once installation completes, your agent will send you a **claim link**. It looks something like this:

```
Your TeamoRouter agent has been registered!
Click here to claim your account: https://router.teamolab.com/claim/xxxxx
```

Click that link. It opens in your browser where you:

1. **Bind your wallet** (for pay-as-you-go billing)
2. **Confirm your account**

That's it — your account is live. You even get **free sign-up credit** to start exploring immediately.

---

## Step 3: You're Done! Try It Out

Back in your OpenClaw chat, just type:

```
Switch to claude-opus-4.6
```

Your agent now routes through TeamoRouter and responds using Claude Opus 4.6. Want to try another model? Just say:

```
Switch to gpt-5
```

Or:

```
Switch to gemini
```

Available models include:

| Model | Description |
|-------|-------------|
| `claude-opus-4.6` | Anthropic's most capable model |
| `claude-sonnet-4.6` | Fast and smart from Anthropic |
| `gpt-5` | OpenAI's latest flagship |
| `gemini` | Google's multimodal model |
| `deepseek` | Strong reasoning at low cost |
| `kimi-k2` | Moonshot AI's latest |
| `minimax` | Efficient general-purpose model |

Switching is instant. No config changes, no restarts.

---

## Understanding Routing Tiers

Don't want to pick a specific model every time? TeamoRouter offers three **smart routing** options that automatically choose the best model for each request:

### `teamo-best` — Quality First

Routes every request to the most capable model available. Use this when output quality matters most and cost is secondary.

```
Switch to teamo-best
```

### `teamo-balanced` — Best Value

Balances quality and cost intelligently. It picks a strong model that won't break the bank. This is the sweet spot for most users.

```
Switch to teamo-balanced
```

### `teamo-eco` — Cheapest

Routes to the most cost-effective model that can handle your request. Great for high-volume tasks, drafts, or when you're exploring.

```
Switch to teamo-eco
```

> **Tip:** Start with `teamo-balanced` for everyday use. Switch to `teamo-best` when you need peak performance on complex tasks.

---

## Managing Your Account

### Dashboard

Visit your dashboard at any time:

**[https://router.teamolab.com/router/dashboard](https://router.teamolab.com/router/dashboard)**

Here you can:

- Check your **current balance**
- View **usage history** broken down by model
- See **cost per request**
- **Top up** your account

### Billing

- **Pay-as-you-go** — no subscriptions, no commitments
- **USD billing** — straightforward pricing
- **Up to 50% off** official model API prices
- **Free sign-up credit** included to get you started

---

## FAQ

### Do I need separate API keys for each model?

No. That's the whole point of TeamoRouter. One installation, one account, access to all models.

### How do I switch models?

Just type `Switch to <model-name>` in your OpenClaw chat. For example: `Switch to gpt-5` or `Switch to teamo-balanced`.

### Is my data secure?

TeamoRouter acts as a routing gateway. Your requests are forwarded to the model provider and responses are returned directly. TeamoRouter does not store your conversation content.

### What happens when my balance runs out?

Requests will stop routing until you top up. Visit the [dashboard](https://router.teamolab.com/router/dashboard) to add funds.

### Can I use TeamoRouter outside of OpenClaw?

TeamoRouter is purpose-built for OpenClaw. It's the native LLM router for the platform.

### What OpenClaw version do I need?

OpenClaw 2026.3.x or later.

---

## Get Help & Stay Updated

Join the TeamoRouter community on Discord for support, feature requests, and updates:

**[Join the Discord](https://discord.gg/NN6SaDnpMb)**

---

**Ready to get started?** Open your OpenClaw and paste this:

```
Read https://gateway.teamo.ai/skill.md and follow the instructions to install TeamoRouter.
```

Two seconds. Every top LLM. One key. Go build something.
