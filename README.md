 -- Farewell Infortality.

-- Version: 2.82

-- Instances:

local Theexploit = Instance.new("ScreenGui")

local GUIopenframe = Instance.new("Frame")

local GuiOpen = Instance.new("TextButton")

local GUImain = Instance.new("Frame")

local HatSpam = Instance.new("TextButton")

local flingkill = Instance.new("TextButton")

local Admin = Instance.new("TextButton")

local fly = Instance.new("TextButton")

local AnimationGui = Instance.new("TextButton")

local Brickspam = Instance.new("TextButton")

local ExitGUI = Instance.new("TextButton")

local credits = Instance.new("TextLabel")

local Title = Instance.new("TextLabel")

local page2 = Instance.new("TextButton")

local GUImain2 = Instance.new("Frame")

local title2 = Instance.new("TextLabel")

local btools = Instance.new("TextButton")

local unlockWS = Instance.new("TextButton")

local lowgravity = Instance.new("TextButton")

local comingsoon = Instance.new("TextLabel")

local ExitGUI2 = Instance.new("TextButton")

--Properties:

Theexploit.Name = "The exploit"

Theexploit.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

GUIopenframe.Name = "GUI open frame"

GUIopenframe.Parent = Theexploit

GUIopenframe.BackgroundColor3 = Color3.new(0.0313726, 0, 1)

GUIopenframe.Position = UDim2.new(0.0304878056, 0, 0.880596995, 0)

GUIopenframe.Size = UDim2.new(0, 130, 0, 22)

GuiOpen.Name = "Gui Open"

GuiOpen.Parent = GUIopenframe

GuiOpen.BackgroundColor3 = Color3.new(0.992157, 0.152941, 0.00392157)

GuiOpen.BorderColor3 = Color3.new(0.0509804, 0, 0)

GuiOpen.Size = UDim2.new(0, 138, 0, 21)

GuiOpen.Font = Enum.Font.SciFi

GuiOpen.Text = "Open Gui"

GuiOpen.TextColor3 = Color3.new(0, 0, 0)

GuiOpen.TextSize = 14

GuiOpen.MouseButton1Down:connect(function()

GUImain.Visible = true

GUIopenframe.Visible = false

end)

GUImain.Name = "GUI main"

GUImain.Parent = Theexploit

GUImain.BackgroundColor3 = Color3.new(0, 0, 1)

GUImain.Position = UDim2.new(0.283536583, 0, 0.215351805, 0)

GUImain.Size = UDim2.new(0, 222, 0, 277)

GUImain.Visible = false

HatSpam.Name = "HatSpam"

HatSpam.Parent = GUImain

HatSpam.BackgroundColor3 = Color3.new(1, 0, 0)

HatSpam.Position = UDim2.new(0, 11, 0, 51)

HatSpam.Size = UDim2.new(0, 200, 0, 23)

HatSpam.Font = Enum.Font.SourceSans

HatSpam.Text = "Hat Spam (Life in Paridise)"

HatSpam.TextColor3 = Color3.new(0, 0, 0)

HatSpam.TextSize = 14

HatSpam.MouseButton1Down:connect(function()

for i=1,500 do

local A_1 = 

{

[1] = "Wear", 

[2] = "100427922", 

[3] = "Hats"

}

local Event = game:GetService("ReplicatedStorage").WearItem

Event:FireServer(A_1)

wait(0.1)

for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do

if v:IsA("Hat") or v:IsA("Accessory") then

v.Parent = game:GetService("Workspace")

end

end

end

end)

flingkill.Name = "flingkill"

flingkill.Parent = GUImain

flingkill.BackgroundColor3 = Color3.new(1, 0, 0)

flingkill.Position = UDim2.new(0, 11, 0, 89)

flingkill.Size = UDim2.new(0, 200, 0, 23)

flingkill.Font = Enum.Font.SourceSans

flingkill.Text = "FE fling/kill"

flingkill.TextColor3 = Color3.new(0, 0, 0)

flingkill.TextSize = 14

flingkill.MouseButton1Down:connect(function()

 -- Made By NubDeveloper

local FlingKill = Instance.new("ScreenGui")

local Main = Instance.new("Frame")

local Label = Instance.new("Frame")

local Shadow = Instance.new("Frame")

local StartKill = Instance.new("TextButton")

local StopKill = Instance.new("TextButton")

local Instructions = Instance.new("TextLabel")

local CurrentPower = Instance.new("TextLabel")

local Recomendation = Instance.new("TextLabel")

local NameOfGui = Instance.new("TextLabel")

local Exit = Instance.new("TextButton")

local UPArrow = Instance.new("TextButton")

local DownArrow = Instance.new("TextButton")

-- Properties

FlingKill.Name = "Fling/Kill"

FlingKill.Parent = game.CoreGui

Main.Name = "Main"

Main.Parent = FlingKill

Main.BackgroundColor3 = Color3.new(0.92549, 0.941177, 0.945098)

Main.BorderSizePixel = 0

Main.Position = UDim2.new(0.702554762, 0, 0.446640313, 0)

Main.Size = UDim2.new(0, 217, 0, 233)

Main.Selectable = true

Main.Active = true

Main.Draggable = true

Label.Name = "Label"

Label.Parent = Main

Label.BackgroundColor3 = Color3.new(0.741176, 0.764706, 0.780392)

Label.BorderSizePixel = 0

Label.Size = UDim2.new(0, 217, 0, 27)

Shadow.Name = "Shadow"

Shadow.Parent = Main

Shadow.BackgroundColor3 = Color3.new(0.67451, 0.694118, 0.705882)

Shadow.BorderSizePixel = 0

Shadow.Position = UDim2.new(0, 0, 0.115879826, 0)

Shadow.Size = UDim2.new(0, 217, 0, 9)

StartKill.Name = "StartKill"

StartKill.Parent = Main

StartKill.BackgroundColor3 = Color3.new(0.741176, 0.764706, 0.780392)

StartKill.BorderSizePixel = 0

StartKill.Position = UDim2.new(0.195852548, 0, 0.227467805, 0)

StartKill.Size = UDim2.new(0, 126, 0, 23)

StartKill.Font = Enum.Font.Cartoon

StartKill.Text = "FE Kill/Fling"

StartKill.TextColor3 = Color3.new(0, 0, 0)

StartKill.TextSize = 14

StopKill.Name = "StopKill"

StopKill.Parent = Main

StopKill.BackgroundColor3 = Color3.new(0.741176, 0.764706, 0.780392)

StopKill.BorderSizePixel = 0

StopKill.Position = UDim2.new(0.207373276, 0, 0.38197428, 0)

StopKill.Size = UDim2.new(0, 124, 0, 23)

StopKill.Font = Enum.Font.Cartoon

StopKill.Text = "Stop FE Kill/Fling"

StopKill.TextColor3 = Color3.new(0, 0, 0)

StopKill.TextSize = 14

Instructions.Name = "Instructions"

Instructions.Parent = Main

Instructions.BackgroundColor3 = Color3.new(1, 1, 1)

Instructions.BackgroundTransparency = 1

Instructions.Position = UDim2.new(0.0391705073, 0, 0.549356222, 0)

Instructions.Size = UDim2.new(0, 200, 0, 32)

Instructions.Font = Enum.Font.Cartoon

Instructions.Text = "Just touch someone to watch the fly to their death!"

Instructions.TextColor3 = Color3.new(0, 0, 0)

Instructions.TextSize = 14

Instructions.TextWrapped = true

CurrentPower.Name = "CurrentPower"

CurrentPower.Parent = Main

CurrentPower.BackgroundColor3 = Color3.new(1, 1, 1)

CurrentPower.BackgroundTransparency = 1

CurrentPower.Position = UDim2.new(0.276497692, 0, 0.686695278, 0)

CurrentPower.Size = UDim2.new(0, 98, 0, 36)

CurrentPower.Font = Enum.Font.Cartoon

CurrentPower.Text = "Current Power = 5"

CurrentPower.TextColor3 = Color3.new(0, 0, 0)

CurrentPower.TextSize = 14

Recomendation.Name = "Recomendation"

Recomendation.Parent = Main

Recomendation.BackgroundColor3 = Color3.new(1, 1, 1)

Recomendation.BackgroundTransparency = 1

Recomendation.Position = UDim2.new(0.0414746553, 0, 0.884120166, 0)

Recomendation.Size = UDim2.new(0, 200, 0, 21)

Recomendation.Font = Enum.Font.Cartoon

Recomendation.Text = "Recommended Power is 5"

Recomendation.TextColor3 = Color3.new(0, 0, 0)

Recomendation.TextSize = 14

NameOfGui.Name = "NameOfGui"

NameOfGui.Parent = Main

NameOfGui.BackgroundColor3 = Color3.new(1, 1, 1)

NameOfGui.BackgroundTransparency = 1

NameOfGui.Position = UDim2.new(0.0806451589, 0, 0, 0)

NameOfGui.Size = UDim2.new(0, 154, 0, 27)

NameOfGui.Font = Enum.Font.Cartoon

NameOfGui.Text = "FE Kill/Fling By NubDeveloper"

NameOfGui.TextColor3 = Color3.new(0, 0, 0)

NameOfGui.TextSize = 14

Exit.Name = "Exit"

Exit.Parent = Main

Exit.BackgroundColor3 = Color3.new(1, 1, 1)

Exit.BackgroundTransparency = 1

Exit.Position = UDim2.new(0.907834113, 0, 0, 0)

Exit.Size = UDim2.new(0, 20, 0, 27)

Exit.Font = Enum.Font.Cartoon

Exit.Text = "X"

Exit.TextColor3 = Color3.new(0, 0, 0)

Exit.TextSize = 14

UPArrow.Name = "UPArrow"

UPArrow.Parent = Main

UPArrow.BackgroundColor3 = Color3.new(1, 1, 1)

UPArrow.BackgroundTransparency = 1

UPArrow.Position = UDim2.new(0.0783410147, 0, 0.716738224, 0)

UPArrow.Size = UDim2.new(0, 26, 0, 23)

UPArrow.Font = Enum.Font.Cartoon

UPArrow.Text = "Up"

UPArrow.TextColor3 = Color3.new(0, 0, 0)

UPArrow.TextSize = 12

UPArrow.TextWrapped = true

DownArrow.Name = "DownArrow"

DownArrow.Parent = Main

DownArrow.BackgroundColor3 = Color3.new(1, 1, 1)

DownArrow.BackgroundTransparency = 1

DownArrow.Position = UDim2.new(0.792626739, 0, 0.714592278, 0)

DownArrow.Size = UDim2.new(0, 26, 0, 23)

DownArrow.Font = Enum.Font.Cartoon

DownArrow.Text = "Down"

DownArrow.TextColor3 = Color3.new(0, 0, 0)

DownArrow.TextSize = 12

DownArrow.TextWrapped = true

power = 500

active = false

local val = Instance.new("IntValue")

val.Name = "Number"

val.Parent = game.Players.LocalPlayer

val.Value = 5

Exit.MouseButton1Click:connect(function()

FlingKill.Enabled = false

end)

StartKill.MouseButton1Click:connect(function()

game:GetService('RunService').Stepped:connect(function()

if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R6 then

game.Players.LocalPlayer.Character.Head.CanCollide = false

game.Players.LocalPlayer.Character.Torso.CanCollide = false

game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false

game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false

else

if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R15 then

game.Players.LocalPlayer.Character.Head.CanCollide = false

game.Players.LocalPlayer.Character.UpperTorso.CanCollide = false

game.Players.LocalPlayer.Character.LowerTorso.CanCollide = false

game.Players.LocalPlayer.Character.HumanoidRootPart.CanCollide = false

end

end

end)

wait(.1)

local bambam = Instance.new("BodyThrust")

bambam.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart

bambam.Force = Vector3.new(power,0,power)

bambam.Location = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

end)

StopKill.MouseButton1Click:connect(function()

active = false

game.Players.LocalPlayer.Character.HumanoidRootPart.BodyThrust:Remove()

end)

UPArrow.MouseButton1Click:connect(function()

power = power + 100

game.Players.LocalPlayer.Number.Value = game.Players.LocalPlayer.Number.Value + 1

CurrentPower.Text = "Current Power = " .. game.Players.LocalPlayer.Number.Value

end)

DownArrow.MouseButton1Click:connect(function()

power = power - 100

game.Players.LocalPlayer.Number.Value = game.Players.LocalPlayer.Number.Value - 1

CurrentPower.Text = "Current Power = " .. game.Players.LocalPlayer.Number.Value

end)

end)

Admin.Name = "Admin"

Admin.Parent = GUImain

Admin.BackgroundColor3 = Color3.new(1, 0, 0)

Admin.Position = UDim2.new(0, 11, 0, 156)

Admin.Size = UDim2.new(0, 200, 0, 23)

Admin.Font = Enum.Font.SourceSans

Admin.Text = "FE Reviz Admin V2"

Admin.TextColor3 = Color3.new(0, 0, 0)

Admin.TextSize = 14

Admin.MouseButton1Down:connect(function()

loadstring(game:HttpGet("https://pastebin.com/raw/KNUzQPYS"))()

end)

fly.Name = "fly"

fly.Parent = GUImain

fly.BackgroundColor3 = Color3.new(1, 0, 0)

fly.Position = UDim2.new(0, 11, 0, 122)

fly.Size = UDim2.new(0, 200, 0, 23)

fly.Font = Enum.Font.SourceSans

fly.Text = "FE Toggle Fly (E)"

fly.TextColor3 = Color3.new(0, 0, 0)

fly.TextSize = 14

fly.MouseButton1Down:connect(function()

repeat wait()

   until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")

local mouse = game.Players.LocalPlayer:GetMouse()

repeat wait() until mouse

local plr = game.Players.LocalPlayer

local torso = plr.Character.Torso

local flying = true

local deb = true

local ctrl = {f = 0, b = 0, l = 0, r = 0}

local lastctrl = {f = 0, b = 0, l = 0, r = 0}

local maxspeed = 50

local speed = 0

function Fly()

local bg = Instance.new("BodyGyro", torso)

bg.P = 9e4

bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)

bg.cframe = torso.CFrame

local bv = Instance.new("BodyVelocity", torso)

bv.velocity = Vector3.new(0,0.1,0)

bv.maxForce = Vector3.new(9e9, 9e9, 9e9)

repeat wait()

plr.Character.Humanoid.PlatformStand = true

if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then

speed = speed+.5+(speed/maxspeed)

if speed > maxspeed then

speed = maxspeed

end

elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then

speed = speed-1

if speed < 0 then

speed = 0

end

end

if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then

bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed

lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}

elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then

bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed

else

bv.velocity = Vector3.new(0,0.1,0)

end

bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)

until not flying

ctrl = {f = 0, b = 0, l = 0, r = 0}

lastctrl = {f = 0, b = 0, l = 0, r = 0}

speed = 0

bg:Destroy()

bv:Destroy()

plr.Character.Humanoid.PlatformStand = false

end

mouse.KeyDown:connect(function(key)

if key:lower() == "e" then

if flying then flying = false

else

flying = true

Fly()

end

elseif key:lower() == "w" then

ctrl.f = 1

elseif key:lower() == "s" then

ctrl.b = -1

elseif key:lower() == "a" then

ctrl.l = -1

elseif key:lower() == "d" then

ctrl.r = 1

end

end)

mouse.KeyUp:connect(function(key)

if key:lower() == "w" then

ctrl.f = 0

elseif key:lower() == "s" then

ctrl.b = 0

elseif key:lower() == "a" then

ctrl.l = 0

elseif key:lower() == "d" then

ctrl.r = 0

end

end)

Fly()

end)

AnimationGui.Name = "AnimationGui"

AnimationGui.Parent = GUImain

AnimationGui.BackgroundColor3 = Color3.new(1, 0, 0)

AnimationGui.Position = UDim2.new(0, 11, 0, 221)

AnimationGui.Size = UDim2.new(0, 200, 0, 23)

AnimationGui.Font = Enum.Font.SourceSans

AnimationGui.Text = "FE Animation Gui"

AnimationGui.TextColor3 = Color3.new(0, 0, 0)

AnimationGui.TextSize = 14

AnimationGui.MouseButton1Down:connect(function()

--FE Animation Gui Made by Dark Magic Rblx in ROBLOX Studio, please give credits if you use this.

--You can use all and me in the Name Here Section!

gui = Instance.new("ScreenGui",game.CoreGui)

gui.Name = "FE Animation Gui by Dark Magic Rblx"

box = Instance.new("Frame",gui)

box.Size = UDim2.new(0,400,0,100)

box.Position = UDim2.new(0,800,0,500)

box.BackgroundTransparency = 0

box.BackgroundColor3 = Color3.new(167,0,0)

box.BorderSizePixel = 5

box.BorderColor3 = Color3.new(27,42,53)

o = Instance.new("TextBox",gui)

o.Name = "Speed Here"

o.Size = UDim2.new(0,150,0,15)

o.Position = UDim2.new(0,1000,0,590)

o.BackgroundTransparency = 0

o.BackgroundColor3 = Color3.new(0,0,0)

o.BorderSizePixel = 0

o.Font = "Arcade"

o.TextColor3 = Color3.new(255,255,255)

o.TextScaled = true

o.TextWrapped = true

o.Text = "Speed Here"

a = Instance.new("TextBox",gui)

a.Name = "ID Here"

a.Size = UDim2.new(0,300,0,25)

a.Position = UDim2.new(0,900,0,530)

a.BackgroundTransparency = 0

a.BackgroundColor3 = Color3.new(0,0,0)

a.BorderSizePixel = 0

a.Font = "Arcade"

a.TextColor3 = Color3.new(255,255,255)

a.TextScaled = true

a.TextWrapped = true

a.Text = "ID Here"

b = Instance.new("TextBox",gui)

b.Name = "Namehere"

b.Size = UDim2.new(0,300,0,25)

b.Position = UDim2.new(0,900,0,560)

b.BackgroundTransparency = 0

b.BackgroundColor3 = Color3.new(0,0,0)

b.BorderSizePixel = 0

b.Font = "Arcade"

b.TextColor3 = Color3.new(255,255,255)

b.TextScaled = true

b.TextWrapped = true

b.Text = "Name here"

c = Instance.new("TextButton",gui)

c.Name = "Animation"

c.Size = UDim2.new(0,100,0,40)

c.Position = UDim2.new(0,800,0,520)

c.BackgroundTransparency = 0

c.BackgroundColor3 = Color3.new(0,0,0)

c.BorderSizePixel = 0

c.Font = "Arcade"

c.TextColor3 = Color3.new(255,255,255)

c.TextScaled = true

c.TextWrapped = true

c.Text = "Animation"

d = Instance.new("TextButton",gui)

d.Name = "Player"

d.Size = UDim2.new(0,100,0,40)

d.Position = UDim2.new(0,800,0,560)

d.BackgroundTransparency = 0

d.BackgroundColor3 = Color3.new(0,0,0)

d.BorderSizePixel = 0

d.Font = "Arcade"

d.TextColor3 = Color3.new(255,255,255)

d.TextScaled = true

d.TextWrapped = true

d.Text = "Player"

cred = Instance.new("TextLabel",gui)

cred.Name = "Credits"

cred.Size = UDim2.new(0,400,0,20)

cred.Position = UDim2.new(0,800,0,500)

cred.BackgroundTransparency = 0

cred.BackgroundColor3 = Color3.new(0,0,0)

box.BorderSizePixel = 5

box.BorderColor3 = Color3.new(27,42,53)

cred.Font = "Arcade"

cred.FontSize = "Size24"

cred.TextColor3 = Color3.new(255,255,255)

cred.Text = "FE Animation Gui by Dark Magic Rblx!"

cred.TextSize = 19

c.MouseButton1Down:connect(function()

local AnimationId = gui["ID Here"].Text

local Anim = Instance.new("Animation")

Anim.AnimationId = "rbxassetid://"..AnimationId

local Player = game.Players:FindFirstChild(gui.Namehere.Text)

if Player ~= nil then

local k = Player.Character.Humanoid:LoadAnimation(Anim)

k:Play()  

k:AdjustSpeed(gui["Speed Here"].Text)

end 

if gui.Namehere.Text =="me" then

local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)

k:Play()  

k:AdjustSpeed(gui["Speed Here"].Text)	

end

if gui.Namehere.Text =="all" then

for i,v in pairs(game.Players:GetChildren()) do

local k = v.Character.Humanoid:LoadAnimation(Anim)

k:Play()  

k:AdjustSpeed(gui["Speed Here"].Text)	

end

end

end)

   

d.MouseButton1Down:connect(function()

local AnimationId = gui["ID Here"].Text

local Anim = Instance.new("Animation")

Anim.AnimationId = "rbxassetid://"..AnimationId

local Player = game.Players:FindFirstChild(gui.Namehere.Text)

if Player ~= nil then

local k = Player.Character.Humanoid:LoadAnimation(Anim)

k:Play()  

k:AdjustSpeed(gui["Speed Here"].Text)

end 

if gui.Namehere.Text =="me" then

local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)

k:Play()  

k:AdjustSpeed(gui["Speed Here"].Text)	

end

if gui.Namehere.Text =="all" then

for i,v in pairs(game.Players:GetChildren()) do

local k = v.Character.Humanoid:LoadAnimation(Anim)

k:Play()  

k:AdjustSpeed(gui["Speed Here"].Text)	

end

end

end)

end)

Brickspam.Name = "Brickspam"

Brickspam.Parent = GUImain

Brickspam.BackgroundColor3 = Color3.new(1, 0, 0)

Brickspam.Position = UDim2.new(0, 11, 0, 189)

Brickspam.Size = UDim2.new(0, 200, 0, 23)

Brickspam.Font = Enum.Font.SourceSans

Brickspam.Text = "FE Brick Spam"

Brickspam.TextColor3 = Color3.new(0, 0, 0)

Brickspam.TextSize = 14

Brickspam.MouseButton1Down:connect(function()

for i=1,500 do

local A_1 = 

{

[1] = "Wear", 

[2] = "100427922", 

[3] = "Hats"

}

local Event = game:GetService("ReplicatedStorage").WearItem

Event:FireServer(A_1)

wait(0.1)

for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetDescendants()) do

if v:IsA("Hat") or v:IsA("Accessory") then

v.Handle.Mesh:Destroy()

v.Parent = game:GetService("Workspace")

end

end

end

end)

Title.Name = "Title"

Title.Parent = GUImain

Title.BackgroundColor3 = Color3.new(0, 1, 0.498039)

Title.BorderColor3 = Color3.new(0, 0, 0)

Title.Size = UDim2.new(0, 222, 0, 29)

Title.Font = Enum.Font.SourceSans

Title.Text = "FE Destroyer v2.0"

Title.TextColor3 = Color3.new(0, 0, 0)

Title.TextSize = 18

Title.TextWrapped = true

credits.Name = "credits"

credits.Parent = GUImain

credits.BackgroundColor3 = Color3.new(0, 0, 1)

credits.BorderColor3 = Color3.new(0, 0, 1)

credits.Position = UDim2.new(0, 0, 0.902527094, 0)

credits.Size = UDim2.new(0, 200, 0, 27)

credits.Font = Enum.Font.SourceSans

credits.Text = "GUI created by JamiePro248#5569"

credits.TextColor3 = Color3.new(1, 0, 0)

credits.TextSize = 14

ExitGUI.Name = "ExitGUI"

ExitGUI.Parent = GUImain

ExitGUI.BackgroundColor3 = Color3.new(1, 0, 0)

ExitGUI.Position = UDim2.new(0, 201, 0, 0)

ExitGUI.Size = UDim2.new(0, 21, 0, 19)

ExitGUI.Font = Enum.Font.SourceSans

ExitGUI.Text = "X"

ExitGUI.TextColor3 = Color3.new(0, 0, 0)

ExitGUI.TextSize = 14

ExitGUI.MouseButton1Down:connect(function()

GUImain.Visible = false

GUIopenframe.Visible = true

end)

page2.Name = "page2"

page2.Parent = GUImain

page2.BackgroundColor3 = Color3.new(1, 0, 0)

page2.Position = UDim2.new(0.851351202, 0, 0.902527094, 0)

page2.Size = UDim2.new(0, 33, 0, 27)

page2.Font = Enum.Font.SourceSans

page2.Text = "->"

page2.TextColor3 = Color3.new(0, 0, 0)

page2.TextScaled = true

page2.TextSize = 14

page2.TextWrapped = true

page2.MouseButton1Down:connect(function()

GUImain2.Visible = true

page2.Visible = false

end)

GUImain2.Name = "GUImain2"

GUImain2.Parent = Theexploit

GUImain2.BackgroundColor3 = Color3.new(0, 0, 1)

GUImain2.Position = UDim2.new(0.512345672, 0, 0.214285716, 0)

GUImain2.Size = UDim2.new(0, 232, 0, 277)

GUImain2.Visible = false

title2.Name = "title2"

title2.Parent = GUImain2

title2.BackgroundColor3 = Color3.new(0, 1, 0.498039)

title2.Size = UDim2.new(0, 232, 0, 29)

title2.Font = Enum.Font.SourceSans

title2.Text = "FE Destroyer Page 2"

title2.TextColor3 = Color3.new(0, 0, 0)

title2.TextSize = 18

title2.TextWrapped = true

btools.Name = "btools"

btools.Parent = GUImain2

btools.BackgroundColor3 = Color3.new(1, 0, 0)

btools.Position = UDim2.new(0.0474137925, 0, 0.184115529, 0)

btools.Size = UDim2.new(0, 209, 0, 23)

btools.Font = Enum.Font.SourceSans

btools.Text = "Btools (Local)"

btools.TextColor3 = Color3.new(0, 0, 0)

btools.TextSize = 14

btools.MouseButton1Down:connect(function()

a = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)

a.BinType = 2

b = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)

b.BinType = 3

c = Instance.new("HopperBin", game.Players.LocalPlayer.Backpack)

c.BinType = 4

end)

unlockWS.Name = "unlockWS"

unlockWS.Parent = GUImain2

unlockWS.BackgroundColor3 = Color3.new(1, 0, 0)

unlockWS.Position = UDim2.new(0.0474137925, 0, 0.321299642, 0)

unlockWS.Size = UDim2.new(0, 209, 0, 23)

unlockWS.Font = Enum.Font.SourceSans

unlockWS.Text = "Unlock WS (local)"

unlockWS.TextColor3 = Color3.new(0, 0, 0)

unlockWS.TextSize = 14

unlockWS.MouseButton1Down:connect(function()

function unlock(obj)

for i,v in pairs(obj:GetChildren()) do

if v:IsA("BasePart") then

v.Locked = false

end

unlock(v)

end

end

unlock(workspace)

end)

lowgravity.Name = " lowgravity"

lowgravity.Parent = GUImain2

lowgravity.BackgroundColor3 = Color3.new(1, 0, 0)

lowgravity.Position = UDim2.new(0.0474137925, 0, 0.458483756, 0)

lowgravity.Size = UDim2.new(0, 209, 0, 23)

lowgravity.Font = Enum.Font.SourceSans

lowgravity.Text = "Low gravity (local)"

lowgravity.TextColor3 = Color3.new(0, 0, 0)

lowgravity.TextSize = 14

lowgravity.MouseButton1Down:connect(function()

game.Workspace.Gravity = 20

end)

comingsoon.Name = "comingsoon"

comingsoon.Parent = GUImain2

comingsoon.BackgroundColor3 = Color3.new(0, 0, 1)

comingsoon.BorderColor3 = Color3.new(0, 0, 1)

comingsoon.Position = UDim2.new(0.0474137925, 0, 0.584837556, 0)

comingsoon.Size = UDim2.new(0, 209, 0, 99)

comingsoon.Font = Enum.Font.SourceSans

comingsoon.Text = "MORE COMING SOON..."

comingsoon.TextColor3 = Color3.new(1, 0, 0)

comingsoon.TextScaled = true

comingsoon.TextSize = 14

comingsoon.TextWrapped = true

ExitGUI2.Name = "ExitGUI2"

ExitGUI2.Parent = GUImain2

ExitGUI2.BackgroundColor3 = Color3.new(1, 0, 0)

ExitGUI2.Position = UDim2.new(0, 210, 0, 4)

ExitGUI2.Size = UDim2.new(0, 21, 0, 19)

ExitGUI2.Font = Enum.Font.SourceSans

ExitGUI2.Text = "X"

ExitGUI2.TextColor3 = Color3.new(0, 0, 0)

ExitGUI2.TextSize = 14

ExitGUI2.MouseButton1Down:connect(function()

GUImain2.Visible = false

page2.Visible = true

end)

-- Scripts:
