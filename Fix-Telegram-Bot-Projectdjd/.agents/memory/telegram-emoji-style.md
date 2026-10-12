---
name: Telegram bot emoji style
description: The user's current preference for custom emoji in the Telegram casino bot.
---

Use static, non-animated premium emoji from `CasinoDCMoji_by_CheakLeaksBot` for withdrawal coin icons. Use ordinary Unicode emoji or plain text when a matching static icon is unavailable. Other UI may use static emoji only when a specific location calls for one. Never use animated premium emoji.

**Why:** the user supplied this pack as the source of all coin icons and explicitly prohibited animated emoji. The linked pack currently has 124 stickers, all marked static by Telegram.

**How to apply:** When editing the withdrawal picker, map each supported coin to its verified sticker from this pack and check both `is_animated` and `is_video` before using downloaded sticker IDs. Avoid global emoji substitution; keep a Unicode fallback if a static match is unavailable.
