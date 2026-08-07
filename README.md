# Telegram Mini App — Reward Dashboard Demo

This project recreates the general mobile dashboard style shown in the supplied screenshot:
- dark gradient interface
- balance card
- level and reward cycles
- income card/chart
- Deposit/Add Demo Coins and Withdraw buttons
- Telegram Mini App user name/avatar support
- bottom navigation

## Important
This is a **demo UI**. The displayed coins/USDT are not real money, and withdrawals are disabled.

## Test locally
Open `index.html` in a browser. Some Telegram-specific features only work when launched inside Telegram.

## Put it inside Telegram
1. Upload the files to an HTTPS web host.
2. Create a Telegram bot using BotFather.
3. Configure the bot's Mini App/Web App URL to point to your hosted `index.html`.
4. Open the Mini App from your bot.
5. The included Telegram Web App script reads the Telegram user's first name when Telegram provides it.

For a real rewards service, you would need a secure backend, database, authentication, server-side Telegram init-data validation, fraud prevention, clear terms/privacy information, and a legitimate payment system. Do not use client-side JavaScript as proof of a user's balance or payment status.
