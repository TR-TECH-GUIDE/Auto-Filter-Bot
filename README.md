# Auto Filter Bot

<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg">

  </a>
</p>
<p align="center">
  <a href="https://github.com/TR-TECH-GUIDE/Auto-Filter-Bot/stargazers">
    <img src="https://img.shields.io/github/stars/TR-TECH-GUIDE/Auto-Filter-Bot?style=social">

  </a>
  
  <a href="https://github.com/TR-TECH-GUIDE/Auto-Filter-Bot/fork">
    <img src="https://img.shields.io/github/forks/TR-TECH-GUIDE/Auto-Filter-Bot?label=Fork&style=social">

  </a>  
</p>

[![TR-TECH-GUIDE](https://img.shields.io/badge/SLBotsOfficial-Channel-orange?style=for-the-badge&logo=telegram)](https://telegram.dog/SLBotsOfficial)  
ㅤㅤㅤㅤㅤㅤㅤ  
[![TR-TECH-GUIDE](https://img.shields.io/badge/TRTECHGUIDE-Support-red?style=flat&logo=telegram)](https://telegram.dog/trtechguide)  [![TRTECHGUIDE](https://img.shields.io/badge/TRTECHGUIDE-Website-red?style=flat&logo=CodersRank)](https://trtechguide.wordpress.com/)  
ㅤㅤㅤㅤㅤㅤㅤ  
[![MIT license](https://img.shields.io/badge/License-MIT-blue?style=flat)](https://github.com/TR-TECH-GUIDE/Auto-Filter-Bot/blob/main/LICENSE)  [![Open Source](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/TR-TECH-GUIDE/Auto-Filter-Bot)





#### You can call this as an Auto Filter Bot if you like :D
#### Bot simply search for the files from provided channel according to given query and gives link to those files as buttons!

## How to use the bot
* Add bot to your group with admin rights.

* Add bot to all channels which you want to link with all admin rights!

## Bot Commands - Works in Group only

(You need to be a Auth User in order to use these commands)

* /add channelid  -  Links channel to your group.
or
* /add @channelusername - Links channel to your group.

<i>NOTE : You can get your channel ID from @ChannelidHEXbot </i>


* /del channelid  -  Delinks channel from group
or
* /del @channelusername  -  Delinks channel from group

<i>NOTE : You can get connected channel details by /filterstats </i>


* /delall  -  Removes all connected channels and filters from group!

* /filterstats  -  Check connected channels and number of filters.


## Any bugs or errors or suggestions, report at [TRTECHGUIDE Support](https://telegram.dog/trtechguide)


## Installation

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/TR-TECH-GUIDE/Auto-Filter-Bot)

### Deploy in your vps
```sh
git clone https://github.com/TR-TECH-GUIDE/Auto-Filter-Bot
cd Auto-Filter-Bot
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 main.py
```

## Configs

* TG_BOT_TOKEN  - Get bot token from @BotFather

* APP_ID        - From my.telegram.org (or @UseTGXBot)

* API_HASH      - From my.telegram.org (or @UseTGXBot)

* TG_USER_SESSION  - A pyrogram user session string. Generate by [clicking here](https://replit.com/@PDTharukRenuja/Pyrogram-String-Session)

* AUTH_USERS  - ID of users that can use the bot commands. Get from [TheAmandabot](https://telegram.dog/TheAmandabot) by using /id command

* DATABASE_URI  - Mongo Database URL from https://cloud.mongodb.com/

* DATABASE_NAME  - Your database name from mongoDB. Default will be 'Cluster0'

* DOC_SEARCH  - Should bot search for document files ( Give 'yes' or 'no' )

* VID_SEARCH  - Should bot search for video files ( Give 'yes' or 'no' )

* MUSIC_SEARCH  - Should bot search for music files ( Give 'yes' or 'no' )

