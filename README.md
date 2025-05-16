# Parvus  [![Discord Shield](https://discordapp.com/api/guilds/958056630321303602/widget.png)](https://discord.gg/sYqDpbPYb7)
Free Roblox Script Hub designed for shooters.  
Made With :heart: By ***@AlexR32***

> [!CAUTION]
> ***Make sure you always use alts when running this, there's always a risk of being banned.***

> [!CAUTION]
> ***I am personally not working on any other game BUT Apocalypse Rising 2, do not run this Hub in any other game.***


### Loadstring
```lua
local IsDevelopmentBranch, NotificationTime = false, 30
local Branch = IsDevelopmentBranch and "development" or "main"
local Source = "https://raw.githubusercontent.com/FlusteredCola594/ParvusAR2/" .. Branch .. "/"
loadstring(game:HttpGet(Source .. "Loader.lua"), "Loader")(Branch, NotificationTime)
```