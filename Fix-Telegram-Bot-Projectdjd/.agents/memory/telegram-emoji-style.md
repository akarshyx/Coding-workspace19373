---
name: Telegram bot emoji style
description: The user's current preference for custom emoji in the Telegram casino bot.
---

Use static, non-animated premium emoji from `rollerscasino_by_rollersgamebot` only in a few deliberate places. Use ordinary Unicode emoji or plain text by default. Do not use RaikaRanks or animated premium emoji packs in normal bot UI.

**Why:** the user explicitly corrected the bot's emoji style and asked for the Rollers Casino pack's normal, static premium emoji instead.

**How to apply:** When editing Telegram bot messages or menus, avoid global emoji substitution and animated emoji. Only add a custom emoji when the user has clearly selected that location; otherwise keep the Unicode fallback.
