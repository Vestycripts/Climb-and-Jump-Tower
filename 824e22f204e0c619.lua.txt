-- ts file was generated at discord.gg/25ms


local a = {}
a['1'] = Instance.new'ScreenGui'
a['1'].Name = 'NatHub'
a['1'].ZIndexBehavior = Enum.ZIndexBehavior.Sibling
a['1'].ResetOnSpawn = false
local b = cloneref or function(...)
    return ...
end
if protect_gui then
    protect_gui(a['1'])
elseif gethui then
    a['1'].Parent = gethui()
elseif pcall(function()
    game.CoreGui:GetChildren()
end) then
    a['1'].Parent = b(game:GetService'CoreGui')
else
    a['1'].Parent = game.Players.LocalPlayer:WaitForChild'PlayerGui'
end
a['2'] = Instance.new('Frame', a['1'])
a['2'].ZIndex = 0
a['2'].BorderSizePixel = 2
a['2'].BackgroundColor3 = Color3.fromRGB(37, 40, 47)
a['2'].AnchorPoint = Vector2.new(0.5, 0.5)
a['2'].Size = UDim2.new(0, 528, 0, 334)
a['2'].Position = UDim2.new(0.5278, 0, 0.5, 0)
a['2'].BorderColor3 = Color3.fromRGB(61, 61, 75)
a['2'].Name = 'Window'
a['3'] = Instance.new('UICorner', a['2'])
a['3'].CornerRadius = UDim.new(0, 10)
a['4'] = Instance.new('Frame', a['2'])
a['4'].Visible = false
a['4'].ZIndex = 4
a['4'].BorderSizePixel = 0
a['4'].BackgroundColor3 = Color3.fromRGB(32, 35, 41)
a['4'].AnchorPoint = Vector2.new(0.5, 0.5)
a['4'].ClipsDescendants = true
a['4'].Size = UDim2.new(0.7281, 0, 0.68367, 0)
a['4'].Position = UDim2.new(0.5, 0, 0.5, 0)
a['4'].BorderColor3 = Color3.fromRGB(61, 61, 75)
a['4'].Name = 'DropdownSelection'
a['5'] = Instance.new('UICorner', a['4'])
a['5'].CornerRadius = UDim.new(0, 6)
a['6'] = Instance.new('UIStroke', a['4'])
a['6'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['6'].Thickness = 1.5
a['6'].Color = Color3.fromRGB(61, 61, 75)
a['7'] = Instance.new('Frame', a['4'])
a['7'].BorderSizePixel = 0
a['7'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['7'].Size = UDim2.new(1, 0, 0, 50)
a['7'].Position = UDim2.new(0, 0, 0, 0)
a['7'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['7'].Name = 'TopBar'
a['7'].BackgroundTransparency = 1
a['8'] = Instance.new('Frame', a['7'])
a['8'].BorderSizePixel = 0
a['8'].AnchorPoint = Vector2.new(1, 0.5)
a['8'].Size = UDim2.new(0, 120, 0, 25)
a['8'].Position = UDim2.new(1, - 50, 0.5, 0)
a['8'].Name = 'BoxFrame'
a['8'].BackgroundTransparency = 1
a['9'] = Instance.new('ImageLabel', a['8'])
a['9'].ZIndex = 0
a['9'].BorderSizePixel = 0
a['9'].SliceCenter = Rect.new(49, 49, 450, 450)
a['9'].ScaleType = Enum.ScaleType.Slice
a['9'].ImageTransparency = 0.75
a['9'].ImageColor3 = Color3.fromRGB(0, 0, 0)
a['9'].AnchorPoint = Vector2.new(0.5, 0.5)
a['9'].Image = 'rbxassetid://6014261993'
a['9'].Size = UDim2.new(1, 30, 1, 30)
a['9'].BackgroundTransparency = 1
a['9'].Name = 'DropShadow'
a['9'].Position = UDim2.new(0.5, 0, 0.5, 0)
a.a = Instance.new('Frame', a['8'])
a.a.BorderSizePixel = 0
a.a.BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a.a.AutomaticSize = Enum.AutomaticSize.Y
a.a.Size = UDim2.new(1, 0, 1, 0)
a.a.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.b = Instance.new('UICorner', a.a)
a.b.CornerRadius = UDim.new(0, 5)
a.c = Instance.new('UIStroke', a.a)
a.c.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a.c.Thickness = 1.5
a.c.Color = Color3.fromRGB(61, 61, 75)
a.d = Instance.new('TextBox', a.a)
a.d.TextXAlignment = Enum.TextXAlignment.Left
a.d.BorderSizePixel = 0
a.d.TextWrapped = true
a.d.TextTruncate = Enum.TextTruncate.AtEnd
a.d.TextSize = 14
a.d.TextColor3 = Color3.fromRGB(197, 204, 219)
a.d.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.d.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a.d.ClipsDescendants = true
a.d.PlaceholderText = 'Input here...'
a.d.Size = UDim2.new(1, - 25, 1, 0)
a.d.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.d.Text = ''
a.d.BackgroundTransparency = 1
a.e = Instance.new('UIPadding', a.d)
a.e.PaddingTop = UDim.new(0, 10)
a.e.PaddingRight = UDim.new(0, 10)
a.e.PaddingLeft = UDim.new(0, 10)
a.e.PaddingBottom = UDim.new(0, 10)
a.f = Instance.new('ImageButton', a.a)
a.f.BorderSizePixel = 0
a.f.BackgroundTransparency = 1
a.f.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.f.ImageColor3 = Color3.fromRGB(197, 204, 219)
a.f.AnchorPoint = Vector2.new(1, 0.5)
a.f.Image = 'rbxassetid://86928976705683'
a.f.Size = UDim2.new(0, 15, 0, 15)
a.f.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.f.Position = UDim2.new(1, - 5, 0.5, 0)
a['10'] = Instance.new('ImageButton', a['7'])
a['10'].BorderSizePixel = 0
a['10'].BackgroundTransparency = 1
a['10'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['10'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['10'].ZIndex = 0
a['10'].AnchorPoint = Vector2.new(1, 0.5)
a['10'].Image = 'rbxassetid://132453323679056'
a['10'].Size = UDim2.new(0, 25, 0, 25)
a['10'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['10'].Name = 'Close'
a['10'].Position = UDim2.new(1, - 12, 0.5, 0)
a['11'] = Instance.new('TextLabel', a['7'])
a['11'].TextWrapped = true
a['11'].Interactable = false
a['11'].ZIndex = 0
a['11'].BorderSizePixel = 0
a['11'].TextSize = 18
a['11'].TextXAlignment = Enum.TextXAlignment.Left
a['11'].TextScaled = true
a['11'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['11'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a['11'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['11'].BackgroundTransparency = 1
a['11'].AnchorPoint = Vector2.new(0, 0.5)
a['11'].Size = UDim2.new(0.5, 0, 0, 18)
a['11'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['11'].Text = 'Dropdown'
a['11'].Name = 'Title'
a['11'].Position = UDim2.new(0, 12, 0.5, 0)
a['12'] = Instance.new('Folder', a['4'])
a['12'].Name = 'Dropdowns'
a['13'] = Instance.new('Frame', a['2'])
a['13'].BorderSizePixel = 0
a['13'].BackgroundColor3 = Color3.fromRGB(37, 40, 47)
a['13'].ClipsDescendants = true
a['13'].Size = UDim2.new(0, 165, 1, - 35)
a['13'].Position = UDim2.new(0, 0, 0, 35)
a['13'].BorderColor3 = Color3.fromRGB(61, 61, 75)
a['13'].Name = 'TabButtons'
a['13'].SelectionGroup = true
a['14'] = Instance.new('ScrollingFrame', a['13'])
a['14'].Active = true
a['14'].ScrollingDirection = Enum.ScrollingDirection.Y
a['14'].BorderSizePixel = 0
a['14'].CanvasSize = UDim2.new(0, 0, 0, 0)
a['14'].ElasticBehavior = Enum.ElasticBehavior.Never
a['14'].TopImage = 'rbxasset://textures/ui/Scroll/scroll-middle.png'
a['14'].BackgroundColor3 = Color3.fromRGB(37, 40, 47)
a['14'].Name = 'Lists'
a['14'].Selectable = false
a['14'].BottomImage = 'rbxasset://textures/ui/Scroll/scroll-middle.png'
a['14'].AutomaticCanvasSize = Enum.AutomaticSize.Y
a['14'].Size = UDim2.new(1, 0, 1, 0)
a['14'].BorderColor3 = Color3.fromRGB(61, 61, 75)
a['14'].ScrollBarThickness = 4
a['14'].BackgroundTransparency = 1
a['15'] = Instance.new('UIListLayout', a['14'])
a['15'].SortOrder = Enum.SortOrder.LayoutOrder
a['16'] = Instance.new('Frame', a['14'])
a['16'].Visible = false
a['16'].BorderSizePixel = 0
a['16'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['16'].Size = UDim2.new(1, 0, 0, 36)
a['16'].Position = UDim2.new(- 3.75E-2, 0, 0.38434, 0)
a['16'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['16'].Name = 'TabButton'
a['16'].BackgroundTransparency = 1
a['17'] = Instance.new('Frame', a['16'])
a['17'].BorderSizePixel = 0
a['17'].BackgroundColor3 = Color3.fromRGB(197, 204, 219)
a['17'].AnchorPoint = Vector2.new(0, 0.5)
a['17'].Size = UDim2.new(0, 5, 0, 25)
a['17'].Position = UDim2.new(0, 8, 0, 18)
a['17'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['17'].Name = 'Bar'
a['18'] = Instance.new('UIGradient', a['17'])
a['18'].Enabled = false
a['18'].Rotation = 90
a['18'].Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(110, 212, 255)),
    ColorSequenceKeypoint.new(0.978, Color3.fromRGB(0, 124, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 218, 255))
}
a['19'] = Instance.new('UICorner', a['17'])
a['19'].CornerRadius = UDim.new(0, 100)
a['1a'] = Instance.new('ImageButton', a['16'])
a['1a'].BorderSizePixel = 0
a['1a'].BackgroundTransparency = 1
a['1a'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['1a'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['1a'].AnchorPoint = Vector2.new(0, 0.5)
a['1a'].Image = 'rbxassetid://113216930555884'
a['1a'].Size = UDim2.new(0, 31, 0, 30)
a['1a'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['1a'].Position = UDim2.new(0, 21, 0, 18)
a['1b'] = Instance.new('UIAspectRatioConstraint', a['1a'])
a['1c'] = Instance.new('TextLabel', a['16'])
a['1c'].TextWrapped = true
a['1c'].BorderSizePixel = 0
a['1c'].TextSize = 14
a['1c'].TextXAlignment = Enum.TextXAlignment.Left
a['1c'].TextScaled = true
a['1c'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['1c'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a['1c'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['1c'].BackgroundTransparency = 1
a['1c'].AnchorPoint = Vector2.new(0, 0.5)
a['1c'].Size = UDim2.new(0, 88, 0, 16)
a['1c'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['1c'].Text = 'NatHub'
a['1c'].Position = UDim2.new(0, 57, 0.5, 0)
a['1d'] = Instance.new('UIPadding', a['14'])
a['1d'].PaddingTop = UDim.new(0, 8)
a['1e'] = Instance.new('Frame', a['14'])
a['1e'].Visible = false
a['1e'].BorderSizePixel = 0
a['1e'].BackgroundColor3 = Color3.fromRGB(61, 61, 75)
a['1e'].Size = UDim2.new(1, 0, 0, 1)
a['1e'].BorderColor3 = Color3.fromRGB(61, 61, 75)
a['1e'].Name = 'Divider'
a['1f'] = Instance.new('ImageButton', a['14'])
a['1f'].Active = false
a['1f'].BorderSizePixel = 0
a['1f'].AutoButtonColor = false
a['1f'].Visible = false
a['1f'].BackgroundTransparency = 1
a['1f'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['1f'].Selectable = false
a['1f'].Size = UDim2.new(1, 0, 0, 36)
a['1f'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['1f'].Name = 'TabButton'
a['20'] = Instance.new('ImageButton', a['1f'])
a['20'].BorderSizePixel = 0
a['20'].ImageTransparency = 0.5
a['20'].BackgroundTransparency = 1
a['20'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['20'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['20'].AnchorPoint = Vector2.new(0, 0.5)
a['20'].Image = 'rbxassetid://113216930555884'
a['20'].Size = UDim2.new(0, 31, 0, 30)
a['20'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['20'].Position = UDim2.new(0, 6, 0, 18)
a['21'] = Instance.new('UIAspectRatioConstraint', a['20'])
a['22'] = Instance.new('TextLabel', a['1f'])
a['22'].TextWrapped = true
a['22'].BorderSizePixel = 0
a['22'].TextSize = 14
a['22'].TextXAlignment = Enum.TextXAlignment.Left
a['22'].TextTransparency = 0.5
a['22'].TextScaled = true
a['22'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['22'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a['22'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['22'].BackgroundTransparency = 1
a['22'].AnchorPoint = Vector2.new(0, 0.5)
a['22'].Size = UDim2.new(0, 103, 0, 16)
a['22'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['22'].Text = 'NatHub'
a['22'].Position = UDim2.new(0, 42, 0.5, 0)
a['23'] = Instance.new('Frame', a['1f'])
a['23'].BorderSizePixel = 0
a['23'].BackgroundColor3 = Color3.fromRGB(197, 204, 219)
a['23'].AnchorPoint = Vector2.new(0, 0.5)
a['23'].Size = UDim2.new(0, 5, 0, 0)
a['23'].Position = UDim2.new(0, 8, 0, 18)
a['23'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['23'].Name = 'Bar'
a['23'].BackgroundTransparency = 1
a['24'] = Instance.new('UICorner', a['23'])
a['24'].CornerRadius = UDim.new(0, 100)
a['25'] = Instance.new('UICorner', a['13'])
a['25'].CornerRadius = UDim.new(0, 6)
a['26'] = Instance.new('Frame', a['13'])
a['26'].BorderSizePixel = 0
a['26'].BackgroundColor3 = Color3.fromRGB(37, 40, 47)
a['26'].Size = UDim2.new(1, 0, 0, 5)
a['26'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['26'].Name = 'AntiCornerTop'
a['27'] = Instance.new('Frame', a['13'])
a['27'].BorderSizePixel = 0
a['27'].BackgroundColor3 = Color3.fromRGB(37, 40, 47)
a['27'].AnchorPoint = Vector2.new(0.5, 0)
a['27'].Size = UDim2.new(0, 2, 1, 0)
a['27'].Position = UDim2.new(1, 1, 0, 0)
a['27'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['27'].Name = 'AntiCornerRight'
a['28'] = Instance.new('Frame', a['13'])
a['28'].ZIndex = 2
a['28'].BorderSizePixel = 0
a['28'].BackgroundColor3 = Color3.fromRGB(61, 61, 75)
a['28'].AnchorPoint = Vector2.new(1, 0)
a['28'].Size = UDim2.new(0, 2, 1, 0)
a['28'].Position = UDim2.new(1, 0, 0, 0)
a['28'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['28'].Name = 'Border'
a['29'] = Instance.new('Frame', a['2'])
a['29'].BorderSizePixel = 0
a['29'].BackgroundColor3 = Color3.fromRGB(37, 40, 47)
a['29'].ClipsDescendants = true
a['29'].Size = UDim2.new(1, 0, 0, 35)
a['29'].BorderColor3 = Color3.fromRGB(61, 61, 75)
a['29'].Name = 'TopFrame'
a['2a'] = Instance.new('ImageButton', a['29'])
a['2a'].Active = false
a['2a'].Interactable = false
a['2a'].BorderSizePixel = 0
a['2a'].BackgroundTransparency = 1
a['2a'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['2a'].AnchorPoint = Vector2.new(0, 0.5)
a['2a'].Image = 'rbxassetid://113216930555884'
a['2a'].Size = UDim2.new(0, 25, 0, 25)
a['2a'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['2a'].Name = 'Icon'
a['2a'].Position = UDim2.new(0, 10, 0.5, 0)
a['2b'] = Instance.new('UIAspectRatioConstraint', a['2a'])
a['2c'] = Instance.new('TextLabel', a['29'])
a['2c'].TextWrapped = true
a['2c'].Interactable = false
a['2c'].BorderSizePixel = 0
a['2c'].TextSize = 14
a['2c'].TextScaled = true
a['2c'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['2c'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a['2c'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['2c'].BackgroundTransparency = 1
a['2c'].AnchorPoint = Vector2.new(0.5, 0.5)
a['2c'].Size = UDim2.new(1, 0, 0, 16)
a['2c'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['2c'].Text = 'NatHub - v1.2.3'
a['2c'].Position = UDim2.new(0.5, 0, 0.5, - 1)
a['2d'] = Instance.new('ImageButton', a['29'])
a['2d'].BorderSizePixel = 0
a['2d'].BackgroundTransparency = 1
a['2d'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['2d'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['2d'].AnchorPoint = Vector2.new(1, 0.5)
a['2d'].Image = 'rbxassetid://132453323679056'
a['2d'].Size = UDim2.new(0, 20, 0, 20)
a['2d'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['2d'].Name = 'Close'
a['2d'].Position = UDim2.new(1, - 15, 0.5, 0)
a['2e'] = Instance.new('ImageButton', a['29'])
a['2e'].BorderSizePixel = 0
a['2e'].BackgroundTransparency = 1
a['2e'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['2e'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['2e'].AnchorPoint = Vector2.new(1, 0.5)
a['2e'].Image = 'rbxassetid://108285848026510'
a['2e'].Size = UDim2.new(0, 15, 0, 15)
a['2e'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['2e'].Name = 'Maximize'
a['2e'].Position = UDim2.new(1, - 55, 0.5, 0)
a['2f'] = Instance.new('ImageButton', a['29'])
a['2f'].BorderSizePixel = 0
a['2f'].BackgroundTransparency = 1
a['2f'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['2f'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['2f'].AnchorPoint = Vector2.new(1, 0.5)
a['2f'].Image = 'rbxassetid://128209591224511'
a['2f'].Size = UDim2.new(0, 20, 0, 20)
a['2f'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['2f'].Name = 'Hide'
a['2f'].Position = UDim2.new(1, - 90, 0.5, 0)
a['30'] = Instance.new('UICorner', a['29'])
a['30'].CornerRadius = UDim.new(0, 6)
a['31'] = Instance.new('Frame', a['29'])
a['31'].ZIndex = 2
a['31'].BorderSizePixel = 0
a['31'].BackgroundColor3 = Color3.fromRGB(61, 61, 75)
a['31'].AnchorPoint = Vector2.new(0, 0.5)
a['31'].Size = UDim2.new(1, 0, 0, 2)
a['31'].Position = UDim2.new(0, 0, 1, 0)
a['31'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['31'].Name = 'Border'
a['32'] = Instance.new('UIStroke', a['2'])
a['32'].Transparency = 0.5
a['32'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['32'].Color = Color3.fromRGB(95, 95, 117)
a['33'] = Instance.new('Frame', a['2'])
a['33'].BorderSizePixel = 0
a['33'].BackgroundColor3 = Color3.fromRGB(32, 35, 41)
a['33'].Size = UDim2.new(1, - 165, 1, - 35)
a['33'].Position = UDim2.new(0, 165, 0, 35)
a['33'].BorderColor3 = Color3.fromRGB(61, 61, 75)
a['33'].Name = 'Tabs'
a['34'] = Instance.new('UICorner', a['33'])
a['34'].CornerRadius = UDim.new(0, 6)
a['35'] = Instance.new('Frame', a['33'])
a['35'].Visible = false
a['35'].BorderSizePixel = 0
a['35'].BackgroundColor3 = Color3.fromRGB(32, 35, 41)
a['35'].Size = UDim2.new(0, 5, 1, 0)
a['35'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['35'].Name = 'AntiCornerLeft'
a['36'] = Instance.new('Frame', a['33'])
a['36'].BorderSizePixel = 0
a['36'].BackgroundColor3 = Color3.fromRGB(32, 35, 41)
a['36'].Size = UDim2.new(1, 0, 0, 5)
a['36'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['36'].Name = 'AntiCornerTop'
a['37'] = Instance.new('TextLabel', a['33'])
a['37'].TextWrapped = true
a['37'].Interactable = false
a['37'].BorderSizePixel = 0
a['37'].TextSize = 14
a['37'].TextScaled = true
a['37'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['37'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a['37'].TextColor3 = Color3.fromRGB(135, 140, 150)
a['37'].BackgroundTransparency = 1
a['37'].AnchorPoint = Vector2.new(0.5, 0.5)
a['37'].Size = UDim2.new(1, 0, 0, 16)
a['37'].Visible = false
a['37'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['37'].Text = 'This tab is empty :('
a['37'].Name = 'NoObjectFoundText'
a['37'].Position = UDim2.new(0.5, 0, 0.45, 0)
a['38'] = Instance.new('Frame', a['2'])
a['38'].BorderSizePixel = 0
a['38'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['38'].ClipsDescendants = true
a['38'].Size = UDim2.new(1, 0, 1, 0)
a['38'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['38'].Name = 'NotificationFrame'
a['38'].BackgroundTransparency = 1
a['39'] = Instance.new('Frame', a['38'])
a['39'].ZIndex = 5
a['39'].BorderSizePixel = 0
a['39'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['39'].AnchorPoint = Vector2.new(0.5, 0)
a['39'].ClipsDescendants = true
a['39'].Size = UDim2.new(0, 630, 1, - 35)
a['39'].Position = UDim2.new(1, 0, 0, 35)
a['39'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['39'].Name = 'NotificationList'
a['39'].BackgroundTransparency = 1
a['3a'] = Instance.new('UIListLayout', a['39'])
a['3a'].Padding = UDim.new(0, 12)
a['3a'].SortOrder = Enum.SortOrder.LayoutOrder
a['3b'] = Instance.new('UIPadding', a['39'])
a['3b'].PaddingTop = UDim.new(0, 10)
a['3b'].PaddingRight = UDim.new(0, 40)
a['3b'].PaddingLeft = UDim.new(0, 40)
a['3c'] = Instance.new('Frame', a['2'])
a['3c'].Visible = false
a['3c'].BorderSizePixel = 0
a['3c'].BackgroundColor3 = Color3.fromRGB(0, 0, 0)
a['3c'].Size = UDim2.new(1, 0, 1, 0)
a['3c'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['3c'].Name = 'DarkOverlay'
a['3c'].BackgroundTransparency = 0.6
a['3d'] = Instance.new('UICorner', a['3c'])
a['3d'].CornerRadius = UDim.new(0, 10)
a['3e'] = Instance.new('ModuleScript', a['1'])
a['3e'].Name = 'Library'
a['3f'] = Instance.new('ModuleScript', a['3e'])
a['3f'].Name = 'IconModule'
a['40'] = Instance.new('ModuleScript', a['3f'])
a['40'].Name = 'Lucide'
a['41'] = Instance.new('Folder', a['1'])
a['41'].Name = 'Templates'
a['42'] = Instance.new('Frame', a['41'])
a['42'].Visible = false
a['42'].BorderSizePixel = 0
a['42'].BackgroundColor3 = Color3.fromRGB(61, 61, 75)
a['42'].Size = UDim2.new(1, 0, 0, 1)
a['42'].BorderColor3 = Color3.fromRGB(61, 61, 75)
a['42'].Name = 'Divider'
a['43'] = Instance.new('ScrollingFrame', a['41'])
a['43'].Visible = false
a['43'].Active = true
a['43'].ScrollingDirection = Enum.ScrollingDirection.Y
a['43'].BorderSizePixel = 0
a['43'].CanvasSize = UDim2.new(0, 0, 0, 0)
a['43'].ElasticBehavior = Enum.ElasticBehavior.Never
a['43'].TopImage = 'rbxasset://textures/ui/Scroll/scroll-middle.png'
a['43'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['43'].Name = 'Tab'
a['43'].Selectable = false
a['43'].BottomImage = 'rbxasset://textures/ui/Scroll/scroll-middle.png'
a['43'].AutomaticCanvasSize = Enum.AutomaticSize.Y
a['43'].Size = UDim2.new(1, 0, 1, 0)
a['43'].ScrollBarImageColor3 = Color3.fromRGB(99, 106, 122)
a['43'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['43'].ScrollBarThickness = 5
a['43'].BackgroundTransparency = 1
a['44'] = Instance.new('UIListLayout', a['43'])
a['44'].Padding = UDim.new(0, 15)
a['44'].SortOrder = Enum.SortOrder.LayoutOrder
a['45'] = Instance.new('UIPadding', a['43'])
a['45'].PaddingTop = UDim.new(0, 10)
a['45'].PaddingRight = UDim.new(0, 14)
a['45'].PaddingLeft = UDim.new(0, 10)
a['45'].PaddingBottom = UDim.new(0, 10)
a['46'] = Instance.new('ImageButton', a['41'])
a['46'].BorderSizePixel = 0
a['46'].AutoButtonColor = false
a['46'].Visible = false
a['46'].BackgroundTransparency = 1
a['46'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['46'].Selectable = false
a['46'].Size = UDim2.new(1, 0, 0, 36)
a['46'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['46'].Name = 'TabButton'
a['47'] = Instance.new('ImageButton', a['46'])
a['47'].BorderSizePixel = 0
a['47'].ImageTransparency = 0.5
a['47'].BackgroundTransparency = 1
a['47'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['47'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['47'].AnchorPoint = Vector2.new(0, 0.5)
a['47'].Image = 'rbxassetid://113216930555884'
a['47'].Size = UDim2.new(0, 20, 0, 20)
a['47'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['47'].Position = UDim2.new(0, 12, 0, 18)
a['48'] = Instance.new('UIAspectRatioConstraint', a['47'])
a['49'] = Instance.new('TextLabel', a['46'])
a['49'].TextWrapped = true
a['49'].BorderSizePixel = 0
a['49'].TextSize = 14
a['49'].TextXAlignment = Enum.TextXAlignment.Left
a['49'].TextTransparency = 0.5
a['49'].TextScaled = true
a['49'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['49'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a['49'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['49'].BackgroundTransparency = 1
a['49'].AnchorPoint = Vector2.new(0, 0.5)
a['49'].Size = UDim2.new(0, 103, 0, 16)
a['49'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['49'].Text = ''
a['49'].Position = UDim2.new(0, 42, 0.5, 0)
a['4a'] = Instance.new('Frame', a['46'])
a['4a'].BorderSizePixel = 0
a['4a'].BackgroundColor3 = Color3.fromRGB(197, 204, 219)
a['4a'].AnchorPoint = Vector2.new(0, 0.5)
a['4a'].Size = UDim2.new(0, 5, 0, 0)
a['4a'].Position = UDim2.new(0, 8, 0, 18)
a['4a'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['4a'].Name = 'Bar'
a['4a'].BackgroundTransparency = 1
a['4b'] = Instance.new('UICorner', a['4a'])
a['4b'].CornerRadius = UDim.new(0, 100)
a['4c'] = Instance.new('ImageButton', a['41'])
a['4c'].BorderSizePixel = 0
a['4c'].AutoButtonColor = false
a['4c'].Visible = false
a['4c'].BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a['4c'].Selectable = false
a['4c'].AutomaticSize = Enum.AutomaticSize.Y
a['4c'].Size = UDim2.new(1, 0, 0, 35)
a['4c'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['4c'].Name = 'Button'
a['4c'].Position = UDim2.new(0, 0, 0.384, 0)
a['4d'] = Instance.new('UICorner', a['4c'])
a['4d'].CornerRadius = UDim.new(0, 6)
a['4e'] = Instance.new('Frame', a['4c'])
a['4e'].BorderSizePixel = 0
a['4e'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['4e'].AutomaticSize = Enum.AutomaticSize.Y
a['4e'].Size = UDim2.new(1, 0, 0, 35)
a['4e'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['4e'].BackgroundTransparency = 1
a['4f'] = Instance.new('UIListLayout', a['4e'])
a['4f'].Padding = UDim.new(0, 5)
a['4f'].SortOrder = Enum.SortOrder.LayoutOrder
a['50'] = Instance.new('UIPadding', a['4e'])
a['50'].PaddingTop = UDim.new(0, 10)
a['50'].PaddingRight = UDim.new(0, 10)
a['50'].PaddingLeft = UDim.new(0, 10)
a['50'].PaddingBottom = UDim.new(0, 10)
a['51'] = Instance.new('TextLabel', a['4e'])
a['51'].TextWrapped = true
a['51'].Interactable = false
a['51'].BorderSizePixel = 0
a['51'].TextSize = 16
a['51'].TextXAlignment = Enum.TextXAlignment.Left
a['51'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['51'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a['51'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['51'].BackgroundTransparency = 1
a['51'].Size = UDim2.new(1, 0, 0, 15)
a['51'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['51'].Text = 'Button'
a['51'].Name = 'Title'
a['52'] = Instance.new('ImageButton', a['51'])
a['52'].BorderSizePixel = 0
a['52'].AutoButtonColor = false
a['52'].BackgroundTransparency = 1
a['52'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['52'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['52'].AnchorPoint = Vector2.new(1, 0.5)
a['52'].Image = 'rbxassetid://91877599529856'
a['52'].Size = UDim2.new(0, 23, 0, 23)
a['52'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['52'].Name = 'ClickIcon'
a['52'].Position = UDim2.new(1, 0, 0.5, 0)
a['53'] = Instance.new('TextLabel', a['4e'])
a['53'].TextWrapped = true
a['53'].Interactable = false
a['53'].BorderSizePixel = 0
a['53'].TextSize = 16
a['53'].TextXAlignment = Enum.TextXAlignment.Left
a['53'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['53'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a['53'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['53'].BackgroundTransparency = 1
a['53'].Size = UDim2.new(1, 0, 0, 15)
a['53'].Visible = false
a['53'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['53'].Text = [[Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus placerat lacus in enim congue, fermentum euismod leo ultricies. Nulla sodales. ]]
a['53'].LayoutOrder = 1
a['53'].AutomaticSize = Enum.AutomaticSize.Y
a['53'].Name = 'Description'
a['54'] = Instance.new('UIGradient', a['4e'])
a['54'].Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a['55'] = Instance.new('UIGradient', a['4e'])
a['55'].Enabled = false
a['55'].Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a['56'] = Instance.new('UIGradient', a['4e'])
a['56'].Enabled = false
a['56'].Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a['57'] = Instance.new('UICorner', a['4e'])
a['57'].CornerRadius = UDim.new(0, 6)
a['58'] = Instance.new('UIStroke', a['4c'])
a['58'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['58'].Thickness = 1.5
a['58'].Color = Color3.fromRGB(61, 61, 75)
a['59'] = Instance.new('Frame', a['41'])
a['59'].Visible = false
a['59'].BorderSizePixel = 0
a['59'].BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a['59'].AutomaticSize = Enum.AutomaticSize.Y
a['59'].Size = UDim2.new(1, 0, 0, 35)
a['59'].Position = UDim2.new(- 3.75E-2, 0, 0.38434, 0)
a['59'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['59'].Name = 'Paragraph'
a['5a'] = Instance.new('UICorner', a['59'])
a['5a'].CornerRadius = UDim.new(0, 6)
a['5b'] = Instance.new('UIStroke', a['59'])
a['5b'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['5b'].Thickness = 1.5
a['5b'].Color = Color3.fromRGB(61, 61, 75)
a['5c'] = Instance.new('TextLabel', a['59'])
a['5c'].TextWrapped = true
a['5c'].Interactable = false
a['5c'].BorderSizePixel = 0
a['5c'].TextSize = 16
a['5c'].TextXAlignment = Enum.TextXAlignment.Left
a['5c'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['5c'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Bold, Enum.FontStyle.Normal)
a['5c'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['5c'].BackgroundTransparency = 1
a['5c'].Size = UDim2.new(1, 0, 0, 15)
a['5c'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['5c'].Text = 'Title'
a['5c'].AutomaticSize = Enum.AutomaticSize.Y
a['5c'].Name = 'Title'
a['5d'] = Instance.new('UIPadding', a['59'])
a['5d'].PaddingTop = UDim.new(0, 10)
a['5d'].PaddingRight = UDim.new(0, 10)
a['5d'].PaddingLeft = UDim.new(0, 10)
a['5d'].PaddingBottom = UDim.new(0, 10)
a['5e'] = Instance.new('UIListLayout', a['59'])
a['5e'].Padding = UDim.new(0, 5)
a['5e'].SortOrder = Enum.SortOrder.LayoutOrder
a['5f'] = Instance.new('TextLabel', a['59'])
a['5f'].TextWrapped = true
a['5f'].Interactable = false
a['5f'].BorderSizePixel = 0
a['5f'].TextSize = 16
a['5f'].TextXAlignment = Enum.TextXAlignment.Left
a['5f'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['5f'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a['5f'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['5f'].BackgroundTransparency = 1
a['5f'].Size = UDim2.new(1, 0, 0, 15)
a['5f'].Visible = false
a['5f'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['5f'].Text = [[Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus placerat lacus in enim congue, fermentum euismod leo ultricies. Nulla sodales. ]]
a['5f'].LayoutOrder = 1
a['5f'].AutomaticSize = Enum.AutomaticSize.Y
a['5f'].Name = 'Description'
a['60'] = Instance.new('ImageButton', a['41'])
a['60'].BorderSizePixel = 0
a['60'].AutoButtonColor = false
a['60'].Visible = false
a['60'].BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a['60'].Selectable = false
a['60'].AutomaticSize = Enum.AutomaticSize.Y
a['60'].Size = UDim2.new(1, 0, 0, 35)
a['60'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['60'].Name = 'Toggle'
a['60'].Position = UDim2.new(- 3.75E-2, 0, 0.38434, 0)
a['61'] = Instance.new('UICorner', a['60'])
a['61'].CornerRadius = UDim.new(0, 6)
a['62'] = Instance.new('UIStroke', a['60'])
a['62'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['62'].Thickness = 1.5
a['62'].Color = Color3.fromRGB(61, 61, 75)
a['63'] = Instance.new('UIPadding', a['60'])
a['63'].PaddingTop = UDim.new(0, 10)
a['63'].PaddingRight = UDim.new(0, 10)
a['63'].PaddingLeft = UDim.new(0, 10)
a['63'].PaddingBottom = UDim.new(0, 10)
a['64'] = Instance.new('UIListLayout', a['60'])
a['64'].Padding = UDim.new(0, 5)
a['64'].SortOrder = Enum.SortOrder.LayoutOrder
a['65'] = Instance.new('TextLabel', a['60'])
a['65'].TextWrapped = true
a['65'].Interactable = false
a['65'].BorderSizePixel = 0
a['65'].TextSize = 16
a['65'].TextXAlignment = Enum.TextXAlignment.Left
a['65'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['65'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a['65'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['65'].BackgroundTransparency = 1
a['65'].Size = UDim2.new(1, 0, 0, 15)
a['65'].Visible = false
a['65'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['65'].Text = [[Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus placerat lacus in enim congue, fermentum euismod leo ultricies. Nulla sodales. ]]
a['65'].LayoutOrder = 1
a['65'].AutomaticSize = Enum.AutomaticSize.Y
a['65'].Name = 'Description'
a['66'] = Instance.new('TextLabel', a['60'])
a['66'].TextWrapped = true
a['66'].BorderSizePixel = 0
a['66'].TextSize = 16
a['66'].TextXAlignment = Enum.TextXAlignment.Left
a['66'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['66'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a['66'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['66'].BackgroundTransparency = 1
a['66'].Size = UDim2.new(1, 0, 0, 15)
a['66'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['66'].Text = 'Toggle'
a['66'].Name = 'Title'
a['67'] = Instance.new('ImageButton', a['66'])
a['67'].BorderSizePixel = 0
a['67'].AutoButtonColor = false
a['67'].BackgroundColor3 = Color3.fromRGB(54, 57, 63)
a['67'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['67'].AnchorPoint = Vector2.new(1, 0.5)
a['67'].Size = UDim2.new(0, 45, 0, 25)
a['67'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['67'].Name = 'Fill'
a['67'].Position = UDim2.new(1, 0, 0.5, 0)
a['68'] = Instance.new('UICorner', a['67'])
a['68'].CornerRadius = UDim.new(100, 0)
a['69'] = Instance.new('ImageButton', a['67'])
a['69'].Active = false
a['69'].Interactable = false
a['69'].BorderSizePixel = 0
a['69'].AutoButtonColor = false
a['69'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['69'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['69'].AnchorPoint = Vector2.new(0, 0.5)
a['69'].Size = UDim2.new(0, 20, 0, 20)
a['69'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['69'].Name = 'Ball'
a['69'].Position = UDim2.new(0, 0, 0.5, 0)
a['6a'] = Instance.new('UICorner', a['69'])
a['6a'].CornerRadius = UDim.new(100, 0)
a['6b'] = Instance.new('ImageLabel', a['69'])
a['6b'].BorderSizePixel = 0
a['6b'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['6b'].ImageColor3 = Color3.fromRGB(54, 57, 63)
a['6b'].AnchorPoint = Vector2.new(0.5, 0.5)
a['6b'].Size = UDim2.new(1, - 5, 1, - 5)
a['6b'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['6b'].BackgroundTransparency = 1
a['6b'].Name = 'Icon'
a['6b'].Position = UDim2.new(0.5, 0, 0.5, 0)
a['6c'] = Instance.new('UIPadding', a['67'])
a['6c'].PaddingTop = UDim.new(0, 2)
a['6c'].PaddingRight = UDim.new(0, 2)
a['6c'].PaddingLeft = UDim.new(0, 2)
a['6c'].PaddingBottom = UDim.new(0, 2)
a['6d'] = Instance.new('Frame', a['41'])
a['6d'].Visible = false
a['6d'].BorderSizePixel = 0
a['6d'].BackgroundColor3 = Color3.fromRGB(37, 40, 47)
a['6d'].AnchorPoint = Vector2.new(0.5, 0.5)
a['6d'].AutomaticSize = Enum.AutomaticSize.Y
a['6d'].Size = UDim2.new(1, 0, 0, 65)
a['6d'].Position = UDim2.new(0.8244, 0, 0.88221, 0)
a['6d'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['6d'].Name = 'Notification'
a['6d'].BackgroundTransparency = 1
a['6e'] = Instance.new('CanvasGroup', a['6d'])
a['6e'].ZIndex = 2
a['6e'].BorderSizePixel = 0
a['6e'].BackgroundColor3 = Color3.fromRGB(37, 40, 47)
a['6e'].AutomaticSize = Enum.AutomaticSize.Y
a['6e'].Size = UDim2.new(0, 265, 0, 70)
a['6e'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['6e'].Name = 'Items'
a['6f'] = Instance.new('Frame', a['6e'])
a['6f'].BorderSizePixel = 0
a['6f'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['6f'].AutomaticSize = Enum.AutomaticSize.Y
a['6f'].Size = UDim2.new(0, 265, 0, 70)
a['6f'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['6f'].BackgroundTransparency = 1
a['70'] = Instance.new('UIListLayout', a['6f'])
a['70'].Padding = UDim.new(0, 5)
a['70'].VerticalAlignment = Enum.VerticalAlignment.Center
a['70'].SortOrder = Enum.SortOrder.LayoutOrder
a['71'] = Instance.new('UIPadding', a['6f'])
a['71'].PaddingTop = UDim.new(0, 15)
a['71'].PaddingLeft = UDim.new(0, 15)
a['71'].PaddingBottom = UDim.new(0, 15)
a['72'] = Instance.new('TextLabel', a['6f'])
a['72'].TextWrapped = true
a['72'].BorderSizePixel = 0
a['72'].TextSize = 12
a['72'].TextXAlignment = Enum.TextXAlignment.Left
a['72'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['72'].FontFace = Font.new('rbxasset://fonts/families/GothamSSm.json', Enum.FontWeight.Regular, Enum.FontStyle.Normal)
a['72'].TextColor3 = Color3.fromRGB(181, 181, 181)
a['72'].BackgroundTransparency = 1
a['72'].AnchorPoint = Vector2.new(0, 0.5)
a['72'].Size = UDim2.new(0, 218, 0, 10)
a['72'].Visible = false
a['72'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['72'].Text = 'This is a notification'
a['72'].LayoutOrder = 1
a['72'].AutomaticSize = Enum.AutomaticSize.Y
a['72'].Name = 'SubContent'
a['72'].Position = UDim2.new(0, 0, 0, 19)
a['73'] = Instance.new('UIGradient', a['72'])
a['73'].Enabled = false
a['73'].Rotation = - 90
a['73'].Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(3, 100, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 255, 226))
}
a['74'] = Instance.new('TextLabel', a['6f'])
a['74'].TextWrapped = true
a['74'].BorderSizePixel = 0
a['74'].TextSize = 16
a['74'].TextXAlignment = Enum.TextXAlignment.Left
a['74'].TextScaled = true
a['74'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['74'].FontFace = Font.new('rbxasset://fonts/families/GothamSSm.json', Enum.FontWeight.Bold, Enum.FontStyle.Normal)
a['74'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['74'].BackgroundTransparency = 1
a['74'].AnchorPoint = Vector2.new(0, 0.5)
a['74'].Size = UDim2.new(0, 235, 0, 18)
a['74'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['74'].Text = 'Title'
a['74'].Name = 'Title'
a['74'].Position = UDim2.new(0, 0, 0, 9)
a['75'] = Instance.new('ImageButton', a['74'])
a['75'].BorderSizePixel = 0
a['75'].BackgroundTransparency = 1
a['75'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['75'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['75'].AnchorPoint = Vector2.new(0, 0.5)
a['75'].Image = 'rbxassetid://132453323679056'
a['75'].Size = UDim2.new(0.09706, 0, 1.33333, 0)
a['75'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['75'].Name = 'Close'
a['75'].Position = UDim2.new(0.92, 0, 0.5, 0)
a['76'] = Instance.new('UIAspectRatioConstraint', a['75'])
a['77'] = Instance.new('UIPadding', a['74'])
a['77'].PaddingLeft = UDim.new(0, 30)
a['78'] = Instance.new('ImageButton', a['74'])
a['78'].BorderSizePixel = 0
a['78'].BackgroundTransparency = 1
a['78'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['78'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['78'].AnchorPoint = Vector2.new(0, 0.5)
a['78'].Image = 'rbxassetid://92049322344253'
a['78'].Size = UDim2.new(0.09706, 0, 1.33333, 0)
a['78'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['78'].Name = 'Icon'
a['78'].Position = UDim2.new(0, - 30, 0.5, 0)
a['79'] = Instance.new('UIAspectRatioConstraint', a['78'])
a['7a'] = Instance.new('TextLabel', a['6f'])
a['7a'].TextWrapped = true
a['7a'].BorderSizePixel = 0
a['7a'].TextSize = 16
a['7a'].TextXAlignment = Enum.TextXAlignment.Left
a['7a'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['7a'].FontFace = Font.new('rbxasset://fonts/families/GothamSSm.json', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a['7a'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['7a'].BackgroundTransparency = 1
a['7a'].AnchorPoint = Vector2.new(0, 0.5)
a['7a'].Size = UDim2.new(0, 218, 0, 10)
a['7a'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['7a'].Text = 'Content'
a['7a'].LayoutOrder = 2
a['7a'].AutomaticSize = Enum.AutomaticSize.Y
a['7a'].Name = 'Content'
a['7a'].Position = UDim2.new(0, 0, 0, 19)
a['7b'] = Instance.new('UIGradient', a['7a'])
a['7b'].Enabled = false
a['7b'].Rotation = - 90
a['7b'].Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(3, 100, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 255, 226))
}
a['7c'] = Instance.new('Frame', a['6e'])
a['7c'].BorderSizePixel = 0
a['7c'].BackgroundColor3 = Color3.fromRGB(61, 61, 75)
a['7c'].AnchorPoint = Vector2.new(0, 1)
a['7c'].Size = UDim2.new(1, 0, 0, 5)
a['7c'].Position = UDim2.new(0, 0, 1, 0)
a['7c'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['7c'].Name = 'TimerBarFill'
a['7c'].BackgroundTransparency = 0.7
a['7d'] = Instance.new('UICorner', a['7c'])
a['7e'] = Instance.new('Frame', a['7c'])
a['7e'].BorderSizePixel = 0
a['7e'].BackgroundColor3 = Color3.fromRGB(61, 61, 75)
a['7e'].Size = UDim2.new(1, 0, 1, 0)
a['7e'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['7e'].Name = 'Bar'
a['7f'] = Instance.new('UICorner', a['7e'])
a['80'] = Instance.new('UIStroke', a['6e'])
a['80'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['80'].Thickness = 1.5
a['80'].Color = Color3.fromRGB(61, 61, 75)
a['81'] = Instance.new('UICorner', a['6e'])
a['82'] = Instance.new('Frame', a['41'])
a['82'].Visible = false
a['82'].BorderSizePixel = 0
a['82'].BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a['82'].AutomaticSize = Enum.AutomaticSize.Y
a['82'].Size = UDim2.new(1, 0, 0, 35)
a['82'].Position = UDim2.new(- 3.75E-2, 0, 0.38434, 0)
a['82'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['82'].Name = 'Slider'
a['83'] = Instance.new('UICorner', a['82'])
a['83'].CornerRadius = UDim.new(0, 6)
a['84'] = Instance.new('UIStroke', a['82'])
a['84'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['84'].Thickness = 1.5
a['84'].Color = Color3.fromRGB(61, 61, 75)
a['85'] = Instance.new('TextLabel', a['82'])
a['85'].TextWrapped = true
a['85'].Interactable = false
a['85'].BorderSizePixel = 0
a['85'].TextSize = 16
a['85'].TextXAlignment = Enum.TextXAlignment.Left
a['85'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['85'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Bold, Enum.FontStyle.Normal)
a['85'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['85'].BackgroundTransparency = 1
a['85'].Size = UDim2.new(1, 0, 0, 15)
a['85'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['85'].Text = 'Slider'
a['85'].AutomaticSize = Enum.AutomaticSize.Y
a['85'].Name = 'Title'
a['86'] = Instance.new('UIPadding', a['82'])
a['86'].PaddingTop = UDim.new(0, 10)
a['86'].PaddingRight = UDim.new(0, 10)
a['86'].PaddingLeft = UDim.new(0, 10)
a['86'].PaddingBottom = UDim.new(0, 10)
a['87'] = Instance.new('UIListLayout', a['82'])
a['87'].Padding = UDim.new(0, 5)
a['87'].SortOrder = Enum.SortOrder.LayoutOrder
a['88'] = Instance.new('TextLabel', a['82'])
a['88'].TextWrapped = true
a['88'].Interactable = false
a['88'].BorderSizePixel = 0
a['88'].TextSize = 16
a['88'].TextXAlignment = Enum.TextXAlignment.Left
a['88'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['88'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a['88'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['88'].BackgroundTransparency = 1
a['88'].Size = UDim2.new(1, 0, 0, 15)
a['88'].Visible = false
a['88'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['88'].Text = [[Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus placerat lacus in enim congue, fermentum euismod leo ultricies. Nulla sodales. ]]
a['88'].LayoutOrder = 1
a['88'].AutomaticSize = Enum.AutomaticSize.Y
a['88'].Name = 'Description'
a['89'] = Instance.new('Frame', a['82'])
a['89'].ZIndex = 0
a['89'].BorderSizePixel = 0
a['89'].Size = UDim2.new(1, 0, 0, 25)
a['89'].Name = 'SliderFrame'
a['89'].LayoutOrder = 2
a['89'].BackgroundTransparency = 1
a['8a'] = Instance.new('Frame', a['89'])
a['8a'].ZIndex = 0
a['8a'].BorderSizePixel = 0
a['8a'].AnchorPoint = Vector2.new(0, 0.5)
a['8a'].Size = UDim2.new(1, 0, 0, 20)
a['8a'].Position = UDim2.new(0, 0, 0.5, 0)
a['8a'].BackgroundTransparency = 1
a['8b'] = Instance.new('ImageLabel', a['8a'])
a['8b'].ZIndex = 0
a['8b'].BorderSizePixel = 0
a['8b'].SliceCenter = Rect.new(49, 49, 450, 450)
a['8b'].ScaleType = Enum.ScaleType.Slice
a['8b'].ImageTransparency = 0.75
a['8b'].ImageColor3 = Color3.fromRGB(0, 0, 0)
a['8b'].AnchorPoint = Vector2.new(0.5, 0.5)
a['8b'].Image = 'rbxassetid://6014261993'
a['8b'].Size = UDim2.new(1, 25, 1, 25)
a['8b'].BackgroundTransparency = 1
a['8b'].Name = 'DropShadow'
a['8b'].Position = UDim2.new(0.5, 0, 0.5, 0)
a['8c'] = Instance.new('CanvasGroup', a['8a'])
a['8c'].BorderSizePixel = 0
a['8c'].BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a['8c'].Size = UDim2.new(1, 0, 1, 0)
a['8c'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['8c'].Name = 'Slider'
a['8d'] = Instance.new('UICorner', a['8c'])
a['8d'].CornerRadius = UDim.new(0, 5)
a['8e'] = Instance.new('UIStroke', a['8c'])
a['8e'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['8e'].Thickness = 1.5
a['8e'].Color = Color3.fromRGB(61, 61, 75)
a['8f'] = Instance.new('UIPadding', a['8c'])
a['8f'].PaddingTop = UDim.new(0, 2)
a['8f'].PaddingRight = UDim.new(0, 2)
a['8f'].PaddingLeft = UDim.new(0, 2)
a['8f'].PaddingBottom = UDim.new(0, 2)
a['90'] = Instance.new('TextButton', a['8c'])
a['90'].BorderSizePixel = 0
a['90'].TextSize = 14
a['90'].AutoButtonColor = false
a['90'].TextColor3 = Color3.fromRGB(0, 0, 0)
a['90'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['90'].FontFace = Font.new('rbxasset://fonts/families/SourceSansPro.json', Enum.FontWeight.Regular, Enum.FontStyle.Normal)
a['90'].BackgroundTransparency = 1
a['90'].Size = UDim2.new(1, 0, 1, 0)
a['90'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['90'].Text = ''
a['90'].Name = 'Trigger'
a['91'] = Instance.new('ImageButton', a['8c'])
a['91'].Active = false
a['91'].Interactable = false
a['91'].BorderSizePixel = 0
a['91'].AutoButtonColor = false
a['91'].BackgroundTransparency = 1
a['91'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['91'].Selectable = false
a['91'].AnchorPoint = Vector2.new(0, 0.5)
a['91'].Size = UDim2.new(0, 0, 1, 0)
a['91'].ClipsDescendants = true
a['91'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['91'].Name = 'Fill'
a['91'].Position = UDim2.new(0, 0, 0.5, 0)
a['92'] = Instance.new('UICorner', a['91'])
a['92'].CornerRadius = UDim.new(0, 4)
a['93'] = Instance.new('UIStroke', a['91'])
a['93'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['93'].Thickness = 1.5
a['93'].Color = Color3.fromRGB(11, 136, 214)
a['94'] = Instance.new('ImageButton', a['91'])
a['94'].Active = false
a['94'].Interactable = false
a['94'].BorderSizePixel = 0
a['94'].AutoButtonColor = false
a['94'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['94'].Selectable = false
a['94'].AnchorPoint = Vector2.new(0, 0.5)
a['94'].Size = UDim2.new(1, 0, 1, 0)
a['94'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['94'].Name = 'BackgroundGradient'
a['94'].Position = UDim2.new(0, 0, 0.5, 0)
a['95'] = Instance.new('UICorner', a['94'])
a['95'].CornerRadius = UDim.new(0, 4)
a['96'] = Instance.new('UIGradient', a['94'])
a['96'].Enabled = false
a['96'].Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a['97'] = Instance.new('UIGradient', a['94'])
a['97'].Enabled = false
a['97'].Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a['98'] = Instance.new('UIGradient', a['94'])
a['98'].Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a['99'] = Instance.new('TextLabel', a['8a'])
a['99'].TextWrapped = true
a['99'].Interactable = false
a['99'].ZIndex = 2
a['99'].BorderSizePixel = 0
a['99'].TextSize = 14
a['99'].TextXAlignment = Enum.TextXAlignment.Left
a['99'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['99'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Bold, Enum.FontStyle.Normal)
a['99'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['99'].BackgroundTransparency = 1
a['99'].RichText = true
a['99'].AnchorPoint = Vector2.new(0.5, 0.5)
a['99'].Size = UDim2.new(1, - 15, 1, 0)
a['99'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['99'].Text = '0'
a['99'].Name = 'ValueText'
a['99'].Position = UDim2.new(0.5, 0, 0.5, 0)
a['9a'] = Instance.new('Frame', a['41'])
a['9a'].Visible = false
a['9a'].BorderSizePixel = 0
a['9a'].BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a['9a'].AutomaticSize = Enum.AutomaticSize.Y
a['9a'].Size = UDim2.new(1, 0, 0, 35)
a['9a'].Position = UDim2.new(- 3.75E-2, 0, 0.38434, 0)
a['9a'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['9a'].Name = 'TextBox'
a['9b'] = Instance.new('UICorner', a['9a'])
a['9b'].CornerRadius = UDim.new(0, 6)
a['9c'] = Instance.new('UIStroke', a['9a'])
a['9c'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['9c'].Thickness = 1.5
a['9c'].Color = Color3.fromRGB(61, 61, 75)
a['9d'] = Instance.new('TextLabel', a['9a'])
a['9d'].TextWrapped = true
a['9d'].Interactable = false
a['9d'].BorderSizePixel = 0
a['9d'].TextSize = 16
a['9d'].TextXAlignment = Enum.TextXAlignment.Left
a['9d'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['9d'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Bold, Enum.FontStyle.Normal)
a['9d'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['9d'].BackgroundTransparency = 1
a['9d'].Size = UDim2.new(1, 0, 0, 15)
a['9d'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['9d'].Text = 'Input Textbox'
a['9d'].AutomaticSize = Enum.AutomaticSize.Y
a['9d'].Name = 'Title'
a['9e'] = Instance.new('UIPadding', a['9a'])
a['9e'].PaddingTop = UDim.new(0, 10)
a['9e'].PaddingRight = UDim.new(0, 10)
a['9e'].PaddingLeft = UDim.new(0, 10)
a['9e'].PaddingBottom = UDim.new(0, 10)
a['9f'] = Instance.new('UIListLayout', a['9a'])
a['9f'].Padding = UDim.new(0, 10)
a['9f'].SortOrder = Enum.SortOrder.LayoutOrder
a.a0 = Instance.new('TextLabel', a['9a'])
a.a0.TextWrapped = true
a.a0.Interactable = false
a.a0.BorderSizePixel = 0
a.a0.TextSize = 16
a.a0.TextXAlignment = Enum.TextXAlignment.Left
a.a0.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.a0.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a.a0.TextColor3 = Color3.fromRGB(197, 204, 219)
a.a0.BackgroundTransparency = 1
a.a0.Size = UDim2.new(1, 0, 0, 15)
a.a0.Visible = false
a.a0.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.a0.Text = [[Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus placerat lacus in enim congue, fermentum euismod leo ultricies. Nulla sodales. ]]
a.a0.LayoutOrder = 1
a.a0.AutomaticSize = Enum.AutomaticSize.Y
a.a0.Name = 'Description'
a.a1 = Instance.new('Frame', a['9a'])
a.a1.ZIndex = 0
a.a1.BorderSizePixel = 0
a.a1.AutomaticSize = Enum.AutomaticSize.Y
a.a1.Size = UDim2.new(1, 0, 0, 25)
a.a1.Name = 'BoxFrame'
a.a1.LayoutOrder = 2
a.a1.BackgroundTransparency = 1
a.a2 = Instance.new('ImageLabel', a.a1)
a.a2.ZIndex = 0
a.a2.BorderSizePixel = 0
a.a2.SliceCenter = Rect.new(49, 49, 450, 450)
a.a2.ScaleType = Enum.ScaleType.Slice
a.a2.ImageTransparency = 0.75
a.a2.ImageColor3 = Color3.fromRGB(0, 0, 0)
a.a2.AnchorPoint = Vector2.new(0.5, 0.5)
a.a2.Image = 'rbxassetid://6014261993'
a.a2.Size = UDim2.new(1, 35, 1, 30)
a.a2.BackgroundTransparency = 1
a.a2.Name = 'DropShadow'
a.a2.Position = UDim2.new(0.5, 0, 0.5, 0)
a.a3 = Instance.new('Frame', a.a1)
a.a3.BorderSizePixel = 0
a.a3.BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a.a3.AutomaticSize = Enum.AutomaticSize.Y
a.a3.Size = UDim2.new(1, 0, 0, 25)
a.a3.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.a4 = Instance.new('UICorner', a.a3)
a.a4.CornerRadius = UDim.new(0, 5)
a.a5 = Instance.new('UIStroke', a.a3)
a.a5.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a.a5.Thickness = 1.5
a.a5.Color = Color3.fromRGB(61, 61, 75)
a.a6 = Instance.new('UIListLayout', a.a3)
a.a6.HorizontalAlignment = Enum.HorizontalAlignment.Center
a.a6.Padding = UDim.new(0, 5)
a.a6.VerticalAlignment = Enum.VerticalAlignment.Center
a.a6.SortOrder = Enum.SortOrder.LayoutOrder
a.a7 = Instance.new('TextBox', a.a3)
a.a7.TextXAlignment = Enum.TextXAlignment.Left
a.a7.PlaceholderColor3 = Color3.fromRGB(140, 140, 140)
a.a7.BorderSizePixel = 0
a.a7.TextWrapped = true
a.a7.TextTruncate = Enum.TextTruncate.AtEnd
a.a7.TextSize = 14
a.a7.TextColor3 = Color3.fromRGB(197, 204, 219)
a.a7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.a7.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a.a7.AutomaticSize = Enum.AutomaticSize.Y
a.a7.ClipsDescendants = true
a.a7.PlaceholderText = 'Input here...'
a.a7.Size = UDim2.new(1, 0, 0, 25)
a.a7.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.a7.Text = ''
a.a7.BackgroundTransparency = 1
a.a8 = Instance.new('UIPadding', a.a7)
a.a8.PaddingTop = UDim.new(0, 5)
a.a8.PaddingRight = UDim.new(0, 10)
a.a8.PaddingLeft = UDim.new(0, 10)
a.a8.PaddingBottom = UDim.new(0, 5)
a.a9 = Instance.new('ImageButton', a['41'])
a.a9.BorderSizePixel = 0
a.a9.AutoButtonColor = false
a.a9.Visible = false
a.a9.BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a.a9.Selectable = false
a.a9.AutomaticSize = Enum.AutomaticSize.Y
a.a9.Size = UDim2.new(1, 0, 0, 35)
a.a9.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.a9.Name = 'Dropdown'
a.a9.Position = UDim2.new(- 3.75E-2, 0, 0.38434, 0)
a.aa = Instance.new('UICorner', a.a9)
a.aa.CornerRadius = UDim.new(0, 6)
a.ab = Instance.new('UIStroke', a.a9)
a.ab.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a.ab.Thickness = 1.5
a.ab.Color = Color3.fromRGB(61, 61, 75)
a.ac = Instance.new('TextLabel', a.a9)
a.ac.TextWrapped = true
a.ac.BorderSizePixel = 0
a.ac.TextSize = 16
a.ac.TextXAlignment = Enum.TextXAlignment.Left
a.ac.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.ac.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a.ac.TextColor3 = Color3.fromRGB(197, 204, 219)
a.ac.BackgroundTransparency = 1
a.ac.Size = UDim2.new(1, 0, 0, 15)
a.ac.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.ac.Text = 'Dropdown'
a.ac.Name = 'Title'
a.ac.Position = UDim2.new(0.03135, 0, 0, 0)
a.ad = Instance.new('ImageButton', a.ac)
a.ad.BorderSizePixel = 0
a.ad.AutoButtonColor = false
a.ad.BackgroundTransparency = 1
a.ad.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.ad.ImageColor3 = Color3.fromRGB(197, 204, 219)
a.ad.AnchorPoint = Vector2.new(1, 0.5)
a.ad.Image = 'rbxassetid://77563793724007'
a.ad.Size = UDim2.new(0, 23, 0, 23)
a.ad.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.ad.Name = 'ClickIcon'
a.ad.Position = UDim2.new(1, 0, 0.5, 0)
a.ae = Instance.new('ImageButton', a.ac)
a.ae.Active = false
a.ae.BorderSizePixel = 0
a.ae.BackgroundTransparency = 1
a.ae.Selectable = false
a.ae.ZIndex = 0
a.ae.AnchorPoint = Vector2.new(1, 0.5)
a.ae.AutomaticSize = Enum.AutomaticSize.X
a.ae.Size = UDim2.new(0, 20, 0, 20)
a.ae.Name = 'BoxFrame'
a.ae.Position = UDim2.new(1, - 33, 0.5, 0)
a.af = Instance.new('ImageLabel', a.ae)
a.af.Interactable = false
a.af.ZIndex = 0
a.af.BorderSizePixel = 0
a.af.SliceCenter = Rect.new(49, 49, 450, 450)
a.af.ScaleType = Enum.ScaleType.Slice
a.af.ImageTransparency = 0.75
a.af.AutomaticSize = Enum.AutomaticSize.X
a.af.ImageColor3 = Color3.fromRGB(0, 0, 0)
a.af.AnchorPoint = Vector2.new(0.5, 0.5)
a.af.Image = 'rbxassetid://6014261993'
a.af.Size = UDim2.new(1, 28, 1, 28)
a.af.Visible = false
a.af.BackgroundTransparency = 1
a.af.Name = 'DropShadow'
a.af.Position = UDim2.new(0.5, 0, 0.5, 0)
a.b0 = Instance.new('ImageButton', a.ae)
a.b0.BorderSizePixel = 0
a.b0.AutoButtonColor = false
a.b0.BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a.b0.Selectable = false
a.b0.AnchorPoint = Vector2.new(0.5, 0.5)
a.b0.AutomaticSize = Enum.AutomaticSize.X
a.b0.Size = UDim2.new(0, 20, 0, 20)
a.b0.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.b0.Name = 'Trigger'
a.b0.Position = UDim2.new(0.5, 0, 0.5, 0)
a.b1 = Instance.new('UICorner', a.b0)
a.b1.CornerRadius = UDim.new(0, 5)
a.b2 = Instance.new('UIStroke', a.b0)
a.b2.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a.b2.Thickness = 1.5
a.b2.Color = Color3.fromRGB(61, 61, 75)
a.b3 = Instance.new('UIListLayout', a.b0)
a.b3.Padding = UDim.new(0, 5)
a.b3.VerticalAlignment = Enum.VerticalAlignment.Center
a.b3.SortOrder = Enum.SortOrder.LayoutOrder
a.b4 = Instance.new('TextLabel', a.b0)
a.b4.TextWrapped = true
a.b4.Interactable = false
a.b4.BorderSizePixel = 0
a.b4.TextSize = 16
a.b4.TextScaled = true
a.b4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.b4.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a.b4.TextColor3 = Color3.fromRGB(197, 204, 219)
a.b4.BackgroundTransparency = 1
a.b4.AnchorPoint = Vector2.new(0, 0.5)
a.b4.Size = UDim2.new(0, 15, 0, 14)
a.b4.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.b4.Text = ''
a.b4.AutomaticSize = Enum.AutomaticSize.X
a.b4.Name = 'Title'
a.b4.Position = UDim2.new(- 3.45E-3, 0, 0.5, 0)
a.b5 = Instance.new('UIPadding', a.b0)
a.b5.PaddingRight = UDim.new(0, 5)
a.b5.PaddingLeft = UDim.new(0, 5)
a.b6 = Instance.new('UIPadding', a.a9)
a.b6.PaddingTop = UDim.new(0, 10)
a.b6.PaddingRight = UDim.new(0, 10)
a.b6.PaddingLeft = UDim.new(0, 10)
a.b6.PaddingBottom = UDim.new(0, 10)
a.b7 = Instance.new('UIListLayout', a.a9)
a.b7.Padding = UDim.new(0, 5)
a.b7.SortOrder = Enum.SortOrder.LayoutOrder
a.b8 = Instance.new('TextLabel', a.a9)
a.b8.TextWrapped = true
a.b8.Interactable = false
a.b8.BorderSizePixel = 0
a.b8.TextSize = 16
a.b8.TextXAlignment = Enum.TextXAlignment.Left
a.b8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.b8.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a.b8.TextColor3 = Color3.fromRGB(197, 204, 219)
a.b8.BackgroundTransparency = 1
a.b8.Size = UDim2.new(1, 0, 0, 15)
a.b8.Visible = false
a.b8.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.b8.Text = [[Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus placerat lacus in enim congue, fermentum euismod leo ultricies. Nulla sodales. ]]
a.b8.LayoutOrder = 1
a.b8.AutomaticSize = Enum.AutomaticSize.Y
a.b8.Name = 'Description'
a.b9 = Instance.new('UIGradient', a.a9)
a.b9.Enabled = false
a.b9.Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a.ba = Instance.new('UIGradient', a.a9)
a.ba.Enabled = false
a.ba.Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a.bb = Instance.new('UIGradient', a.a9)
a.bb.Enabled = false
a.bb.Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a.bc = Instance.new('Folder', a['41'])
a.bc.Name = 'DropdownList'
a.bd = Instance.new('ScrollingFrame', a.bc)
a.bd.Visible = false
a.bd.Active = true
a.bd.ScrollingDirection = Enum.ScrollingDirection.Y
a.bd.BorderSizePixel = 0
a.bd.CanvasSize = UDim2.new(0, 0, 0, 0)
a.bd.ElasticBehavior = Enum.ElasticBehavior.Never
a.bd.TopImage = 'rbxasset://textures/ui/Scroll/scroll-middle.png'
a.bd.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.bd.Name = 'DropdownItems'
a.bd.Selectable = false
a.bd.BottomImage = 'rbxasset://textures/ui/Scroll/scroll-middle.png'
a.bd.AutomaticCanvasSize = Enum.AutomaticSize.Y
a.bd.Size = UDim2.new(1, 0, 1, - 50)
a.bd.ScrollBarImageColor3 = Color3.fromRGB(99, 106, 122)
a.bd.Position = UDim2.new(0, 0, 0, 50)
a.bd.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.bd.ScrollBarThickness = 5
a.bd.BackgroundTransparency = 1
a.be = Instance.new('UIListLayout', a.bd)
a.be.Padding = UDim.new(0, 15)
a.be.SortOrder = Enum.SortOrder.LayoutOrder
a.bf = Instance.new('UIPadding', a.bd)
a.bf.PaddingTop = UDim.new(0, 2)
a.bf.PaddingRight = UDim.new(0, 10)
a.bf.PaddingLeft = UDim.new(0, 10)
a.bf.PaddingBottom = UDim.new(0, 10)
a.c0 = Instance.new('ScrollingFrame', a.bc)
a.c0.Visible = false
a.c0.Active = true
a.c0.ScrollingDirection = Enum.ScrollingDirection.Y
a.c0.BorderSizePixel = 0
a.c0.CanvasSize = UDim2.new(0, 0, 0, 0)
a.c0.ElasticBehavior = Enum.ElasticBehavior.Never
a.c0.TopImage = 'rbxasset://textures/ui/Scroll/scroll-middle.png'
a.c0.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.c0.Name = 'DropdownItemsSearch'
a.c0.Selectable = false
a.c0.BottomImage = 'rbxasset://textures/ui/Scroll/scroll-middle.png'
a.c0.AutomaticCanvasSize = Enum.AutomaticSize.Y
a.c0.Size = UDim2.new(1, 0, 1, - 50)
a.c0.ScrollBarImageColor3 = Color3.fromRGB(99, 106, 122)
a.c0.Position = UDim2.new(0, 0, 0, 50)
a.c0.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.c0.ScrollBarThickness = 5
a.c0.BackgroundTransparency = 1
a.c1 = Instance.new('UIListLayout', a.c0)
a.c1.Padding = UDim.new(0, 15)
a.c1.SortOrder = Enum.SortOrder.LayoutOrder
a.c2 = Instance.new('UIPadding', a.c0)
a.c2.PaddingTop = UDim.new(0, 2)
a.c2.PaddingRight = UDim.new(0, 10)
a.c2.PaddingLeft = UDim.new(0, 10)
a.c2.PaddingBottom = UDim.new(0, 10)
a.c3 = Instance.new('ImageButton', a['41'])
a.c3.BorderSizePixel = 0
a.c3.AutoButtonColor = false
a.c3.Visible = false
a.c3.BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a.c3.Selectable = false
a.c3.AutomaticSize = Enum.AutomaticSize.Y
a.c3.Size = UDim2.new(1, 0, 0, 35)
a.c3.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.c3.Name = 'DropdownButton'
a.c3.Position = UDim2.new(0, 0, 0.384, 0)
a.c4 = Instance.new('UICorner', a.c3)
a.c4.CornerRadius = UDim.new(0, 6)
a.c5 = Instance.new('Frame', a.c3)
a.c5.BorderSizePixel = 0
a.c5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.c5.AutomaticSize = Enum.AutomaticSize.Y
a.c5.Size = UDim2.new(1, 0, 0, 35)
a.c5.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.c5.BackgroundTransparency = 1
a.c6 = Instance.new('UIListLayout', a.c5)
a.c6.Padding = UDim.new(0, 5)
a.c6.SortOrder = Enum.SortOrder.LayoutOrder
a.c7 = Instance.new('UIPadding', a.c5)
a.c7.PaddingTop = UDim.new(0, 10)
a.c7.PaddingRight = UDim.new(0, 10)
a.c7.PaddingLeft = UDim.new(0, 10)
a.c7.PaddingBottom = UDim.new(0, 10)
a.c8 = Instance.new('TextLabel', a.c5)
a.c8.TextWrapped = true
a.c8.Interactable = false
a.c8.BorderSizePixel = 0
a.c8.TextSize = 16
a.c8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.c8.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a.c8.TextColor3 = Color3.fromRGB(197, 204, 219)
a.c8.BackgroundTransparency = 1
a.c8.Size = UDim2.new(1, 0, 0, 15)
a.c8.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.c8.Text = 'Button'
a.c8.Name = 'Title'
a.c9 = Instance.new('TextLabel', a.c5)
a.c9.TextWrapped = true
a.c9.Interactable = false
a.c9.BorderSizePixel = 0
a.c9.TextSize = 16
a.c9.TextXAlignment = Enum.TextXAlignment.Left
a.c9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.c9.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a.c9.TextColor3 = Color3.fromRGB(197, 204, 219)
a.c9.BackgroundTransparency = 1
a.c9.Size = UDim2.new(1, 0, 0, 15)
a.c9.Visible = false
a.c9.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.c9.Text = [[Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus placerat lacus in enim congue, fermentum euismod leo ultricies. Nulla sodales. ]]
a.c9.LayoutOrder = 1
a.c9.AutomaticSize = Enum.AutomaticSize.Y
a.c9.Name = 'Description'
a.ca = Instance.new('UIGradient', a.c5)
a.ca.Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a.cb = Instance.new('UIGradient', a.c5)
a.cb.Enabled = false
a.cb.Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a.cc = Instance.new('UIGradient', a.c5)
a.cc.Enabled = false
a.cc.Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a.cd = Instance.new('UICorner', a.c5)
a.cd.CornerRadius = UDim.new(0, 6)
a.ce = Instance.new('UIStroke', a.c3)
a.ce.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a.ce.Thickness = 1.5
a.ce.Color = Color3.fromRGB(61, 61, 75)
a.cf = Instance.new('Frame', a['41'])
a.cf.Visible = false
a.cf.BorderSizePixel = 0
a.cf.BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a.cf.AutomaticSize = Enum.AutomaticSize.Y
a.cf.Size = UDim2.new(1, 0, 0, 35)
a.cf.Position = UDim2.new(- 3.75E-2, 0, 0.38434, 0)
a.cf.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.cf.Name = 'Code'
a.d0 = Instance.new('UICorner', a.cf)
a.d0.CornerRadius = UDim.new(0, 6)
a.d1 = Instance.new('UIStroke', a.cf)
a.d1.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a.d1.Thickness = 1.5
a.d1.Color = Color3.fromRGB(61, 61, 75)
a.d2 = Instance.new('TextLabel', a.cf)
a.d2.TextWrapped = true
a.d2.Interactable = false
a.d2.BorderSizePixel = 0
a.d2.TextSize = 16
a.d2.TextXAlignment = Enum.TextXAlignment.Left
a.d2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.d2.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Bold, Enum.FontStyle.Normal)
a.d2.TextColor3 = Color3.fromRGB(197, 204, 219)
a.d2.BackgroundTransparency = 1
a.d2.Size = UDim2.new(1, 0, 0, 15)
a.d2.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.d2.Text = 'Title'
a.d2.AutomaticSize = Enum.AutomaticSize.Y
a.d2.Name = 'Title'
a.d3 = Instance.new('UIPadding', a.cf)
a.d3.PaddingTop = UDim.new(0, 10)
a.d3.PaddingRight = UDim.new(0, 10)
a.d3.PaddingLeft = UDim.new(0, 10)
a.d3.PaddingBottom = UDim.new(0, 10)
a.d4 = Instance.new('UIListLayout', a.cf)
a.d4.Padding = UDim.new(0, 5)
a.d4.SortOrder = Enum.SortOrder.LayoutOrder
a.d5 = Instance.new('TextBox', a.cf)
a.d5.Name = 'Code'
a.d5.TextXAlignment = Enum.TextXAlignment.Left
a.d5.BorderSizePixel = 0
a.d5.TextEditable = false
a.d5.TextWrapped = true
a.d5.TextSize = 16
a.d5.TextColor3 = Color3.fromRGB(197, 204, 219)
a.d5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.d5.FontFace = Font.new('rbxasset://fonts/families/Inconsolata.json', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a.d5.AutomaticSize = Enum.AutomaticSize.Y
a.d5.Selectable = false
a.d5.MultiLine = true
a.d5.ClearTextOnFocus = false
a.d5.Size = UDim2.new(1, 0, 0, 15)
a.d5.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.d5.Text = 'print("Hello World!")'
a.d5.LayoutOrder = 1
a.d5.BackgroundTransparency = 1
a.d6 = Instance.new('Frame', a['41'])
a.d6.Visible = false
a.d6.BorderSizePixel = 0
a.d6.BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a.d6.AutomaticSize = Enum.AutomaticSize.Y
a.d6.Size = UDim2.new(1, 0, 0, 35)
a.d6.Position = UDim2.new(0, 0, 0.43728, 0)
a.d6.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.d6.Name = 'Section'
a.d6.BackgroundTransparency = 1
a.d7 = Instance.new('ImageButton', a.d6)
a.d7.BorderSizePixel = 0
a.d7.AutoButtonColor = false
a.d7.BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a.d7.Selectable = false
a.d7.AutomaticSize = Enum.AutomaticSize.Y
a.d7.Size = UDim2.new(1, 0, 0, 35)
a.d7.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.d7.Name = 'Button'
a.d8 = Instance.new('UICorner', a.d7)
a.d8.CornerRadius = UDim.new(0, 6)
a.d9 = Instance.new('UIStroke', a.d7)
a.d9.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a.d9.Thickness = 1.5
a.d9.Color = Color3.fromRGB(61, 61, 75)
a.da = Instance.new('TextLabel', a.d7)
a.da.TextWrapped = true
a.da.Interactable = false
a.da.BorderSizePixel = 0
a.da.TextSize = 16
a.da.TextXAlignment = Enum.TextXAlignment.Left
a.da.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.da.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a.da.TextColor3 = Color3.fromRGB(197, 204, 219)
a.da.BackgroundTransparency = 1
a.da.Size = UDim2.new(1, 0, 0, 15)
a.da.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.da.Text = 'Section'
a.da.Name = 'Title'
a.db = Instance.new('ImageButton', a.da)
a.db.BorderSizePixel = 0
a.db.AutoButtonColor = false
a.db.BackgroundTransparency = 1
a.db.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.db.ImageColor3 = Color3.fromRGB(197, 204, 219)
a.db.AnchorPoint = Vector2.new(1, 0.5)
a.db.Image = 'rbxassetid://120292618616139'
a.db.Size = UDim2.new(0, 23, 0, 23)
a.db.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.db.Name = 'Arrow'
a.db.Position = UDim2.new(1, 0, 0.5, 0)
a.dc = Instance.new('UIPadding', a.d7)
a.dc.PaddingTop = UDim.new(0, 10)
a.dc.PaddingRight = UDim.new(0, 10)
a.dc.PaddingLeft = UDim.new(0, 10)
a.dc.PaddingBottom = UDim.new(0, 10)
a.dd = Instance.new('UIListLayout', a.d7)
a.dd.Padding = UDim.new(0, 5)
a.dd.SortOrder = Enum.SortOrder.LayoutOrder
a.de = Instance.new('TextLabel', a.d7)
a.de.TextWrapped = true
a.de.Interactable = false
a.de.BorderSizePixel = 0
a.de.TextSize = 16
a.de.TextXAlignment = Enum.TextXAlignment.Left
a.de.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.de.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Medium, Enum.FontStyle.Normal)
a.de.TextColor3 = Color3.fromRGB(197, 204, 219)
a.de.BackgroundTransparency = 1
a.de.Size = UDim2.new(1, 0, 0, 15)
a.de.Visible = false
a.de.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.de.Text = [[Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus placerat lacus in enim congue, fermentum euismod leo ultricies. Nulla sodales. ]]
a.de.LayoutOrder = 1
a.de.AutomaticSize = Enum.AutomaticSize.Y
a.de.Name = 'Description'
a.df = Instance.new('UIGradient', a.d7)
a.df.Enabled = false
a.df.Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a.e0 = Instance.new('UIGradient', a.d7)
a.e0.Enabled = false
a.e0.Transparency = NumberSequence.new{
    NumberSequenceKeypoint.new(0, 1),
    NumberSequenceKeypoint.new(1, 1)
}
a.e0.Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a.e1 = Instance.new('UIGradient', a.d7)
a.e1.Enabled = false
a.e1.Color = ColorSequence.new{
    ColorSequenceKeypoint.new(0, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.16, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(0.32, Color3.fromRGB(0, 158, 255)),
    ColorSequenceKeypoint.new(0.54, Color3.fromRGB(0, 5, 255)),
    ColorSequenceKeypoint.new(0.782, Color3.fromRGB(0, 235, 255)),
    ColorSequenceKeypoint.new(1, Color3.fromRGB(0, 158, 255))
}
a.e2 = Instance.new('UIStroke', a.d7)
a.e2.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a.e2.Thickness = 1.5
a.e2.Color = Color3.fromRGB(61, 61, 75)
a.e3 = Instance.new('Frame', a.d6)
a.e3.Visible = false
a.e3.BorderSizePixel = 0
a.e3.BackgroundColor3 = Color3.fromRGB(207, 222, 255)
a.e3.AutomaticSize = Enum.AutomaticSize.Y
a.e3.Size = UDim2.new(1, 0, 0, 30)
a.e3.Position = UDim2.new(0, 0, 0, 35)
a.e3.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.e3.BackgroundTransparency = 1
a.e4 = Instance.new('UIListLayout', a.e3)
a.e4.HorizontalAlignment = Enum.HorizontalAlignment.Center
a.e4.Padding = UDim.new(0, 10)
a.e4.SortOrder = Enum.SortOrder.LayoutOrder
a.e5 = Instance.new('UIPadding', a.e3)
a.e5.PaddingTop = UDim.new(0, 10)
a.e5.PaddingRight = UDim.new(0, 8)
a.e5.PaddingLeft = UDim.new(0, 8)
a.e6 = Instance.new('Frame', a.e3)
a.e6.BorderSizePixel = 0
a.e6.BackgroundColor3 = Color3.fromRGB(61, 61, 75)
a.e6.Size = UDim2.new(1, 0, 0, 3)
a.e6.BorderColor3 = Color3.fromRGB(61, 61, 75)
a.e6.Name = 'Divider'
a.e7 = Instance.new('Folder', a['41'])
a.e7.Name = 'DialogElements'
a.e8 = Instance.new('Frame', a.e7)
a.e8.Visible = false
a.e8.BorderSizePixel = 0
a.e8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
a.e8.Size = UDim2.new(1, 0, 1, 0)
a.e8.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.e8.Name = 'DarkOverlayDialog'
a.e8.BackgroundTransparency = 0.6
a.e9 = Instance.new('UICorner', a.e8)
a.e9.CornerRadius = UDim.new(0, 10)
a.ea = Instance.new('Frame', a.e7)
a.ea.Visible = false
a.ea.ZIndex = 4
a.ea.BorderSizePixel = 0
a.ea.BackgroundColor3 = Color3.fromRGB(32, 35, 41)
a.ea.AnchorPoint = Vector2.new(0.5, 0.5)
a.ea.ClipsDescendants = true
a.ea.AutomaticSize = Enum.AutomaticSize.Y
a.ea.Size = UDim2.new(0, 250, 0, 0)
a.ea.Position = UDim2.new(0.5, 0, 0.5, 0)
a.ea.BorderColor3 = Color3.fromRGB(61, 61, 75)
a.ea.Name = 'Dialog'
a.eb = Instance.new('UICorner', a.ea)
a.eb.CornerRadius = UDim.new(0, 6)
a.ec = Instance.new('UIStroke', a.ea)
a.ec.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a.ec.Thickness = 1.5
a.ec.Color = Color3.fromRGB(61, 61, 75)
a.ed = Instance.new('Frame', a.ea)
a.ed.BorderSizePixel = 0
a.ed.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.ed.AutomaticSize = Enum.AutomaticSize.Y
a.ed.Size = UDim2.new(1, 0, 0, 25)
a.ed.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.ed.Name = 'Title'
a.ed.BackgroundTransparency = 1
a.ee = Instance.new('TextLabel', a.ed)
a.ee.Interactable = false
a.ee.ZIndex = 0
a.ee.BorderSizePixel = 0
a.ee.TextSize = 20
a.ee.TextXAlignment = Enum.TextXAlignment.Left
a.ee.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.ee.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a.ee.TextColor3 = Color3.fromRGB(197, 204, 219)
a.ee.BackgroundTransparency = 1
a.ee.AnchorPoint = Vector2.new(0, 0.5)
a.ee.Size = UDim2.new(0, 0, 0, 20)
a.ee.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.ee.Text = ''
a.ee.LayoutOrder = 1
a.ee.AutomaticSize = Enum.AutomaticSize.XY
a.ee.Position = UDim2.new(- 5.455E-2, 12, 0.5, 0)
a.ef = Instance.new('UIListLayout', a.ed)
a.ef.Padding = UDim.new(0, 10)
a.ef.VerticalAlignment = Enum.VerticalAlignment.Center
a.ef.SortOrder = Enum.SortOrder.LayoutOrder
a.ef.FillDirection = Enum.FillDirection.Horizontal
a.f0 = Instance.new('UIPadding', a.ed)
a.f0.PaddingTop = UDim.new(0, 5)
a.f0.PaddingRight = UDim.new(0, 15)
a.f0.PaddingLeft = UDim.new(0, 15)
a.f0.PaddingBottom = UDim.new(0, 5)
a.f1 = Instance.new('ImageButton', a.ed)
a.f1.BorderSizePixel = 0
a.f1.Visible = false
a.f1.BackgroundTransparency = 1
a.f1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.f1.ImageColor3 = Color3.fromRGB(197, 204, 219)
a.f1.Size = UDim2.new(0, 33, 0, 25)
a.f1.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.f1.Name = 'Icon'
a.f1.Position = UDim2.new(0, 0, 0.2125, 0)
a.f2 = Instance.new('UIAspectRatioConstraint', a.f1)
a.f3 = Instance.new('UIListLayout', a.ea)
a.f3.HorizontalAlignment = Enum.HorizontalAlignment.Center
a.f3.SortOrder = Enum.SortOrder.LayoutOrder
a.f4 = Instance.new('Frame', a.ea)
a.f4.Visible = false
a.f4.ZIndex = 2
a.f4.BorderSizePixel = 0
a.f4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.f4.AutomaticSize = Enum.AutomaticSize.Y
a.f4.Size = UDim2.new(1, 0, 0, 0)
a.f4.Position = UDim2.new(0, 0, 0.21886, 0)
a.f4.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.f4.Name = 'Content'
a.f4.BackgroundTransparency = 1
a.f5 = Instance.new('UIListLayout', a.f4)
a.f5.VerticalAlignment = Enum.VerticalAlignment.Center
a.f5.SortOrder = Enum.SortOrder.LayoutOrder
a.f6 = Instance.new('UIPadding', a.f4)
a.f6.PaddingTop = UDim.new(0, 5)
a.f6.PaddingRight = UDim.new(0, 15)
a.f6.PaddingLeft = UDim.new(0, 15)
a.f6.PaddingBottom = UDim.new(0, 5)
a.f7 = Instance.new('TextLabel', a.f4)
a.f7.TextWrapped = true
a.f7.Interactable = false
a.f7.BorderSizePixel = 0
a.f7.TextSize = 15
a.f7.TextXAlignment = Enum.TextXAlignment.Left
a.f7.TextYAlignment = Enum.TextYAlignment.Top
a.f7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.f7.FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a.f7.TextColor3 = Color3.fromRGB(145, 154, 173)
a.f7.BackgroundTransparency = 1
a.f7.Size = UDim2.new(1, 0, 0, 0)
a.f7.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.f7.Text = ''
a.f7.AutomaticSize = Enum.AutomaticSize.Y
a.f7.Position = UDim2.new(0, 0, 0.125, 0)
a.f8 = Instance.new('UIPadding', a.ea)
a.f8.PaddingTop = UDim.new(0, 10)
a.f8.PaddingBottom = UDim.new(0, 10)
a.f9 = Instance.new('Frame', a.ea)
a.f9.ZIndex = 3
a.f9.BorderSizePixel = 0
a.f9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.f9.AutomaticSize = Enum.AutomaticSize.Y
a.f9.Size = UDim2.new(1, 0, 0, 0)
a.f9.Position = UDim2.new(0, 0, 0.53017, 0)
a.f9.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.f9.Name = 'Buttons'
a.f9.BackgroundTransparency = 1
a.fa = Instance.new('UIListLayout', a.f9)
a.fa.HorizontalAlignment = Enum.HorizontalAlignment.Center
a.fa.Padding = UDim.new(0, 10)
a.fa.SortOrder = Enum.SortOrder.LayoutOrder
a.fb = Instance.new('UIPadding', a.f9)
a.fb.PaddingTop = UDim.new(0, 5)
a.fb.PaddingRight = UDim.new(0, 10)
a.fb.PaddingLeft = UDim.new(0, 10)
a.fc = Instance.new('Frame', a.e7)
a.fc.Visible = false
a.fc.BorderSizePixel = 0
a.fc.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a.fc.AnchorPoint = Vector2.new(0.5, 1)
a.fc.Size = UDim2.new(1, 0, 0, 30)
a.fc.Position = UDim2.new(0.5, 0, 0.327, 0)
a.fc.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.fc.Name = 'DialogButton'
a.fc.BackgroundTransparency = 1
a.fd = Instance.new('TextButton', a.fc)
a.fd.BorderSizePixel = 0
a.fd.AutoButtonColor = false
a.fd.BackgroundColor3 = Color3.fromRGB(43, 46, 53)
a.fd.Selectable = false
a.fd.AnchorPoint = Vector2.new(0.5, 0.5)
a.fd.Size = UDim2.new(1, 0, 1, 0)
a.fd.BorderColor3 = Color3.fromRGB(0, 0, 0)
a.fd.Name = 'Button'
a.fd.Position = UDim2.new(0.5, 0, 0.5, 0)
a.fe = Instance.new('UICorner', a.fd)
a.fe.CornerRadius = UDim.new(0, 5)
a.ff = Instance.new('UIStroke', a.fd)
a.ff.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a.ff.Thickness = 1.5
a.ff.Color = Color3.fromRGB(61, 61, 75)
a['100'] = Instance.new('UIListLayout', a.fd)
a['100'].HorizontalAlignment = Enum.HorizontalAlignment.Center
a['100'].Padding = UDim.new(0, 5)
a['100'].VerticalAlignment = Enum.VerticalAlignment.Center
a['100'].SortOrder = Enum.SortOrder.LayoutOrder
a['101'] = Instance.new('TextLabel', a.fd)
a['101'].TextWrapped = true
a['101'].Interactable = false
a['101'].BorderSizePixel = 0
a['101'].TextSize = 14
a['101'].TextScaled = true
a['101'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['101'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.Bold, Enum.FontStyle.Normal)
a['101'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['101'].BackgroundTransparency = 1
a['101'].Size = UDim2.new(1, 0, 0.45, 0)
a['101'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['101'].Text = ''
a['101'].Name = 'Label'
a['101'].Position = UDim2.new(0, 45, 0.083, 0)
a['102'] = Instance.new('Frame', a['1'])
a['102'].ZIndex = 10
a['102'].BorderSizePixel = 0
a['102'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['102'].AnchorPoint = Vector2.new(0.5, 0)
a['102'].Size = UDim2.new(0, 630, 1, 0)
a['102'].Position = UDim2.new(1, 0, 0, 0)
a['102'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['102'].Name = 'NotificationList'
a['102'].BackgroundTransparency = 1
a['103'] = Instance.new('UIListLayout', a['102'])
a['103'].Padding = UDim.new(0, 12)
a['103'].SortOrder = Enum.SortOrder.LayoutOrder
a['104'] = Instance.new('UIPadding', a['102'])
a['104'].PaddingTop = UDim.new(0, 10)
a['104'].PaddingRight = UDim.new(0, 40)
a['104'].PaddingLeft = UDim.new(0, 40)
a['105'] = Instance.new('Frame', a['1'])
a['105'].Visible = false
a['105'].ZIndex = 0
a['105'].BorderSizePixel = 2
a['105'].BackgroundColor3 = Color3.fromRGB(37, 40, 47)
a['105'].AnchorPoint = Vector2.new(0.5, 0.5)
a['105'].ClipsDescendants = true
a['105'].AutomaticSize = Enum.AutomaticSize.X
a['105'].Size = UDim2.new(0, 85, 0, 45)
a['105'].Position = UDim2.new(0.5, 0, 0, 45)
a['105'].BorderColor3 = Color3.fromRGB(61, 61, 75)
a['105'].Name = 'FloatIcon'
a['106'] = Instance.new('UICorner', a['105'])
a['106'].CornerRadius = UDim.new(0, 10)
a['107'] = Instance.new('UIStroke', a['105'])
a['107'].Transparency = 0.5
a['107'].ApplyStrokeMode = Enum.ApplyStrokeMode.Border
a['107'].Thickness = 1.5
a['107'].Color = Color3.fromRGB(95, 95, 117)
a['108'] = Instance.new('UIPadding', a['105'])
a['108'].PaddingTop = UDim.new(0, 8)
a['108'].PaddingRight = UDim.new(0, 10)
a['108'].PaddingLeft = UDim.new(0, 10)
a['108'].PaddingBottom = UDim.new(0, 8)
a['109'] = Instance.new('UIListLayout', a['105'])
a['109'].Padding = UDim.new(0, 8)
a['109'].VerticalAlignment = Enum.VerticalAlignment.Center
a['109'].SortOrder = Enum.SortOrder.LayoutOrder
a['109'].FillDirection = Enum.FillDirection.Horizontal
a['10a'] = Instance.new('ImageButton', a['105'])
a['10a'].Active = false
a['10a'].Interactable = false
a['10a'].BorderSizePixel = 0
a['10a'].AutoButtonColor = false
a['10a'].BackgroundTransparency = 1
a['10a'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['10a'].AnchorPoint = Vector2.new(0, 0.5)
a['10a'].Image = 'rbxassetid://113216930555884'
a['10a'].Size = UDim2.new(1, 0, 1, 0)
a['10a'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['10a'].Name = 'Icon'
a['10a'].Position = UDim2.new(0, 10, 0.5, 0)
a['10b'] = Instance.new('UIAspectRatioConstraint', a['10a'])
a['10c'] = Instance.new('TextLabel', a['105'])
a['10c'].Interactable = false
a['10c'].BorderSizePixel = 0
a['10c'].TextSize = 16
a['10c'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['10c'].FontFace = Font.new('rbxassetid://11702779517', Enum.FontWeight.SemiBold, Enum.FontStyle.Normal)
a['10c'].TextColor3 = Color3.fromRGB(197, 204, 219)
a['10c'].BackgroundTransparency = 1
a['10c'].AnchorPoint = Vector2.new(0.5, 0.5)
a['10c'].Size = UDim2.new(0, 20, 0, 20)
a['10c'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['10c'].Text = 'NatHub'
a['10c'].AutomaticSize = Enum.AutomaticSize.X
a['10c'].Position = UDim2.new(0.38615, 0, 0.53448, - 1)
a['10d'] = Instance.new('ImageButton', a['105'])
a['10d'].BorderSizePixel = 0
a['10d'].AutoButtonColor = false
a['10d'].BackgroundTransparency = 1
a['10d'].BackgroundColor3 = Color3.fromRGB(255, 255, 255)
a['10d'].ImageColor3 = Color3.fromRGB(197, 204, 219)
a['10d'].Selectable = false
a['10d'].AnchorPoint = Vector2.new(0, 0.5)
a['10d'].Image = 'rbxassetid://122219713887461'
a['10d'].Size = UDim2.new(0, 20, 0, 20)
a['10d'].BorderColor3 = Color3.fromRGB(0, 0, 0)
a['10d'].Name = 'Open'
a['10d'].Position = UDim2.new(0, 128, 0.5, 0)
a['10e'] = Instance.new('UIAspectRatioConstraint', a['10d'])
a['10f'] = Instance.new('UICorner', a['10d'])
local c, d = require, {}
local e = function(e)
    local f = d[e]
    if f then
        if not f.Required then
            f.Required = true
            f.Value = f.Closure()
        end
        return f.Value
    end
    return c(e)
end
d[a['3e'] ] = {
    Closure = function()
        local f, g = a['3e'], {}
        local h, i, j, k, l, m = e(f.IconModule), game:GetService'UserInputService', f.Parent, f.Parent.Templates, f.Parent.Window, f.Parent.FloatIcon
        k.Parent = nil
        l.Parent = nil
        m.Parent = nil
        local n, o, p, q = {
            Global = {
                Duration = 0.25,
                EasingStyle = Enum.EasingStyle.Quart,
                EasingDirection = Enum.EasingDirection.Out
            },
            Notification = {
                Duration = 0.5,
                EasingStyle = Enum.EasingStyle.Back,
                EasingDirection = Enum.EasingDirection.Out
            },
            PopupOpen = {
                Duration = 0.4,
                EasingStyle = Enum.EasingStyle.Back,
                EasingDirection = Enum.EasingDirection.Out
            },
            PopupClose = {
                Duration = 0.4,
                EasingStyle = Enum.EasingStyle.Back,
                EasingDirection = Enum.EasingDirection.In
            }
        }, function(n, o, p)
            local q = TweenInfo.new(p.Duration, p.EasingStyle or Enum.EasingStyle.Linear, p.EasingDirection or Enum.EasingDirection.Out)
            local r = game:GetService'TweenService':Create(n, q, o)
            r:Play()
            return r
        end, function(n, o)
            local p, q, r, s, t, u, v = {}, game:GetService'TweenService', true
            local w = function(w)
                local x = w.Position - u
                local y = UDim2.new(v.X.Scale, v.X.Offset + x.X, v.Y.Scale, v.Y.Offset + x.Y)
                q:Create(o, TweenInfo.new(0.2, Enum.EasingStyle.Quart), {
                    Position = y
                }):Play()
            end
            n.InputBegan:Connect(function(x)
                if r and x.UserInputType == Enum.UserInputType.MouseButton1 or x.UserInputType == Enum.UserInputType.Touch then
                    s = true
                    u = x.Position
                    v = o.Position
                    x.Changed:Connect(function()
                        if x.UserInputState == Enum.UserInputState.End then
                            s = false
                        end
                    end)
                end
            end)
            n.InputChanged:Connect(function(x)
                if r and x.UserInputType == Enum.UserInputType.MouseMovement or x.UserInputType == Enum.UserInputType.Touch then
                    t = x
                end
            end)
            i.InputChanged:Connect(function(x)
                if r and x == t and s then
                    w(x)
                end
            end)
            function p.SetAllowDragging(x, y)
                r = y
            end
            return p
        end, {}
        function g.CreateWindow(r, s)
            local t, u = {
                Title = s.Title,
                Icon = s.Icon,
                Version = s.Author,
                Folder = s.Folder,
                Size = s.Size,
                ToggleKey = s.ToggleKey or Enum.KeyCode.RightShift,
                LiveSearchDropdown = s.LiveSearchDropdown or false
            }, Instance.new'Folder'
            u.Parent = j
            j.Name = t.Title
            local v = m:Clone()
            v.Parent = u
            v.TextLabel.Text = t.Title
            v.Visible = false
            if not t.Icon:find'rbxassetid' then
                v.Icon.Image = h.Icon(t.Icon)[1] or t.Icon or ''
                v.Icon.ImageRectOffset = h.Icon(t.Icon)[2].ImageRectPosition or Vector2.new(0, 0)
                v.Icon.ImageRectSize = h.Icon(t.Icon)[2].ImageRectSize or Vector2.new(0, 0)
            else
                v.Icon.Image = t.Icon
            end
            local w = l:Clone()
            local x = w
            local y, z, A = x.TopFrame, x.TabButtons, x.Tabs
            w.Name = t.Title
            y.TextLabel.Text = t.Title .. ' - ' .. t.Version
            if not t.Icon:find'rbxassetid' then
                y.Icon.Image = h.Icon(t.Icon)[1] or t.Icon or ''
                y.Icon.ImageRectOffset = h.Icon(t.Icon)[2].ImageRectPosition or Vector2.new(0, 0)
                y.Icon.ImageRectSize = h.Icon(t.Icon)[2].ImageRectSize or Vector2.new(0, 0)
            else
                y.Icon.Image = t.Icon
            end
            w.Size = t.Size
            w.Visible = false
            w.Parent = u
            table.insert(q, w)
            local B, C, D = {}, {}
            local E, F, G = function(E, F, G, H)
                local I = {
                    Name = E,
                    TabObject = F,
                    TabButton = G,
                    HasIcon = H
                }
                B[E] = I
                table.insert(C, B[E])
            end, false
            local H, I = function(H, I)
                if I and F == false then
                    G = I
                    for J, K in w.DropdownSelection.Dropdowns:GetChildren() do
                        if K:IsA'Folder' then
                            K:FindFirstChild'DropdownItems'.Visible = false
                            K:FindFirstChild'DropdownItemsSearch'.Visible = false
                        end
                    end
                    w.DropdownSelection.TopBar.Title.Text = I
                    w.DropdownSelection.Dropdowns:FindFirstChild(I):FindFirstChild'DropdownItems'.Visible = true
                    w.DropdownSelection.Dropdowns:FindFirstChild(I):FindFirstChild'DropdownItemsSearch'.Visible = false
                end
                if H == true then
                    w.DropdownSelection.Size = UDim2.new(0, 0, 0, 0)
                    w.DarkOverlay.BackgroundTransparency = 1
                    w.DropdownSelection.Visible = true
                    w.DarkOverlay.Visible = true
                    w.DropdownSelection.Size = UDim2.new(0.728, 0, 0.684, 0)
                    o(w.DarkOverlay, {
                        BackgroundTransparency = 0.6
                    }, n.PopupOpen)
                    F = H
                elseif H == false then
                    w.DropdownSelection.Size = UDim2.new(0, 0, 0, 0)
                    local J = o(w.DarkOverlay, {
                        BackgroundTransparency = 1
                    }, n.PopupClose)
                    J.Completed:Wait()
                    w.DropdownSelection.Visible = false
                    w.DarkOverlay.Visible = false
                    F = H
                else
                    if F then
                        w.DropdownSelection.Size = UDim2.new(0, 0, 0, 0)
                        local J = o(w.DarkOverlay, {
                            BackgroundTransparency = 1
                        }, n.PopupClose)
                        J.Completed:Wait()
                        w.DropdownSelection.Visible = false
                        w.DarkOverlay.Visible = false
                        F = false
                    else
                        w.DropdownSelection.Size = UDim2.new(0, 0, 0, 0)
                        w.DarkOverlay.BackgroundTransparency = 1
                        w.DropdownSelection.Visible = true
                        w.DarkOverlay.Visible = true
                        w.DropdownSelection.Size = UDim2.new(0.728, 0, 0.684, 0)
                        o(w.DarkOverlay, {
                            BackgroundTransparency = 0.6
                        }, n.PopupOpen)
                        F = true
                    end
                end
            end, function(H)
                for I, J in pairs(B) do
                    if I ~= H then
                        J.TabObject.Visible = false
                        o(J.TabButton.TextLabel, {
                            Position = UDim2.new(0, 42, 0.5, 0),
                            Size = UDim2.new(0, 103, 0, 16),
                            TextTransparency = 0.5
                        }, n.Global)
                        o(J.TabButton.ImageButton, {
                            Position = UDim2.new(0, 12, 0, 18),
                            ImageTransparency = 0.5
                        }, n.Global)
                        o(J.TabButton.Bar, {
                            Size = UDim2.new(0, 5, 0, 0),
                            BackgroundTransparency = 1
                        }, n.Global)
                    elseif I == H then
                        D = H
                        J.TabObject.Visible = true
                        o(J.TabButton.TextLabel, {
                            Position = UDim2.new(0, 57, 0.5, 0),
                            Size = UDim2.new(0, 88, 0, 16),
                            TextTransparency = 0
                        }, n.Global)
                        o(J.TabButton.ImageButton, {
                            Position = UDim2.new(0, 25, 0, 18),
                            ImageTransparency = 0
                        }, n.Global)
                        o(J.TabButton.Bar, {
                            Size = UDim2.new(0, 5, 0, 25),
                            BackgroundTransparency = 0
                        }, n.Global)
                        local K = 0
                        for L, M in ipairs(J.TabObject:GetChildren()) do
                            if M:IsA'GuiObject' then
                                K = K + 1
                            end
                        end
                        if K == 0 then
                            A.NoObjectFoundText.Visible = true
                        else
                            A.NoObjectFoundText.Visible = false
                        end
                    end
                end
            end
            w.DropdownSelection.TopBar.Close.MouseButton1Click:Connect(function()
                H(false)
            end)
            local J = w.DropdownSelection.TopBar.BoxFrame.Frame.TextBox
            J:GetPropertyChangedSignal'Text':Connect(function()
                if not t.LiveSearchDropdown then
                    return
                end
                local K = w.DropdownSelection.Dropdowns:FindFirstChild(G)
                if string.gsub(J.Text, ' ', '') ~= '' then
                    if not K then
                        return
                    end
                    K:FindFirstChild'DropdownItems'.Visible = false
                    K:FindFirstChild'DropdownItemsSearch'.Visible = true
                    for L, M in K:FindFirstChild'DropdownItemsSearch':GetChildren() do
                        if M:IsA'GuiButton' then
                            if string.find(M.Name:lower(), J.Text:lower()) then
                                M.Visible = true
                            else
                                M.Visible = false
                            end
                        end
                    end
                else
                    K:FindFirstChild'DropdownItems'.Visible = true
                    K:FindFirstChild'DropdownItemsSearch'.Visible = false
                end
            end)
            J.FocusLost:Connect(function()
                if t.LiveSearchDropdown then
                    return
                end
                local K = w.DropdownSelection.Dropdowns:FindFirstChild(G)
                if string.gsub(J.Text, ' ', '') ~= '' then
                    if not K then
                        return
                    end
                    K:FindFirstChild'DropdownItems'.Visible = false
                    K:FindFirstChild'DropdownItemsSearch'.Visible = true
                    for L, M in K:FindFirstChild'DropdownItemsSearch':GetChildren() do
                        if M:IsA'GuiButton' then
                            if string.find(M.Name:lower(), J.Text:lower()) then
                                M.Visible = true
                            else
                                M.Visible = false
                            end
                        end
                    end
                else
                    K:FindFirstChild'DropdownItems'.Visible = true
                    K:FindFirstChild'DropdownItemsSearch'.Visible = false
                end
            end)
            function t.Tab(K, L)
                local M, N, O = {}, {
                    Title = L.Title,
                    Icon = L.Icon
                }, k.TabButton:Clone()
                O.Name = N.Title
                O.Parent = w.TabButtons.Lists
                O.Visible = true
                O.TextLabel.Text = N.Title
                O.ImageButton.Image = (h.Icon(N.Icon) and h.Icon(N.Icon)[1]) or N.Icon or ''
                O.ImageButton.ImageRectOffset = (h.Icon(N.Icon) and h.Icon(N.Icon)[2].ImageRectPosition) or Vector2.new(0, 0)
                O.ImageButton.ImageRectSize = (h.Icon(N.Icon) and h.Icon(N.Icon)[2].ImageRectSize) or Vector2.new(0, 0)
                local P = k.Tab:Clone()
                P.Name = N.Title
                P.Parent = w.Tabs
                P.Visible = false
                E(L.Title, P, O)
                if D == N.Title then
                    P.Visible = true
                    O.TextLabel.Position = UDim2.new(0, 57, 0.5, 0)
                    O.TextLabel.Size = UDim2.new(0, 88, 0, 16)
                    O.TextLabel.TextTransparency = 0
                    O.ImageButton.Position = UDim2.new(0, 25, 0, 18)
                    O.ImageButton.ImageTransparency = 0
                    O.Bar.Size = UDim2.new(0, 5, 0, 25)
                    O.Bar.BackgroundTransparency = 0
                else
                    O.TextLabel.Position = UDim2.new(0, 42, 0.5, 0)
                    O.TextLabel.Size = UDim2.new(0, 103, 0, 16)
                    O.TextLabel.TextTransparency = 0.5
                    O.ImageButton.Position = UDim2.new(0, 12, 0, 18)
                    O.ImageButton.ImageTransparency = 0.5
                    O.Bar.Size = UDim2.new(0, 5, 0, 0)
                    O.Bar.BackgroundTransparency = 1
                end
                O.MouseButton1Click:Connect(function()
                    I(N.Title)
                end)
                local Q, R = function()
                    local Q = {}
                    for R, S in pairs(P:GetChildren()) do
                        if S:IsA'GuiObject' then
                            table.insert(Q, S)
                        end
                    end
                    return Q
                end, P
                function M.Section(S, T)
                    local U, V = {
                        Title = T.Title,
                        State = T.Default or false,
                        TextXAlignment = T.TextXAlignment or 'Left'
                    }, k.Section:Clone()
                    V.Name = U.Title
                    V.Button.Title.Text = U.Title
                    V.Button.Title.TextXAlignment = Enum.TextXAlignment[U.TextXAlignment]
                    V.Visible = true
                    V.Parent = P
                    V.Button.MouseButton1Click:Connect(function()
                        if U.State == true then
                            V.Frame.Visible = false
                            o(V.Button.Title.Arrow, {
                                Rotation = 0
                            }, n.Global)
                            U.State = false
                        elseif U.State == false then
                            V.Frame.Visible = true
                            o(V.Button.Title.Arrow, {
                                Rotation = 90
                            }, n.Global)
                            U.State = true
                        end
                    end)
                    function U.SetTitle(W, X)
                        U.Title = X
                        V.Button.Title.Text = X
                    end
                    function U.Destroy(W)
                        R:Destroy()
                    end
                    R = V.Frame
                    return U
                end
                function M.Button(S, T)
                    local U, V, W = {}, {
                        Title = T.Title,
                        Desc = T.Desc,
                        Locked = T.Locked or false,
                        Callback = T.Callback or function()
                        end
                    }, k.Button:Clone()
                    W.Name = V.Title
                    W.Parent = R
                    W.Frame.Title.Text = V.Title
                    if V.Desc and V.Desc ~= '' then
                        W.Frame.Description.Visible = true
                        W.Frame.Description.Text = V.Desc
                    end
                    if V.Locked then
                        W.UIStroke.Color = Color3.fromRGB(47, 47, 58)
                        W.BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        W.Frame.Title.TextColor3 = Color3.fromRGB(75, 77, 83)
                        W.Frame.Title.ClickIcon.ImageColor3 = Color3.fromRGB(75, 77, 83)
                        W.Frame.Description.TextColor3 = Color3.fromRGB(75, 77, 83)
                    end
                    W.Visible = true
                    local X = function()
                        local X = {}
                        for Y, Z in ipairs(W.Frame:GetChildren()) do
                            if Z:IsA'UIGradient' then
                                Z.Enabled = false
                                table.insert(X, Z)
                            end
                        end
                        local Y = X[math.random(1, # X)]
                        Y.Enabled = true
                        return Y
                    end
                    X()
                    W.MouseEnter:Connect(function()
                        if not V.Locked then
                            o(W.UIStroke, {
                                Color = Color3.fromRGB(10, 135, 213)
                            }, n.Global)
                        end
                    end)
                    W.MouseLeave:Connect(function()
                        if not V.Locked then
                            o(W.UIStroke, {
                                Color = Color3.fromRGB(60, 60, 74)
                            }, n.Global)
                            W.BackgroundColor3 = Color3.fromRGB(42, 45, 52)
                            o(W.Frame.Title, {
                                TextColor3 = Color3.fromRGB(196, 203, 218)
                            }, n.Global)
                            o(W.Frame.Description, {
                                TextColor3 = Color3.fromRGB(196, 203, 218)
                            }, n.Global)
                        end
                    end)
                    W.MouseButton1Down:Connect(function()
                        if not V.Locked then
                            X()
                            o(W.Frame.Title, {
                                TextColor3 = Color3.fromRGB(255, 255, 255)
                            }, n.Global)
                            o(W.Frame.Title.ClickIcon, {
                                ImageColor3 = Color3.fromRGB(255, 255, 255)
                            }, n.Global)
                            o(W.Frame.Description, {
                                TextColor3 = Color3.fromRGB(255, 255, 255)
                            }, n.Global)
                            o(W.Frame, {
                                BackgroundTransparency = 0
                            }, n.Global)
                        end
                    end)
                    W.MouseButton1Up:Connect(function()
                        if not V.Locked then
                            o(W.Frame.Title, {
                                TextColor3 = Color3.fromRGB(196, 203, 218)
                            }, n.Global)
                            o(W.Frame.Title.ClickIcon, {
                                ImageColor3 = Color3.fromRGB(196, 203, 218)
                            }, n.Global)
                            o(W.Frame.Description, {
                                TextColor3 = Color3.fromRGB(196, 203, 218)
                            }, n.Global)
                            o(W.Frame, {
                                BackgroundTransparency = 1
                            }, n.Global)
                        end
                    end)
                    W.MouseLeave:Connect(function()
                        if not V.Locked then
                            o(W.Frame.Title, {
                                TextColor3 = Color3.fromRGB(196, 203, 218)
                            }, n.Global)
                            o(W.Frame.Title.ClickIcon, {
                                ImageColor3 = Color3.fromRGB(196, 203, 218)
                            }, n.Global)
                            o(W.Frame.Description, {
                                TextColor3 = Color3.fromRGB(196, 203, 218)
                            }, n.Global)
                            o(W.Frame, {
                                BackgroundTransparency = 1
                            }, n.Global)
                        end
                    end)
                    W.MouseButton1Click:Connect(function()
                        if not V.Locked then
                            V.Callback()
                        end
                    end)
                    P.ChildAdded:Connect(function()
                        if # Q() > 0 then
                            A.NoObjectFoundText.Visible = false
                        else
                            A.NoObjectFoundText.Visible = true
                        end
                    end)
                    P.ChildRemoved:Connect(function()
                        if # Q() > 0 then
                            A.NoObjectFoundText.Visible = false
                        else
                            A.NoObjectFoundText.Visible = true
                        end
                    end)
                    function U.SetTitle(Y, Z)
                        W.Frame.Title.Text = Z
                    end
                    function U.SetDesc(Y, Z)
                        if Z and Z ~= '' then
                            W.Frame.Description.Text = Z
                        end
                    end
                    function U.Lock(Y)
                        V.Locked = true
                        o(W, {
                            BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        }, n.Global)
                        o(W.UIStroke, {
                            Color = Color3.fromRGB(47, 47, 58)
                        }, n.Global)
                        o(W.Frame.Title, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(W.Frame.Title.ClickIcon, {
                            ImageColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(W.Frame.Description, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                    end
                    function U.Unlock(Y)
                        V.Locked = false
                        o(W, {
                            BackgroundColor3 = Color3.fromRGB(42, 45, 52)
                        }, n.Global)
                        o(W.UIStroke, {
                            Color = Color3.fromRGB(60, 60, 74)
                        }, n.Global)
                        o(W.Frame.Title, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(W.Frame.Title.ClickIcon, {
                            ImageColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(W.Frame.Description, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                    end
                    function U.Destroy(Y)
                        W:Destroy()
                    end
                    return U
                end
                function M.Code(S, T)
                    local U, V = {
                        Title = T.Title,
                        Code = T.Code
                    }, k.Code:Clone()
                    V.Name = U.Title
                    V.Parent = R
                    V.Title.Text = U.Title
                    V.Code.Text = U.Code
                    V.Code.Visible = true
                    V.Code.Font = Enum.Font.Code
                    V.Visible = true
                    function U.SetTitle(W, X)
                        U.Title = X
                        V.Title.Text = X
                    end
                    function U.SetCode(W, X)
                        U.Code = X
                        V.Code.Text = X
                    end
                    function U.Destroy(W)
                        V:Destroy()
                    end
                    return U
                end
                function M.Paragraph(S, T)
                    local U, V = {
                        Title = T.Title,
                        Desc = T.Desc,
                        RichText = T.RichText or false
                    }, k.Paragraph:Clone()
                    V.Name = U.Title
                    V.Parent = R
                    V.Title.Text = U.Title
                    if U.Desc and U.Desc ~= '' then
                        V.Description.Text = U.Desc
                        V.Description.Visible = true
                    else
                        V.Description.Visible = false
                    end
                    V.Title.RichText = U.RichText
                    V.Description.RichText = U.RichText
                    V.Visible = true
                    function U.SetTitle(W, X)
                        U.Title = X
                        V.Title.Text = X
                    end
                    function U.SetDesc(W, X)
                        U.Desc = X
                        V.Description.Text = X
                        if X ~= '' then
                            V.Visible = true
                        else
                            V.Visible = false
                        end
                    end
                    function U.Destroy(W)
                        V:Destroy()
                    end
                    return U
                end
                function M.Colorpicker(S)
                end
                function M.Toggle(S, T)
                    local U, V = {
                        Title = T.Title,
                        Desc = T.Desc,
                        State = T.Default or T.Value or false,
                        Locked = T.Locked or false,
                        Icon = T.Icon,
                        Callback = T.Callback or function()
                        end
                    }, k.Toggle:Clone()
                    V.Name = U.Title
                    V.Parent = R
                    V.Title.Text = U.Title
                    if U.Icon then
                        if string.find(U.Icon, 'rbxassetid') or string.match(U.Icon, '%d') then
                            V.Title.Fill.Ball.Icon.Image = U.Icon
                        else
                            V.Title.Fill.Ball.Icon.Image = (h.Icon(U.Icon) and h.Icon(U.Icon)[1]) or U.Icon or ''
                            V.Title.Fill.Ball.Icon.ImageRectOffset = (h.Icon(U.Icon) and h.Icon(U.Icon)[2].ImageRectPosition) or Vector2.new(0, 0)
                            V.Title.Fill.Ball.Icon.ImageRectSize = (h.Icon(U.Icon) and h.Icon(U.Icon)[2].ImageRectSize) or Vector2.new(0, 0)
                        end
                    end
                    if U.Desc and U.Desc ~= '' then
                        V.Description.Visible = true
                        V.Description.Text = U.Desc
                    end
                    if U.State == true then
                        V.Title.Fill.Ball.Position = UDim2.new(0.5, 0, 0.5, 0)
                        V.Title.Fill.BackgroundColor3 = Color3.fromRGB(192, 209, 199)
                        V.Title.Fill.Ball.Icon.ImageTransparency = 0
                    else
                        V.Title.Fill.Ball.Position = UDim2.new(0, 0, 0.5, 0)
                        V.Title.Fill.BackgroundColor3 = Color3.fromRGB(53, 56, 62)
                        V.Title.Fill.Ball.Icon.ImageTransparency = 1
                    end
                    if U.Locked then
                        V.UIStroke.Color = Color3.fromRGB(47, 47, 58)
                        V.BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        V.Title.TextColor3 = Color3.fromRGB(75, 77, 83)
                        V.Description.TextColor3 = Color3.fromRGB(75, 77, 83)
                        V.Title.Fill.BackgroundTransparency = 0.7
                        V.Title.Fill.Ball.BackgroundTransparency = 0.7
                    end
                    V.Visible = true
                    V.Title.Fill.MouseEnter:Connect(function()
                        if not U.Locked then
                            o(V.UIStroke, {
                                Color = Color3.fromRGB(10, 135, 213)
                            }, n.Global)
                        end
                    end)
                    V.Title.Fill.MouseLeave:Connect(function()
                        if not U.Locked then
                            o(V.UIStroke, {
                                Color = Color3.fromRGB(60, 60, 74)
                            }, n.Global)
                            V.BackgroundColor3 = Color3.fromRGB(42, 45, 52)
                            o(V.Title, {
                                TextColor3 = Color3.fromRGB(196, 203, 218)
                            }, n.Global)
                            o(V.Description, {
                                TextColor3 = Color3.fromRGB(196, 203, 218)
                            }, n.Global)
                        end
                    end)
                    local W = function(W)
                        if W == true then
                            o(V.Title.Fill.Ball, {
                                Position = UDim2.new(0.5, 0, 0.5, 0)
                            }, n.Global)
                            o(V.Title.Fill, {
                                BackgroundColor3 = Color3.fromRGB(192, 209, 199)
                            }, n.Global)
                            o(V.Title.Fill.Ball.Icon, {
                                ImageTransparency = 0
                            }, n.Global)
                        elseif W == false then
                            o(V.Title.Fill.Ball, {
                                Position = UDim2.new(0, 0, 0.5, 0)
                            }, n.Global)
                            o(V.Title.Fill, {
                                BackgroundColor3 = Color3.fromRGB(53, 56, 62)
                            }, n.Global)
                            o(V.Title.Fill.Ball.Icon, {
                                ImageTransparency = 1
                            }, n.Global)
                        end
                    end
                    local X = function(X)
                        if X then
                            W(X)
                        else
                            W(not U.State)
                        end
                        U.State = X or not U.State
                        U.Callback(U.State)
                    end
                    V.Title.Fill.MouseButton1Click:Connect(function()
                        if not U.Locked then
                            X()
                        end
                    end)
                    function U.SetTitle(Y, Z)
                        U.Title = Z
                        V.Title.Text = Z
                    end
                    function U.SetDesc(Y, Z)
                        if Z and Z ~= '' then
                            U.Desc = Z
                            V.Description.Text = Z
                        end
                    end
                    function U.Set(Y, Z)
                        X(Z)
                    end
                    function U.Lock(Y)
                        U.Locked = true
                        o(V, {
                            BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        }, n.Global)
                        o(V.UIStroke, {
                            Color = Color3.fromRGB(47, 47, 58)
                        }, n.Global)
                        o(V.Title, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(V.Description, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(V.Title.Fill, {
                            BackgroundTransparency = 0.7
                        }, n.Global)
                        o(V.Title.Fill.Ball, {
                            BackgroundTransparency = 0.7
                        }, n.Global)
                    end
                    function U.Unlock(Y)
                        U.Locked = false
                        o(V, {
                            BackgroundColor3 = Color3.fromRGB(42, 45, 52)
                        }, n.Global)
                        o(V.UIStroke, {
                            Color = Color3.fromRGB(60, 60, 74)
                        }, n.Global)
                        o(V.Title, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(V.Description, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(V.Title.Fill, {
                            BackgroundTransparency = 0
                        }, n.Global)
                        o(V.Title.Fill.Ball, {
                            BackgroundTransparency = 0
                        }, n.Global)
                    end
                    function U.Destroy(Y)
                        V:Destroy()
                    end
                    U.Callback(U.State)
                    return U
                end
                function M.Slider(S, T)
                    local U = {
                        Title = T.Title,
                        Desc = T.Desc,
                        Step = T.Step or 1,
                        Value = {
                            Min = T.Value.Min or 0,
                            Max = T.Value.Max or nil,
                            Default = nil
                        },
                        Locked = T.Locked,
                        Callback = T.Callback or function()
                        end
                    }
                    U.Value.Default = T.Value.Default or T.Default or T.Value.Min
                    local V, W, X, Y = U.Step, k.Slider:Clone(), game.Players.LocalPlayer:GetMouse(), k.Slider:Clone()
                    Y.Parent = R
                    Y.Name = U.Title
                    Y.Title.Text = U.Title
                    if U.Desc and U.Desc ~= '' then
                        Y.Description.Visible = true
                        Y.Description.Text = U.Desc
                    end
                    Y.Visible = true
                    local aa = function()
                        local Z = {}
                        for _, aa in ipairs(Y.SliderFrame.Frame.Slider.Fill.BackgroundGradient:GetChildren()) do
                            if aa:IsA'UIGradient' then
                                aa.Enabled = false
                                table.insert(Z, aa)
                            end
                        end
                        local aa = Z[math.random(1, # Z)]
                        aa.Enabled = true
                        return aa
                    end
                    Y.SliderFrame.Frame.Slider.Fill.BackgroundGradient.Size = UDim2.new(0, Y.SliderFrame.Frame.Slider.AbsoluteSize.X, 1, 0)
                    Y.SliderFrame.Frame.Slider:GetPropertyChangedSignal'AbsoluteSize':Connect(function()
                        Y.SliderFrame.Frame.Slider.Fill.BackgroundGradient.Size = UDim2.new(0, Y.SliderFrame.Frame.Slider.AbsoluteSize.X, 1, 0)
                    end)
                    local Z
                    Y.SliderFrame.Frame.Slider.Fill:GetPropertyChangedSignal'AbsoluteSize':Connect(function()
                        if Y.SliderFrame.Frame.Slider.Fill.AbsoluteSize.X <= 3 then
                            Z = Y.SliderFrame.Frame.Slider.Fill.AbsoluteSize.X
                        end
                        if Z and Y.SliderFrame.Frame.Slider.Fill.AbsoluteSize.X > Z then
                            aa()
                            Z = nil
                        end
                    end)
                    aa()
                    if U.Locked then
                        Y.UIStroke.Color = Color3.fromRGB(47, 47, 58)
                        Y.BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        Y.Title.TextColor3 = Color3.fromRGB(75, 77, 83)
                        Y.Description.TextColor3 = Color3.fromRGB(75, 77, 83)
                        Y.SliderFrame.Frame.Slider.UIStroke.Color = Color3.fromRGB(47, 47, 58)
                        Y.SliderFrame.Frame.Slider.BackgroundTransparency = 0.5
                        Y.SliderFrame.Frame.Slider.Fill.UIStroke.Transparency = 0.5
                        Y.SliderFrame.Frame.Slider.Fill.BackgroundGradient.BackgroundTransparency = 0.5
                        Y.SliderFrame.Frame.ValueText.TextTransparency = 0.6
                    end
                    local _, ab, ac, ad, ae, af, ag, ah, ai, aj, ak, al = Y.SliderFrame.Frame.Slider.Trigger, Y.SliderFrame.Frame.ValueText, Y.SliderFrame.Frame.Slider.Fill, Y, U.Value.Default, U.Value.Min, U.Value.Max, V or 1, U.Value.Default, false, false
                    local am = function(am)
                        return (am - af) / (ag - af) * (1) + 0
                    end
                    ab.Text = tostring(ae) or tostring(af)
                    ac.Size = UDim2.fromScale(am(ae), 1)
                    local an, ao = function()
                        aj = true
                        if U.Locked then
                            return
                        end
                        repeat
                            task.wait()
                            al = math.clamp((X.X - ad.AbsolutePosition.X) / ad.AbsoluteSize.X, 0, 1)
                            ai = af + (al * (ag - af))
                            local an = math.round(ai / ah) * ah
                            ai = math.clamp(an, af, ag)
                            o(ac, {
                                Size = UDim2.fromScale(am(ai), 1)
                            }, n.Global)
                            ab.Text = tostring(ai)
                            U.Value = ai
                            task.spawn(U.Callback, ai)
                        until aj == false or U.Locked == true
                        if not ak then
                            o(Y.UIStroke, {
                                Color = Color3.fromRGB(60, 60, 74)
                            }, n.Global)
                        end
                    end, function(an)
                        if not an or an > ag or an < af then
                            return
                        end
                        local ao = math.round(an / ah) * ah
                        ai = math.clamp(ao, af, ag)
                        o(ac, {
                            Size = UDim2.fromScale(am(an), 1)
                        }, n.Global)
                        ai = an
                        ab.Text = tostring(ai)
                        U.Value = ai
                        task.spawn(U.Callback, ai)
                    end
                    _.MouseEnter:Connect(function()
                        ak = true
                        if not U.Locked then
                            o(Y.UIStroke, {
                                Color = Color3.fromRGB(10, 135, 213)
                            }, n.Global)
                        end
                    end)
                    _.MouseLeave:Connect(function()
                        ak = false
                        if not U.Locked and not aj then
                            o(Y.UIStroke, {
                                Color = Color3.fromRGB(60, 60, 74)
                            }, n.Global)
                        end
                    end)
                    _.MouseButton1Down:Connect(function()
                        an()
                    end)
                    game:GetService'UserInputService'.InputEnded:Connect(function(ap)
                        if ap.UserInputType == Enum.UserInputType.MouseButton1 or ap.UserInputType == Enum.UserInputType.Touch then
                            aj = false
                        end
                    end)
                    function U.SetTitle(ap, aq)
                        U.Title = aq
                        Y.Title.Text = aq
                    end
                    function U.SetDesc(ap, aq)
                        if aq and aq ~= '' then
                            U.Desc = aq
                            Y.Description.Text = aq
                        end
                    end
                    function U.Set(ap, aq)
                        ao(aq)
                    end
                    function U.Lock(ap)
                        U.Locked = true
                        o(Y, {
                            BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        }, n.Global)
                        o(Y.UIStroke, {
                            Color = Color3.fromRGB(47, 47, 58)
                        }, n.Global)
                        o(Y.Title, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(Y.Description, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(Y.SliderFrame.Frame.Slider.UIStroke, {
                            Color = Color3.fromRGB(47, 47, 58)
                        }, n.Global)
                        o(Y.SliderFrame.Frame.Slider, {
                            BackgroundTransparency = 0.5
                        }, n.Global)
                        o(Y.SliderFrame.Frame.Slider.Fill.UIStroke, {
                            Transparency = 0.5
                        }, n.Global)
                        o(Y.SliderFrame.Frame.Slider.Fill.BackgroundGradient, {
                            BackgroundTransparency = 0.5
                        }, n.Global)
                        o(Y.SliderFrame.Frame.ValueText, {
                            TextTransparency = 0.6
                        }, n.Global)
                    end
                    function U.Unlock(ap)
                        U.Locked = false
                        o(Y, {
                            BackgroundColor3 = Color3.fromRGB(42, 45, 52)
                        }, n.Global)
                        o(Y.UIStroke, {
                            Color = Color3.fromRGB(60, 60, 74)
                        }, n.Global)
                        o(Y.Title, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(Y.Description, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(Y.SliderFrame.Frame.Slider.UIStroke, {
                            Color = Color3.fromRGB(60, 60, 74)
                        }, n.Global)
                        o(Y.SliderFrame.Frame.Slider, {
                            BackgroundTransparency = 0
                        }, n.Global)
                        o(Y.SliderFrame.Frame.Slider.Fill.UIStroke, {
                            Transparency = 0
                        }, n.Global)
                        o(Y.SliderFrame.Frame.Slider.Fill.BackgroundGradient, {
                            BackgroundTransparency = 0
                        }, n.Global)
                        o(Y.SliderFrame.Frame.ValueText, {
                            TextTransparency = 0
                        }, n.Global)
                    end
                    function U.Destroy(ap)
                        Y:Destroy()
                    end
                    U.Callback(ae)
                    return U
                end
                function M.Input(aa, ab)
                    local ac, ad = {
                        Title = ab.Title,
                        Desc = ab.Desc,
                        Placeholder = ab.Placeholder or '',
                        Default = ab.Default or ab.Value or '',
                        Text = ab.Default or ab.Value or '',
                        ClearTextOnFocus = ab.ClearTextOnFocus or false,
                        Locked = ab.Locked or false,
                        MultiLine = ab.MultiLine or false,
                        Callback = ab.Callback or function()
                        end
                    }, k.TextBox:Clone()
                    ad.Name = ac.Title
                    ad.Parent = R
                    ad.Title.Text = ac.Title
                    if ac.Desc and ac.Desc ~= '' then
                        ad.Description.Text = ac.Desc
                        ad.Description.Visible = true
                    else
                        ad.Description.Visible = false
                    end
                    if ac.Locked then
                        ad.UIStroke.Color = Color3.fromRGB(47, 47, 58)
                        ad.BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        ad.Title.TextColor3 = Color3.fromRGB(75, 77, 83)
                        ad.Description.TextColor3 = Color3.fromRGB(75, 77, 83)
                        ad.BoxFrame.Frame.BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        ad.BoxFrame.Frame.UIStroke.Color = Color3.fromRGB(47, 47, 58)
                        ad.BoxFrame.Frame.TextBox.TextColor3 = Color3.fromRGB(75, 77, 83)
                        ad.BoxFrame.Frame.TextBox.PlaceholderColor3 = Color3.fromRGB(75, 77, 83)
                        ad.BoxFrame.Frame.TextBox.Active = false
                        ad.BoxFrame.Frame.TextBox.Interactable = false
                        ad.BoxFrame.Frame.TextBox.TextEditable = false
                    end
                    ad.BoxFrame.Frame.TextBox.Text = ac.Default
                    ad.BoxFrame.Frame.TextBox.PlaceholderText = ac.Placeholder
                    ad.BoxFrame.Frame.TextBox.MultiLine = ac.MultiLine
                    if ac.MultiLine then
                        ad.BoxFrame.Frame.TextBox.AutomaticSize = Enum.AutomaticSize.Y
                    else
                        ad.BoxFrame.Frame.TextBox.AutomaticSize = Enum.AutomaticSize.None
                    end
                    ad.BoxFrame.Frame.TextBox.ClearTextOnFocus = ac.ClearTextOnFocus
                    ad.Visible = true
                    ad.BoxFrame.Frame.TextBox.MouseEnter:Connect(function()
                        if not ac.Locked then
                            o(ad.UIStroke, {
                                Color = Color3.fromRGB(10, 135, 213)
                            }, n.Global)
                        end
                    end)
                    ad.BoxFrame.Frame.TextBox.MouseLeave:Connect(function()
                        if not ac.Locked then
                            o(ad.UIStroke, {
                                Color = Color3.fromRGB(60, 60, 74)
                            }, n.Global)
                        end
                    end)
                    ad.BoxFrame.Frame.TextBox.Focused:Connect(function()
                        if not ac.Locked then
                            o(ad.UIStroke, {
                                Color = Color3.fromRGB(60, 60, 74)
                            }, n.Global)
                            o(ad.BoxFrame.Frame.UIStroke, {
                                Color = Color3.fromRGB(10, 135, 213)
                            }, n.Global)
                        end
                    end)
                    ad.BoxFrame.Frame.TextBox.FocusLost:Connect(function()
                        if not ac.Locked then
                            o(ad.BoxFrame.Frame.UIStroke, {
                                Color = Color3.fromRGB(60, 60, 74)
                            }, n.Global)
                            ac.Text = ad.BoxFrame.Frame.TextBox.Text
                            ac.Callback(ac.Text)
                        end
                    end)
                    function ac.Set(ae, af)
                        ad.BoxFrame.Frame.TextBox.Text = af
                        ac.Text = af
                        ac.Callback(af)
                    end
                    function ac.SetTitle(ae, af)
                        ad.Title.Text = af
                    end
                    function ac.SetDesc(ae, af)
                        if af and af ~= '' then
                            ad.Description.Text = af
                        end
                    end
                    function ac.SetPlaceholder(ae, af)
                        if af then
                            ad.Description.Placeholder = af
                        end
                    end
                    function ac.Lock(ae)
                        ac.Locked = true
                        o(ad.UIStroke, {
                            Color = Color3.fromRGB(47, 47, 58)
                        }, n.Global)
                        o(ad, {
                            BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        }, n.Global)
                        o(ad.Title, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(ad.Description, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(ad.BoxFrame.Frame, {
                            BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        }, n.Global)
                        o(ad.BoxFrame.Frame.UIStroke, {
                            Color = Color3.fromRGB(47, 47, 58)
                        }, n.Global)
                        o(ad.BoxFrame.Frame.TextBox, {
                            TextColor3 = Color3.fromRGB(75, 77, 83),
                            PlaceholderColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        ad.BoxFrame.Frame.TextBox.Active = false
                        ad.BoxFrame.Frame.TextBox.Interactable = false
                        ad.BoxFrame.Frame.TextBox.TextEditable = false
                    end
                    function ac.Unlock(ae)
                        ac.Locked = false
                        o(ad.UIStroke, {
                            Color = Color3.fromRGB(60, 60, 74)
                        }, n.Global)
                        o(ad, {
                            BackgroundColor3 = Color3.fromRGB(42, 45, 52)
                        }, n.Global)
                        o(ad.Title, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(ad.Description, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(ad.BoxFrame.Frame, {
                            BackgroundColor3 = Color3.fromRGB(42, 45, 52)
                        }, n.Global)
                        o(ad.BoxFrame.Frame.UIStroke, {
                            Color = Color3.fromRGB(60, 60, 74)
                        }, n.Global)
                        o(ad.BoxFrame.Frame.TextBox, {
                            TextColor3 = Color3.fromRGB(196, 203, 218),
                            PlaceholderColor3 = Color3.fromRGB(139, 139, 139)
                        }, n.Global)
                        ad.BoxFrame.Frame.TextBox.Active = true
                        ad.BoxFrame.Frame.TextBox.Interactable = true
                        ad.BoxFrame.Frame.TextBox.TextEditable = true
                    end
                    function ac.Destroy(ae)
                        ad:Destroy()
                    end
                    ac.Callback(ac.Text)
                    return ac
                end
                local aa, ab = function(aa, ab)
                    local ac = k.DropdownButton:Clone()
                    ac.Parent = ab or nil
                    ac.Name = aa
                    ac.Frame.Title.Text = aa
                    local ad = function()
                        local ad = {}
                        for ae, af in ipairs(ac.Frame:GetChildren()) do
                            if af:IsA'UIGradient' then
                                af.Enabled = false
                                table.insert(ad, af)
                            end
                        end
                        local ae = ad[math.random(1, # ad)]
                        ae.Enabled = true
                        return ae
                    end
                    ad()
                    return ac
                end, function(aa)
                    return table.concat(aa, ', ')
                end
                function M.Dropdown(ac, ad)
                    local ae, af, ag, ah = {
                        Title = ad.Title,
                        Desc = ad.Desc,
                        Multi = ad.Multi or false,
                        Values = ad.Values or {},
                        Value = ad.Value or ad.Default,
                        AllowNone = ad.AllowNone or false,
                        Locked = ad.Locked or false,
                        Callback = ad.Callback or function()
                        end
                    }, k.Dropdown:Clone(), (k.DropdownList:Clone())
                    ag.Name = ae.Title
                    ag.Parent = w.DropdownSelection.Dropdowns
                    af.Parent = R
                    af.Name = ae.Title
                    af.Title.Text = ae.Title
                    if ae.Desc and ae.Desc ~= '' then
                        af.Description.Visible = true
                        af.Description.Text = ae.Desc
                    else
                        af.Description.Visible = false
                    end
                    if ae.Locked then
                        af.UIStroke.Color = Color3.fromRGB(47, 47, 58)
                        af.BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        af.Title.TextColor3 = Color3.fromRGB(75, 77, 83)
                        af.Description.TextColor3 = Color3.fromRGB(75, 77, 83)
                        af.Title.ClickIcon.ImageColor3 = Color3.fromRGB(75, 77, 83)
                        af.Title.BoxFrame.Trigger.BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        af.Title.BoxFrame.Trigger.UIStroke.Color = Color3.fromRGB(47, 47, 58)
                        af.Title.BoxFrame.Trigger.Title.TextColor3 = Color3.fromRGB(75, 77, 83)
                        af.Active = false
                        af.Interactable = false
                    end
                    af.Visible = true
                    local ai = function(ai, aj)
                        if not ai then
                            local ak, al = ag.DropdownItems:FindFirstChild(aj), ag.DropdownItemsSearch:FindFirstChild(aj)
                            ah = aj
                            ae.Value = ah
                            af.Title.BoxFrame.Trigger.Title.Text = ah
                            for am, an in ag.DropdownItems:GetChildren() do
                                if an:IsA'GuiButton' and an.Name ~= aj then
                                    o(an.Frame.Title, {
                                        TextColor3 = Color3.fromRGB(196, 203, 218)
                                    }, n.Global)
                                    o(an.Frame.Description, {
                                        TextColor3 = Color3.fromRGB(196, 203, 218)
                                    }, n.Global)
                                    o(an.Frame, {
                                        BackgroundTransparency = 1
                                    }, n.Global)
                                    o(an.UIStroke, {
                                        Color = Color3.fromRGB(60, 60, 74)
                                    }, n.Global)
                                end
                            end
                            for am, an in ag.DropdownItemsSearch:GetChildren() do
                                if an:IsA'GuiButton' and an.Name ~= aj then
                                    o(an.Frame.Title, {
                                        TextColor3 = Color3.fromRGB(196, 203, 218)
                                    }, n.Global)
                                    o(an.Frame.Description, {
                                        TextColor3 = Color3.fromRGB(196, 203, 218)
                                    }, n.Global)
                                    o(an.Frame, {
                                        BackgroundTransparency = 1
                                    }, n.Global)
                                    o(an.UIStroke, {
                                        Color = Color3.fromRGB(60, 60, 74)
                                    }, n.Global)
                                end
                            end
                            o(ak.Frame.Title, {
                                TextColor3 = Color3.fromRGB(255, 255, 255)
                            }, n.Global)
                            o(ak.Frame.Description, {
                                TextColor3 = Color3.fromRGB(255, 255, 255)
                            }, n.Global)
                            o(ak.UIStroke, {
                                Color = Color3.fromRGB(10, 135, 213)
                            }, n.Global)
                            o(ak.Frame, {
                                BackgroundTransparency = 0
                            }, n.Global)
                            o(al.Frame.Title, {
                                TextColor3 = Color3.fromRGB(255, 255, 255)
                            }, n.Global)
                            o(al.Frame.Description, {
                                TextColor3 = Color3.fromRGB(255, 255, 255)
                            }, n.Global)
                            o(al.UIStroke, {
                                Color = Color3.fromRGB(10, 135, 213)
                            }, n.Global)
                            o(al.Frame, {
                                BackgroundTransparency = 0
                            }, n.Global)
                            return ah
                        elseif ai then
                            for ak, al in aj do
                                local am, an, ao = ag.DropdownItems:FindFirstChild(al), ag.DropdownItemsSearch:FindFirstChild(al), table.find(ah, al)
                                if ao then
                                    if not ae.AllowNone and # ae.Value == 1 then
                                        return
                                    end
                                    table.remove(ah, ao)
                                    o(am.Frame.Title, {
                                        TextColor3 = Color3.fromRGB(196, 203, 218)
                                    }, n.Global)
                                    o(am.Frame.Description, {
                                        TextColor3 = Color3.fromRGB(196, 203, 2185)
                                    }, n.Global)
                                    o(am.UIStroke, {
                                        Color = Color3.fromRGB(60, 60, 74)
                                    }, n.Global)
                                    o(am.Frame, {
                                        BackgroundTransparency = 1
                                    }, n.Global)
                                    o(an.Frame.Title, {
                                        TextColor3 = Color3.fromRGB(196, 203, 218)
                                    }, n.Global)
                                    o(an.Frame.Description, {
                                        TextColor3 = Color3.fromRGB(196, 203, 2185)
                                    }, n.Global)
                                    o(an.UIStroke, {
                                        Color = Color3.fromRGB(60, 60, 74)
                                    }, n.Global)
                                    o(an.Frame, {
                                        BackgroundTransparency = 1
                                    }, n.Global)
                                else
                                    table.insert(ah, al)
                                    o(am.Frame.Title, {
                                        TextColor3 = Color3.fromRGB(255, 255, 255)
                                    }, n.Global)
                                    o(am.Frame.Description, {
                                        TextColor3 = Color3.fromRGB(255, 255, 255)
                                    }, n.Global)
                                    o(am.UIStroke, {
                                        Color = Color3.fromRGB(10, 135, 213)
                                    }, n.Global)
                                    o(am.Frame, {
                                        BackgroundTransparency = 0
                                    }, n.Global)
                                    o(an.Frame.Title, {
                                        TextColor3 = Color3.fromRGB(255, 255, 255)
                                    }, n.Global)
                                    o(an.Frame.Description, {
                                        TextColor3 = Color3.fromRGB(255, 255, 255)
                                    }, n.Global)
                                    o(an.UIStroke, {
                                        Color = Color3.fromRGB(10, 135, 213)
                                    }, n.Global)
                                    o(an.Frame, {
                                        BackgroundTransparency = 0
                                    }, n.Global)
                                end
                            end
                            ae.Value = ah
                            af.Title.BoxFrame.Trigger.Title.Text = ab(ah)
                            return ah
                        end
                    end
                    local aj = function(aj, ak)
                        local al, am = {}, {}
                        for an, ao in aj do
                            if typeof(ao) == 'string' then
                                if not al[ao] then
                                    al[ao] = 1
                                    table.insert(am, ao)
                                else
                                    al[ao] = al[ao] + 1
                                    table.insert(am, ao .. ' (' .. al[ao] .. ')')
                                end
                            end
                        end
                        if ak then
                            ae.Values = am
                            for an, ao in ag.DropdownItems:GetChildren() do
                                if ao:IsA'GuiButton' then
                                    ao:Destroy()
                                end
                            end
                            for an, ao in ag.DropdownItemsSearch:GetChildren() do
                                if ao:IsA'GuiButton' then
                                    ao:Destroy()
                                end
                            end
                        end
                        if not ae.Multi then
                            if ak then
                                ah = nil
                                af.Title.BoxFrame.Trigger.Title.Text = ''
                            end
                            for an, ao in am do
                                local ap, aq = aa(ao, ag.DropdownItems), aa(ao, ag.DropdownItemsSearch)
                                ap.Visible = true
                                aq.Visible = true
                                if ah == ao then
                                    ap.Frame.Title.TextColor3 = Color3.fromRGB(255, 255, 255)
                                    ap.Frame.Description.TextColor3 = Color3.fromRGB(255, 255, 255)
                                    ap.UIStroke.Color = Color3.fromRGB(10, 135, 213)
                                    ap.Frame.BackgroundTransparency = 0
                                    ap.Frame.Title.TextColor3 = Color3.fromRGB(255, 255, 255)
                                    aq.Frame.Title.TextColor3 = Color3.fromRGB(255, 255, 255)
                                    aq.Frame.Description.TextColor3 = Color3.fromRGB(255, 255, 255)
                                    aq.UIStroke.Color = Color3.fromRGB(10, 135, 213)
                                    aq.Frame.BackgroundTransparency = 0
                                    aq.Frame.Title.TextColor3 = Color3.fromRGB(255, 255, 255)
                                end
                                ap.MouseButton1Click:Connect(function()
                                    if not ae.Locked then
                                        local S = ai(false, ao)
                                        if S then
                                            ae.Callback(S)
                                        end
                                    end
                                end)
                                aq.MouseButton1Click:Connect(function()
                                    if not ae.Locked then
                                        local S = ai(false, ao)
                                        if S then
                                            ae.Callback(S)
                                        end
                                    end
                                end)
                            end
                        elseif ae.Multi then
                            if ak then
                                ah = {}
                                af.Title.BoxFrame.Trigger.Title.Text = ab(ah)
                            end
                            for an, ao in am do
                                local ap, aq = aa(ao, ag.DropdownItems), aa(ao, ag.DropdownItemsSearch)
                                ap.Visible = true
                                aq.Visible = true
                                if table.find(ah, ao) then
                                    ap.Frame.Title.TextColor3 = Color3.fromRGB(255, 255, 255)
                                    ap.Frame.Description.TextColor3 = Color3.fromRGB(255, 255, 255)
                                    ap.UIStroke.Color = Color3.fromRGB(10, 135, 213)
                                    ap.Frame.BackgroundTransparency = 0
                                    ap.Frame.Title.TextColor3 = Color3.fromRGB(255, 255, 255)
                                    aq.Frame.Title.TextColor3 = Color3.fromRGB(255, 255, 255)
                                    aq.Frame.Description.TextColor3 = Color3.fromRGB(255, 255, 255)
                                    aq.UIStroke.Color = Color3.fromRGB(10, 135, 213)
                                    aq.Frame.BackgroundTransparency = 0
                                    aq.Frame.Title.TextColor3 = Color3.fromRGB(255, 255, 255)
                                end
                                ap.MouseButton1Click:Connect(function()
                                    if not ae.Locked then
                                        local S = ai(true, {
                                            ao
                                        })
                                        if S then
                                            ae.Callback(S)
                                        end
                                    end
                                end)
                                aq.MouseButton1Click:Connect(function()
                                    if not ae.Locked then
                                        local S = ai(true, {
                                            ao
                                        })
                                        if S then
                                            ae.Callback(S)
                                        end
                                    end
                                end)
                            end
                        end
                    end
                    if not ae.Multi then
                        ah = ae.Value or nil
                        af.Title.BoxFrame.Trigger.Title.Text = ah
                        aj(ae.Values)
                    elseif ae.Multi then
                        af.Title.ClickIcon.Image = 'rbxassetid://91415671397056'
                        if type(ae.Value) == 'string' then
                            ae.Value = {
                                ae.Value
                            }
                        end
                        ah = ae.Value or {}
                        af.Title.BoxFrame.Trigger.Title.Text = ab(ah)
                        aj(ae.Values)
                    end
                    af.Title.BoxFrame.Trigger.MouseButton1Click:Connect(function()
                        H(nil, ae.Title)
                    end)
                    function ae.SetTitle(ak, al)
                        ae.Title = al
                        af.Title.Text = al
                    end
                    function ae.SetDesc(ak, al)
                        if al and al ~= '' then
                            ae.Desc = al
                            af.Description.Text = al
                        end
                    end
                    function ae.Refresh(ak, al)
                        aj(al, true)
                    end
                    function ae.Select(ak, al)
                        ae.Callback(ai(ae.Multi, al))
                    end
                    function ae.Lock(ak)
                        ae.Locked = true
                        o(af.UIStroke, {
                            Color = Color3.fromRGB(47, 47, 58)
                        }, n.Global)
                        o(af, {
                            BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        }, n.Global)
                        o(af.Title, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(af.Description, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(af.Title.ClickIcon, {
                            ImageColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        o(af.Title.BoxFrame.Trigger, {
                            BackgroundColor3 = Color3.fromRGB(32, 35, 40)
                        }, n.Global)
                        o(af.Title.BoxFrame.Trigger.UIStroke, {
                            Color = Color3.fromRGB(47, 47, 58)
                        }, n.Global)
                        o(af.Title.BoxFrame.Trigger.Title, {
                            TextColor3 = Color3.fromRGB(75, 77, 83)
                        }, n.Global)
                        af.Active = false
                        af.Interactable = false
                    end
                    function ae.Unlock(ak)
                        ae.Locked = false
                        o(af.UIStroke, {
                            Color = Color3.fromRGB(60, 60, 74)
                        }, n.Global)
                        o(af, {
                            BackgroundColor3 = Color3.fromRGB(42, 45, 52)
                        }, n.Global)
                        o(af.Title, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(af.Description, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(af.Title.ClickIcon, {
                            ImageColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        o(af.Title.BoxFrame.Trigger, {
                            BackgroundColor3 = Color3.fromRGB(42, 45, 52)
                        }, n.Global)
                        o(af.Title.BoxFrame.Trigger.UIStroke, {
                            Color = Color3.fromRGB(60, 60, 74)
                        }, n.Global)
                        o(af.Title.BoxFrame.Trigger.Title, {
                            TextColor3 = Color3.fromRGB(196, 203, 218)
                        }, n.Global)
                        af.Active = true
                        af.Interactable = true
                    end
                    function ae.Destroy(ak)
                        af:Destroy()
                    end
                    ae.Callback(ae.Value)
                    return ae
                end
                return M
            end
            function t.SelectTab(aa, ab)
                local ac = C[ab]
                if ac then
                    I(ac.Name)
                end
            end
            function t.Divider(aa)
                local ab = k.Divider:Clone()
                ab.Parent = w.TabButtons.Lists
                ab.Visible = true
            end
            function t.SetToggleKey(aa, ab)
                if type(ab) == 'string' then
                    t.ToggleKey = Enum.KeyCode[ab]
                else
                    t.ToggleKey = ab
                end
            end
            function t.EditOpenButton(aa)
            end
            function t.Dialog(aa, ab)
                local ac, ad, ae = {
                    Title = ab.Title,
                    Content = ab.Content,
                    Icon = ab.Icon,
                    Buttons = ab.Buttons or {},
                    Size = nil,
                    PressDecreaseSize = UDim2.fromOffset(5, 5)
                }, k.DialogElements.Dialog:Clone(), k.DialogElements.DarkOverlayDialog:Clone()
                ad.Title.TextLabel.Text = ac.Title
                if ac and ac ~= '' then
                    ad.Content.Visible = true
                    ad.Content.TextLabel.Text = ac.Content
                end
                if ac.Icon then
                    if string.find(ac.Icon, 'rbxassetid') or string.match(ac.Icon, '%d') then
                        ad.Title.Icon.Image = ac.Icon
                    else
                        ad.Title.Icon.Image = (h.Icon(ac.Icon) and h.Icon(ac.Icon)[1]) or ac.Icon or ''
                        ad.Title.Icon.ImageRectOffset = (h.Icon(ac.Icon) and h.Icon(ac.Icon)[2].ImageRectPosition) or Vector2.new(0, 0)
                        ad.Title.Icon.ImageRectSize = (h.Icon(ac.Icon) and h.Icon(ac.Icon)[2].ImageRectSize) or Vector2.new(0, 0)
                    end
                    ad.Title.Icon.Visible = true
                end
                ad.Parent = w
                ae.Parent = w
                ac.Size = UDim2.fromOffset(ad.AbsoluteSize.X, ad.AbsoluteSize.Y)
                ae.Transparency = 1
                for af, ag in ac.Buttons do
                    local ah, ai = {
                        Title = ag.Title or 'Button',
                        Callback = ag.Callback or function()
                        end
                    }, k.DialogElements.DialogButton:Clone()
                    local aj = ai.Button.Size
                    ai.Button.Label.Text = ah.Title
                    ai.Button.MouseButton1Click:Connect(function()
                        ah.Callback()
                        local ak = o(ae, {
                            Transparency = 1
                        }, n.Global)
                        ad:Destroy()
                        ak.Completed:Wait()
                        ae:Destroy()
                    end)
                    ai.Button.MouseButton1Down:Connect(function()
                        o(ai.Button, {
                            Size = aj - ac.PressDecreaseSize
                        }, n.Global)
                    end)
                    ai.Button.MouseButton1Up:Connect(function()
                        o(ai.Button, {
                            Size = aj
                        }, n.Global)
                    end)
                    ai.Button.MouseLeave:Connect(function()
                        o(ai.Button, {
                            Size = aj
                        }, n.Global)
                    end)
                    ai.Parent = ad.Buttons
                    ai.Visible = true
                end
                o(ae, {
                    Transparency = 0.6
                }, n.Global)
                ad.Visible = true
                ae.Visible = true
                return ac
            end
            local aa, ab, ac, ad, ae, af = v.Size, t.Size, t.Size, w.Position, false, p(w.TopFrame, w)
            p(v, v)
            w.Visible = true
            w.Size = UDim2.fromOffset(0, 0)
            local ag, ah = w.Visible, false
            local ai = function(ai)
                if ai == true then
                    m = v.Size
                    w.Size = UDim2.fromOffset(0, 0)
                    w.Visible = true
                    o(v, {
                        Size = UDim2.new(0, 0, 0, 0)
                    }, n.Global)
                    o(w, {
                        Size = ab
                    }, n.Global).Completed:Wait()
                    w.Tabs.Visible = true
                    w.TabButtons.Visible = true
                    v.Visible = false
                elseif ai == false then
                    ab = w.Size
                    v.Size = UDim2.fromOffset(0, 0)
                    v.Visible = true
                    w.Tabs.Visible = false
                    w.TabButtons.Visible = false
                    o(v, {
                        Size = aa
                    }, n.Global)
                    o(w, {
                        Size = UDim2.fromOffset(0, 0)
                    }, n.Global).Completed:Wait()
                    w.Visible = false
                else
                    if ag then
                        ab = w.Size
                        v.Size = UDim2.fromOffset(0, 0)
                        v.Visible = true
                        w.Tabs.Visible = false
                        w.TabButtons.Visible = false
                        w.DropShadow.Visible = false
                        o(v, {
                            Size = aa
                        }, n.Global)
                        o(w, {
                            Size = UDim2.fromOffset(0, 0)
                        }, n.Global).Completed:Wait()
                        w.Visible = false
                        ag = false
                    else
                        m = v.Size
                        w.Size = UDim2.fromOffset(0, 0)
                        w.Visible = true
                        w.DropShadow.Visible = true
                        o(v, {
                            Size = UDim2.new(0, 0, 0, 0)
                        }, n.Global)
                        o(w, {
                            Size = ab
                        }, n.Global).Completed:Wait()
                        w.Tabs.Visible = true
                        w.TabButtons.Visible = true
                        v.Visible = false
                        ag = true
                    end
                end
            end
            w.TopFrame.Hide.MouseButton1Click:Connect(function()
                if not ah then
                    ah = true
                    ai(false)
                    task.delay(n.Global.Duration, function()
                        ah = false
                    end)
                end
            end)
            v.Open.MouseButton1Click:Connect(function()
                if not ah then
                    ah = true
                    ai(true)
                    task.delay(n.Global.Duration, function()
                        ah = false
                    end)
                end
            end)
            w.TopFrame.Close.MouseButton1Click:Connect(function()
                t:Dialog{
                    Icon = 'triangle-alert',
                    Title = 'Close Window',
                    Content = [[Do you want to close this window? You will not able to open it again.]],
                    Buttons = {
                        {
                            Title = 'Cancel'
                        },
                        {
                            Title = 'Close Window',
                            Callback = function()
                                u.Parent = nil
                            end
                        }
                    }
                }
            end)
            w.TopFrame.Maximize.MouseButton1Click:Connect(function()
                if not ae then
                    af:SetAllowDragging(false)
                    ac = w.Size
                    ad = w.Position
                    o(w, {
                        Size = UDim2.new(1, 0, 1, 0)
                    }, n.Global)
                    o(w, {
                        Position = UDim2.new(0.5, 0, 0.5, 0)
                    }, n.Global)
                    o(w.UICorner, {
                        CornerRadius = UDim.new(0, 0)
                    }, n.Global)
                    ae = true
                else
                    af:SetAllowDragging(true)
                    o(w, {
                        Size = ac
                    }, n.Global)
                    o(w, {
                        Position = ad
                    }, n.Global)
                    o(w.UICorner, {
                        CornerRadius = UDim.new(0, 10)
                    }, n.Global)
                    ae = false
                end
            end)
            o(w, {
                Size = ab
            }, n.Global)
            i.InputBegan:Connect(function(aj, ak)
                if not ah and not ak and aj.KeyCode == t.ToggleKey then
                    ah = true
                    ai()
                    task.delay(n.Global.Duration, function()
                        ah = false
                    end)
                end
            end)
            return t
        end
        function g.Notify(aa, ab)
            local ac, ad, ae = {}, {
                Title = ab.Title,
                Content = ab.Content,
                Icon = ab.Icon,
                Duration = ab.Duration or 5
            }, k.Notification:Clone()
            if # q == 1 and q[1].Visible and q[1].Tabs.Visible then
                ae.Parent = q[1].NotificationFrame.NotificationList
            else
                ae.Parent = j.NotificationList
            end
            ae.Items.Frame.Title.Text = ad.Title
            ae.Items.Frame.Content.Text = ad.Content
            ae.Items.Frame.Title.Icon.Image = (h.Icon(ad.Icon) and h.Icon(ad.Icon)[1]) or ad.Icon or ''
            ae.Items.Frame.Title.Icon.ImageRectOffset = (h.Icon(ad.Icon) and h.Icon(ad.Icon)[2].ImageRectPosition) or Vector2.new(0, 0)
            ae.Items.Frame.Title.Icon.ImageRectSize = (h.Icon(ad.Icon) and h.Icon(ad.Icon)[2].ImageRectSize) or Vector2.new(0, 0)
            ae.Items.Position = UDim2.new(0.75, 0, 0, 0)
            ae.Visible = true
            local af = function()
                if ae then
                    o(ae.Items, {
                        Position = UDim2.new(0.75, 0, 0, 0)
                    }, n.Notification)
                    task.wait(n.Notification.Duration - (n.Notification.Duration / 2))
                    if ae then
                        ae:Destroy()
                    end
                    ae = nil
                end
            end
            ae.Items.Frame.Title.Close.MouseButton1Click:Connect(af)
            local ag = o(ae.Items, {
                Position = UDim2.new(0, 0, 0, 0)
            }, n.Notification)
            ag.Completed:Connect(function()
                o(ae.Items.TimerBarFill.Bar, {
                    Size = UDim2.new(0, 0, 1, 0)
                }, {
                    Duration = ad.Duration
                })
                task.delay(ad.Duration, af)
            end)
            function ac.Close(ah)
                af()
            end
            return ac
        end
        return g
    end
}
d[a['3f'] ] = {
    Closure = function()
        local aa = a['3f']
        local ab, ac = {
            lucide = e(aa.Lucide)
        }, {
            IconsType = 'lucide'
        }
        function ac.SetIconsType(ad)
            ac.IconsType = ad
        end
        function ac.Icon(ad, ae)
            local af = ab[ae or ac.IconsType]
            if af.Icons[ad] then
                return {
                    af.Spritesheets[tostring(af.Icons[ad].Image)],
                    af.Icons[ad]
                }
            end
            return nil
        end
        return ac
    end
}
d[a['40'] ] = {
    Closure = function()
        local aa = a['40']
        return {
            Spritesheets = {
                ['1'] = 'rbxassetid://131526378523863',
                ['10'] = 'rbxassetid://98656588890340',
                ['11'] = 'rbxassetid://122516128999742',
                ['12'] = 'rbxassetid://136045238860745',
                ['13'] = 'rbxassetid://138056954680929',
                ['14'] = 'rbxassetid://139241675471365',
                ['15'] = 'rbxassetid://120281540002144',
                ['16'] = 'rbxassetid://122481504913348',
                ['2'] = 'rbxassetid://125136326597802',
                ['3'] = 'rbxassetid://132619645919851',
                ['4'] = 'rbxassetid://124546836680911',
                ['5'] = 'rbxassetid://138714413596023',
                ['6'] = 'rbxassetid://95318701976229',
                ['7'] = 'rbxassetid://87465848394141',
                ['8'] = 'rbxassetid://77771201330939',
                ['9'] = 'rbxassetid://126006375824005'
            },
            Icons = {['a-arrow-down'] = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['a-arrow-up'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['a-large-small'] = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },accessibility = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },activity = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['air-vent'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },airplay = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['alarm-clock-check'] = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['alarm-clock-minus'] = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['alarm-clock-off'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['alarm-clock-plus'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['alarm-clock'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['alarm-smoke'] = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },album = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-center-horizontal'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-center-vertical'] = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-center'] = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-end-horizontal'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-end-vertical'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-horizontal-distribute-center'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-horizontal-distribute-end'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-horizontal-distribute-start'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-horizontal-justify-center'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-horizontal-justify-end'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-horizontal-justify-start'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-horizontal-space-around'] = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-horizontal-space-between'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-justify'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-left'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-right'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-start-horizontal'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-start-vertical'] = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-vertical-distribute-center'] = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-vertical-distribute-end'] = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-vertical-distribute-start'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-vertical-justify-center'] = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-vertical-justify-end'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-vertical-justify-start'] = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-vertical-space-around'] = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['align-vertical-space-between'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },ambulance = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },ampersand = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },ampersands = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },amphora = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },anchor = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },angry = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },annoyed = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },antenna = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },anvil = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },aperture = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['app-window-mac'] = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['app-window'] = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },apple = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['archive-restore'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['archive-x'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },archive = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },armchair = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-big-down-dash'] = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-big-down'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-big-left-dash'] = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-big-left'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-big-right-dash'] = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-big-right'] = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-big-up-dash'] = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-big-up'] = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-0-1'] = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-1-0'] = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-a-z'] = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-from-line'] = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-left'] = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-narrow-wide'] = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-right'] = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-to-dot'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-to-line'] = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-up'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-wide-narrow'] = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down-z-a'] = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-down'] = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-left-from-line'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-left-right'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-left-to-line'] = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-left'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-right-from-line'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-right-left'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-right-to-line'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-right'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-0-1'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-1-0'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-a-z'] = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-down'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-from-dot'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-from-line'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-left'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-narrow-wide'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-right'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-to-line'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-wide-narrow'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up-z-a'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrow-up'] = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },['arrows-up-from-line'] = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 1
                },asterisk = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['at-sign'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },atom = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['audio-lines'] = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['audio-waveform'] = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },award = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },axe = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['axis-3d'] = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },baby = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },backpack = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-alert'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-cent'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-check'] = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-dollar-sign'] = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-euro'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-help'] = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-indian-rupee'] = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-info'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-japanese-yen'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-minus'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-percent'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-plus'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-pound-sterling'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-russian-ruble'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-swiss-franc'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['badge-x'] = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },badge = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['baggage-claim'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },ban = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },banana = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bandage = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },banknote = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },barcode = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },baseline = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bath = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['battery-charging'] = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['battery-full'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['battery-low'] = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['battery-medium'] = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['battery-plus'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['battery-warning'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },battery = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },beaker = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bean-off'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bean = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bed-double'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bed-single'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bed = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },beef = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['beer-off'] = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },beer = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bell-dot'] = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bell-electric'] = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bell-minus'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bell-off'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bell-plus'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bell-ring'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bell = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['between-horizontal-end'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['between-horizontal-start'] = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['between-vertical-end'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['between-vertical-start'] = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['biceps-flexed'] = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bike = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },binary = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },binoculars = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },biohazard = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bird = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bitcoin = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },blend = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },blinds = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },blocks = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bluetooth-connected'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bluetooth-off'] = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['bluetooth-searching'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bluetooth = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bold = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bolt = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bomb = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },bone = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-a'] = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-audio'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-check'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-copy'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-dashed'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-down'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-headphones'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-heart'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-image'] = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-key'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-lock'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-marked'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-minus'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-open-check'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-open-text'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-open'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-plus'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-text'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-type'] = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-up-2'] = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 2
                },['book-up'] = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['book-user'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['book-x'] = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },book = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['bookmark-check'] = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['bookmark-minus'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['bookmark-plus'] = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['bookmark-x'] = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },bookmark = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['boom-box'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['bot-message-square'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['bot-off'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },bot = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },box = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },boxes = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },braces = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },brackets = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['brain-circuit'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['brain-cog'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },brain = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['brick-wall'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['briefcase-business'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['briefcase-conveyor-belt'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['briefcase-medical'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },briefcase = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['bring-to-front'] = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },brush = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['bug-off'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['bug-play'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },bug = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['building-2'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },building = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['bus-front'] = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },bus = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['cable-car'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },cable = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['cake-slice'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },cake = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },calculator = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-1'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-arrow-down'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-arrow-up'] = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-check-2'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-check'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-clock'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-cog'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-days'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-fold'] = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-heart'] = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-minus-2'] = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-minus'] = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-off'] = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-plus-2'] = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-plus'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-range'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-search'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-sync'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-x-2'] = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['calendar-x'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },calendar = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['camera-off'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },camera = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['candy-cane'] = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['candy-off'] = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },candy = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },cannabis = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['captions-off'] = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },captions = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['car-front'] = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['car-taxi-front'] = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },car = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },caravan = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },carrot = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['case-lower'] = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['case-sensitive'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['case-upper'] = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['cassette-tape'] = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },cast = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },castle = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },cat = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },cctv = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-area'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-bar-big'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-bar-decreasing'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-bar-increasing'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-bar-stacked'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-bar'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-candlestick'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-column-big'] = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-column-decreasing'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-column-increasing'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-column-stacked'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-column'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-gantt'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-line'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-network'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-no-axes-column-decreasing'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-no-axes-column-increasing'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-no-axes-column'] = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-no-axes-combined'] = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 3
                },['chart-no-axes-gantt'] = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chart-pie'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chart-scatter'] = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chart-spline'] = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['check-check'] = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },check = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chef-hat'] = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },cherry = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevron-down'] = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevron-first'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevron-last'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevron-left'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevron-right'] = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevron-up'] = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevrons-down-up'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevrons-down'] = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevrons-left-right-ellipsis'] = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevrons-left-right'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevrons-left'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevrons-right-left'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevrons-right'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevrons-up-down'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['chevrons-up'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },chrome = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },church = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['cigarette-off'] = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },cigarette = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-alert'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-arrow-down'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-arrow-left'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-arrow-out-down-left'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-arrow-out-down-right'] = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-arrow-out-up-left'] = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-arrow-out-up-right'] = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-arrow-right'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-arrow-up'] = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-check-big'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-check'] = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-chevron-down'] = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-chevron-left'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-chevron-right'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-chevron-up'] = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-dashed'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-divide'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-dollar-sign'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-dot-dashed'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-dot'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-ellipsis'] = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-equal'] = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-fading-arrow-up'] = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-fading-plus'] = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-gauge'] = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-help'] = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-minus'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-off'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-parking-off'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-parking'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-pause'] = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-percent'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-play'] = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-plus'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-power'] = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-slash-2'] = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-slash'] = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-stop'] = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-user-round'] = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-user'] = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circle-x'] = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },circle = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['circuit-board'] = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },citrus = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },clapperboard = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clipboard-check'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clipboard-copy'] = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clipboard-list'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clipboard-minus'] = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clipboard-paste'] = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clipboard-pen-line'] = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clipboard-pen'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clipboard-plus'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clipboard-type'] = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clipboard-x'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },clipboard = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-1'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-10'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-11'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-12'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-2'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-3'] = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-4'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-5'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-6'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-7'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-8'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-9'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-alert'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-arrow-down'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['clock-arrow-up'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },clock = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['cloud-alert'] = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 4
                },['cloud-cog'] = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-download'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-drizzle'] = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-fog'] = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-hail'] = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-lightning'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-moon-rain'] = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-moon'] = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-off'] = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-rain-wind'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-rain'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-snow'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-sun-rain'] = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-sun'] = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cloud-upload'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },cloud = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },cloudy = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },clover = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },club = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['code-xml'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },code = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },codepen = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },codesandbox = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },coffee = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },cog = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },coins = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['columns-2'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['columns-3'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['columns-4'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },combine = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },command = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },compass = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },component = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },computer = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['concierge-bell'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },cone = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },construction = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['contact-round'] = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },contact = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },container = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },contrast = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },cookie = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cooking-pot'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['copy-check'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['copy-minus'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['copy-plus'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['copy-slash'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['copy-x'] = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },copy = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },copyleft = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },copyright = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['corner-down-left'] = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['corner-down-right'] = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['corner-left-down'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['corner-left-up'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['corner-right-down'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['corner-right-up'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['corner-up-left'] = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['corner-up-right'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },cpu = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['creative-commons'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['credit-card'] = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },croissant = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },crop = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },cross = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },crosshair = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },crown = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },cuboid = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['cup-soda'] = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },currency = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },cylinder = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },dam = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['database-backup'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['database-zap'] = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },database = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },delete = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },dessert = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },diameter = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['diamond-minus'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['diamond-percent'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['diamond-plus'] = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },diamond = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['dice-1'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['dice-2'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['dice-3'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['dice-4'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['dice-5'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['dice-6'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },dices = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },diff = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['disc-2'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['disc-3'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['disc-album'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },disc = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },divide = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['dna-off'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },dna = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },dock = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },dog = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },['dollar-sign'] = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 5
                },donut = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['door-closed'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['door-open'] = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },dot = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },download = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['drafting-compass'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },drama = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },dribbble = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },drill = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['droplet-off'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },droplet = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },droplets = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },drum = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },drumstick = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },dumbbell = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['ear-off'] = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },ear = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['earth-lock'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },earth = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },eclipse = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['egg-fried'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['egg-off'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },egg = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['ellipsis-vertical'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },ellipsis = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['equal-approximately'] = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['equal-not'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },equal = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },eraser = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['ethernet-port'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },euro = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },expand = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['external-link'] = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['eye-closed'] = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['eye-off'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },eye = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },facebook = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },factory = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },fan = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['fast-forward'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },feather = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },fence = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['ferris-wheel'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },figma = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-archive'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-audio-2'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-audio'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-axis-3d'] = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-badge-2'] = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-badge'] = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-box'] = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-chart-column-increasing'] = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-chart-column'] = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-chart-line'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-chart-pie'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-check-2'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-check'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-clock'] = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-code-2'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-code'] = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-cog'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-diff'] = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-digit'] = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-down'] = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-heart'] = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-image'] = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-input'] = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-json-2'] = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-json'] = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-key-2'] = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-key'] = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-lock-2'] = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-lock'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-minus-2'] = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-minus'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-music'] = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-output'] = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-pen-line'] = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-pen'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-plus-2'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-plus'] = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-question'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-scan'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-search-2'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-search'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-sliders'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-spreadsheet'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-stack'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-symlink'] = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-terminal'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-text'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-type-2'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-type'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-up'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-user'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-video-2'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-video'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-volume-2'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-volume'] = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-warning'] = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 6
                },['file-x-2'] = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['file-x'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },file = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },files = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },film = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['filter-x'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },filter = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },fingerprint = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['fire-extinguisher'] = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['fish-off'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['fish-symbol'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },fish = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flag-off'] = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flag-triangle-left'] = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flag-triangle-right'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },flag = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flame-kindling'] = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },flame = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flashlight-off'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },flashlight = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flask-conical-off'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flask-conical'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flask-round'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flip-horizontal-2'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flip-horizontal'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flip-vertical-2'] = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flip-vertical'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['flower-2'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },flower = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },focus = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['fold-horizontal'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['fold-vertical'] = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-archive'] = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-check'] = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-clock'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-closed'] = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-code'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-cog'] = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-dot'] = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-down'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-git-2'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-git'] = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-heart'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-input'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-kanban'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-key'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-lock'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-minus'] = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-open-dot'] = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-open'] = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-output'] = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-pen'] = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-plus'] = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-root'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-search-2'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-search'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-symlink'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-sync'] = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-tree'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-up'] = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['folder-x'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },folder = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },folders = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },footprints = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },forklift = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },forward = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },frame = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },framer = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },frown = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },fuel = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },fullscreen = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['gallery-horizontal-end'] = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['gallery-horizontal'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['gallery-thumbnails'] = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['gallery-vertical-end'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['gallery-vertical'] = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['gamepad-2'] = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },gamepad = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },gauge = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },gavel = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },gem = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },ghost = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },gift = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-branch-plus'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-branch'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-commit-horizontal'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-commit-vertical'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-compare-arrows'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-compare'] = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-fork'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-graph'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-merge'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-pull-request-arrow'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-pull-request-closed'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-pull-request-create-arrow'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-pull-request-create'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-pull-request-draft'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['git-pull-request'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },github = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },gitlab = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 7
                },['glass-water'] = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },glasses = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['globe-lock'] = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },globe = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },goal = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },grab = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['graduation-cap'] = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },grape = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['grid-2x2-check'] = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['grid-2x2-plus'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['grid-2x2-x'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['grid-2x2'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['grid-3x3'] = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['grip-horizontal'] = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['grip-vertical'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },grip = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },group = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },guitar = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },ham = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },hammer = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hand-coins'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hand-heart'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hand-helping'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hand-metal'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hand-platter'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },hand = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },handshake = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hard-drive-download'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hard-drive-upload'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hard-drive'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hard-hat'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },hash = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },haze = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hdmi-port'] = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['heading-1'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['heading-2'] = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['heading-3'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['heading-4'] = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['heading-5'] = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['heading-6'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },heading = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['headphone-off'] = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },headphones = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },headset = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['heart-crack'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['heart-handshake'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['heart-off'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['heart-pulse'] = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },heart = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },heater = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },hexagon = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },highlighter = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },history = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['hop-off'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },hop = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },hospital = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },hotel = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },hourglass = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['house-plug'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['house-plus'] = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['house-wifi'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },house = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['ice-cream-bowl'] = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['ice-cream-cone'] = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['id-card'] = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['image-down'] = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['image-minus'] = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['image-off'] = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['image-play'] = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['image-plus'] = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['image-up'] = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['image-upscale'] = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },image = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },images = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },import = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },inbox = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['indent-decrease'] = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['indent-increase'] = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['indian-rupee'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },infinity = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },info = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['inspection-panel'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },instagram = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },italic = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['iteration-ccw'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['iteration-cw'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['japanese-yen'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },joystick = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },kanban = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['key-round'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['key-square'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },key = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['keyboard-music'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['keyboard-off'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },keyboard = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['lamp-ceiling'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['lamp-desk'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['lamp-floor'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['lamp-wall-down'] = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },['lamp-wall-up'] = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 8
                },lamp = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['land-plot'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },landmark = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },languages = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['laptop-minimal-check'] = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['laptop-minimal'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },laptop = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['lasso-select'] = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },lasso = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },laugh = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['layers-2'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },layers = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['layout-dashboard'] = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['layout-grid'] = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['layout-list'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['layout-panel-left'] = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['layout-panel-top'] = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['layout-template'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },leaf = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['leafy-green'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },lectern = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['letter-text'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['library-big'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },library = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['life-buoy'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },ligature = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['lightbulb-off'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },lightbulb = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['link-2-off'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['link-2'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },link = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },linkedin = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-check'] = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-checks'] = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-collapse'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-end'] = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-filter-plus'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-filter'] = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-minus'] = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-music'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-ordered'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-plus'] = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-restart'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-start'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-todo'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-tree'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-video'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['list-x'] = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },list = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['loader-circle'] = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['loader-pinwheel'] = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },loader = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['locate-fixed'] = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['locate-off'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },locate = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['lock-keyhole-open'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['lock-keyhole'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['lock-open'] = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },lock = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['log-in'] = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['log-out'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },logs = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },lollipop = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },luggage = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },magnet = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['mail-check'] = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['mail-minus'] = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['mail-open'] = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['mail-plus'] = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['mail-question'] = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['mail-search'] = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['mail-warning'] = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['mail-x'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },mail = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },mailbox = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },mails = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin-check-inside'] = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin-check'] = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin-house'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin-minus-inside'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin-minus'] = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin-off'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin-plus-inside'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin-plus'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin-x-inside'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin-x'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pin'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-pinned'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['map-plus'] = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },map = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },martini = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['maximize-2'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },maximize = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },medal = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['megaphone-off'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },megaphone = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },meh = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['memory-stick'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },menu = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },merge = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 9
                },['message-circle-code'] = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-circle-dashed'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-circle-heart'] = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-circle-more'] = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-circle-off'] = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-circle-plus'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-circle-question'] = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-circle-reply'] = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-circle-warning'] = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-circle-x'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-circle'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-code'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-dashed'] = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-diff'] = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-dot'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-heart'] = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-lock'] = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-more'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-off'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-plus'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-quote'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-reply'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-share'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-text'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-warning'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square-x'] = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['message-square'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['messages-square'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['mic-off'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['mic-vocal'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },mic = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },microchip = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },microscope = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },microwave = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },milestone = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['milk-off'] = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },milk = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['minimize-2'] = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },minimize = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },minus = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-check'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-cog'] = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-dot'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-down'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-off'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-pause'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-play'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-smartphone'] = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-speaker'] = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-stop'] = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-up'] = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['monitor-x'] = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },monitor = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['moon-star'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },moon = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['mountain-snow'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },mountain = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['mouse-off'] = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['mouse-pointer-2'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['mouse-pointer-ban'] = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['mouse-pointer-click'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['mouse-pointer'] = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },mouse = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-3d'] = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-diagonal-2'] = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-diagonal'] = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-down-left'] = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-down-right'] = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-down'] = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-horizontal'] = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-left'] = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-right'] = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-up-left'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-up-right'] = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-up'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['move-vertical'] = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },move = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['music-2'] = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['music-3'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['music-4'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },music = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['navigation-2-off'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['navigation-2'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['navigation-off'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },navigation = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },network = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },newspaper = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },nfc = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['notebook-pen'] = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['notebook-tabs'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['notebook-text'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },notebook = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['notepad-text-dashed'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['notepad-text'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['nut-off'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },nut = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['octagon-alert'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['octagon-minus'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['octagon-pause'] = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },['octagon-x'] = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 10
                },octagon = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },omega = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },option = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },orbit = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },origami = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['package-2'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['package-check'] = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['package-minus'] = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['package-open'] = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['package-plus'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['package-search'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['package-x'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },package = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['paint-bucket'] = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['paint-roller'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['paintbrush-vertical'] = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },paintbrush = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },palette = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-bottom-close'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-bottom-dashed'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-bottom-open'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-bottom'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-left-close'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-left-dashed'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-left-open'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-left'] = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-right-close'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-right-dashed'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-right-open'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-right'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-top-close'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-top-dashed'] = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-top-open'] = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panel-top'] = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panels-left-bottom'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panels-right-bottom'] = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['panels-top-left'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },paperclip = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },parentheses = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['parking-meter'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['party-popper'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pause = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['paw-print'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pc-case'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pen-line'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pen-off'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pen-tool'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pen = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pencil-line'] = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pencil-off'] = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pencil-ruler'] = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pencil = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pentagon = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },percent = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['person-standing'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['philippine-peso'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['phone-call'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['phone-forwarded'] = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['phone-incoming'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['phone-missed'] = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['phone-off'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['phone-outgoing'] = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },phone = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pi = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },piano = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pickaxe = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['picture-in-picture-2'] = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['picture-in-picture'] = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['piggy-bank'] = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pilcrow-left'] = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pilcrow-right'] = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pilcrow = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pill-bottle'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pill = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pin-off'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pin = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pipette = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pizza = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['plane-landing'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['plane-takeoff'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },plane = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },play = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['plug-2'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['plug-zap'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },plug = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },plus = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pocket-knife'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pocket = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },podcast = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pointer-off'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },pointer = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },popcorn = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },popsicle = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['pound-sterling'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['power-off'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },power = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },presentation = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },['printer-check'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },printer = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },projector = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 11
                },proportions = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },puzzle = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },pyramid = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['qr-code'] = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },quote = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },rabbit = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },radar = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },radiation = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },radical = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['radio-receiver'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['radio-tower'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },radio = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },radius = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rail-symbol'] = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },rainbow = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },rat = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },ratio = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['receipt-cent'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['receipt-euro'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['receipt-indian-rupee'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['receipt-japanese-yen'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['receipt-pound-sterling'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['receipt-russian-ruble'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['receipt-swiss-franc'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['receipt-text'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },receipt = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rectangle-ellipsis'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rectangle-horizontal'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rectangle-vertical'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },recycle = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['redo-2'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['redo-dot'] = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },redo = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['refresh-ccw-dot'] = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['refresh-ccw'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['refresh-cw-off'] = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['refresh-cw'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },refrigerator = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },regex = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['remove-formatting'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['repeat-1'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['repeat-2'] = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['repeat'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['replace-all'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },replace = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['reply-all'] = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },reply = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },rewind = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },ribbon = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },rocket = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rocking-chair'] = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['roller-coaster'] = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rotate-3d'] = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rotate-ccw-square'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rotate-ccw'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rotate-cw-square'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rotate-cw'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['route-off'] = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },route = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },router = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rows-2'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rows-3'] = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['rows-4'] = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },rss = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },ruler = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['russian-ruble'] = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },sailboat = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },salad = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },sandwich = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['satellite-dish'] = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },satellite = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['save-all'] = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['save-off'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },save = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scale-3d'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },scale = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },scaling = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scan-barcode'] = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scan-eye'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scan-face'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scan-heart'] = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scan-line'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scan-qr-code'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scan-search'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scan-text'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },scan = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },school = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scissors-line-dashed'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },scissors = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['screen-share-off'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['screen-share'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['scroll-text'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },scroll = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['search-check'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['search-code'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['search-slash'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['search-x'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },search = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },section = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['send-horizontal'] = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 12
                },['send-to-back'] = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },send = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['separator-horizontal'] = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['separator-vertical'] = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['server-cog'] = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['server-crash'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['server-off'] = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },server = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['settings-2'] = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },settings = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },shapes = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['share-2'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },share = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },sheet = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },shell = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shield-alert'] = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shield-ban'] = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shield-check'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shield-ellipsis'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shield-half'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shield-minus'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shield-off'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shield-plus'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shield-question'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shield-x'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },shield = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['ship-wheel'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },ship = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },shirt = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shopping-bag'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shopping-basket'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shopping-cart'] = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },shovel = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['shower-head'] = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },shrink = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },shrub = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },shuffle = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },sigma = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['signal-high'] = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['signal-low'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['signal-medium'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['signal-zero'] = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },signal = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },signature = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['signpost-big'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },signpost = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },siren = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['skip-back'] = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['skip-forward'] = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },skull = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },slack = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },slash = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },slice = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['sliders-horizontal'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['sliders-vertical'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['smartphone-charging'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['smartphone-nfc'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },smartphone = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['smile-plus'] = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },smile = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },snail = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },snowflake = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },sofa = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },soup = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },space = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },spade = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },sparkle = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },sparkles = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },speaker = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },speech = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['spell-check-2'] = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['spell-check'] = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },spline = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },split = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['spray-can'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },sprout = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-activity'] = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-down-left'] = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-down-right'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-down'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-left'] = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-out-down-left'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-out-down-right'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-out-up-left'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-out-up-right'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-right'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-up-left'] = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-up-right'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-arrow-up'] = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-asterisk'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-bottom-dashed-scissors'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-chart-gantt'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-check-big'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-check'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-chevron-down'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-chevron-left'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-chevron-right'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-chevron-up'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-code'] = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-dashed-bottom-code'] = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 13
                },['square-dashed-bottom'] = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-dashed-kanban'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-dashed-mouse-pointer'] = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-dashed'] = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-divide'] = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-dot'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-equal'] = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-function'] = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-kanban'] = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-library'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-m'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-menu'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-minus'] = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-mouse-pointer'] = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-parking-off'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-parking'] = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-pen'] = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-percent'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-pi'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-pilcrow'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-play'] = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-plus'] = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-power'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-radical'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-scissors'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-sigma'] = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-slash'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-split-horizontal'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-split-vertical'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-square'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-stack'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-terminal'] = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-user-round'] = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-user'] = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['square-x'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },square = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },squircle = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },squirrel = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },stamp = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['star-half'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['star-off'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },star = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['step-back'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['step-forward'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },stethoscope = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },sticker = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['sticky-note'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },store = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['stretch-horizontal'] = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['stretch-vertical'] = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },strikethrough = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },subscript = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['sun-dim'] = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['sun-medium'] = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['sun-moon'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['sun-snow'] = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },sun = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },sunrise = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },sunset = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },superscript = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['swatch-book'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['swiss-franc'] = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['switch-camera'] = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },sword = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },swords = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },syringe = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['table-2'] = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['table-cells-merge'] = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['table-cells-split'] = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['table-columns-split'] = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['table-of-contents'] = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['table-properties'] = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['table-rows-split'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },table = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['tablet-smartphone'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },tablet = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },tablets = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },tag = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },tags = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['tally-1'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['tally-2'] = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['tally-3'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['tally-4'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['tally-5'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },tangent = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },target = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },telescope = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['tent-tree'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },tent = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },terminal = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['test-tube-diagonal'] = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['test-tube'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['test-tubes'] = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['text-cursor-input'] = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['text-cursor'] = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['text-quote'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['text-search'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['text-select'] = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },text = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },theater = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 14
                },['thermometer-snowflake'] = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['thermometer-sun'] = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },thermometer = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['thumbs-down'] = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['thumbs-up'] = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['ticket-check'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['ticket-minus'] = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['ticket-percent'] = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['ticket-plus'] = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['ticket-slash'] = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['ticket-x'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },ticket = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['tickets-plane'] = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },tickets = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['timer-off'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['timer-reset'] = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },timer = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['toggle-left'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['toggle-right'] = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },toilet = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },tornado = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },torus = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['touchpad-off'] = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },touchpad = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['tower-control'] = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['toy-brick'] = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },tractor = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['traffic-cone'] = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['train-front-tunnel'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['train-front'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['train-track'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['tram-front'] = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['trash-2'] = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },trash = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['tree-deciduous'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['tree-palm'] = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['tree-pine'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },trees = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },trello = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['trending-down'] = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['trending-up-down'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['trending-up'] = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['triangle-alert'] = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['triangle-dashed'] = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['triangle-right'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },triangle = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },trophy = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },truck = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },turtle = {
                    ImageRectPosition = Vector2.new(768, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['tv-minimal-play'] = {
                    ImageRectPosition = Vector2.new(864, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['tv-minimal'] = {
                    ImageRectPosition = Vector2.new(0, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },tv = {
                    ImageRectPosition = Vector2.new(96, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },twitch = {
                    ImageRectPosition = Vector2.new(192, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },twitter = {
                    ImageRectPosition = Vector2.new(288, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['type-outline'] = {
                    ImageRectPosition = Vector2.new(384, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },type = {
                    ImageRectPosition = Vector2.new(480, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['umbrella-off'] = {
                    ImageRectPosition = Vector2.new(576, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },umbrella = {
                    ImageRectPosition = Vector2.new(672, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },underline = {
                    ImageRectPosition = Vector2.new(768, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['undo-2'] = {
                    ImageRectPosition = Vector2.new(864, 480),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['undo-dot'] = {
                    ImageRectPosition = Vector2.new(0, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },undo = {
                    ImageRectPosition = Vector2.new(96, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['unfold-horizontal'] = {
                    ImageRectPosition = Vector2.new(192, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['unfold-vertical'] = {
                    ImageRectPosition = Vector2.new(288, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },ungroup = {
                    ImageRectPosition = Vector2.new(384, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },university = {
                    ImageRectPosition = Vector2.new(480, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['unlink-2'] = {
                    ImageRectPosition = Vector2.new(576, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },unlink = {
                    ImageRectPosition = Vector2.new(672, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },unplug = {
                    ImageRectPosition = Vector2.new(768, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },upload = {
                    ImageRectPosition = Vector2.new(864, 576),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },usb = {
                    ImageRectPosition = Vector2.new(0, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-check'] = {
                    ImageRectPosition = Vector2.new(96, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-cog'] = {
                    ImageRectPosition = Vector2.new(192, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-minus'] = {
                    ImageRectPosition = Vector2.new(288, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-pen'] = {
                    ImageRectPosition = Vector2.new(384, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-plus'] = {
                    ImageRectPosition = Vector2.new(480, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-round-check'] = {
                    ImageRectPosition = Vector2.new(576, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-round-cog'] = {
                    ImageRectPosition = Vector2.new(672, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-round-minus'] = {
                    ImageRectPosition = Vector2.new(768, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-round-pen'] = {
                    ImageRectPosition = Vector2.new(864, 672),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-round-plus'] = {
                    ImageRectPosition = Vector2.new(0, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-round-search'] = {
                    ImageRectPosition = Vector2.new(96, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-round-x'] = {
                    ImageRectPosition = Vector2.new(192, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-round'] = {
                    ImageRectPosition = Vector2.new(288, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-search'] = {
                    ImageRectPosition = Vector2.new(384, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['user-x'] = {
                    ImageRectPosition = Vector2.new(480, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },user = {
                    ImageRectPosition = Vector2.new(576, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['users-round'] = {
                    ImageRectPosition = Vector2.new(672, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },users = {
                    ImageRectPosition = Vector2.new(768, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['utensils-crossed'] = {
                    ImageRectPosition = Vector2.new(864, 768),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },utensils = {
                    ImageRectPosition = Vector2.new(0, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['utility-pole'] = {
                    ImageRectPosition = Vector2.new(96, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },variable = {
                    ImageRectPosition = Vector2.new(192, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },vault = {
                    ImageRectPosition = Vector2.new(288, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },vegan = {
                    ImageRectPosition = Vector2.new(384, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['venetian-mask'] = {
                    ImageRectPosition = Vector2.new(480, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['vibrate-off'] = {
                    ImageRectPosition = Vector2.new(576, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },vibrate = {
                    ImageRectPosition = Vector2.new(672, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },['video-off'] = {
                    ImageRectPosition = Vector2.new(768, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },video = {
                    ImageRectPosition = Vector2.new(864, 864),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 15
                },videotape = {
                    ImageRectPosition = Vector2.new(0, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },view = {
                    ImageRectPosition = Vector2.new(96, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },voicemail = {
                    ImageRectPosition = Vector2.new(192, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },volleyball = {
                    ImageRectPosition = Vector2.new(288, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['volume-1'] = {
                    ImageRectPosition = Vector2.new(384, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['volume-2'] = {
                    ImageRectPosition = Vector2.new(480, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['volume-off'] = {
                    ImageRectPosition = Vector2.new(576, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['volume-x'] = {
                    ImageRectPosition = Vector2.new(672, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },volume = {
                    ImageRectPosition = Vector2.new(768, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },vote = {
                    ImageRectPosition = Vector2.new(864, 0),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wallet-cards'] = {
                    ImageRectPosition = Vector2.new(0, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wallet-minimal'] = {
                    ImageRectPosition = Vector2.new(96, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },wallet = {
                    ImageRectPosition = Vector2.new(192, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },wallpaper = {
                    ImageRectPosition = Vector2.new(288, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wand-sparkles'] = {
                    ImageRectPosition = Vector2.new(384, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },wand = {
                    ImageRectPosition = Vector2.new(480, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },warehouse = {
                    ImageRectPosition = Vector2.new(576, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['washing-machine'] = {
                    ImageRectPosition = Vector2.new(672, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },watch = {
                    ImageRectPosition = Vector2.new(768, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['waves-ladder'] = {
                    ImageRectPosition = Vector2.new(864, 96),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },waves = {
                    ImageRectPosition = Vector2.new(0, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },waypoints = {
                    ImageRectPosition = Vector2.new(96, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },webcam = {
                    ImageRectPosition = Vector2.new(192, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['webhook-off'] = {
                    ImageRectPosition = Vector2.new(288, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },webhook = {
                    ImageRectPosition = Vector2.new(384, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },weight = {
                    ImageRectPosition = Vector2.new(480, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wheat-off'] = {
                    ImageRectPosition = Vector2.new(576, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },wheat = {
                    ImageRectPosition = Vector2.new(672, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['whole-word'] = {
                    ImageRectPosition = Vector2.new(768, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wifi-high'] = {
                    ImageRectPosition = Vector2.new(864, 192),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wifi-low'] = {
                    ImageRectPosition = Vector2.new(0, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wifi-off'] = {
                    ImageRectPosition = Vector2.new(96, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wifi-zero'] = {
                    ImageRectPosition = Vector2.new(192, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },wifi = {
                    ImageRectPosition = Vector2.new(288, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wind-arrow-down'] = {
                    ImageRectPosition = Vector2.new(384, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },wind = {
                    ImageRectPosition = Vector2.new(480, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wine-off'] = {
                    ImageRectPosition = Vector2.new(576, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },wine = {
                    ImageRectPosition = Vector2.new(672, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },workflow = {
                    ImageRectPosition = Vector2.new(768, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },worm = {
                    ImageRectPosition = Vector2.new(864, 288),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['wrap-text'] = {
                    ImageRectPosition = Vector2.new(0, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },wrench = {
                    ImageRectPosition = Vector2.new(96, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },x = {
                    ImageRectPosition = Vector2.new(192, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },youtube = {
                    ImageRectPosition = Vector2.new(288, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['zap-off'] = {
                    ImageRectPosition = Vector2.new(384, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },zap = {
                    ImageRectPosition = Vector2.new(480, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['zoom-in'] = {
                    ImageRectPosition = Vector2.new(576, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                },['zoom-out'] = {
                    ImageRectPosition = Vector2.new(672, 384),
                    ImageRectSize = Vector2.new(96, 96),
                    Image = 16
                }}
        }
    end
}
return e(a['3e'])