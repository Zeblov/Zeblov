local players = game:GetService("Players")
local plr = players.LocalPlayer
local tween = game:GetService("TweenService")
game.Workspace.Gravity = 0.5 -- reduces glitchiness
function main()
    local humroot = plr.Character:WaitForChild("HumanoidRootPart")
    local startTween = tween:Create(humroot, TweenInfo.new(0, Enum.EasingStyle.Linear, Enum.EasingDirection.Out, 0, false, 0), {CFrame = CFrame.new(-51.3946900, 67.3164978, 814.888123, -0.999501824, -0.00451373775, 0.0312365349, -8.62000427e-09, 0.989720345, 0.14301616, -0.0315609723, 0.142944917, -0.989227295)})
    startTween:Play()
    startTween.Completed:Wait()
    local mainTween = tween:Create(humroot, TweenInfo.new(22, Enum.EasingStyle.Linear, Enum.EasingDirection.Out, 0, false, 0), {CFrame = CFrame.new(-77.0485153, 82.6013031, 8625.86719, -0.995574772, 0.022579968, -0.0912195817, -4.97565011e-09, 0.970703065, 0.240282282, 0.0939726979, 0.23921898, -0.966407478)})
    mainTween:Play()
    mainTween.Completed:Wait()
    local endTween = tween:Create(humroot, TweenInfo.new(0, Enum.EasingStyle.Linear, Enum.EasingDirection.Out, 0, false, 0), {CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.GoldenChest.Trigger.CFrame})
    endTween:Play()
game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
    wait(0.60)
game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false

end
main()
plr.CharacterAdded:Connect(function(char)
    char:WaitForChild("HumanoidRootPart")
    main()
end)
ลองทดสอบสคริปต์ใหม่ๆ ดูไหม?


สคริปต์ Zombie Attack – (ฟาร์มอัตโนมัติ)
20.07.2024

สคริปต์ Sharkbite 2 – (ฟาร์มอัตโนมัติ)
20.07.2024

สคริปต์ยิมลีก – (Auto Train)
20.07.2024

สคริปต์ Break In 2 – (รับไอเทม)
20.07.2024

สคริปต์ Wordie – (ชนะอัตโนมัติ)
20.07.2024

ค้นหาสคริปต์ Auras – (รับ Auras)
20.07.2024

ลิขสิทธิ์ © 2024 ผู้เขียนสคริปต์ ROBLOX
เมนู

ข้อกำหนดและเงื่อนไข
นโยบายความเป็นส่วนตัว
การปฏิเสธความรับผิดชอบ
ติดต่อ
local players = game:GetService("Players")
local plr = players.LocalPlayer
local tween = game:GetService("TweenService")
game.Workspace.Gravity = 0.5 -- reduces glitchiness
function main()
    local humroot = plr.Character:WaitForChild("HumanoidRootPart")
    local startTween = tween:Create(humroot, TweenInfo.new(0, Enum.EasingStyle.Linear, Enum.EasingDirection.Out, 0, false, 0), {CFrame = CFrame.new(-51.3946900, 67.3164978, 814.888123, -0.999501824, -0.00451373775, 0.0312365349, -8.62000427e-09, 0.989720345, 0.14301616, -0.0315609723, 0.142944917, -0.989227295)})
    startTween:Play()
    startTween.Completed:Wait()
    local mainTween = tween:Create(humroot, TweenInfo.new(22, Enum.EasingStyle.Linear, Enum.EasingDirection.Out, 0, false, 0), {CFrame = CFrame.new(-77.0485153, 82.6013031, 8625.86719, -0.995574772, 0.022579968, -0.0912195817, -4.97565011e-09, 0.970703065, 0.240282282, 0.0939726979, 0.23921898, -0.966407478)})
    mainTween:Play()
    mainTween.Completed:Wait()
    local endTween = tween:Create(humroot, TweenInfo.new(0, Enum.EasingStyle.Linear, Enum.EasingDirection.Out, 0, false, 0), {CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.GoldenChest.Trigger.CFrame})
    endTween:Play()
game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
    wait(0.60)
game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false

end
main()
plr.CharacterAdded:Connect(function(char)
    char:WaitForChild("HumanoidRootPart")
    main()
end)
ลองทดสอบสคริปต์ใหม่ๆ ดูไหม?


สคริปต์ Zombie Attack – (ฟาร์มอัตโนมัติ)
20.07.2024

สคริปต์ Sharkbite 2 – (ฟาร์มอัตโนมัติ)
20.07.2024

สคริปต์ยิมลีก – (Auto Train)
20.07.2024

สคริปต์ Break In 2 – (รับไอเทม)
20.07.2024

สคริปต์ Wordie – (ชนะอัตโนมัติ)
20.07.2024

ค้นหาสคริปต์ Auras – (รับ Auras)
20.07.2024

ลิขสิทธิ์ © 2024 ผู้เขียนสคริปต์ ROBLOX
เมนู

ข้อกำหนดและเงื่อนไข
นโยบายความเป็นส่วนตัว
การปฏิเสธความรับผิดชอบ
ติดต่อ

