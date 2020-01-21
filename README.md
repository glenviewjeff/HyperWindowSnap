# Hyper Window Snap

Hyper Window Snap is a script for [AutoHotKey] that expands upon Windows built-in window-snapping hotkeys (which are <kbd>Win</kbd> + <kbd>LEFT</kbd> by adding many new snap methods, including docking, moving, shrinking, windows. It can also detach Chrome tabs into a new window in a desired screen position.

## Installation Steps

1. Install [AutoHotKey]
2. Copy or Download the **HyperWindowSnap.ahk** file to your computer and double click it to run it.
3. (Optional) To have the program run when you start up your computer, place the .ahk file into your computer's [startup] folder. 
    * The Windows 7 startup folder can be accessed by mousing to **Start** > **All Programs**, then right-clicking on **Startup** and selecting "**Open**".
    * For newer windows versions, the startup folder can be accessed by tapping <kbd>Win</kbd> + <kbd>R</kbd> on your keyboard, then in the Open: field, type `shell:startup` then press <kbd>Enter</kbd>.

## Hyper Window Snap Keybindings

**NOTE:** Numeric keypad hotkeys will work only if you have NumLock turned **ON**. 

### Dock Windows to Fixed Positions:
Hotkey | Behavior
------ | --------
<kbd>Win</kbd> + <kbd>Numpad 7</kbd> | Window will snap to the top-left **quarter** of the screen.
<kbd>Win</kbd> + <kbd>Numpad 8</kbd> | Window will snap to the top **half** of the screen.
<kbd>Win</kbd> + <kbd>Numpad 9</kbd> | Window will snap to the top-right **quarter** of the screen.
<kbd>Win</kbd> + <kbd>Numpad 4</kbd> | Window will snap to the left **half** of the screen.
<kbd>Win</kbd> + <kbd>Numpad 6</kbd> | Window will snap to the right **half** of the screen.
<kbd>Win</kbd> + <kbd>Numpad 1</kbd> | Window will snap to the bottom-left **quarter** of the screen.
<kbd>Win</kbd> + <kbd>Numpad 2</kbd> | Window will snap to the bottom **half** of the screen.
<kbd>Win</kbd> + <kbd>Numpad 3</kbd> | Window will snap to the bottom-right **quarter** of the screen.

### Shrink Windows:
<kbd>Alt</kbd> + <kbd>Win</kbd> + numeric keypad direction will shrink the active window in the direction of the keypad, either by half or quarter as applicable.

Hotkey | Behavior
------ | --------
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 7</kbd> | Window will shrink **up & left**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 8</kbd> | Window will shrink **up**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 9</kbd> | Window will shrink **up & right**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 4</kbd> | Window will shrink **left**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 6</kbd> | Window will shrink **right**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 1</kbd> | Window will shrink **down & left**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 2</kbd> | Window will shrink **down**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 3</kbd> | Window will shrink **down & right**.

### "Scoot" Windows:
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad</kbd> will "scoot" windows in the specified direction, jumping one window width in the direction selected. This works alongside window shrinking, to create subquadrants. **Minor Note:** the keypad 1 and 3 directions aren't yet implemented, but the ones below are functional.

Hotkey | Behavior
------ | --------
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 7</kbd> | Window will move **up & left**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 8</kbd> | Window will move **up**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 9</kbd> | Window will move **up & right**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 4</kbd> | Window will move **left**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 6</kbd> | Window will move **right**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 1</kbd> | Window will move **down & left**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 2</kbd> | Window will move **down**.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad 3</kbd> | Window will move **down & right**.

### Detach Chrome Tab and Snap New Window:
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad</kbd> moves the current Chrome tab into a new window positioned according to the keypad direction chosen.

Hotkey | Behavior
------ | --------
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 7</kbd> | Window will snap to the top-left **quarter** of the screen.
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 8</kbd> | Window will snap to the top **half** of the screen.
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 9</kbd> | Window will snap to the top-right **quarter** of the screen.
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 4</kbd> | Window will snap to the left **half** of the screen.
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 6</kbd> | Window will snap to the right **half** of the screen.
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 1</kbd> | Window will snap to the bottom-left **quarter** of the screen.
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 2</kbd> | Window will snap to the bottom **half** of the screen.
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 3</kbd> | Window will snap to the bottom-right **quarter** of the screen.


### Ctrl + Numberpad Hotkeys for Sizing Wide Landscape Windows:
Hotkey | Behavior
------ | --------
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>Numpad 8</kbd> | Window will snap to the top **third** of the screen.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>Numpad 2</kbd> | Window will snap to the bottom **third** of the screen

### Directional Arrow Hotkeys for Sizing Wide Landscape Windows:
Hotkey | Behavior
------ | --------
<kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>UP</kbd> | Window will snap to the top **half** of the screen.
<kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>DOWN</kbd> | Window will snap to the bottom **half** of the screen.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>UP</kbd> | Window will snap to the top **third** of the screen.
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Alt</kbd> + <kbd>DOWN</kbd> | Window will snap to the bottom **third** of the screen.

## Changelog

- **v1.00**, *19 Jan 2020*
    - Initial Version forked from Advanced Window Snap

## Recommendation For Editing AHK Files
If you plan on working with AutoHotKey files, consider using [Sublime Text 3]. Read my steps for setting up Sublime Text 3 to edit AutoHotKey files here: [Working with AutoHotKey in Sublime Text].

[AutoHotKey]:http://ahkscript.org/
[startup]:http://www.autohotkey.com/docs/FAQ.htm#Startup]
[Sublime Text 3]:http://www.sublimetext.com/3
[Package Control]:https://packagecontrol.io/installation
[AutoHotKey Package]:https://packagecontrol.io/packages/AutoHotkey
[Working with AutoHotKey in Sublime Text]:https://gist.github.com/AWMooreCO/d0308bab265cc8c5e122
