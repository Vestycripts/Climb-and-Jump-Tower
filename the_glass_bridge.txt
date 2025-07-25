local player = game.Players.LocalPlayer
local gui = Instance.new("ScreenGui", player:WaitForChild("PlayerGui"))
gui.Name = "G2DVGlassChecker"
gui.ResetOnSpawn = false

-- Main Frame
local mainFrame = Instance.new("Frame", gui)
mainFrame.Size = UDim2.new(0, 360, 0, 300)
mainFrame.Position = UDim2.new(0.5, -180, 0.5, -150)
mainFrame.BackgroundColor3 = Color3.fromRGB(20, 0, 0)
mainFrame.BorderSizePixel = 0
mainFrame.Active = true
mainFrame.Draggable = true
Instance.new("UICorner", mainFrame).CornerRadius = UDim.new(0, 20)

-- Title Bar
local titleBar = Instance.new("TextLabel", mainFrame)
titleBar.Size = UDim2.new(1, 0, 0, 40)
titleBar.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
titleBar.Text = "G2DV Glass Checker"
titleBar.TextColor3 = Color3.fromRGB(200, 0, 0)
titleBar.Font = Enum.Font.GothamBlack
titleBar.TextSize = 22
titleBar.BorderSizePixel = 0
Instance.new("UICorner", titleBar).CornerRadius = UDim.new(0, 20)

-- Toggle Button (Original Logic)
local toggle = Instance.new("TextButton", mainFrame)
toggle.Size = UDim2.new(0, 220, 0, 60)
toggle.Position = UDim2.new(0.5, -110, 0, 60)
toggle.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
toggle.TextColor3 = Color3.fromRGB(200, 0, 0)
toggle.Font = Enum.Font.GothamBold
toggle.TextSize = 20
toggle.Text = "🔴 Classic Glass Toggle"
Instance.new("UICorner", toggle).CornerRadius = UDim.new(0, 16)

-- Advanced Button
local advToggle = Instance.new("TextButton", mainFrame)
advToggle.Size = UDim2.new(0, 220, 0, 60)
advToggle.Position = UDim2.new(0.5, -110, 0, 135)
advToggle.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
advToggle.TextColor3 = Color3.fromRGB(200, 0, 0)
advToggle.Font = Enum.Font.GothamBold
advToggle.TextSize = 18
advToggle.Text = "🧪 Advanced ❤️‍🩹 Improved"
Instance.new("UICorner", advToggle).CornerRadius = UDim.new(0, 16)

-- Close Button
local close = Instance.new("TextButton", mainFrame)
close.Size = UDim2.new(0, 30, 0, 30)
close.Position = UDim2.new(1, -35, 0, 5)
close.Text = "✖"
close.Font = Enum.Font.GothamBold
close.TextColor3 = Color3.fromRGB(200, 0, 0)
close.TextSize = 16
close.BackgroundTransparency = 1

-- Bubble Button
local bubble = Instance.new("TextButton", gui)
bubble.Size = UDim2.new(0, 50, 0, 50)
bubble.Position = UDim2.new(0, 20, 0.5, -25)
bubble.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
bubble.Text = "🧊"
bubble.TextColor3 = Color3.fromRGB(200, 0, 0)
bubble.TextSize = 24
bubble.Visible = false
bubble.Draggable = true
bubble.Active = true
Instance.new("UICorner", bubble).CornerRadius = UDim.new(1, 0)

-- Classic Toggle Logic
local isOn = false
local function runClassic()
	for _, row in pairs(workspace.GameRunningService.GlassBridges.GlassPairs:GetChildren()) do
		for _, glass in pairs(row:GetChildren()) do
			if glass:IsA("BasePart") then
				glass.Transparency = 0
				if glass:FindFirstChild("GlassFall") and glass:FindFirstChild("TouchInterest") then
					local hi = Instance.new("Highlight", glass)
					hi.FillColor = Color3.fromRGB(0, 255, 0)
					hi.OutlineTransparency = 1
					hi.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
					hi.Adornee = glass
				elseif glass:FindFirstChild("TouchInterest") and not glass:FindFirstChild("GlassFall") then
					local hi = Instance.new("Highlight", glass)
					hi.FillColor = Color3.fromRGB(255, 0, 0)
					hi.OutlineTransparency = 1
					hi.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
					hi.Adornee = glass
				end
			end
		end
	end
end

local function clearClassic()
	for _, row in pairs(workspace.GameRunningService.GlassBridges.GlassPairs:GetChildren()) do
		for _, glass in pairs(row:GetChildren()) do
			if glass:IsA("BasePart") then
				for _, obj in ipairs(glass:GetChildren()) do
					if obj:IsA("Highlight") then obj:Destroy() end
				end
			end
		end
	end
end

toggle.MouseButton1Click:Connect(function()
	isOn = not isOn
	if isOn then
		toggle.Text = "🟢 Classic Glass ON"
		runClassic()
	else
		toggle.Text = "🔴 Classic Glass Toggle"
		clearClassic()
	end
end)

-- Advanced Feature Logic
local advancedOn = false
local connection

local function check(obj)
	if obj.Name == "GlassFall" and obj.Parent:IsA("Part") then
		if not obj.Parent:FindFirstChildOfClass("Highlight") then
			obj.Parent.Transparency = 0
			local hi = Instance.new("Highlight", obj.Parent)
			hi.FillColor = Color3.fromRGB(0, 255, 0)
			hi.OutlineTransparency = 1
			hi.FillTransparency = 0.5
			hi.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
			hi.Adornee = obj.Parent
		end
	end
end

advToggle.MouseButton1Click:Connect(function()
	advancedOn = not advancedOn
	if advancedOn then
		advToggle.Text = "🟢 Advanced ON ❤️‍🩹"
		for _, obj in ipairs(workspace:GetDescendants()) do check(obj) end
		connection = workspace.DescendantAdded:Connect(check)
		print("✅ Advanced ❤️‍🩹 Enabled | Credits:  G2DV, FOXChecks")
	else
		advToggle.Text = "🧪 Advanced ❤️‍🩹 Improved"
		if connection then connection:Disconnect() end
		for _, part in ipairs(workspace:GetDescendants()) do
			if part:IsA("BasePart") then
				for _, child in ipairs(part:GetChildren()) do
					if child:IsA("Highlight") then child:Destroy() end
				end
			end
		end
		print("❌ Advanced Mode Disabled")
	end
end)

-- TP to End Button
local tpButton = Instance.new("TextButton", mainFrame)
tpButton.Size = UDim2.new(0, 220, 0, 60)
tpButton.Position = UDim2.new(0.5, -110, 0, 210)
tpButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
tpButton.TextColor3 = Color3.fromRGB(200, 0, 0)
tpButton.Font = Enum.Font.GothamBold
tpButton.TextSize = 18
tpButton.Text = "🚀 TP to End"
Instance.new("UICorner", tpButton).CornerRadius = UDim.new(0, 16)

tpButton.MouseButton1Click:Connect(function()
    local character = player.Character or player.CharacterAdded:Wait()
    local hrp = character:WaitForChild("HumanoidRootPart", 2)
    local glassPairs = workspace:FindFirstChild("GameRunningService") and workspace.GameRunningService:FindFirstChild("GlassBridges") and workspace.GameRunningService.GlassBridges:FindFirstChild("GlassPairs")
    
    if glassPairs and hrp then
        local lastRow = glassPairs:GetChildren()[#glassPairs:GetChildren()]
        if lastRow then
            local lastGlass = lastRow:GetChildren()[1]
            if lastGlass and lastGlass:IsA("BasePart") then
                hrp.CFrame = lastGlass.CFrame + Vector3.new(0, 5, 0)
                print("✅ Teleported to the end of the Glass Bridge.")
            else
                warn("⚠️ Last glass part not found.")
            end
        else
            warn("⚠️ Last row not found.")
        end
    else
        warn("⚠️ Couldn't find GlassBridges or HRP.")
    end
end)

-- Close/Open GUI
close.MouseButton1Click:Connect(function()
	mainFrame.Visible = false
	bubble.Visible = true
end)
bubble.MouseButton1Click:Connect(function()
	mainFrame.Visible = true
	bubble.Visible = false
end)