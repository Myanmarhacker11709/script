local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Fox_Hack", "Synapse")

--Main
local Main = Window:NewTab("Main")
local MainSection = Main:NewSection("Main")

MainSection:NewButton("Ctrl+Click tp", "Make ypu tp", function()
    loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Click%20Teleport.txt"))()
end)

MainSection:NewButton("Air_Jump", "Make you jump in the air", function()
    loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Infinite%20Jump.txt"))()
end)

--Player
local Player = Window:NewTab("Player")
local PlayerSection = Player:NewSection("Player")


PlayerSection:NewSlider("Walk speed", "Walk_Speed", 500, 16, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

PlayerSection:NewSlider("JumpPower", "Jump  _Power", 500, 50, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)

--Rainbow
local RainbowFriends = Window:NewTab("RainbowFriends")
local RainbowFriendsSection = RainbowFriends:NewSection("RainbowFriends")

RainbowFriendsSection:NewButton("Gui", "Esp", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Ihaveash0rtnamefordiscord/BorkWare/main/Scripts/' .. game.GameId .. ".lua"))(' Watermelon ? ')
end)

--Arsenal
local Arsenal = Window:NewTab("Arsenal")
local ArsenalSection = Arsenal:NewSection("Arsenal")

ArsenalSection:NewButton("Gui", "ainbot,esp,ect...", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/SmoxHub/SmoxHub-V2/main/Arsenal-V2"))()
end)

--Car Dealership Tycoon
local Car_Dealership = Window:NewTab("Car_Dealership")
local Car_DealershipSection = Car_Dealership:NewSection("Car_Dealership")

Car_DealershipSection:NewButton("Gui", "autofarm", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GodXNation/GodXNation/main/midnight%20racing%20hubV2%20fixed", true))()
end)

local Car_DealershipSection = Car_Dealership:NewSection("godxnation356j")
