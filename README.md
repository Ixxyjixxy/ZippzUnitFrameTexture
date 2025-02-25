Change the default player, target and focus frames texture using Sharedmedia.
To change the texture edit the ZippzUnitFrameTexture.lua file and find within the code shown below where it says "Flat" to any texture using Sharedmedia capability.
local newTexture = media:Fetch("statusbar", "Flat") -- Change this to any SharedMedia texture
