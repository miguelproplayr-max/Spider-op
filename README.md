
-- SpiderOP v1.0
local player = game.Players.LocalPlayer
local char = player.Character or player.CharacterAdded:Wait()

-- Velocidade alta
char.Humanoid.WalkSpeed = 150

-- Pulo alto
char.Humanoid.JumpPower = 120

-- Anti Hit básico (desativa colisão)
for _, part in pairs(char:GetDescendants()) do
    if part:IsA("BasePart") then
        part.CanCollide = false
    end
end

print("SpiderOP ativado com sucesso!")<img width="1024" height="1024" alt="file_000000002c0c61f4b5498ec0ebf41d57" src="https://github.com/user-attachments/assets/741f4ea7-11d9-42e4-b106-1a128b2a11f3" />
