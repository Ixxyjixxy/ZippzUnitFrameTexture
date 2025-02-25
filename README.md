![Screenshot 2025-02-25 014958](https://github.com/user-attachments/assets/90eb410f-694c-4778-a28b-c0681619bc72)

Change the default player, target, focus and pet frames texture using Sharedmedia.

To change the texture edit the ZippzUnitFrameTexture.lua file and find within the code shown below where it says "Flat" to any texture using Sharedmedia capability.

local newTexture = media:Fetch("statusbar", "Flat") -- Change this to any SharedMedia texture
