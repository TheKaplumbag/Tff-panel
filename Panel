local main = game:GetService("Players").LocalPlayer.PlayerGui.KontrolcuGui.Main
local sbk = game:GetService("Players").LocalPlayer.PlayerGui.SkorTablosuEditor
local plr = game.Players.LocalPlayer.Character.Humanoid
local me = game.Players.LocalPlayer.PlayerGui
local Gui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Button = Instance.new("TextButton")
local Text1 = Instance.new("TextLabel")
local ExitButton = Instance.new("TextButton")
local TextButton1 = Instance.new("TextButton")
local sbkButton = Instance.new("TextButton")
--// Editing Gui \\--
Gui.Parent = me
Gui.Name = "Helele"
Gui.ResetOnSpawn = false
--// Editing frame \\--
Frame.Parent = Gui
Frame.Draggable = true
Frame.Size = UDim2.new(0, 200, 0, 200)
Frame.Active = true
Frame.AutoLocalize = true
--// Editing text \\--
Text1.Text = "Welcome"
Text1.Parent = Frame
Text1.Size = UDim2.new(0, 200, 0, 50)
Text1.TextScaled = true
Text1.Position = UDim2.new(0, 0, 0, 50)
-- // Editing button \\--
Button.Parent = Frame
Button.Position = UDim2.new(0, 0, 0, 200)
Button.Size = UDim2.new(0, 200, 0, 50)
Button.Text = "open panel"
Button.TextScaled = true
Button.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
Button.MouseButton1Click:Connect(function() 
main.Visible = not main.Visible
end)
--//Editing ExitButton \\--
ExitButton.Parent = Frame
ExitButton.Size = UDim2.new(0, 200, 0, 50)
ExitButton.Text = "Close Gui"
ExitButton.TextScaled = true
ExitButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
ExitButton.MouseButton1Click:Connect(function()
TextButton1.Visible = true
Frame.Visible = false
end)
--// Editing sbk button \\--
sbkButton.Parent = Frame
sbkButton.Size = UDim2.new(0, 200, 0, 50)
sbkButton.Position = UDim2.new(0, 0, 0, 150)
sbkButton.Text = "Open Scoreboard control panel"
sbkButton.TextScaled = true
sbkButton.BackgroundColor3 = Color3.fromRGB(0,255,0)
sbkButton.MouseButton1Click:Connect(function()
sbk.Enabled = not sbk.Enabled
end)
--// Editing open button \\--
TextButton1.Parent = Gui
TextButton1.Size = UDim2.new(0.08, 0, 0.1)
TextButton1.Text = "Click to open menu"
TextButton1.Draggable = true
TextButton1.Active = true
TextButton1.Visible = false
TextButton1.Position = UDim2.new(0, 0, 0, 200)
TextButton1.MouseButton1Click:Connect(function() 
Frame.Visible = true
TextButton1.Visible = false
end)







