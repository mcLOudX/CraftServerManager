CraftServerManager
==================

Simple Bukkit server manager

========================================================
I. Introduction
========================================================

CraftServerManager is a simple Bukkit Server wrapper. 
Because it is simple, it doesn't offer very advanced 
functions like the other wrappers.

========================================================
II. Features
========================================================

- Auto start server. Double click and go.
- Send commands through the application
- Install plugin(s) then reload automatically. The server
  will temporarily stops when overwriting plugin(s) (i.e updating) then
  starts again after the plugin(s) is/are installed. All done automatically.
- Run batch commands (one command after another)
- Save and run command routines with modifiable arguments.
- No need to stop the server before closing. Clicking the exit
  button will automatically send "stop" command.
- Auto-detection of Essentials. Some commands will adapt to the change.

========================================================
III. Todo
========================================================

- Player list (haven't found a way yet)
- Auto update (bukkit.jar and CraftServerManager.exe)
