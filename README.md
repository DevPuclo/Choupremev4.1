--[[
	 Gui to Lua Converter
-- Revamped by:HoIyScript
--]]



-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local TextButton_6 = Instance.new("TextButton")
local TextButton_7 = Instance.new("TextButton")
local TextButton_8 = Instance.new("TextButton")
local TextButton_9 = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local Frame2 = Instance.new("Frame")
local TextButton_10 = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")


--[[
	Properties:
--]]

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(0.164706, 0.164706, 0.164706)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0383211672, 0, 0.0656063631, 0)
Frame.Size = UDim2.new(0.0994525552, 0, 0.0337972157, 0)
Frame.Active = true
Frame.Draggable = true

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton.BackgroundTransparency = 1
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.854838729, 0, 0, 0)
TextButton.Size = UDim2.new(0.145161286, 0, 1, 0)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.Text = "-"
TextButton.TextColor3 = Color3.new(1, 1, 1)
TextButton.TextScaled = true
TextButton.TextSize = 14
TextButton.TextWrapped = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel.BackgroundTransparency = 1
TextLabel.Size = UDim2.new(1, 0, 1, 0)
TextLabel.Font = Enum.Font.SourceSansLight
TextLabel.Text = "Main"
TextLabel.TextColor3 = Color3.new(1, 1, 1)
TextLabel.TextScaled = true
TextLabel.TextSize = 14
TextLabel.TextWrapped = true

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.new(0.164706, 0.164706, 0.164706)
Frame_2.BorderColor3 = Color3.new(0.164706, 0.164706, 0.164706)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0, 0, 1.00900004, 0)
Frame_2.Size = UDim2.new(1, 0, 6.1800001, 0)

TextButton_2.Parent = Frame_2
TextButton_2.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_2.BackgroundTransparency = 1
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0, 0, 0.0272358228, 0)
TextButton_2.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_2.Font = Enum.Font.SourceSansLight
TextButton_2.Text = "God Mode"
TextButton_2.TextColor3 = Color3.new(1, 1, 1)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 16
TextButton_2.TextWrapped = true

TextButton_3.Parent = Frame_2
TextButton_3.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_3.BackgroundTransparency = 1
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0, 0, 0.148021415, 0)
TextButton_3.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_3.Font = Enum.Font.SourceSansLight
TextButton_3.Text = "Remove"
TextButton_3.TextColor3 = Color3.new(1, 1, 1)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 16
TextButton_3.TextWrapped = true

TextButton_4.Parent = Frame_2
TextButton_4.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_4.BackgroundTransparency = 1
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0, 0, 0.268807083, 0)
TextButton_4.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_4.Font = Enum.Font.SourceSansLight
TextButton_4.Text = "God Mode [ALL]"
TextButton_4.TextColor3 = Color3.new(1, 1, 1)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 16
TextButton_4.TextWrapped = true

TextButton_5.Parent = Frame_2
TextButton_5.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_5.BackgroundTransparency = 1
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0, 0, 0.389592737, 0)
TextButton_5.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_5.Font = Enum.Font.SourceSansLight
TextButton_5.Text = "Remove [ALL]"
TextButton_5.TextColor3 = Color3.new(1, 1, 1)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 16
TextButton_5.TextWrapped = true

TextButton_6.Parent = Frame_2
TextButton_6.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_6.BackgroundTransparency = 1
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0, 0, 0.51037842, 0)
TextButton_6.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_6.Font = Enum.Font.SourceSansLight
TextButton_6.Text = "No name"
TextButton_6.TextColor3 = Color3.new(1, 1, 1)
TextButton_6.TextScaled = true
TextButton_6.TextSize = 16
TextButton_6.TextWrapped = true

TextButton_7.Parent = Frame_2
TextButton_7.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_7.BackgroundTransparency = 1
TextButton_7.BorderSizePixel = 0
TextButton_7.Position = UDim2.new(0, 0, 0.631163955, 0)
TextButton_7.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_7.Font = Enum.Font.SourceSansLight
TextButton_7.Text = ""
TextButton_7.TextColor3 = Color3.new(1, 1, 1)
TextButton_7.TextScaled = true
TextButton_7.TextSize = 16
TextButton_7.TextWrapped = true

TextButton_8.Parent = Frame_2
TextButton_8.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_8.BackgroundTransparency = 1
TextButton_8.BorderSizePixel = 0
TextButton_8.Position = UDim2.new(0, 0, 0.751949549, 0)
TextButton_8.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_8.Font = Enum.Font.SourceSansLight
TextButton_8.Text = ""
TextButton_8.TextColor3 = Color3.new(1, 1, 1)
TextButton_8.TextScaled = true
TextButton_8.TextSize = 16
TextButton_8.TextWrapped = true

TextButton_9.Parent = Frame_2
TextButton_9.BackgroundColor3 = Color3.new(1, 1, 1)
TextButton_9.BackgroundTransparency = 1
TextButton_9.BorderSizePixel = 0
TextButton_9.Position = UDim2.new(0, 0, 0.879840255, 0)
TextButton_9.Size = UDim2.new(1, 0, 0.124845669, 0)
TextButton_9.Font = Enum.Font.SourceSansLight
TextButton_9.Text = ""
TextButton_9.TextColor3 = Color3.new(1, 1, 1)
TextButton_9.TextScaled = true
TextButton_9.TextSize = 16
TextButton_9.TextWrapped = true

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.new(1, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0, 0, 1, 0)
TextLabel_2.Size = UDim2.new(1, 0, 0.100000001, 0)
TextLabel_2.ZIndex = 5
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = ""
TextLabel_2.TextColor3 = Color3.new(0, 0, 0)
TextLabel_2.TextSize = 14





--[[
	 Scripts:
--]]

local function DAUB_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Text == "-" then
			script.Parent.Text = "+"
			script.Parent.Parent.Frame:TweenSize(UDim2.new(1, 0,0, 0),"In","Quint",0.5)
		elseif
			script.Parent.Text == "+" then
				script.Parent.Text = "-"
				script.Parent.Parent.Frame:TweenSize(UDim2.new(1, 0,6.15, 0),"Out","Quint",0.5)
		end
	end)
end
coroutine.wrap(DAUB_fake_script)()
local function MOBT_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
-- Madcity Godmode (LocalPlayer)

local this_guy_has_godmode = game.Players.LocalPlayer.Name
_G.God = true -- On/Off
while _G.God and wait() do
       pcall(function()
           local A_1 = "RevivePlayer"
           local A_2 = game:GetService("Workspace")[this_guy_has_godmode]
           local A_3 = game:GetService("Workspace").ObjectSelection.DownedPart.DownedPart
           local Event = game:GetService("ReplicatedStorage").Event
           Event:FireServer(A_1, A_2, A_3)
           end)
end
	end)
end
coroutine.wrap(MOBT_fake_script)()
local function UTMXHAV_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
-- Madcity Godmode (LocalPlayer)

local this_guy_has_godmode = game.Players.LocalPlayer.Name
_G.God = false -- On/Off
while _G.God and wait() do
       pcall(function()
           local A_1 = "RevivePlayer"
           local A_2 = game:GetService("Workspace")[this_guy_has_godmode]
           local A_3 = game:GetService("Workspace").ObjectSelection.DownedPart.DownedPart
           local Event = game:GetService("ReplicatedStorage").Event
           Event:FireServer(A_1, A_2, A_3)
           end)
end
	end)
end
coroutine.wrap(UTMXHAV_fake_script)()
local function HKCZUDL_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
-- Madcity Godmode Server

local Players = game:GetService("Players")
_G.Godserver = true -- On/Off
while wait() and _G.Godserver do
   pcall(function()
       for i, all in pairs(Players:GetPlayers()) do
           local A_1 = "RevivePlayer"
           local A_2 = game:GetService("Workspace")[all.Name]
           local A_3 = game:GetService("Workspace").ObjectSelection.DownedPart.DownedPart
           local Event = game:GetService("ReplicatedStorage").Event
           Event:FireServer(A_1, A_2, A_3)
       end
   end)
end
	end)
end
coroutine.wrap(HKCZUDL_fake_script)()
local function NBFTUGO_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Click:Connect(function()
-- Madcity Godmode Server

local Players = game:GetService("Players")
_G.Godserver = false -- On/Off
while wait() and _G.Godserver do
   pcall(function()
       for i, all in pairs(Players:GetPlayers()) do
           local A_1 = "RevivePlayer"
           local A_2 = game:GetService("Workspace")[all.Name]
           local A_3 = game:GetService("Workspace").ObjectSelection.DownedPart.DownedPart
           local Event = game:GetService("ReplicatedStorage").Event
           Event:FireServer(A_1, A_2, A_3)
       end
   end)
end
	end)
end
coroutine.wrap(NBFTUGO_fake_script)()
local function ZRLV_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	script.Parent.MouseButton1Click:Connect(function()
	
	    
	       for _,m in pairs(game:GetService("Workspace"):GetDescendants()) do
if m.ClassName == "TextLabel" then 
if m.Text == game:GetService("Players").LocalPlayer.Name then
m:Destroy()
for j,m in pairs(game:GetService("Players").LocalPlayer:GetDescendants()) do
if m.ClassName == "TextLabel" then 
if m.Text == game:GetService("Players").LocalPlayer.Name then
m:Destroy()
for h,v in pairs(workspace[game.Players.LocalPlayer.Name].Head:GetChildren()) do
if v:IsA('BillboardGui') then
v:Remove()
end
end
end
end
end
end
end
end

while true do
    for i,s in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
    if s:IsA("") then
    s.Parent = workspace
    end
    end

    for i,f in pairs(game.Workspace[game.Players.LocalPlayer.Name].Head:GetChildren()) do
        if f:IsA("Decal") and f.Name == "face" then
            f.Parent = nil
        end
    end

    if game.Players.LocalPlayer.Character.Shirt then
    game.Players.LocalPlayer.Character.Shirt:Remove()
    else
    end
    if game.Players.LocalPlayer.Character.Pants then
    game.Players.LocalPlayer.Character.Pants:Remove()
    else
    end
    if game.Players.LocalPlayer.Character["Shirt Graphic"] then
    game.Players.LocalPlayer.Character["Shirt Graphic"]:Remove()
    else
    end
    if game.Players.LocalPlayer.Character.Torso.roblox then
    game.Players.LocalPlayer.Character.Torso.roblox:Remove()
    else
    end
end
	end)
end
coroutine.wrap(ZRLV_fake_script)()
local function BAMBFIU_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	script.Parent.MouseButton1Click:Connect(function()
	    game.ReplicatedStorage.RemoteEvents.BuyItem:FireServer("Pan", 0)
	    
	end)
end
coroutine.wrap(BAMBFIU_fake_script)()
local function DHQO_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	script.Parent.MouseButton1Click:Connect(function()
	    for i,v in pairs(game.Workspace.BadGuys:GetChildren()) do
	
	        for i = 1, 50 do
	
	            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,10)
	            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,996)
	            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,9)
	            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,996)
	
	        end
	
	        end
	end)
end
coroutine.wrap(DHQO_fake_script)()
local function FJYXQET_fake_script() -- TextButton_9.LocalScript 
	local script = Instance.new('LocalScript', TextButton_9)

	script.Parent.MouseButton1Click:Connect(function()
	if workspace:findFirstChild("CodeNote") then
	game.ReplicatedStorage.RemoteEvents.Safe:FireServer(workspace.CodeNote.SurfaceGui.TextLabel.Text)
	end
	end)
end

coroutine.wrap(FKRBDAC_fake_script)()

