# Cordevall for Lua
### Basically Cordevall Discord Bot for Lua

For more bots in different programming languages, go to: https://github.com/Eveeifyeve/DiscordBots

## How to Install Lua
#### Step  1:
Go to http://github.com/rjpcomputing/luaforwindows/releases

#### Step  2:
Download the most recent version (the .exe file) and open it.

#### Step  3:
Go through the installer and click Finish (optional: If you are a beginner, before you click 'Finish', click the 'Run a simple introduction' checkbox. It will open an introduction on how to use Lua.)

### Before you begin, you need to install Luvit and Discordia as they aren't pre-installed into Lua for Windows.

#### Step 4:
Go to http://luvit.io and follow the instructions provided for your platform

#### Step 5:
To install Discordia, run ```lit install SinisterRectus/discordia```

#### Step 6:
Run your bot script using, for example, ```luvit bot.lua```

### Example from Discordia
```
local discordia = require('discordia')
local client = discordia.Client()

client:on('ready', function()
	print('Logged in as '.. client.user.username)
end)

client:on('messageCreate', function(message)
	if message.content == '!ping' then
		message.channel:send('Pong!')
	end
end)

client:run('Bot INSERT_TOKEN_HERE')
```
# Credits:
#### Cordevall was created by Eveeifyeve
#### Cordevall for Lua was created by StarryTheSuperstar
