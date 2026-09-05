# Free Fire Likes Bot 🎮

A powerful Telegram bot designed to send likes to **Garena Free Fire** profiles using a UID and Server Name. Built with **Telebot (pyTelegramBotAPI)** and **Flask**, supporting both **Webhook** and **Polling** modes for high performance and reliability.

---

## 🌟 Features
- **Instant Likes**: Send likes to any Free Fire UID globally.
- **Verification System**: Ensures users are subscribed to required channels before using the bot.
- **Usage Tracking**: In-memory tracking of daily limits for users.
- **Dual Mode**: Seamlessly switches between Webhook (for production) and Polling (for development).
- **Owner Dashboard**: `/remain` command for the owner to monitor user statistics.
- **Threaded Processing**: Non-blocking API calls for a smooth user experience.

---

## 🤖 Bot Commands
- `/start` - Start the bot and verify membership.
- `/like <region> <uid>` - Send likes to the specified UID (Example: `/like id 12345678`).
- `/help` - Show the help menu with all available commands.
- `/remain` - (Owner Only) View detailed daily usage stats.

---

## 🚀 Deployment
[![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://dashboard.render.com/web/new)
### Prerequisites
- Python 3.9+
- A Telegram Bot Token from [@BotFather](https://t.me/BotFather)

### Environment Variables
Set the following environment variables in your hosting provider (e.g., Render, Railway, Vercel):

```bash
BOT_TOKEN=your_bot_token_here
WEBHOOK_URL=https://your-app-domain.com  # Optional: Only for Webhook mode
PORT=5000                                # Optional: Default is 5000
```

