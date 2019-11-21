# APOD Bot

APOD Bot is a simple Telegram bot managing a channel that provides a mirror image of NASA's [Astoronomy Picture Of the Day](https://apod.nasa.gov) project.

This bot is built using [pyTelegramBotAPI](https://github.com/eternnoir/pyTelegramBotAPI). The channel itself can be found [here](https://t.me/AstronomyPictureADay).

## Running your own instance

If you want to try this bot out or run your own instance of it, simply run `pip3 install pyTelegramBotAPI` to install the API package. Then replace values of `tg_key`, `nasa_key` and `chat_id` with your Telegram and NASA API-keys and ID of the chat that you want to send messages to.

Then you can schedule the bot to run once a day using [cron](https://pubs.opengroup.org/onlinepubs/9699919799/utilities/crontab.html) utility.
