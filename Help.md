# How to use the AFK bot
If you are here you probalby had trouble working the application and here are the answers to your questions.

# Screenshoting and Discord Webhooks
This application automatically screenshots your screen and sends it to a discord webhook every 30 seconds

if you do not want it to be sent to a disord webhook then you can just make the webook URL space blank

you can also temporarily disable the screenshots in the main application page

My reccomendation is to set it up but just disable the notifications for it in discord

# Roblox/Private Servers
To make the bot automatically open roblox you must have a roblox private server link in the settings page where it asks for it

without this the application will not automatically open roblox or get in a server

if there are other roblox links that make you automatically open roblox and join a server then go ahead and use that

if you do not know where to get that private server link you must go to the servers tab of the game you wish to AFK on click on the configure/... button and in that page there will be the private server join link and that is what you want to in the link spot of the application


# Flask Server/Bot API
upon opening the application for the first time this option will be disabled

this setting is meant for remotely controlling the bot through a discord server

this basically means that it launches a localhost server on port 5000 where a discord bot can send http requests to control the AFK bot

you must create your own discord bot for this to work OR you can use the bot code that i created myself

PLEASE NOTE: THE DISCORD BOT AND AFK BOT MUST BUT RUNNING ON THE SAME WIFI NETWORK 

to get a discord bot token you must go to the discord dev site and create an application and then go to the app settings and then the bot section where you can see the bot token that you will paste in the .env file for the bot to work
