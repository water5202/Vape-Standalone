# vapetweaker
A wrapper for VapeV4ForRoblox by 7GrandDad to make it easier to make your own custom modules.<br>
```lua
local vapetweaker = loadstring(game:HttpGet("https://raw.githubusercontent.com/water5202/vapetweaker/refs/heads/main/src/wrapper.lua"))()
```
#Usage
It preloads most libraries that vape uses (vapetweaker.getvapeasset, you get the picture).<br>
Use it like any other, for example<br>
```lua
vape.Categories.Blatant:CreateModule("Ragebot", Function = function() end, Tooltip = "Detects and shoots any enemies if it seen by raycast")
```
