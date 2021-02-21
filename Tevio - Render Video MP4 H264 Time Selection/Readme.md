
# Tevio - Render Video MP4 H264 Time Selection
Custom: Tevio - Render Video MP4 H264 Time Selection

### Create this custom action on Reaper in this order:

| Function name | Description                    |
| ------------- | ------------------------------ |
| `help()`      | Script: mpl_Set render directory to 'Render' in project folder.lua|
| `destroy()`   | **Destroy your computer!**     |

1. 
2. Script: Tevio - Set render time selection Track format to Video MP4 h264.lua `<download>` : [Tevio Script_SRTSTFTVMH] (https://github.com)
3. Script: mpl_Enable add rendered files to project after render.lua
4. File: Render project, using the most recent render settings, auto-close render dialog
5. Script: me2beats_Select only last track.lua
6. Script: X-Raym_Move selected tracks up to the top of the visible track list.lua
7. Script: mpl_Disable add rendered files to project after render.lua
8. Script: Apply render preset - Default.lua
