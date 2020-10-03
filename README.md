# Steve the bot - A discord bot for the CGS 2025 discord server.
## Features   
Says 'citation needed' whenever YAGPDB says anything outragous, tells people looking for their !rank to chill, and quotes Steve and Dale.

## How to run the bot locally
Create a seperate folder and clone the repository in the that folder using `git clone https://github.com/KazMalhotra/discordbot.git` or by downloading the code from [here](https://github.com/KazMalhotra/discordbot/archive/master.zip)

After cloning the repository use the command `npm install` or `npm i` to install all the dependencies from `package.json`, this automatically installs `node_modules` too. 

To run the bot locally replace the `process.env.TOKEN` in `var token` in the `index.js` file with your bot token which you can aquire from the [Discord developer portal](https://discord.com/developers/applications)

For exmaple
```
var token = "<Replace this with your token>";
```

## Contributing   
If you would like to contribute to the bot, make sure you are somewhat familiar with node.js. This bot uses the discord.js wrapper for the discord api. If you would like to contribute, just send me a pull request!

### Contributing quotes:  
If you would like to contribute Steve quotes, either add them to the `quotes` array and send me a PR, or fill out [this form](https://forms.gle/xu6HuagzRK1uWvyC9)
