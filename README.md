# It's Wednesday My Dudes Discord Bot

[![Build Status](https://travis-ci.org/brooksbecton/ItsWednesdayMyDudesDiscordBot.svg?branch=master)](https://travis-ci.org/brooksbecton/ItsWednesdayMyDudesDiscordBot)
[![codecov](https://codecov.io/gh/brooksbecton/ItsWednesdayMyDudesDiscordBot/branch/master/graph/badge.svg)](https://codecov.io/gh/brooksbecton/ItsWednesdayMyDudesDiscordBot)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

Bot that will tell a channel that it is Wednesday and will link a "It's Wednesday my dudes" meme

## Setup

You will need an .env file in the root of the project with structure like

```env
token=YOUR_DISCORD_TOKEN
```

[How to get a Discord token](https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token)

## Functionality

* Listens for "_my dude_" and "_wednesday_" and will tell you if it is Wednesday
* Listens for "_ping_" and will reply with "_pong_", by popular demand
