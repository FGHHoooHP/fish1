
local requiredKeys = {
    [7144504097] = "Water-hub-656a-423f-9618-fe1672243f7e", -- ผู้เล่น ID 7144504097 ต้องกรอกคีย์นี้
    [5370483427] = "Water-hub-656e-465f-9328-fe1542243f7e"
    [2225408985] = "Water-hub-d748-4ab6-881d-6dd6989fcec4"
    
}

-- ฟังก์ชันเช็คผู้เล่นและคีย์
local playerID = game.Players.LocalPlayer.UserId -- ใช้ ID ของผู้เล่นปัจจุบัน
local player = game.Players:GetPlayerByUserId(playerID)

-- ถ้าผู้เล่นมีในรายชื่อ
if player then
    local requiredKey = requiredKeys[playerID] -- คีย์ที่ต้องกรอกตาม ID ของผู้เล่น
    if requiredKey then
        local enteredKey = getgenv().key -- คีย์ที่ผู้เล่นกรอกมา

        -- ตรวจสอบคีย์ที่ผู้เล่นกรอก
        if enteredKey == requiredKey then
            -- คีย์ถูกต้อง
-- เข้าถึงผู้เล่นในเกม
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid") -- ใช้ Humanoid ในการเช็คค่าเลือด

-- ฟังก์ชันตรวจสอบเลือด
local function checkHealth()
    if humanoid.Health == 0 then
        local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

if character:FindFirstChild("Humanoid") then
    character.Humanoid.Health = 0
end
        
local targetPosition = Vector3.new(3023, 14, 1933)
game.Players.LocalPlayer.Character:SetPrimaryPartCFrame(CFrame.new(targetPosition))
wait(0.2)
local args = {
    [1] = "fire",
    [3] = "Supermarket",
    [4] = "Bait",
    [5] = 150
}

game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
if not character:FindFirstChild("Fishingrod") then

    local args = {
        [1] = "fire",
        [2] = "ToolName",  -- Add the name of the tool you're using (if needed)
        [3] = "Use Tool",
        [4] = "Fishingrod"
    }

    game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
end

wait(0.1)
local targetPosition1 = Vector3.new(3325, 7, 1854)
game.Players.LocalPlayer.Character:SetPrimaryPartCFrame(CFrame.new(targetPosition1))
wait(0.1)
local VU = game:GetService("VirtualUser")
    VU:CaptureController()     VU:ClickButton1(Vector2.new()) 
    wait(0.1)
local player = game.Players.LocalPlayer

spawn(function()
    while wait(10) do  -- Wait 1 second before checking again
        pcall(function()
            if player then
                local inventory = player:FindFirstChild("Inventory")
                if inventory and inventory:GetAttribute("Bait") == 0 then
                    -- วาร์ปผู้เล่นไปยังตำแหน่งที่กำหนด
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

if character:FindFirstChild("Humanoid") then
    character.Humanoid.Health = 0
end
wait(3)
local targetPosition2 = Vector3.new(2846, 14, 2079)
game.Players.LocalPlayer.Character:SetPrimaryPartCFrame(CFrame.new(targetPosition2))
wait(1)
for i = 1, 150 do
  local args = {
        [1] = "fire",
        [3] = "Economy",
        [4] = "Fish",
        [5] = 1
    }

    game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
    local args = {
        [1] = "fire",
        [3] = "Economy",
        [4] = "Shrimp",
        [5] = 1
    }

    game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
    local args = {
    [1] = "fire",
    [3] = "Economy",
    [4] = "Squid",
    [5] = 1
}

game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
local args = {
    [1] = "fire",
    [3] = "Economy",
    [4] = "Stingray",
    [5] = 1
}

game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
local args = {
    [1] = "fire",
    [3] = "Economy",
    [4] = "Crab",
    [5] = 1
}

game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
local args = {
    [1] = "fire",
    [3] = "Economy",
    [4] = "Dolphin",
    [5] = 1
}

game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
local args = {
    [1] = "fire",
    [3] = "Economy",
    [4] = "Shark",
    [5] = 1
}

game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))

end
wait(0.2)
local targetPosition2 = Vector3.new(3023, 14, 1933)
game.Players.LocalPlayer.Character:SetPrimaryPartCFrame(CFrame.new(targetPosition2))
wait(0.2)
local args = {
    [1] = "fire",
    [3] = "Supermarket",
    [4] = "Bait",
    [5] = 150
}

game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
wait(0.2)
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
if not character:FindFirstChild("Fishingrod") then

    local args = {
        [1] = "fire",
        [2] = "ToolName",  -- Add the name of the tool you're using (if needed)
        [3] = "Use Tool",
        [4] = "Fishingrod"
    }

    game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
end
wait(0.2)
local targetPosition1 = Vector3.new(3327, 7, 1864)
game.Players.LocalPlayer.Character:SetPrimaryPartCFrame(CFrame.new(targetPosition1))
wait(0.1)
local VU = game:GetService("VirtualUser")
    VU:CaptureController()     VU:ClickButton1(Vector2.new()) 

                  return  -- Exit the loop by returning from the function
                end
            end
        end)
    end
end) -- แสดงข้อความใน Output
    end
end

-- Loop เช็คค่า Health ทุก 5 วินาที
while true do
    checkHealth() -- เรียกฟังก์ชันตรวจสอบเลือด
    wait(5) -- รอ 5 วินาที
end

            -- ดำเนินการเพิ่มเติม (แสดง UI, เปิดฟีเจอร์ ฯลฯ)
        else
            -- คีย์ไม่ถูกต้อง
            player:Kick("Invalid key!") -- เตะผู้เล่นออกจากเกม
        end
    else
        -- ถ้าผู้เล่นไม่มีคีย์ที่กำหนดไว้
        print("No key requirement for this player.")
    end
else
    -- ถ้าผู้เล่นไม่พบในเกม
    print("Player not found.")
end
