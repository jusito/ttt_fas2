# Patch Gmod FAS2

Patch for: FA:S 2.0 Alpha SWEPs
https://steamcommunity.com/sharedfiles/filedetails/?id=180507408

Shotgun:
[ERROR] lua/weapons/fas2_base_shotgun/shared.lua:291: attempt to call method 'RestartGesture' (a nil value)
  1. ShotgunThink - lua/weapons/fas2_base_shotgun/shared.lua:291
   2. unknown - lua/weapons/fas2_base/shared.lua:1041

The animation is visible but errors occure, the line looks not needed.