# ytdl-bot
Download videos from YouTube and other platforms through a Telegram Bot


# Usage:

[https://t.me/benny_ytdlbot](https://t.me/benny_ytdlbot)

Send link from YouTube directly to the bot. 
Any platform [supported by youtube-dl](https://ytdl-org.github.io/youtube-dl/supportedsites.html) will also work.

# Feature
![](assets/1.jpeg)

1. fast download and upload. Many thanks to [FastTelethon](https://gist.github.com/painor/7e74de80ae0c819d3e9abcf9989a8dd6) and 
[JasonKhew96](https://github.com/JasonKhew96)'s contribution on this!
2. ads free - I'll never send ads to you, also I don't even print logs that will identify you. 
   So feel free to download any type of video from any website.

3. support progress bar 

# How to deploy?
## Normal
1. clone code and update submodule `git submodule update --init --recursive`
2. install ffmpeg   
3. install Python 3.6+
4. pip3 install -r requirements.txt
5. set environment variables `TOKEN`, `APP_ID` and `APP_HASH`
6. `python3 bot.py`
7. supervisor on your own preference.

## docker
see [here](https://github.com/tgbot-collection/BotsRunner)

# Command
```
start - let's start
about - wanna contribute?
ping - bot running status
help - it's not working?
ytdl - download video in group
```

# Test video
https://www.youtube.com/watch?v=BaW_jenozKc

# License
Apache License 2.0
