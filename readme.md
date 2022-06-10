# LoL Human Case Rest API WA MD Bot

# Installation

## Termux

```cmd
> pkg update && pkg upgrade
> pkg install git -y
> pkg install nodejs -y
> pkg install ffmpeg -y
```

## Windows

-   [`Download ffmpeg`](https://ffmpeg.org/download.html#build-windows) and set path
-   [`Download Node JS`](https://nodejs.org/en/download/)
-   [`Download Git`](https://git-scm.com/downloads)

## Linux

```cmd
> apt-get update && apt-get upgrade
> apt install git -y
> apt install nodejs -y
> apt install ffmpeg -y
```

## Cloning this repo

```cmd
> git clone https://github.com/LoL-Human/Case-WA-MD.git
> cd Case-WA-MD
```

## Install the package

```cmd
> npm i
```

## Edit config file

1. Rename `config.json.example` to `config.json`
2. Edit the required value in `config.json`. You can get the apikey at [`LoL Human Rest API`](https://api.lolhuman.xyz/).

```js
{
    "botName": "DWH", // name of bot
    "ownerName": "EnoAr", // owner name, you should add your name
    "ownerNumber": ["6283175371513@s.whatsapp.net"], // owner number, you should add your number
    "sessionName": "lolhuman", // will be lolhuman-session.json
    "apikey": "421e957252cfa879f752840d" // get apikey on my website (https://api.lolhuman.xyz/)
}
```

## Run the bot

```cmd
> npm start
```

## Note:

-   You can help me add case by doing pull requests.

# Thanks To

-   [`Baileys`](https://github.com/adiwajshing/Baileys)
-   [`Faiz Bastomi`](https://github.com/FaizBastomi/)
