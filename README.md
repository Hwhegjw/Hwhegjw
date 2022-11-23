

    


local Tab1 = Window:NewTab("Misc")

local Tab1Section = Tab1:NewSection("Misc")

Tab1Section:NewButton("Infinte yelid", "Loads in the gingerbread Fight (you need to be leader for this to work", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()

end)

Tab1Section:NewButton("Auto Fram", "Loads in the gingerbread Fight (you need to be leader for this to work", function()

local args = { [1] = true } workspace.RefreshLocks:FireServer(unpack(args))

noclip = false

game:GetService('RunService').Stepped:connect(function()

if noclip then

game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)

end

end)

noclip = not noclip

game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)

local Character = game:GetService('Players').LocalPlayer.Character

wait(3)

game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-69.0208588, 108.308792, 644.431091))

wait(1)

local CFrameEnd = CFrame.new(-41.7870445, 77.1494141, 8675.35059) -- Place your coords in here

local Time = 33-- Time in seconds

local tween =  game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd})

tween:Play()

tween.Completed:Wait(X) --- Completes, no need for additional wait time

game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-63.2413521, -357.34967, 8819.09277)) wait(0.5)

local CFrameEnd = CFrame.new(-55.8801956, -361.116333, 9488.1377) -- Place your coords in here

local Time = 0 -- Time in seconds

local tween =  game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd})

tween:Play()

tween.Completed:Wait(X)

game.Players.LocalPlayer.CharacterAdded:Connect(function()

wait(3)

game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-69.0208588, 108.308792, 644.431091))

wait(1)

local CFrameEnd = CFrame.new(-41.7870445, 77.1494141, 8675.35059) -- Place your coords in here

local Time = 33-- Time in seconds

local tween =  game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd})

tween:Play()

tween.Completed:Wait(X) --- Completes, no need for additional wait time

game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-63.2413521, -357.34967, 8819.09277)) wait(0.5)

local CFrameEnd = CFrame.new(-55.8801956, -361.116333, 9488.1377) -- Place your coords in here

local Time = 0 -- Time in seconds

local tween =  game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd})

tween:Play()

tween.Completed:Wait(X)

end)

for i=1, math.huge do

wait(200)

game.Players.LocalPlayer.Character.Head:Destroy() end

end)

Tab1Section:NewButton("Steal Build", "Loads in the gingerbread Fight (you need to be leader for this to work", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/StenDirt/Trash-Game/main/Script.lua"))()

end)

local Tab1 = Window:NewTab("Buy Chest")

local Tab1Section = Tab1:NewSection("Buy Chest")

Tab1Section:NewButton("Common", "Loads in the gingerbread Fight (you need to be leader for this to work", function()

local args = {

    [1] = "Common Chest",

    [2] = 1

}

workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Uncommon Chest", "Loads in the gingerbread Fight (you need to be leader for this to work", function()

local args = {

    [1] = "Uncommon Chest",

    [2] = 1

}

workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Rare Chest", "Loads in the gingerbread Fight (you need to be leader for this to work", function()

local args = {

    [1] = "Rare Chest",

    [2] = 1

}

workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Legendary Chest", "Loads in the gingerbread Fight (you need to be leader for this to work", function()

local args = {

    [1] = "Legendary Chest",

    [2] = 1

}

workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

local Tab1 = Window:NewTab("Change Team Color")

local Tab1Section = Tab1:NewSection("Team Color")

Tab1Section:NewButton("Yellow🟡", "Ok", function()

local args = {

    [1] = game:GetService("Teams").yellow

}

workspace.ChangeTeam:FireServer(unpack(args))

end)

Tab1Section:NewButton("White⚪", "Ok", function()

local args = {

    [1] = game:GetService("Teams").white

}

workspace.ChangeTeam:FireServer(unpack(args))

end)

Tab1Section:NewButton("Red🟥", "Ok", function()

local args = {

    [1] = game:GetService("Teams").red

}

workspace.ChangeTeam:FireServer(unpack(args))

end)

Tab1Section:NewButton("magneta🟣", "Ok", function()

local args = {

    [1] = game:GetService("Teams").magenta

}

workspace.ChangeTeam:FireServer(unpack(args))

end)

Tab1Section:NewButton("green🟢", "Ok", function()

local args = {

    [1] = game:GetService("Teams").green

}

workspace.ChangeTeam:FireServer(unpack(args))

end)

Tab1Section:NewButton("Black⚫", "Ok", function()

local args = {

    [1] = game:GetService("Teams").black

}

workspace.ChangeTeam:FireServer(unpack(args))

end)

Tab1Section:NewButton("Blue🟦", "Ok", function()

local args = {

    [1] = game:GetService("Teams").blue

}

workspace.ChangeTeam:FireServer(unpack(args))

end)

local Tab1 = Window:NewTab("Buy Any Block")

local Tab1Section = Tab1:NewSection("Buy Item")

Tab1Section:NewButton("Buy Seat🪑(10 Gold)", "Ok", function()

local args = {     [1] = "Seat",     [2] = 1 }  workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Buy Truss (Needed 125 Gold)", "Ok", function()

local args = {     [1] = "Truss",     [2] = 1 }  workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Buy Glue (15 Gold)", "Ok", function()

local args = {     [1] = "Glue",     [2] = 1 }  workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Buy Cannon (80 Gold)", "Ok", function()

local args = {     [1] = "Cannon",     [2] = 1 }  workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Buy Switch (50 Gold)", "Ok", function()

local args = {     [1] = "Switch",     [2] = 1 }  workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

local Tab1 = Window:NewTab("Buy Tool Build")

local Tab1Section = Tab1:NewSection("Buy Tool Build")

Tab1Section:NewButton("Buy Paint Tool (1500 Gold)", "Ok", function()

local args = {     [1] = "PaintingTool",     [2] = 1 }  workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Buy Scale Tool (5000 Gold)", "Ok", function()

local args = {     [1] = "ScalingTool",     [2] = 1 }  workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Buy biod tool (2000 Gold)", "Ok", function()

local args = {     [1] = "BindTool",     [2] = 1 }  workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Buy Ppt tool (2500 Gold)", "Ok", function()

local args = {     [1] = "PropertiesTool",     [2] = 1 }  workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Buy TT (7500 Gold)", "Ok", function()

local args = {     [1] = "TrowelTool",     [2] = 1 }  workspace.ItemBoughtFromShop:InvokeServer(unpack(args))

end)

local Tab1 = Window:NewTab("Settings")

local Tab1Section = Tab1:NewSection("U Need Become Leader")

Tab1Section:NewButton("Block On", "Ok", function()

local args = {

    [1] = "BlockRequests",

    [2] = true

}

workspace.SettingFunction:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Block Off", "Ok", function()

local args = {

    [1] = false

}

workspace.RefreshLocks:FireServer(unpack(args))

end)

Tab1Section:NewButton("PvP On", "Ok", function()

local args = {

    [1] = true

}

workspace.PVPRemote:FireServer(unpack(args))

end)

Tab1Section:NewButton("Pvp Off", "Ok", function()

local args = {

    [1] = false

}

workspace.PVPRemote:FireServer(unpack(args))

end)

Tab1Section:NewButton("Hide Tag", "Ok", function()

workspace.HideTagFunction:InvokeServer()

end)

Tab1Section:NewButton("Isolation On", "Ok", function()

local args = {

    [1] = true

}

workspace.RefreshLocks:FireServer(unpack(args))

end)

Tab1Section:NewButton("Isolation Off", "Ok", function()

local args = {

    [1] = false

}

workspace.RefreshLocks:FireServer(unpack(args))

end)

Tab1Section:NewButton("Another V6", "Ok", function()

local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()

local Window = Library.CreateLib("Tutorial", "Ocean")

-- Tabs



local Tab1 = Window:NewTab("Build a Boat Madr by Hwhegjw1 V6 OP")

local Tab1Section = Tab1:NewSection("Made By Hwhegjw1")



-- Buttons/Windows/Idk



Tab1Section:NewButton("Code =D", "Enables Inf Jumps", function()

local args = {

    [1] = "=D"

}

workspace.CheckCodeFunction:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Code =P", "Enables Inf Jumps", function()

local args = {

    [1] = "=P"

}

workspace.CheckCodeFunction:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Code Hi", "Enables Inf Jumps", function()

local args = {

    [1] = "Hi"

}

workspace.CheckCodeFunction:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Code Squid Army", "Enables Inf Jumps", function()

local args = {

    [1] = "Squid Army"

}

workspace.CheckCodeFunction:InvokeServer(unpack(args))

end)

Tab1Section:NewButton("Code chillthrill709 was here", "Enables Inf Jumps", function()

local args = {

    [1] = "chillthrill709 was here"

}

workspace.CheckCodeFunction:InvokeServer(unpack(args))

end)

Tab1Section:NewToggle("Mute Sound", "Changes Fov", function(state)

    if state then

        workspace.MuteMusicRemote:InvokeServer()        

    else

        workspace.MuteMusicRemote:InvokeServer()

    end

end)
