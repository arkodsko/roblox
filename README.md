ball = script.Parent
local allow = 1

--configurations
local Object = "Part"
local PosX,PosY,PosZ = -2.38, math.random(5,15), -1.687 
local Parent = workspace
local SizeX,SizeY,SizeZ = 4, 4, 4
local Shape = "Ball"
local Material = "Glass"
local WaitTime = 0.1
local Color = BrickColor.Red()
local Anchored = false


while allow == 1 do
ball = Instance.new(Object)
ball.Position = Vector3.new(PosX,PosY,PosZ)
ball.Parent = Parent
ball.Size = Vector3.new(SizeX,SizeY,SizeZ)
ball.Shape = Shape
ball.Material = Material
	ball.BrickColor = Color
	ball.Anchored = Anchored
	wait(WaitTime)
	end
