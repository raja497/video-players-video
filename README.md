# Telegram Video Player Bot (Beta)
![GitHub Repo stars](https://img.shields.io/github/stars/AsmSafone/VideoPlayerBot?color=blue&style=flat)
![GitHub forks](https://img.shields.io/github/forks/AsmSafone/VideoPlayerBot?color=green&style=flat)
![GitHub issues](https://img.shields.io/github/issues/AsmSafone/VideoPlayerBot)
![GitHub closed issues](https://img.shields.io/github/issues-closed/AsmSafone/VideoPlayerBot)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AsmSafone/VideoPlayerBot)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/AsmSafone/VideoPlayerBot)
![GitHub contributors](https://img.shields.io/github/contributors/AsmSafone/VideoPlayerBot?style=flat)
![GitHub repo size](https://img.shields.io/github/repo-size/AsmSafone/VideoPlayerBot?color=red)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/AsmSafone/VideoPlayerBot)
![GitHub](https://img.shields.io/github/license/AsmSafone/VideoPlayerBot)
[![Bot Updates](https://img.shields.io/badge/VideoPlayerBot-Updates%20Channel-green)](https://t.me/ABOUT_ABHINAS)
[![Bot Support](https://img.shields.io/badge/VideoPlayerBot-Support%20Group-blue)](https://t.me/DOSTI_GROUP_1234)

An Telegram Bot By [@abhinasroy](https://t.me/abhinasroy) To Stream Videos in Telegram Voice Chat.


## Deploy To Heroku

<p><a href="https://heroku.com/deploy?template=https://github.com/raja497/video-players-video"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>


## Config Vars:

1. `API_ID` : User Account Telegram API_ID, get it from my.telegram.org
2. `API_HASH` : User Account Telegram API_HASH, get it from my.telegram.org
3. `BOT_TOKEN` : Your Telegram Bot Token, get it from @Botfather XD
4. `BOT_USERNAME` : Your Telegram Bot Username, get it from @Botfather XD
4. `SESSION_STRING` : Pyrogram Session String of User Account, get it from [@genStr robot](http://t.me/genStr_robot) or [![genStr](https://img.shields.io/badge/repl.it-genStr-yellowgreen)](https://repl.it/@AsmSafone/genStr)
5. `CHAT_ID` : ID of Channel/Group where the bot will works or stream videos.
6. `AUTH_USERS` : ID of Users who can use Admins commands (for multiple users seperated by space).
7. `REPLY_MESSAGE` : A reply to those who message the USER account in PM. Leave it blank if you do not need this feature.

## Requirements

- Python 3.6 or higher.
- [Telegram API key](https://docs.pyrogram.org/intro/quickstart#enjoy-the-api) 
& a Telegram Account (Needs To Be An Admin In The Channel or Group).
- Latest [FFmpeg Python](https://www.ffmpeg.org/)
- Pyrogram [String Session](http://t.me/genStr_robot) of the account.
- Must Start An Voice Chat In Channel/Group Before Running The Bot.

## Self Host

```sh
$ git clone https://github.com/AsmSafone/VideoPlayerBot.git
$ cd VideoPlayerBot
$ sudo apt-get install python3-pip ffmpeg
$ pip3 install -U pip
$ pip3 install -U -r requirements.txt
# <create .env variables appropriately>
$ python3 main.py
```


## License
```sh
VideoPlayerBot, Telegram Video Chat Bot
Copyright (c) 2021  Asm Safone <https://github.com/AsmSafone>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>
```

## Credits

- [Me](https://github.com/AsmSafone) for [Noting](https://github.com/AsmSafone/VideoPlayerBot) 😬
- [Dan](https://github.com/delivrance) for [Pyrogram](https://github.com/pyrogram/pyrogram) ❤️
- [MarshalX](https://github.com/MarshalX) for [pytgcalls](https://github.com/MarshalX/tgcalls) ❤️
