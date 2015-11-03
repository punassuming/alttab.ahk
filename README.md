

AltTab.ahk
==========

[![Join the chat at https://gitter.im/ralesi/alttab.ahk](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ralesi/alttab.ahk?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
This version of AltTab.ahk features:

* Styling changes (dark theme by ralesi)
* Multi-monitor support (by ralesi)
* Windows 64-bit compatibility
* No warnings from AutoHotKey when using two-finger scrolling
* Hidden group support (by h46incon)
* Tray icon hidden optional, and custom tray icon support (by h46incon)


  ALT-TAB REPLACEMENT (WITH ICONS AND WINDOW TITLES IN A LISTVIEW).

  Latest version can be found at: http://file.autohotkey.net/evl/AltTab/AltTab.ahk
  Forum topic for discussion: http://www.autohotkey.com/forum/viewtopic.php?t=6422

HOTKEYS:
--------

Default:    Alt+Tab - move forwards in window stack
Alt+Shift+Tab - move backwards in window stack
Alt+Esc - cancel switching window
Mouse wheel over the taskbar scrolls the list - Middle button selects a window in this mode.
Window Groups can be assigned hotkeys to load the group/cycle through the windows.

EVENTS:
  Double-click a row to select that item and switch to it.

  Type first letter of program's title to cycle through them while still holding Alt

  Columns can be sorted by clicking on their titles.

  Tabs (window groups) can be re-ordered by drag-and-drop.

  Right-Click (context menu):
  Basic hotkey support for switching to specific windows (using window groups and adding window classes)
  Exclude (and un-exclude) specific windows and specific .EXEs - see "Window Groups" below.
  Window Groups - define lists of windows to easily switch between only showing certain apps.
  Manage groups of windows and processes (min/max all, close all, etc).

  Close windows:
  Alt+Middle mouse - close window under the mouse pointer in the Alt-Tab listview.
  Alt+\ "hotkey"  - close selected window (while list is displayed)
  Alt+/ "hotkey"  - close ALL windows whose EXE matches that of the selected entry (while list is displayed)
  Process menu entry - end selected process or all instance of the EXE in the list.

SETTINGS:
  See "; USER EDITABLE SETTINGS:" section near top of source code.

  TO EXIT:
  Choose Exit from the system tray icon's menu.

NOTE: Stroke-It (and maybe other mouse gesture programs) can cause the context menu to be shown twice/problematic.
Solution: exclude the program within the gesture recognition program (window title = Alt-Tab Replacement).

An autohotkey utility to cycle
This is a public repository for tracking changes I have made to the AltTab.ahk script for AutoHotKey.

See http://www.autohotkey.com/forum/topic6422.html for background on using AltTab.ahk.
