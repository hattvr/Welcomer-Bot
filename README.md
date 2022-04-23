<h1 align="center">Discord Welcomer-Bot</h1>
<p align="center">
    <a href="https://github.com/hattvr/Welcomer-Bot/releases/latest">
        <img src="https://img.shields.io/github/v/release/hattvr/Welcomer-Bot?label=Latest%20Version">
    </a>
    <a href="https://github.com/hattvr/Welcomer-Bot/commit/master">
        <img src="https://img.shields.io/github/last-commit/hattvr/Welcomer-Bot?label=Last%20Update">
    </a>
    <img src="https://img.shields.io/github/languages/code-size/hattvr/Welcomer-Bot?label=Size">
    <a href="https://github.com/hattvr/Welcomer-Bot/issues">
        <img src="https://img.shields.io/github/issues/hattvr/Welcomer-Bot?label=Issues">
    </a>
</p>

---
<div align="center">
    <img src="https://i.imgur.com/G67f6xS.png">
</div>

## **Getting Started**  
Welcomer-Bot is an advanced, easy to setup, free, and unbranded Discord bot. This bot allows users to send a welcome notification, in the form of an image, in a desired channel. To being installing this bot, you're going to want to install the required python libs from the `requirements.txt` file.
```py
pip install -r requirements.txt
```

After you are done installing the required python libraries, you can setup the config file (`config.json`). You will need to grab three different pieces of information before you're able to successfully run the Discord bot.
```json
    "settings": {
        "token": "YOUR_BOT_TOKEN",
        "guild": "YOUR_GUILD_ID",
        "log-channel": "CHANNEL_ID_FOR_LOGS",
        "refreshrate": 600
    }
```
`token` - This is the token for your Discord bot, this can be accessed from your Discord account's Developer Portal!

`guild` - This is the ID of the guild/server you want the bot to send notifications in. You can get a Discord guild/server's id by right-clicking on the server icon and pressing the button named **Copy ID**

`log-channel` - This is the ID of the channel you want the bot to send notifications in. You can get a Discord channel's id by right-clicking on the channel and pressing the button named **Copy ID**

## **Bot Usage**
To setup the welcoming image, you can make your own and replace the `welcome.png` file or you can stil to the default background (refer to picture above).

## **Any Issues?**  
If you run into any issues or problems during the process of setting up this discord bot, you can contact me using any of my socials given on my Github profile!
