getgenv().rejoin = game:GetService("CoreGui").RobloxPromptGui.promptOverlay.ChildAdded:Connect(function(child)
    if child.Name == 'ErrorPrompt' and child:FindFirstChild('MessageArea') and child.MessageArea:FindFirstChild("ErrorFrame") then
        game:GetService("TeleportService"):Teleport(game.PlaceId)
    end
end)
 
 
 
s = Instance.new("Sound",Workspace)
        s.Pitch = 1
        s.Volume = 1000
        s.SoundId = "rbxassetid://9577148759"
        s.Looped = false
        s.PlayOnRemove = false
        s:Play()
 
if game:GetService("Players").LocalPlayer.PlayerGui:FindFirstChild("Ticket") then
    game:GetService("Players").LocalPlayer.PlayerGui:FindFirstChild("Ticket"):Destroy()
    end
 
local DiscordLib =
    loadstring(game:HttpGet "https://pastebin.com/raw/pjQ6yNJK")()
 
local win = DiscordLib:Window("WSS HUB | Original ")
 
local serv = win:Server("Main", "")
 
local A = serv:Channel("Character")
 
 
local C = serv:Channel("SPLIFF")
 
 
local F = serv:Channel("Make niggas mad")
 
A:Button(
    "Fly",
    function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/WspNas/fk7/main/README.md"))()
    end
)
 
A:Button(
    "Fly Bypass (Bike Requests)",
    function()
        local plr = game:GetService("Players").LocalPlayer
        local pos = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
        local roundedPos = math.round(pos.X) .. ", " .. math.round(pos.Y) .. ", " .. math.round(pos.Z)
 
        function bypass()
          if game.Players.LocalPlayer.Character.Humanoid.Sit ~= true then
              rconsoleclear()
            rconsolewarn("Please be seated in any vehicle to inititate Bypass. \n - You can also sit in the passenger seat!")
          end
 
          if game.Players.LocalPlayer.Character.Humanoid.Sit ~= false then
            workspace[plr.Name .. "'s Car"]:MoveTo(roundedPos)
            workspace[plr.Name .. "'s Car"].DriveSeat:Sit(plr.Character.Humanoid)
         end
        end
 
        bypass()
        rconsoleclear()
        rconsolewarn("Successful! \n -If anything bugs out after you stop flying type '/respawn'")
    end
)
 
    A:Button(
    "Walk Speed Bypass",
    function()
        local plr = game.Players.LocalPlayer
            local char = plr.Character
 
            char.Humanoid.WalkSpeed = 40
    end
)
 
A:Button(
    "Skip loading Screen",
    function()
        local LP = game:GetService("Players").LocalPlayer
if LP.PlayerGui:FindFirstChild("Menu") then
LP.PlayerGui:FindFirstChild("Menu"):Destroy()
end
 
if LP.PlayerGui:FindFirstChild("Agreement") then
LP.PlayerGui:FindFirstChild("Agreement"):Destroy()
end
 
LP.PlayerGui.Stats.Enabled = true
LP.PlayerGui.twitter.Enabled = false
 
workspace.CurrentCamera.CameraType = "Custom"
local char = LP.Character or LP.CharacterAdded:Wait()
workspace.CurrentCamera.CameraSubject = char:WaitForChild("Humanoid")
end
)
 
A:Button(
    "Infinite Stamina",
    function()
     while true do 
                    wait(0)
                    game.Players.LocalPlayer.Valuestats.Stamina.Value = 100
                end   
    end
)
 
A:Button(
    "Infinite Hunger",
    function()
       while true do 
                    wait(0)
                    game.Players.LocalPlayer.Valuestats.Hunger.Value = 100
                end  
    end
)
 
A:Button(
    "Infinite Karma",
    function()
         while true do
                    wait(1)
                    game.Players.LocalPlayer.Valuestats.Karma.Value = 999999
                end
    end
)
 
A:Button(
    "Infinite Skittles",
    function()
         while wait() do
                    game:GetService("Players").LocalPlayer.PlayerGui.Run.Value.Value = true
                    game.Players.LocalPlayer.Character.Resistance.Value = true
                    game:GetService("Workspace").LocalPlayer.Resistance = true
                end
    end
)
 
A:Button(
    "Removes Karma Alert",
    function()
  while true do
                    wait(1)
                    game.ReplicatedStorage.KarmaAlert:Destroy()
            end
    end
)
 
A:Button(
    "Removes Traffic City Noises",
    function()
 while true do
                    wait(1)
                    game.SoundService["Traffic City Noises"]:Destroy()
        end
    end
)
 
A:Button(
    "Remove Damage Blood",
    function()
wait(1)
                    game.Players.LocalPlayer.PlayerGui.Dmg:Destroy()
    end
)
 
 
 
 
 
C:Button(
    "ESP",
    function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/WspNas/fwfveef/main/README.md"))()
    end
    )
 
    C:Button(
    "Chat SPY",
    function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/WspNas/defefef/main/README.md"))()
        end
    )
 
 C:Button(
    "Pick Up Tools",
    function()
        local g = game.Workspace.tools
    while task.wait() do
        for fk, fl in pairs((g:GetChildren())) do
            if fl:IsA("Tool") then
                if fl:IsA("Tool") and fl.Name == "Phone" or fl.Name == "Crate" then
                else
                    game:GetService("Players").LocalPlayer.Character.Humanoid:EquipTool(fl)
 
                end
            end
        end
    end
        end
    )
 
 C:Button(
    "Quick Buy Food",
    function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/WspNas/sasasas/main/README.md"))()  
        end
    )
 
 
 
 
 
 
 
 
    F:Button(
    "BoomBox client sided",
    function()
         _G.boomboxb = game:GetObjects('rbxassetid://740618400')[1]
                    _G.boomboxb.Parent = game:GetService'Players'.LocalPlayer.Backpack
                    loadstring(_G.boomboxb.Client.Source)() 
                    loadstring(_G.boomboxb.Server.Source)()
    end
    )
 
     F:Button(
    "No Face",
    function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/WspNas/wqqqq/main/README.md"))()
    end
    )
 
     F:Button(
    "No Head client sided",
    function()
         loadstring(game:HttpGet("https://raw.githubusercontent.com/WspNas/fdqqqqq/main/README.md"))()
    end
    )
 
     F:Button(
    "bald",
    function()
        for i,v in next, game:GetService('Players').LocalPlayer.Character:GetChildren() do
                    if v:IsA('Accessory') then
                        v:Destroy()
                    end
            end
    end
    )
 
     F:Button(
    "No Legs client sided",
    function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/WspNas/eqqqqq/main/README.md"))()  
    end
    )
 
    F:Button(
    "No Arms game will break ",
    function()
        game:GetService("Players").LocalPlayer.Character.RightUpperArm:Destroy()
           game:GetService("Players").LocalPlayer.Character.RightLowerArm:Destroy()
           game:GetService("Players").LocalPlayer.Character.LeftUpperArm:Destroy()
           game:GetService("Players").LocalPlayer.Character.LeftLowerArm:Destroy()
    end
    )
 
    F:Button(
    "No Name",
    function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/WspNas/wwdghjhgfds/main/README.md"))()
    end
    )
 
    F:Button(
    "Fire Hands client sided",
    function()
        Fire.Parent = game.Players.LocalPlayer.Character.RightHand
    Fire.Heat = 5
    Fire.Size = 2
    end
    )
 
    F:Button(
    "Kill Your Self",
    function()
       game.Players.LocalPlayer.Character.Humanoid.Health = 0 
    end
    )
 
     F:Button(
    "Join Low Server",
    function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/WspNas/fgf/main/README.md"))()
    end
    )
 
     F:Button(
    "car Loud Sound lol ",
    function()
        local args = {
            [1] = workspace:FindFirstChild(game.Players.LocalPlayer.Name .. "'s Car")
        }
 
        game:GetService("ReplicatedStorage").TireSmoke:FireServer(unpack(args))
 
        local args = {
            [1] = game.Workspace[game.Players.LocalPlayer.Name .. "'s Car"],
            [2] = 1000,
            [3] = 1000,
            [4] = false,
            [5] = 1000,
            [6] = 1000,
            [7] = 0,
            [8] = 1000,
            [9] = false
        }
 
        game:GetService("ReplicatedStorage").CarSound:FireServer(unpack(args))
    end
    )
 
     F:Button(
    "Ghost Drive A Car",
    function()
        local plr = game.Players.LocalPlayer
 
-- / function
local function SelfDrive()
    if game:GetService("Workspace")[plr.Name.."'s Car"] then
    game:GetService("Workspace")[plr.Name.."'s Car"]["A-Chassis Tune"]:Clone().Parent = game.Players.LocalPlayer.Character
    else
        rconsoleprint("Failed to find car!")
    end
end
 
SelfDrive()
    end
    )
 
     F:Button(
        "Call all",
function()
    local function callAll( )
        for i,v in pairs(Players:GetPlayers( )) do
            if v ~= LocalPlayer then
 
                local args = {
                    [1] = v,
                    [2] = "Starting"
                };        
 
                game:GetService("ReplicatedStorage").Call:FireServer(unpack(args));
 
                print("called " .. v.Name);
            end;
        end;
    end;
    callAll()
end
     )    
     
