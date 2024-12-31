local Library = loadstring(Game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wizard"))()

local PhantomForcesWindow = Library:NewWindow("base do Satox Hub")

local KillingCheats = PhantomForcesWindow:NewSection("Kill Options")



local selectedKillAdvancedPlayer = nil
local couchEquipped = false

local function killAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-8.657157897949219, -222.3133087158203, -23.58349609375) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function FlyAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-107.91380310058594, -10.128937721252441, 261.37420654296875) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function SafeVoidAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(462.886474609375, -75.30844116210938, 123.47378540039062) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function BowAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-588.5294189453125, 8.251455307006836, -182.5675506591797) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function PlaneAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(665.856201171875, 3.6353466510772705, 89.86775970458984) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function LagAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(104.80880737304688, 34.60691833496094, 632.2498168945312) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function BringAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-570.4937133789062, 37.714874267578125, 963.8348999023438) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function SafeVoifAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(104.80880737304688, 34.60691833496094, 632.2498168945312) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function SkyAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(104.80880737304688, 34.60691833496094, 632.2498168945312) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function PriAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-783.1765747070312, -517.522216796875, 1115.422119140625) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function PrisionAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-783.1765747070312, -517.522216796875, 1115.422119140625) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

local function BugAdvancedPlayer()
if selectedKillAdvancedPlayer then
local player = game.Players:FindFirstChild(selectedKillAdvancedPlayer)
if player then
-- Equipa o item 'Couch' no inventário se ainda não estiver equipado
--big
local args = {
[1] = "CharacterSizeDown",
[2] = 5
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))
local backpack = game.Players.LocalPlayer.Backpack
if backpack and not couchEquipped then
local couch = backpack:FindFirstChild("Couch")
if couch then
game.Players.LocalPlayer.Character.Humanoid:EquipTool(couch)
couchEquipped = true
else
print("O item 'Couch' não foi encontrado no seu inventário.")
end
end

-- Looping de teleportes no jogador selecionado da lista
while true do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = player.Character.HumanoidRootPart.CFrame
wait(0.0) -- Intervalo entre cada teleporte, ajuste conforme necessário

-- Verifica se o jogador sentou no 'Couch' e realiza o teleporte para o céu
if player.Character:FindFirstChild("Humanoid") and player.Character.Humanoid.SeatPart then
player.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 0, 0) -- Teleporta para cima novamente
wait(0.0) -- Espera um pouco antes de teleportar de volta para evitar bugs
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(176.63543701171875, 594.9183959960938, 393.3529052734375) -- Teleporta de volta para a posição original
break -- Sai do loop após teleportar de volta
end
end

--Small
local args = {
[1] = "CharacterSizeUp",
[2] = 1
}
game:GetService("ReplicatedStorage").RE:FindFirstChild("1Clothe1s"):FireServer(unpack(args))

-- Remove o item 'Couch' da mão do jogador após o teleporte para o céu
if couchEquipped then
local backpack = game.Players.LocalPlayer.Backpack
if backpack then
local couch = backpack:FindFirstChild("Couch")
if couch then
couch.Parent = nil -- Remove o 'Couch' do inventário
couchEquipped = false
end
end
end
else
print("Jogador não encontrado.")
end
else
print("Nenhum jogador selecionado para o Bring Avançado.")
end
end

-- Lista de Players para Bring Avançado
local killAdvancedPlayerList = {}
for _, player in ipairs(game.Players:GetPlayers()) do
table.insert(killAdvancedPlayerList, player.Name)
end

local function updatePlayerList()
local players = game.Players:GetPlayers()
local playerNames = {}
for _, player in ipairs(players) do
table.insert(playerNames, player.Name)
end
return playerNames
end



KillingCheats:CreateDropdown("Selecionar Jogador", killAdvancedPlayerList, 2, function(playerName)
selectedKillAdvancedPlayer = playerName
end)



KillingCheats:CreateButton("kill", function()
killAdvancedPlayer()
print("HI")
end)
