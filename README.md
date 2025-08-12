# Discord.js-Template
Is a template for make a full customized Discord bot adapted to your server on wich is installed

[![Discord.js](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FSachanime%2FDiscord.js-Template%2Fmain%2Fpackage-lock.json&query=%24.packages%5B'node_modules%2Fdiscord.js'%5D.version&label=Discord.js&color=%235865f2&logo=Discord.js)](https://discord.js.org/)

## How to use
Clone this repository and rename it with any name you want<br>
Next, you can edit your new project with an IDE like [Visual Studio Code](https://code.visualstudio.com/)

## Discord Intents
> \[!IMPORTANT]\
> You must declare Discord Itents to use differents events<br>
> To use Discord Privileged Intents, you must activate it on [Discord Developer Portal](https://discord.com/developers/applications) in your bot settings

> \[!NOTE]\
>You can use a list of Discord Intents you need with `intentsBits`, or use a code with `intentsCode`<br>
> To use `intentsCode`, you can use [Discord Itents Calculator](https://discord-intents-calculator.vercel.app/)<br>
> Also, you can see events you can use with Discord Intents checked

## `deployer.js`
Use this file to deploy slash commands you want to use<br>

You need [Node.js](https://nodejs.org/) to execute this script (`node deployer.js`) and deploy commands<br>
You need to execute only once no matter how many times you restart your Discord bot<br>
You must execute it every time you add or edit commands

## `id.json`
Put in this file all id or token you need, like client id, channels id, guilds id, etc...

> \[!IMPORTANT]\
You must put in this file your bot client id and token to use it in the `index.js` and `deployer.js`

## `package.json` and `package-lock.json`
`package.json` contains informations that you can edit, like Discord bot name, version, author, etc...

`package-lock.json` contains informations about Node.js package used in your project<br>

> \[!WARNING]\
You must not edit this file manualy<br>
If you want update a Node.js package, you need [Node.js](https://nodejs.org/) and execute `npm update <package>`<br>

But you can use this file to get informations about packages and use it in your code<br>
*You can see `infosEmbed` for an exemple*
