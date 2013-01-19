Muffin Debug Topics
---------------
This is a small Cinnamon applet that can toggle the debug topics for the window manager Muffin.

Installation
---------------
Just copy the folder 'muffin-debug@cobinja.de' to '$HOME/.local/share/cinnamon/applets' or create a corresponding softlink. Then you can enable it via Cinnamon Settings

Usage
--------------
The Applet provides a popup menu with various items which control debug topics. Unfortunately there is no public API in Muffin to check for the status of the topics, so the applet assumes that all topics are disabled on startup.

The menu item 'Verbose' turns on the most verbose mode, which includes all other topics.
>This mode is very very verbose, so you should hopefully never have to use it.
