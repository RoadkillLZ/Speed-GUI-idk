```lua

local gh = Game:GetService("Coregui")

local hh = Instance.new("ScreenGui")
hh.Name = "speed"
hh.ResetOnSpawn = false
hh.Parent = gh

local fr = Instance.new("Frame")
fr.Size = UDim2.new(0, 250, 0, 150)
fr.Position = UDim2.new(0.5, -125, 0.5, -75)
fr.BackgroundColor3 = Color3.FromRGB(255, 255, 255)
fr.BorderSizePixel = 0
fr.Parent = hh

local tt = Instance.new("TextLabel")
tt.Size = UDim2.new(1, 0, 0, 30)
tt.BackgroundColor3 = Color3.FromRGB(60, 60, 70)
tt.Text = "Speed 500"
tt.TextColor3 = Color3.new(1,1,1)
tt.Font = Enum.Font.SourceSansBold
tt.TextSize = 20
tt.Parent = hh

hh.Active = true
hh.Draggable = true

local but = Instance.new("TextButton")
but.Size = UDim2.new(0.8, 0, 0, 30)
but.Position = UDim2.new(0.1, 
