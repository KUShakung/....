    local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/naypramx/Ui__Project/Script/XeNonUi", true))()
    library:CreateWatermark("SleepHub") -- Config แตกนะเดียวค่อยแก้รอเน็ตมาก่อน By MeowX#0001
    local CenterHubNo1 = library:CreateWindow("SleepHub | Select Mode Bloxfruit ",Enum.KeyCode.RightControl)
    local Tab = CenterHubNo1:CreateTab("Main")
    local Main = Tab:CreateSector("Select Mode","left")
    Main:AddButton("Mode FarmLevel[ComingSoon]",function()
        
    end)
    Main:AddButton("Mode PVP",function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/KUShakung/PVP/main/README.md"))()
    end)
