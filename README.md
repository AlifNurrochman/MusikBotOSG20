[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://gi)

![logo](https://avatars0.githubusercontent.com/u/72243747?s=460&u=8332fb206eded8fabfdb8c99114db8ada43becab&v=4)

# 🧑🏻‍💻 OSG Music Bot (Discord Music Bot)
> OSG Music Bot adalah Bot Musik Discord yang dibuat dengan discord.js & menggunakan Command Handler dari [discordjs.guide](https://discordjs.guide)

## Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**  
2.1 **(Optional)** Soundcloud Client ID **[Guide](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Node.js v12.0.0 or newer


## Prosedur Instalasi:
```
git clone https://github.com/eritislami/evobot.git
cd evobot
npm install
```
Setelah selesai proses instalasi kamu bisa gunakan `node index.js` to start the bot.

## ⚙️ Configuration

File config.json adalah tempat untuk mengatur bot kamu:

⚠️ **Note: Jangan pernah Share token bot discord kamu kepada orang lain!** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "$",
  "PRUNING": false,
  "STAY_TIME": 30
}
```

## 📝 Features & Commands

> Prefix default dari bot ini adalah '$'

* Memutar musik dari link youtube:

`$play https://www.youtube.com/watch?v=0UVC1Zx0fpg`

* Memutar musik berdasarkan pencarian youtube:

`$play Kekeyi aku bukan boneka`

* Memainkan lagu dari SoundCloud menggunakan url:

`$play https://soundcloud.com/example`

* Mencari lagu dari youtube lalu memilihnya sesukamu:

`$search Kekeyi`

* Memainkan dari playlist youtube kamu!

`$playlist linkplaylist`

Command singkat yang bisa kamu gunakan:
* Now Playing ($np)
* Queue system ($queue, $q)
* Loop / Repeat ($loop)
* Shuffle ($shuffle)
* Volume control ($volume, $v)
* Lyrics ($lyrics, $ly)
* Pause ($pause)
* Resume ($resume, $r)
* Skip ($skip, $s)
* Skip to song # in queue ($skipto, $st)
* Remove song # from queue ($remove, $rm)
* Toggle pruning of bot messages ($pruning)
* Help ($help, $h)


## 📝 Credits

Ketuhanan yang Maha ESA, Offensive Security Ghost member, and RPL20
