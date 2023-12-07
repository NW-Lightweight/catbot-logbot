# catbot-logbot
Created for relaying Team Fortress chat to discord chat
##### Instructions:
1. Download Node.JS (latest version)
2. Git clone this repo
3. Make private.json by using private.example.json
4. Run "npm install" to install all required packages as well as pm2
5. Run the script using command "pm2 start logbot1.js"
##### Changes:
Removes "discord.gg/" from messages to prevent invite spam in relay channel. <br>
To ensure no embed links are sent, go to channel settings and disable "Embed Links" for the discord bot. <br>
Disabling ping perms is also advised.
