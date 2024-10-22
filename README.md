getgenv().Setting = {
    ["Team"] = "Marines", -- Marines / Pirates
    ["Auto Random & Store & Get Fruit"] = true,
    ["Use Move Predict"] = true,
    ["Hit and Run"] = true,
    ["Skip Fruit"] = {
        "Portal-Portal",
        "Leopard-Leopard"
    },
    ["Spam All Skill On V4"] = {
        ["Enabled"] = true,
        ["Weapons"] = {"Melee", "Gun", "Sword"}
    },
    ["Avoid V4"] = true,
    ["Safe Health"] = {30,50},
    ["Auto Chat"] = {""},
    ["Weapons"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Delay"] = 0,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["C"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["V"] = {["Enable"] = false, ["HoldTime"] = 0}
            }
        },
        ["Blox Fruit"] = {
            ["Enable"] = True,
            ["Delay"] = 0,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["C"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["V"] = {["Enable"] = true, ["HoldTime"] = 0.25},
                ["F"] = {["Enable"] = false, ["HoldTime"] = 0}
            }
        },
        ["Sword"] = {
            ["Enable"] = true,
            ["Delay"] = 0,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0.75}
            } 
        },
        ["Gun"] = {
            ["Enable"] = true,          
            ["Delay"] = 0,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0}
            } 
        }
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/Tsuo7/TsuoHub/main/autobounty"))()
