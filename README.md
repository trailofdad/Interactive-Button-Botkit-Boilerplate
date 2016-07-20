# Interactive-Button-Botkit-Seed
A Slackbot project seed for bots with interactive buttons.

Read all the docs on botkit @ https://github.com/howdyai/botkit
Read all the Slack API docs @ https://api.slack.com/ (especially the bit on interactive buttons)

###This project is all you need to get up and running with interactive messages

* Works with interactive buttons
* Includes sample 'interactive_message_callback' method
* Includes sample help method 
* Includes uptime method
* Includes config file for tokens
* Includes a method to get cat gifs on demand.

##To get your App up and running:
    * Run an `npm install`
    * Make sure you are using a Slack App and have a bot user set
    * Plug your tokens and secrets into the config file (Found by managing your App here: https://api.slack.com)
    * Make sure you have localtunnel running (https://localtunnel.me/) with the url set in your app credentials under redirect URI. (https://api.slack.com -> https://yoursubdomain.localtunnel.me/oauth)
    * Make sure you have your Request URL for interactive messages set to https://yoursubdomain.localtunnel.me/slack/receive
    * Run your bot with "node yourbot.js"
    * Hit the URL "https://yoursubdomain.localtunnel.me/login" to add your bot to a team
    * Direct message your bot "test button" to make sure buttons are working
    * Invite your bot to a channel and have fun!

Created by Christian Hapgood
