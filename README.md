**RWC - Roblox WHYI_MFAT Code**
-

Welcome to RWC - Roblox WHYI_MFAT Code!
This module is shortens the process of making scripts in roblox studio by abbreviated commands in a string that simulates code.

-------
**How To Use?**
-

if you want to learn how to use RWC this is the right place!
first you need to know how does it looks like, everything is built from something and then () that inside genders what is inside it.
if there is more then one definition then you can use , (one, two) just like outside in lua.


1. **basics** in here you can see all the basics (most are similar to the normal):

* wait({seconds}) - with this you can wait in seconds how much time you want and then the code will keep running
* print({text}) - with this you can print in the console what you want


2. **operations operation** in here you can see all what doing anything or something like that:

* kill({player name}) - that is will kill a player.
* heal({player name}, {health}) - that is will set player health.
* tp({player name}, {someone to teleport to him player name}) - with this player can teleport to another player.
* kick({player name}, {kick message}) - that is will kick player.

-------
**Example:**
-
this getting RWC model from workspace and players and player and then starting the Run function of RWC and then starting with RWC code it will wait 1 second and then print in the console hi and then wait 2 seconds and then print in the console bye and then kick the player with message lol


```lua

local RWC = require(workspace.RWC)
local plrs = game.Players
local plr = plrs.LocalPlayer

RWC.Run(RWC, [[

wait(1)
print("hi")

wait(2)
print("bye")

kick(]]..plr.Name..[[, "lol")
]])
```


-------
More updates added soon.

-------
You can click in this link: https://www.roblox.com/games/13732365181/RWC-Roblox-WHYI-MFAT-Code
to test RWC inside a game that run the code.
