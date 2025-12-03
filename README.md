# kbot
t.me/vkryzhovets_bot

kbot — Telegram Bot in Go

kbot is a simple Telegram bot written in Go using Cobra (for the CLI) and Telebot.v3 (for working with the Telegram API).

Features

run the bot using the CLI command kbot or kbot start

handle text messages (telebot.OnText)

respond to the payload hello

default reply for unknown commands

flexible token configuration using environment variables

The bot listens for text messages and responds depending on the received payload.
# 1. Install kbot

git clone https://github.com/vkrizhovets/kbot.git
cd kbot
export TELE_TOKEN="your_telegram_token"
# 2. Запуск
go run main.go start
./kbot start



