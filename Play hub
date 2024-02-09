local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/thanhdat4461/OrionMoblie/main/source')))()
local Window = OrionLib:MakeWindow({Name = "PLAY HUB | Premium", HidePremium = false, IntroText = "Play HUB | Premium", SaveConfig = true, ConfigFolder = "OrionTest"})

    local PremiumTab = Window:MakeTab({
    Name = "AutoFarms",
    Icon = "rbxassetid://7733765398",
    PremiumOnly = false
  })

    local section = PremiumTab:AddSection({
    Name = "Summon Banner 2"
})

PremiumTab:AddToggle({
    Name = "open",
    Default = false,
    Callback = function(Value)
        if Value == true then
            stopScript = false
            while not stopScript do
                wait(0.001)
                local args = {
    [1] = "10",
    [2] = "2"
}

game:GetService("ReplicatedStorage").Remotes.Summon:InvokeServer(unpack(args))
        end
      end
    end
      })

    local section = PremiumTab:AddSection({
    Name = "Farms"
})

local stopScript = false

PremiumTab:AddToggle({
    Name = "Namek Night",
    Default = false,
    Callback = function(Value)
        if Value == true then
            stopScript = false
            while not stopScript do
                wait(0.001)
                local args1 = {
                    [1] = "Yami",
                    [2] = CFrame.new(-217.91534423828125, 22.39946746826172, 38.55649948120117) * CFrame.Angles(-0, 0, -0)
                }
                game:GetService("ReplicatedStorage").Remotes.PlaceTower:FireServer(unpack(args1))

                local args2 = {
                    [1] = "Saitama (Bored)",
                    [2] = CFrame.new(-223.1605987548828, 22.399490356445312, 46.12135696411133) * CFrame.Angles(-0, 0, -0)
                }
                game:GetService("ReplicatedStorage").Remotes.PlaceTower:FireServer(unpack(args2))
                    end
      end
      if Value == false then
    stopScript = true
   while not stopScript do
                wait(0.001)
                local args1 = {[1] = "Yami",
                    [2] = CFrame.new(-217.91534423828125, 22.39946746826172, 38.55649948120117) * CFrame.Angles(-0, 0, -0)
                }
                game:GetService("ReplicatedStorage").Remotes.PlaceTower:FireServer(unpack(args1))
                  end
      end
    end
  })
