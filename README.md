local v0=loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/BlackKing/main/Gui%20Lib%20%5BLibrary%5D"))();local v1=loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/COLORS/main/README.md"))();local v2=loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/Gui/main/Gui%20Lib%20%5BSaveManager%5D"))();local v3=loadstring(game:HttpGet("https://raw.githubusercontent.com/KINGHUB01/BlackKing/main/Blackking%20%5BGuiNew!%5D"))();local v4=Instance.new("Sound");v4.Parent=game.SoundService;v4.SoundId="rbxassetid://4590657391";v4.Volume=5;v4.PlayOnRemove=true;v4:Destroy();v3:Introduction();wait(1);v0:Notify("Loaded");local v44=v0:CreateWindow({Title="YOU HUB | Blade Ball | Version 1.1" ,Center=true,AutoShow=true,TabPadding=5,MenuFadeTime=0.2 + 0 });local v45={Main=v44:AddTab("Main")};local v46=v45.Main:AddLeftGroupbox(" ");game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.FieldOfView then game:GetService("Workspace").Camera.FieldOfView=_G.FieldOfViewe;end end);end);v46:AddSlider("MySlider",{Text="Field of View ",Default=120,Min=1226 -(1074 + 82) ,Max=120,Rounding=0 -0 ,Compact=true,Callback=function(v81)_G.FieldOfViewe=v81;end});_G.SelectBoots=1790.5 -(214 + 1570) ;_G.FieldOfViewe=120;v46:AddToggle("MyToggle",{Text="Enable Field of View",Default=false,Tooltip="Field of View Hack",Callback=function(v83)v0:Notify("Increase Field Of View Enable");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();local v84=1455 -(990 + 465) ;while true do if (0==v84) then if (v83==true) then local v449=0 + 0 ;local v450;while true do if (0==v449) then v450=game:GetService("TweenService");v450:Create(game.Workspace.CurrentCamera,TweenInfo.new(0.9),{FieldOfView=_G.FieldOfViewe}):Play();break;end end elseif (v83==false) then local v621=game:GetService("TweenService");v621:Create(game.Workspace.CurrentCamera,TweenInfo.new(0.9),{FieldOfView=31 + 39 }):Play();end wait(0.8 + 0 );v84=3 -2 ;end if (v84==1) then _G.FieldOfView=v83;break;end end end});game:GetService("RunService").RenderStepped:Connect(function()pcall(function()if _G.FullBright then local v315=0 + 0 ;while true do if (v315==1) then game:GetService("Lighting").ClockTime=47 -33 ;game:GetService("Lighting").GlobalShadows=false;v315=2;end if (v315==0) then game:GetService("Lighting").FogEnd=100000;game:GetService("Lighting").Brightness=3;v315=1;end if (v315==(1996 -(109 + 1885))) then game:GetService("Lighting").OutdoorAmbient=Color3.new(1,1,1);break;end end end end);end);v46:AddToggle("MyToggle",{Text="Fullbright",Default=false,Tooltip="No Darkness Light On All",Callback=function(v88)v0:Notify("Fullbright Enable");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();if v88 then _G.FullBright=true;else _G.FullBright=false;game:GetService("Lighting").FogEnd=11111111533265722 -(802 + 24) ;game:GetService("Lighting").Brightness=5 -2 ;game:GetService("Lighting").ClockTime=20;game:GetService("Lighting").GlobalShadows=false;game:GetService("Lighting").OutdoorAmbient=Color3.new(1,1,1);end end});v46:AddButton({Text="Auto Parry",Default=false,Tooltip="Auto Parry",Func=function()v0:Notify("");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/BladeBallScript/main/BLADEBALL"))();end});v46:AddButton({Text="Ball Locate Speed",Default=false,Tooltip="Locate Speed Of Ball",Func=function()v0:Notify("");local v171=Instance.new("Sound");v171.Parent=game.SoundService;v171.SoundId="rbxassetid://4590657391";v171.Volume=11 -6 ;v171.PlayOnRemove=true;v171:Destroy();loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/BladeBallScript/main/AutoParryBallByRechedmcvnAndWaterExecute"))();end});
