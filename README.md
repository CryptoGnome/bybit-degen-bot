# Bybit-Degen-Bot

![Imgur](https://i.imgur.com/GIZxmdF.png)

PLEASE NOTE THIS BOT IS FREE OF USE HOWEVER REQUIRES A AUTH KEY.
YOU CAN OBTAIN THIS BY CREATING A NEW ACCOUNT TO USE WITH THIS BOT,
WE CHECK BYBIT UID TO OUR AFFILATIE ACCOUNT TO AUTHORIZE THE USE.

Bybit-Degen-Bot is an automated Position Manager for Bybit that will use 
trailing profit and stop loss to close your positions.


Grab the Latest Release here:

https://github.com/CryptoGnome/bybit-degen-bot/releases


Licence Keys:
---------------------------------------------------------------
You can use our link here:

https://www.bybit.com/home/en/index.html?affiliate_id=767&group_id=213&group_type=1

You can Register your UID with the BOT here:

https://forms.gle/qkRYbQUq6FwJcUde9

We also have a private discord channel for the BETA TESTERS here:

https://discord.gg/4gBBGjz

Please message @CryptoGnome#7769 on discord for the role to see the private BETA channels.


Installation:
---------------------------------------------------------------
Grab the latest release. This can be found in the pinned messages in the
private discord channel for support members.

Unzip Folder to location of you choice

Install Node & PM2 to Restart your bot if there are any crashes:
----------------------------------------------------------------
Install Node JS:

https://nodejs.org/dist/v12.8.0/node-v12.8.0-x64.msi

Run Install PM2 Using Included Bat File




Edit Settings.py file with text editor:
---------------------------------------------------------------
Enter API Keys for Bybit.



MAIN SETTINGS:
All of these settings effect the core strategy of the bot and there are descriptions next to them in the settings file.



How to Run Bot:
---------------------------------------------------------------
Use the Included .bat file named _**Monitor**_ to launch the PM2 screen.

Use the Included .bat file named _**Start Bot**_ to start the bot. 

If you need to kill the bot use the Included .bat file named _**Stop Bot**_

Common Errors:
---------------------------------------------------------------
```
INFO - 2019-08-13 18:03:20,105 - Failed to retrieve access token: {
  "error": "invalid_grant",
  "error_description": "Invalid JWT: Token must be a short-lived token (60 minutes) and in a reasonable timeframe. Check your iat and exp values and use a clock with skew to account for clock differences between systems."
}
```

Time Clock Sync is OFF use this:

http://www.timesynctool.com/
