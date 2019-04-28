GridMove (Forked for extended 3-digit Win+G shortcuts)
========

Tool for aligning windows to a grid on Windows.
**NOTE**: Requires [AutoHotkey](https://www.autohotkey.com/download/ahk-install.exe).

Setup / Running:
------------

1. After downloading and extracting the project ZIP or cloning the repository, move the base directory to wherever you intended to keep it permanently *(The program sets some paths on first run relative to its current position that it expects to remain unchanged)*.

2. Assuming the current standard version of AutoHotkey is installed, double-click `GridMove.ahk` in the project's root directory.

3. You should see a *"first-run"* popup showing you around. You may also be presented with an error about a grid resource missing. You can dismiss this error if it comes up.

Usage:
-------------

The main interface for the tool is the system tray. There, you can control which grids you'd like to align to, and how to align to them.

One of the default options for window alignment is by *"middle-mouse-button dragging"* which is also my personal preference.

I also find that for HD and 4K monitors, `xipergrid2` is my favorite alignment grid.

Fork details:
------------

This fork fixes an #include path in the most recent push of the official branch, which otherwise would break the tool entirely.

It also adds Win+G command support for 3-digit grid spaces *(useful for xipergrid2 and other grids meant for high-res displays)*.
