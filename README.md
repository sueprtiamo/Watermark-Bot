# Watermark-Bot
A Telegram Video Watermark Adder Bot by [@AbirHasan2005](https://github.com/AbirHasan2005)

＃＃ 特征：
- 保存自定义水印图像。
- 根据视频质量自动调整水印大小。
- 轻松将保存的水印应用到视频。
- 所有任务的进展。
- 可以选择 [FFMPEG](https://www.ffmpeg.org/) 处理预设。
- 可以取消进程。 *（测试版）*
- 任何频道或组 Force Sub。
- 在任何渠道中记录进程。
- 广播功能。
- 可以为用户保存水印位置。
- 可以为用户保存水印大小。
- 如果文件大小超过 2GB，可以上传到 [Streamtape](https://streamtape.com/)。

### Demo Bot:
<a href="https://t.me/VideoWatermark_Bot"><img src="https://img.shields.io/badge/Demo-Telegram%20Bot-blue.svg?logo=telegram"></a>

## Configs:
- `API_ID` - Get this from [@TeleORG_Bot](https://t.me/TeleORG_Bot)
- `API_HASH` - Get this from [@TeleORG_Bot](https://t.me/TeleORG_Bot)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `BOT_USERNAME` - You Bot Username. *(Without [@])*
- `LOG_CHANNEL` - Logs Channel ID
- `OWNER_ID` - Bot Owner UserID
- `DATABASE_URL` - MongoDB Database URI
- `UPDATES_CHANNEL` - Force Sub Channel ID *(Optional)*
- `PRESET` - Video Encoding Preset Type *(Optional)*
	- Better put `ultrafast` or `superfast` or `veryfast`
- `STREAMTAPE_API_PASS` - Get this from [Here](https://streamtape.com/accpanel#collapseThree).
	- For Uploading to Streamtape if File Size is more than 2GB.
- `STREAMTAPE_API_USERNAME` - Get this from [Here](https://streamtape.com/accpanel#collapseThree).
	- For Uploading to Streamtape if File Size is more than 2GB.

## BotFather Commands:
```
start - start the bot
status - Show number of users in DB & Bot Status
broadcast - Broadcast replied message to DB Users
cancel - Cancel Current Task
settings - User Settings Panel
reset - Reset all settings to default
```

### Support Group:
<a href="https://t.me/DevsZone"><img src="https://img.shields.io/badge/Telegram-Join%20Telegram%20Group-blue.svg?logo=telegram"></a>

## Deploy:

#### Easiest Way [Deploy To Heroku] 😪

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/AbirHasan2005/Watermark-Bot)

#### Video Tutorial:
[![YouTube](https://img.shields.io/badge/YouTube-Video%20Tutorial-red?logo=youtube)](https://www.youtube.com/watch?v=A7wnaKMHpvU&t)

#### The Hard Way 🤕
```sh
git clone https://github.com/AbirHasan2005/Watermark-Bot
cd Watermark-Bot
virtualenv -p python3 VENV
. ./VENV/bin/activate
pip3 install -r requirements.txt
--- EDIT configs.py values appropriately ---
python3 bot.py
```

### Follow on:
<p align="left">
<a href="https://github.com/AbirHasan2005"><img src="https://img.shields.io/badge/GitHub-Follow%20on%20GitHub-inactive.svg?logo=github"></a>
</p>
<p align="left">
<a href="https://twitter.com/AbirHasan2005"><img src="https://img.shields.io/badge/Twitter-Follow%20on%20Twitter-informational.svg?logo=twitter"></a>
</p>
<p align="left">
<a href="https://facebook.com/AbirHasan2005"><img src="https://img.shields.io/badge/Facebook-Follow%20on%20Facebook-blue.svg?logo=facebook"></a>
</p>
<p align="left">
<a href="https://instagram.com/AbirHasan2005"><img src="https://img.shields.io/badge/Instagram-Follow%20on%20Instagram-important.svg?logo=instagram"></a>
</p>
