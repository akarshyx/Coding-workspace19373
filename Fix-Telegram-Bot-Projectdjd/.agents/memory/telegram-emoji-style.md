---
name: Telegram bot emoji style
description: The user's current preference for custom emoji in the Telegram casino bot.
---

Use static, non-animated premium emoji from the selected Rollers pack for game and win UI, and from `CasinoDCMoji_by_CheakLeaksBot` for withdrawal coin icons. Use ordinary Unicode emoji or plain text when a matching static icon is unavailable. Never use animated premium emoji or post-win stickers. Keep win results free of self-promotion, link previews, and extra promotional messages.

**Why:** the user asked for the selected static pack emoji in wins and withdrawals, no animated win emoji, and no bot self-promotion after a result.

**How to apply:** Resolve game/win tags and button icons only from verified static pack maps; check both `is_animated` and `is_video` before using sticker IDs. Withdrawal buttons use the mapped coin icons. Do not append promo text, previews, or celebration stickers after results.
