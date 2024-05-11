--Loadstring ("Moveable")
local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
--Ui Window
local Window = Library.CreateLib("ExampleHub", "Ocean")
--Creating Tabs ["Easy"]
local Tab = Window:NewTab("Universal")
--Section ["what is my memory doing."] [Simple]
local Section = Tab:NewSection("Whatever this is")
--Slider ["Intermediate"] I didn't remember if the end had the ")"
Section:NewSlider("jumpPower", "pls", 500, 50, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)
--Button [Intermediate]
Section:NewButton("MySpeedy", "Scaripati", function()
  loadstring(game:HttpGet("https://pastebin.com/raw/KC992jTi"))();
    print("Clicked")
end)
--loadstring(game:HttpGet("https://pastebin.com/raw/KC992jTi"))(); is my Script.

--Next Up Credits tabs
--Tab
local Tab = Window:NewTab("Credits")
--Use The Sections It's Easy
--Sections
local Section = Tab:NewSection("Tutorial On YT")
