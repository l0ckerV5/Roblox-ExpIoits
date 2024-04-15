local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "Earth Hub Premium",
   LoadingTitle = "Loading Earth Hub Premium",
   LoadingSubtitle = "by l0ckerV5",
   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Earth Hub [PREMIUM]"
   },
   Discord = {
      Enabled = false,
      Invite = "64H65f8stX", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "Earth Hub Premium",
      Subtitle = "Key System",
      Note = "Buy the Key in our discord",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"fSizM4vc"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local Tab = Window:CreateTab("Admin Scripts", 17155750103) -- Title, Image

local Section = Tab:CreateSection("Admins")

Rayfield:Notify({
   Title = "Welcome!",
   Content = "Thanks for buying premium!",
   Duration = 6.5,
   Image = 17155750103,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "Okay!",
         Callback = function()
         print("The user tapped Okay!")
      end
   },
},
})

local Button = Tab:CreateButton({
   Name = "Reviz Admin",
   Callback = function() loadstring(game:HttpGet("https://pastebin.com/raw/SdfBVYDA"))();
   end,
})

local Button = Tab:CreateButton({
   Name = "Infinite Yield",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Nameless Admin",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source'))()
   end,
})

local Section = Tab:CreateSection("Player")

local Slider = Tab:CreateSlider({
   Name = "WalkSpeed",
   Min = 16
   Max = 500,
   Default = 16,
   Color = Color3.fromRGB(255,255,255),
 Increment = 1,
 ValueName = "WS",
 Callback = function(Value)
  game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
 end    
})

PlayerTab:AddSlider({
 Name = "Jump Height",
 Min = 16,
 Max = 500,
 Default = 5,
 Color = Color3.fromRGB(255,255,255),
 Increment = 1,
 ValueName = "Height",
 Callback = function(Value)
  game.Players.LocalPlayer.Character.Humanoid.JumpPower = Value
 end

})

local Tab = Window:CreateTab("Main Scripts", 17155750103) -- Title, Image

local Section = Tab:CreateSection("Blade Ball")

local Button = Tab:CreateButton({
   Name = "Bedol Hub",
   Callback = function()
loadstring(game:HttpGet("https://scriptblox.com/raw/Blade-Ball-Autofarm-8968"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "YELOO Hub",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/kierpogihahaxd2/MANUAL/main/Script'))()
   end,
})

local Section = Tab:CreateSection("Da Hood")

local Button = Tab:CreateButton({
   Name = "RayCodex",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/SpaceYes/Lua/Main/DaHood.Lua'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "l0ckerV5 Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/l0ckerV5/robIox/main/l0ckerV5-HUB"))();
   end,
})

local Button = Tab:CreateButton({
   Name = "Faded",
   Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/P1K1K2YS"))();
   end,
})

local Button = Tab:CreateButton({
   Name = "Swagmode V4",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/lerkermer/lua-projects/master/SwagModeV002'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "l0ckerV5 Lock",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/l0ckerV5/roblox/main/l0ckerV5-lock"))();
   end,
})

local Button = Tab:CreateButton({
   Name = "Nyula Lock",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/nyulachan/nyula/main/nyulauh"))();
   end,
})

local Button = Tab:CreateButton({
   Name = "Starlight Hub",
   Callback = function()
loadstring(game:HttpGet("https://pastefy.app/zwDcXfgB/raw"))()
   end,
})

local Section = Tab:CreateSection("Arsenal")

local Button = Tab:CreateButton({
   Name = "TBAO Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHubArsenal"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "PWNER Hub",
   Callback = function()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/Maikderninja/Maikderninja/main/PWNERHUB.lua"), true))()
   end,
})

local Section = Tab:CreateSection("Brookhaven")

local Button = Tab:CreateButton({
   Name = "Game Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamerScripter/Game-Hub/main/loader"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Ice Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMae17/NewIceHub/main/Brookhaven"))()
   end,
})

local Section = Tab:CreateSection("Murder Mystery 2")

local Button = Tab:CreateButton({
   Name = "TBAO Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHubMurderMystery2"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Owl Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))(); -- Like and SUBBBBB
   end,
})

local Section = Tab:CreateSection("The Strongest Battlegrounds")

local Button = Tab:CreateButton({
   Name = "Mrbaconscripts Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/FFJ1/Roblox-Exploits/main/scripts/TSBUtils.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Nex Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CopyReal/NexHub/main/NexHubLoader", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Xtrey Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/xtrey10x/xtrey10x-hub/main/saitama"))()
   end,
})

local Section = Tab:CreateSection("Slap Battles")

local Button = Tab:CreateButton({
   Name = "Slap Battles Hub that exists",
   Callback = function()
loadstring(game:HttpGet("https://scriptblox.com/raw/Slap-Battles-Open-source-for-9484"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "R20",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/cheesynob39/R2O/main/LOADSTRING.lua"))()
   end,
})

local Tab = Window:CreateTab("Other Scripts", 17155750103) -- Title, Image

local Section = Tab:CreateSection("Fun Scripts")

local Button = Tab:CreateButton({
   Name = "FE Bang GUI R15/R6",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/manimcool21/bang/main/Protected%20(27).lua'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "YELOO Hub",
   Callback = function()

   end,
})

local Button = Tab:CreateButton({
   Name = "TimeStop Scripr",
   Callback = function()
loadstring(game:HttpGet('https://pastebin.com/raw/djAd7g2W'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "FE Free Gamepasses",
   Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/Vk5LfiQG"))();
   end,
})

local Button = Tab:CreateButton({
   Name = "FE Invisible Tool",
   Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/LxgLD2vK"))();
   end,
})

local Tab = Window:CreateTab("Misc", 17155750103) -- Title, Image

local Section = Tab:CreateSection("Extra")

local Button = Tab:CreateButton({
   Name = "Mobile Keyboard",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "FPS Booster",
   Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/qQtE2hLr"))();
   end,
})

local Button = Tab:CreateButton({
   Name = "Fly GUI V4",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Earth Hub [FREE VERSION]",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/l0ckerV5/Roblox-Exploits/main/Earth-Hub"))();
   end,
})

local Tab = Window:CreateTab("GUIs", 17155750103) -- Title, Image

local Section = Tab:CreateSection("Hubs")

local Button = Tab:CreateButton({
   Name = "FE Script Hub",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/Dvrknvss/UniversalFEScriptHub/main/Script'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "DomainX Hub",
   Callback = function()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/drakker33/rblx-decaying-winter/main/DecayingWinter.lua"), true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Ultimate Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Roblox-ScriptsWeAreDevs/Ultimate-Hub/main/CODE.md"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Ez Hub",
   Callback = function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/debug42O/Ez-Industries-Launcher-Data/master/Launcher.lua'),true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Mobile Hub",
   Callback = function()
loadstring(game:HttpGet("https://shz.al/~mobile-hub"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Elemental Hub",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamerReady/Elemental-hub-v2-cracked/main/Elemental-hub-v2-cracked", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Game Hub V3",
   Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/18ji1xzk"))();
   end,
})

local Tab = Window:CreateTab("Settings", 17155750103) -- Title, Image

local Section = Tab:CreateSection("Antis")

local Toggle = Tab:CreateToggle({
   Name = "Anti Ban",
   CurrentValue = false,
   Flag = "Anti Ban", 
   end,
})

local Toggle = Tab:CreateToggle({
   Name = "Anti Kick",
   CurrentValue = false,
   Flag = "Anti Kick", 
   end,
})

local Toggle = Tab:CreateToggle({
   Name = "Anti Lag",
   CurrentValue = false,
   Flag = "Anti Lag", 
   end,
})

local Button = Tab:CreateButton({
   Name = "Rejoin",
   Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/9NSejy88"))();
   end,
})

local Button = Tab:CreateButton({
   Name = "ServerHop",
   Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/h5GKw7uX"))()
   end,
})

local Section = Tab:CreateSection("UI Modifier")

local Input = Tab:CreateInput({
   Name = "Menu Size",
   PlaceholderText = "Enter Size",
   RemoveTextAfterFocusLost = false,
   Callback = function(Text)
   end,
})

local ColorPicker = Tab:CreateColorPicker({
    Name = "Menu Color",
    Color = Color3.fromRGB(255,255,255),
    Flag = "Menu Color",
    Callback = function(Value)
end
})
