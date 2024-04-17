local developer = "made by 7remember_"
if game.PlaceId == 11418578067 then -- Fast Lifting Simulator
loadstring(game:HttpGet("https://raw.githubusercontent.com/thraxhvh/scripts/main/anti%20afk"))()
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Fast Lifting Simulator", "DarkTheme")
-- creating tabs
local AutoFarmSection = Window:NewTab("farming")
local PlayerSection = Window:NewTab("player")
local MiscSection = Window:NewTab("misc")

-- auto farm
local farming = AutoFarmSection:NewSection("farm")
farming:NewToggle("enable farm", "ToggleInfo", function(a)
    aa = a
    while aa do task.wait()
        local args = {
            [1] = math.huge
        }
        
        game:GetService("ReplicatedStorage"):WaitForChild("2663824b812c4e1e80abcb37b7ea983c"):FireServer(unpack(args))
    end
end)
farming:NewToggle("auto sell every 1min", "", function(b)
    bb = b
    while bb do task.wait(60)
        local Player = game.Players.LocalPlayer
        local cpos = Player.Character.HumanoidRootPart.CFrame task.wait(1)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").BaseMap.SellBuy.Sell.Surface.CFrame task.wait(1)
        Player.Character.HumanoidRootPart.CFrame = cpos
    end
end)
farming:NewToggle("auto buy weights every 30s", "", function(c)
    cc = c
    while cc do task.wait(30)
        local args = {
            [1] = "BUYALLWEIGHTS"
        }
        
        game:GetService("ReplicatedStorage"):WaitForChild("1eb183c1aa464630895584d6306f8a3c"):InvokeServer(unpack(args))        
    end
end)

-- player
local player = PlayerSection:NewSection("player")
local plr = game.Players.LocalPlayer.Character.Humanoid
player:NewSlider("speed", "", 500, plr.WalkSpeed, function(v) -- 500 (MaxValue) | 0 (MinValue)
    plr.WalkSpeed = v
end)
player:NewSlider("jump", "", 5000, plr.JumpPower, function(v) -- 500 (MaxValue) | 0 (MinValue)
    plr.JumpPower = v
end)

-- misc
local misc = MiscSection:NewSection("misc")
misc:NewKeybind("keybind", "KeybindInfo", Enum.KeyCode.V, function()
	Library:ToggleUI()
end)
misc:NewLabel(developer)
elseif game.PlaceId == 16230991879 then -- Coding Simulator
loadstring(game:HttpGet("https://raw.githubusercontent.com/thraxhvh/scripts/main/anti%20afk"))()
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Coding Simulator", "DarkTheme")
local AutoFarmSection = Window:NewTab("farming")
local MiscSection = Window:NewTab("misc")

-- auto farm
local farming = AutoFarmSection:NewSection("farm")
farming:NewToggle("auto press key", "", function(a)
    aa = a
    while aa do task.wait()
        local args = {
            [1] = "Lua"
        }
        game:GetService("ReplicatedStorage"):WaitForChild("RF"):WaitForChild("Computer"):WaitForChild("SaveProgram"):InvokeServer(unpack(args))
    end
end)

-- misc
local misc = MiscSection:NewSection("misc")
misc:NewKeybind("keybind", "KeybindInfo", Enum.KeyCode.V, function()
	Library:ToggleUI()
end)
misc:NewLabel(developer)
elseif game.PlaceId == 17164500288 then -- joguin do desiii
loadstring(game:HttpGet("https://raw.githubusercontent.com/thraxhvh/scripts/main/anti%20afk"))()
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("joguin do desiii", "DarkTheme")
-- creating tabs
local AutoFarmSection = Window:NewTab("farming")
local MiscSection = Window:NewTab("misc")

-- auto farm
local farming = AutoFarmSection:NewSection("farm")
farming:NewToggle("delete barrier", "", function(state)
    if state then
        workspace.maps.stand["barrier stand"].CanCollide = false
        workspace.maps.stand["stand parts"]:GetChildren()[11].CanCollide = false
    else
        workspace.maps.stand["barrier stand"].CanCollide = true
        workspace.maps.stand["stand parts"]:GetChildren()[11].CanCollide = true
    end
end)
farming:NewToggle("enable farm ( cooldown )", "ToggleInfo", function(a)
    aa = a
    while aa do task.wait(getgenv().Cooldown)
        game:GetService("ReplicatedStorage").ClickEvent:FireServer()
    end
end)
farming:NewToggle("enable farm ( no cooldown )", "ToggleInfo", function(a)
    aa = a
    while aa do task.wait()
        game:GetService("ReplicatedStorage").ClickEvent:FireServer()
    end
end)
farming:NewTextBox("click p/s", "TextboxInfo", function(v)
	getgenv().Cooldown = v
end)
farming:NewTextBox("get clicks", "", function(v)
    for i = 1, v do wait()
        game:GetService("ReplicatedStorage").ClickEvent:FireServer()
    end
end)
farming:NewTextBox("get clicks ( fast / crash chance )", "", function(v)
    for i = 1, v do
        game:GetService("ReplicatedStorage").ClickEvent:FireServer()
    end
end)
farming:NewTextBox("get clicks ( fast / no crash chance )", "", function(v)
    for i = 1, v do wait(0.00000000000000001)
        game:GetService("ReplicatedStorage").ClickEvent:FireServer()
    end
end)

-- misc
local misc = MiscSection:NewSection("misc")
misc:NewKeybind("keybind", "KeybindInfo", Enum.KeyCode.V, function()
	Library:ToggleUI()
end)
misc:NewLabel(developer)
end
