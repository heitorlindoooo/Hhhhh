local OrionLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/shlexware/Orion/main/source"))()

local Window = OrionLib:MakeWindow({Name = "femware v2", HidePremium = false, SaveConfig = true, ConfigFolder = "femware"})

local Tab = Window:MakeTab({
    Name = "Main",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
    })

local Section = Tab:AddSection({
    Name = "Main"
    })

Tab:AddButton({
    Name = "Noclip",
    Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/1G1ZU1g1"))()
      # Hhhhh
