local MacLib: any = loadstring(game:HttpGet("https://github.com/biggaboy212/Maclib/releases/latest/download/maclib.txt"))()

local Window = MacLib:Window({
    Title = "KingLuc's Scripts",
    Subtitle = "ALPHA VERSION",
    Size = UDim2.fromOffset(800, 325),
    DragStyle = 2,
    DisabledWindowControls = {},
    ShowUserInfo = true,
    Keybind = Enum.KeyCode.RightControl,
    AcrylicBlur = false,
})

local GlobalSettingUIBlur = Window:GlobalSetting({
    Name = "UI Blur",
    Default = false,
    Callback = function(enabled)
        Window:SetAcrylicBlurState(enabled)
    end
})

Window:SetAcrylicBlurState(GlobalSettingUIBlur.Default)

local MainGroup = Window:TabGroup({
    Name = "MainGroup"
})

local MainTab = MainGroup:Tab({
    Name = "Main",
    Image = "rbxassetid://133278050769920"
})

local MainSection = MainTab:Section({
    Side = "Left"
})

MainSection:Button({
    Name = "Coming Soon™"
})

local RBTTab = MainGroup:Tab({
    Name = "Roblox's Got Talent",
    Image = "rbxassetid://133278050769920"
})

local RBTSection = RBTTab:Section({
    Side = "Left"
})

RBTSection:Button({
    Name = "Admin Area TP (RISKY)",
    Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(120.301392, 148.144531, -588.02478, -0.992546082, 0.073903434, -0.0969047248, 7.48791606e-09, 0.795149803, 0.606413066, 0.12186978, 0.601892948, -0.789222836)
    end
})
RBTSection:Button({
    Name = "Stage Left Side (Low-Risk)",
    Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(128.135391, 96.1581345, -378.547058, -0.47120896, -7.48401945e-08, 0.882021606, -8.92897276e-08, 1, 3.71488333e-08, -0.882021606, -6.12506099e-08, -0.47120896)
    end
})
