-- Disvelop --

-- This script will:
-- 1) Facilitate conversion of player location to UsRe
-- 2) Handle cross-server communication setup
-- 3) Handle penalization for missing time

-- Last update: May 5, 2022


--[[
local connect = MessagingService:SubscribeAsync("Tournament",function(message)
	print("Tournament message received.")
	game.ReplicatedStorage.Events.Tourney:FireClient(plr)
end)
MessagingService:PublishAsync("Tournament",plr.Name)
]]

--[[
locationData = HTTPService:GetAsync("http://ip-api.com/json/")
location = HTTPService:JSONDecode(locationData)["countryCode"]
]]
