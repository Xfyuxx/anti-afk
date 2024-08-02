-- Optimized Anti-AFK Script
local Players = game:GetService("Players")
local player = Players.LocalPlayer
local VirtualUser = game:GetService("VirtualUser")

-- Trigger small actions to prevent AFK
player.Idled:connect(function()
VirtualUser:CaptureController()
VirtualUser:ClickButton2(Vector2.new()) -- Simulate right mouse click
end)

print("Optimized Anti-AFK Script is active")

-- Loop buat trigger aksi setiap 30 detik (atau lebih sering)
while true do
wait(30) -- interval waktu lebih sering (30 detik)
game:GetService('Players').LocalPlayer.Character.Humanoid:Move(Vector3.new(0, 0, 0), true) -- Pindahin player
end
