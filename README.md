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

## Dicord calls

1) ?play - which makes the bot join the discord server and open the required youtube vedio
              
![image](https://user-images.githubusercontent.com/97995173/219150920-c50d007b-996b-483d-878d-0a121b72b981.png) 


2)  ?pause and ?resume - basicaly pause and resume the music

![image](https://user-images.githubusercontent.com/97995173/219151437-4eef07fa-8304-4e82-94a9-63482d39ae2f.png) ![image](https://user-images.githubusercontent.com/97995173/219153547-0e9dfa14-b779-488c-9c45-031095b8125b.png)

3) ?stop - stop the music and make the bot leave the discord server 



