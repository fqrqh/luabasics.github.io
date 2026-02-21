# luabasic

Une Documentation Personnalisée pour apprendre le Lua!

# 1. Player

Pour avoir accès au Player vous devez tout simplement chargé le modules suivant :

```bash
local Players = game:GetService("Players")
```
Ensuite pour avoir accès au LocalPlayer ainsi qu’au Character, vous devrez les charger comme ceci :

> [!TIP]
> Le `LocalPlayer` représente le joueur local sur le client.

```bash
local Player = Players.LocalPlayer
et pour le character
local character = Player.Character or Player.CharacterAdded:Wait()
```

> [!WARNING]
> `Les codes lua sont sensibles a la case!!`
> ce qui signifie que le language distingue les Maj et les miniscules.
# 2. Services
Pour charger tous les services et modules, vous pouvez utiliser ce script dès le début de votre script : 

```bash
local Players = game:GetService("Players")

local Player = Players.LocalPlayer
local Humanoid = Player:WaitForChild("Humanoid")
local character = Player.Character or Player.CharacterAdded:Wait()
local PlayerGui = Player:WaitForChild("PlayerGui")
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local ServerStorage = game:GetService("ServerStorage")
local ServerScriptService = game:GetService("ServerScriptService")
local Workspace = game:GetService("Workspace")
local Lighting = game:GetService("Lighting")
local StarterGui = game:GetService("StarterGui")
local StarterPack = game:GetService("StarterPack")
local StarterPlayer = game:GetService("StarterPlayer")
local SoundService = game:GetService("SoundService")
local Chat = game:GetService("Chat")
local TextService = game:GetService("TextService")
local uis = game:GetService("UserInputService")
local Camera = workspace:WaitForChild("Camera")
local TweenService = game:GetService("TweenService")
```




