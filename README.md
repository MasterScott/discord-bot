# discord-bot

## What is it?
Basic setup for a customizable Discord bot using Discord.js. More resources for further developing it to your specifications farther down this README.

## How do I set it up?
0. Make a Discord application and bot within the application: https://discordapp.com/developers/applications/. Remember to save your client ID and bot token for later. 
1. Authorize the bot you just made for use in your server by following this link: https://discordapp.com/oauth2/authorize?client_id=INSERT_CLIENT_ID_HERE&scope=bot. (You'll need administrative access to your server to authorize this) Remember to give your bot permissions to post in the channel(s) where you'd like to see output before actually running the code.
2. Paste and save your Discord bot's token in the 'token' section of `config.json`. You can also change the prefix (character that precedes actionable bot commands) in this file; the default is `!`.
3. Install Node.js / NPM: https://www.npmjs.com/get-npm
4. Open Terminal / Command Prompt and execute the following code:
```
cd __directory you saved this code__
npm install 
node main
```
*only run `npm install` the first time you run this code; it installs the necessary packages if you don't have them already.
*you can run `node --inspect main` instead of `node main` for debugging purposes (a Node.js debugging inspector will run alongside your bot)

## Just got it set up, what next?
- Once `main.js` is running (you should see a message saying 'You are now logged in'), type `!help` in any channel that the bot can access.
- Your bot will stay online in your server as long as the Terminal / Command Prompt window from which it was launched is left alive.
- Here's some sample outputs you might see when the bot is online and functioning correctly:

  ![title](https://github.com/washedgram/discord-bot/blob/master/example%20ss.jpg)


## How can I add more functionality?
- Straight from the source: https://discordjs.guide/#/
- Basic features: https://gist.github.com/y21/a599ef74c8746341dbcbd32093a69eb8
- Embed messages: https://anidiots.guide/first-bot/using-embeds-in-messages
- More: https://github.com/discordjs/Commando-guide

I'm going to add more example commands / functions in the future for anyone interested in following this repository. I wasn't able to find a singular resource to help kickstart this process from square one all the way to having the actual bot running, so I figured this might be somewhat useful for someone else.
