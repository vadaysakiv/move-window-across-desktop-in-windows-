As I haven't used AutoHotkey before, I needed to figure out a few additional steps (compared to what is explained in the existing answers) to find a working solution:

Download and install AutoHotKey
Clone the VD.ahk repository (it is an AutoHotkey library adding several script functions for managing virtual desktops)
Inside the cloned directory, create a new file (arbitrary name, ending with .ahk) and paste the content from @Lorenzo Morelli's answer into it.
Double-click the script to run it. The shortcuts (Win+Ctrl+Shift+→: Move current window to the next desktop; Win+Ctrl+Shift+←: Move current window to the previous desktop) should now work.
To make sure the script runs on every Windows startup, create a shortcut to it and put it into the folder for your Startup programs. Open that folder by typing shell:startup in the window that pops up after you hit Win + R.
