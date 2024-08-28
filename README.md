# DiscordChatBridge
A Simple cross-discord server bridge that relays messages from one discord server channel to another.

Installation:
1. Extract contents from zip onto python server. (bot.py is the file you want your server to run)
2. Head to https://discord.com/developers/applications/ and create a bot "application" with 'bot' permissions (Send Msg, Atch Files, Read History, Embed).
3. Invite your bot to your discord server with the Auth2 url generated in the discord developers portal.
4. Go into 'config.py' and add the channelID's (for this you need developer mode enabled within your discord client) as well as your bots TOKEN.
5. Lastly go into your discord server 'Roles', find "|BC|", permissions, and enable 'Manage Webhooks'
6. Start the bot :)
