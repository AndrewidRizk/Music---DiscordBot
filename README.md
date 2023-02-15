## Main reference: 
   1) https://github.com/CreepyD246/discord-music-bot 
   2) https://www.youtube.com/watch?v=j_sD9udZnCk

## Install:
  1) discord 
  2) youtube_dl 
  3) FFmpeg 
  ```bash
   import asyncio
   import discord
   import youtube_dl
```
## About the Discord bot and how it works
When you run the discord bot it connect with Apis to go online

```bash
# bot initialization
intents = discord.Intents.default()
intents.message_content = True

client = discord.Client(intents=intents)
token = '****'
voice_clients = {}

yt_dl_opts = {'format': 'bestaudio/best'}
ytdl = youtube_dl.YoutubeDL(yt_dl_opts)

ffmpeg_options = {'options': "-vn"}

```
![image](https://user-images.githubusercontent.com/97995173/219145803-11e5a3d4-31d8-438c-8bf0-5b40123b06fe.png)
![image](https://user-images.githubusercontent.com/97995173/219148524-332163e0-a827-4424-824c-b4ebd4573448.png)


