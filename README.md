# Telegram Scheduled Message Bot

This project is a Telegram bot that sends messages on a schedule.

## Features
- Send scheduled messages to a chat or user
- Easy configuration of schedule and message content
- Designed for deployment on [Render](https://render.com)

## Setup

1. **Clone the repository**
2. **Set your Telegram API token**
   - The bot token is: `8065594092:AAFcDdP_3KcWPAUBNj73C8BcBHhBYzYthho`
   - You can set this in a `.env` file as `TELEGRAM_BOT_TOKEN=...`
3. **Configure your schedule and message**
   - Edit `config.py` or set environment variables as needed
4. **Deploy to Render**
   - Use `render.yaml` or the Render dashboard to set up a web service

## Quickstart (Local)
```bash
pip install -r requirements.txt
python bot.py
```

## Environment Variables
- `TELEGRAM_BOT_TOKEN` - Your Telegram bot token
- `SCHEDULE_CRON` - (Optional) Cron expression for scheduling
- `MESSAGE_TEXT` - (Optional) The message to send
- `CHAT_ID` - (Optional) The chat/user ID to send the message to

## License
MIT # Telegrambot
