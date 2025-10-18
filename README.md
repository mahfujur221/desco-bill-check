# DESCO Balance Bot Script

## Setting up the Telegram bot:

1. Open Botfather https://t.me/botfather and follow the instructions to create your bot (e.g, Desco Balance Bot). You will get a telegram bot token. 
2. Copy and add it to `TELEGRAM_BOT_TOKEN` in the `.env` file.
3. Send a `hi/hello` chat to your new bot.
4. Open this URL in your browser `https://api.telegram.org/bot{TELEGRAM_BOT_TOKEN}/getUpdates`
5. Copy the chat `id` value and add it to the `TELEGRAM_CHAT_ID` in the `.env` file.



Ignore the SSL warning for now (I will update it later); you should see (True, 'Telegram sent`)

And receive a message in your Telegram app.


So please test this endpoint with your DESCO account and first verify that this is working for your meter.