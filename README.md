# Minecraft Server AFK Bot
An AFK Bot for Minecraft Servers.

Currently, this program only supports online-mode=false.

## Dependencies
If you are building from source, install these NodeJS modules:
- mineflayer
- mineflayer-pathfinder
- minecraft-data

## Install
1. Download `afkbot.zip` from latest release.
2. Extract it.
3. Open `afkbot.exe`.
4. Done! You can open `settings.json` to configure some more settings.

## Custom Actions
You can code custom actions for the bot, including moving, jumping etc.

To do so, you must open the `scripts.js`, then remove the code inside the `modules.export` function.
It has a parameter called `bot`, which you can use to control the bot. Documentation in [api.md](https://github.com/Power-Trip-Labs/Minecraft-Server-AFK-Bot/blob/master/api.md).

You can trigger these actions after saving `scripts.js` by pressing E in the terminal.
