local player = game.Players.LocalPlayer
local OrionLib = loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/Orion/main/source'))()
local Window = OrionLib:MakeWindow({Name = "Jolly Hub", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab1 = Window:MakeTab({Name = "Tab 1", Icon = "rbxassetid://4483345998", PremiumOnly = false})
Tab1:AddSection({Name = "MadeByBengiUw"})
Tab1:AddButton({Name = "High Speed", Callback = function() player.Character.Humanoid.WalkSpeed = 500 end})
Tab1:AddButton({Name = "High Jumppower", Callback = function() player.Character.Humanoid.JumpPower = 100 end})
Tab1:AddButton({Name = "Low Gravity", Callback = function() game.Workspace.Gravity = 10 end})
Tab1:AddButton({Name = "Test Flight", Callback = function() player.Character.Humanoid.JumpPower = 1000 end})
Tab1:AddButton({Name = "Edit Me 2", Callback = function() print("Edit Me 2 Button Clicked!") end})

local Tab2 = Window:MakeTab({Name = "Tab 2", Icon = "rbxassetid://4483345998", PremiumOnly = false})
Tab2:AddSection({Name = "Settings"})
Tab2:AddButton({Name = "Reset Speed", Callback = function() player.Character.Humanoid.WalkSpeed = 16 end})
Tab2:AddButton({Name = "Reset Jump", Callback = function() player.Character.Humanoid.JumpPower = 50 end})
Tab2:AddButton({Name = "Restore Gravity", Callback = function() game.Workspace.Gravity = 196.2 end})
