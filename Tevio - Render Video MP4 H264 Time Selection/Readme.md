
# Tevio - Render Video MP4 H264 Time Selection
Custom: Tevio - Render Video MP4 H264 Time Selection

***Create this custom action on Reaper in this order:***

  Script: mpl_Set render directory to 'Render' in project folder.lua
 
  Script: Tevio - Set render time selection Track format to Video MP4 h264.lua
  Script: mpl_Enable add rendered files to project after render.lua
  File: Render project, using the most recent render settings, auto-close render dialog
  Script: me2beats_Select only last track.lua
  Script: X-Raym_Move selected tracks up to the top of the visible track list.lua
  Script: mpl_Disable add rendered files to project after render.lua
  Script: Apply render preset - Default.lua
