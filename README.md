# Spotify To Discord Bot  ▶
Discord bot that will convert playlist songs from Spotify to a Youtube songs playlist

## Prerequisites

* Python 3 (tested with v3.6.6, should work for 3.5+)
  * [Discord Python module](https://pypi.org/project/discord.py/)

  * Admin permissions on Discord server
 
<b><i>IMPORTANT:</i> I use autoPep 8 formatter in this project.


# How does it work?
All you gotta do is insert your <b> >>PUBLIC<< </b> <a href="http://www.spotify.com">Spotify</a> playlist URL when prompted, then the app will automatically search all songs from that playlist on <a href="http://youtube.com">YouTube</a> and return the URLs.

Check below for instructions on how to make it work.


# How to use it? BotCommands:



## Bot Invite/Hosting Instructions

### Invite Hosted Bot

I am hosting this bot on a server, thus it can be invited to your server easily without the need to host the bot yourself.

1. Open the invite link below to start the process of adding the bot to your Discord server
    * Invite link: 
2. Select the server you wish to invite the bot to
3. Hit 'Authorize' and the bot will be added

### Self-Hosted Bot

1. Follow [these directions](https://discordpy.readthedocs.io/en/rewrite/discord.html) in order to register the bot and create a token
2. Replace the token at the top of the _licensebot.py_ file with your generated token
3. Invite the bot to your server<sup>1<sup>

_<sup>1</sup> The bot does not require any special permissions_
