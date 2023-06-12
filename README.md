local LBLG = Instance.new("ScreenGui", getParent)

local LBL = Instance.new("TextLabel", getParent)

local player = game.Players.LocalPlayer

LBLG.Name = "LBLG"

LBLG.Parent = game.CoreGui

LBLG.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

LBLG.Enabled = true

LBL.Name = "LBL"

LBL.Parent = LBLG

LBL.BackgroundColor3 = Color3.new(1, 1, 1)

LBL.BackgroundTransparency = 1

LBL.BorderColor3 = Color3.new(0, 0, 0)

LBL.Position = UDim2.new(0.75,0,0.010,0)

LBL.Size = UDim2.new(0, 133, 0, 30)

LBL.Font = Enum.Font.GothamSemibold

LBL.Text = "TextLabel"

LBL.TextColor3 = Color3.new(1, 1, 1)

LBL.TextScaled = true

LBL.TextSize = 14

LBL.TextWrapped = true

LBL.Visible = true

local FpsLabel = LBL

local Heartbeat = game:GetService("RunService").Heartbeat

local LastIteration, Start

local FrameUpdateTable = { }

local function HeartbeatUpdate()

	LastIteration = tick()	for Index = #FrameUpdateTable, 1, -1 do

		FrameUpdateTable[Index + 1] = (FrameUpdateTable[Index] >= LastIteration - 1) and FrameUpdateTable[Index] or nil

	end

	FrameUpdateTable[1] = LastIteration

	local CurrentFPS = (tick() - Start >= 1 and #FrameUpdateTable) or (#FrameUpdateTable / (tick() - Start))

	CurrentFPS = CurrentFPS - CurrentFPS % 1

	FpsLabel.Text = ("当前时间:"..os.date("%H").."时"..os.date("%M").."分"..os.date("%S"))

end

Start = tick()

Heartbeat:Connect(HeartbeatUpdate)

local OrionLib = loadstring(game:HttpGet('https://raw.githubusercontent.com/WS857960/-/main/UI.txt'))()

local Window = OrionLib:MakeWindow({Name = "神光脚本重置版", HidePremium = false, SaveConfig = true, ConfigFolder = "神光脚本重制版"})

local Key = Window:MakeTab({

  Name = "岩脚本密钥",

  Icon = "rbxassetid://13429676701",

  PremiumOnly = false

})

 

playername=tostring(game.Players.LocalPlayer.Character);

 

function rightkey()

  OrionLib:MakeNotification({

    Name = "你已添加了密钥用户",

    Content = "你的密钥输入正确-正在启动脚本中-请耐心等待",

    Image = "rbxassetid://13429676701",

    Time = 10

  })

end

 

function load()

  rightkey()

  loadstring(game:HttpGet("https://pastebin.com/raw/vWM2smCZ"))()

end

 

function wrong002()

  OrionLib:MakeNotification({

    Name = "很抱歉，你没有添加密钥用户",

    Content = "你没有卡你情去联系1907157070所以快去",

    Image = "rbxassetid://13429676701",

    Time = 10

  })

end

 

function wrong()

  OrionLib:MakeNotification({

    Name = "你已添加密钥用户",

    Content = "你的密钥错误",

    Image = "rbxassetid://114514",

    Time = 8

  })

end

--密钥和用户名的编辑区

function yhm()

  if playername == "rctcttctc" then

    if Input == "独断万古荒天帝" then

      load()

     else

      wrong()

    end

   else

    yhm1()

  end

end

function yhm1()

  if playername == "xckaoq" then

    if Input == "神" then

      load()

     else

      wrong()

    end

   else

    yhm2()

  end

end

function yhm2()

  if playername == "Chuzhixoan" then

    if Input == "czx" then

      load()

     else

      wrong()

    end

   else

    yhm3()

  end

end

function yhm3()

  if playername == "qwaszxerdfcvtbyh" then

    if Input == "114514" then

      load()

     else

      wrong()

    end

   else

    yhm4()

  end

end

function yhm4()

  if playername == "china80567" then

    if Input == "zm" then

      load()

     else

      wrong()

    end

   else

    yhm5()

  end

end

function yhm5()

  if playername == "用户名" then

    if Input == "卡密" then

      load()

     else

      wrong()

    end

   else

    yhm6()

  end

end

function yhm6()

  if playername == "用户名" then

    if Input == "卡密" then

      load()

     else

      wrong()

    end

   else

    yhm7()

  end

end

function yhm7()

  if playername == "用户名" then

    if Input == "卡密" then

      load()

     else

      wrong()

    end

   else

    yhm8()

  end

end

function yhm8()

  if playername == "dgugouougu" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm9()

  end

end

function yhm9()

  if playername == "lenchenawa114" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm10()

  end

end

function yhm10()

  if playername == "hgcgchvbh" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm11()

  end

end

function yhm11()

  if playername == "fffghjgjh" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm12()

  end

end

function yhm12()

  if playername == "x55411" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm13()

  end

end

function yhm13()

  if playername == "ksbeitong" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm14()

  end

end

function yhm14()

  if playername == "CN_zhc" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm15()

  end

end

function yhm15()

  if playername == "Chuzhixoan" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm16()

  end

end

function yhm16()

  if playername == "vfghnmklop" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm17()

  end

end

function yhm17()

  if playername == "qwer114514kun" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm18()

  end

end

function yhm18()

  if playername == "vvgxefn" then

    if Input == "6" then

      load()

     else

      wrong()

    end

   else

    yhm19()

  end

end

function yhm19()

  if playername == "用户名" then

    if Input == "卡密" then

      load()

     else

      wrong()

    end

   else

    yhm20()

  end

end

function yhm20()

  if playername == "用户名" then

    if Input == "卡密" then

      load()

     else

      wrong()

    end

   else

    yhm21()

  end

end

--验证区

Key:AddParagraph("脚本永久免费","")

Key:AddParagraph("你的用户名是:"..playername,"")

Key:AddParagraph("一人一卡免费作者1907157070","")

 

Key:AddTextbox({

  Name = "请输入你卡密",

  Default = "",

  TextDisappear = true,

  Callback = function(Value)

    Input = Value

  end

})

 

Key:AddButton({

  Name = "确定卡密",

  Callback = function()

    yhm()

  end

})

 

 

OrionLib:Init()
