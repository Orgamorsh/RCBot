# RCBot
A bot for Discord that can be remotely controled like a user.

---Preinstallation---

Install node.js: https://nodejs.org/en/

Extract the zip

---How to set up---

  RCBot is fairly simple to set up. First, go to https://discordapp.com/developers/applications/ . You will need to make a new
application and bot account.

  Afterwards, copy the bot token on the bot page. You will need to extract the zip and open index.js in a text editor such
as Notepad++. Under the section labled "Bot start", replace "Put login token here" with your bot token.

  The bot should be ready to start now. Try running start.bat to launch the bot.
  
---Instructions---

  After launch, the bot should have a CMD open with the text "Bot Online". Select a text channel by typing /channel into
the CMD and entering the channel ID. You can now send messages through the CMD to the text channel. You can send direct messages
the same way, but use /user to select the user and /dm to send the message.

---Commands---

/quit - Sets status to invisible and quits the program

/channel - Selects the active text channel

/user - Selects the active user

/dm - sends a direct message

/currentchannel - Shows current channel ID

/currentuser - Shows current channel ID

/status - Lets you set the bot's status to online, idle, invisible, and DnD.

/game - Sets a playing status

/listening - Sets a listening status

/stream - Sets a stream status

/watch - Sets a watching status
