

_Create this custom action on Reaper in this order:_

| Function |         Name Script           |
| ------------- | ------------------------------ |
| 1. `Set and Create subdirectory for render video`      | Script: mpl_Set render directory to 'Render' in project folder.lua|
| 2. `destroy()`   | Script: Tevio - Set render time selection Track format to Video MP4 h264.lua     |
| 3. `destroy()`   | Script: mpl_Enable add rendered files to project after render.lua     |
|4.  `destroy()`   | File: Render project, using the most recent render settings, auto-close render dialog     |
| 5. `destroy()`   | Script: me2beats_Select only last track.lua     |
| 6. `destroy()`   | Script: X-Raym_Move selected tracks up to the top of the visible track list.lua  |
| 7. `destroy()`   | Script: mpl_Disable add rendered files to project after render.lua     |
| 8. `destroy()`   | Script: Apply render preset - Default.lua     |

1. 
2.  `<download>` : [Tevio Script_SRTSTFTVMH] (https://github.com)
3. 
4. 
5. 
6. 
7. 
8. 
