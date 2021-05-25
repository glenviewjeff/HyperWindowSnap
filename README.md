# Hyper Window Snap

Hyper Window Snap is a script for [AutoHotKey] that expands upon Windows built-in window-snapping hotkeys by adding many new snap methods, including docking, moving, and shrinking windows. It can also detach Chrome or Microsoft Edge browser tabs into a new window in a desired screen position.

## Installation Steps

1. Install [AutoHotKey]
2. Copy or Download the **HyperWindowSnap.ahk** file to your computer and double click it to run it.
3. (Optional) To have the program run when you start up your computer, place the .ahk file into your computer's [startup] folder. 
    * The Windows 7 startup folder can be accessed by mousing to **Start** > **All Programs**, then right-clicking on **Startup** and selecting "**Open**".
    * For newer windows versions, the startup folder can be accessed by tapping <kbd>Win</kbd> + <kbd>R</kbd> on your keyboard, then in the Open: field, type `shell:startup` then press <kbd>Enter</kbd>.

**NOTE:** Numeric keypad hotkeys will work only if you have NumLock turned **ON**. 

## Overview of Keyboard Shortcuts

The below modifier keys are used along with the numeric keypad to manipulate windows.

|Numpad Modifer Keys|Behavior|
|---|---|
|<kbd>No Modifier Key</kbd>|Activate the corresponding window.|
|<kbd>Win</kbd>|Dock window to the corner or side of the screen in the specified direction.|
|<kbd>Alt</kbd> + <kbd>Win</kbd>|Shrink window in the specified direction.|
|<kbd>Ctrl</kbd> + <kbd>Win</kbd>|"Scoot" window in the specified direction, jumping one window size in the direction selected. This works alongside window shrinking, to create subquadrants.|
|<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd>|Detach the current browser tab into a new window positioned according to the keypad direction chosen.|

| |Numeric Keypad| |
|---|---|---|
|<kbd>Numpad 7</kbd> <br/> towards top-left quarter|<kbd>Numpad 8</kbd> <br/> towards top half|<kbd>Numpad 9</kbd> <br/> towards top-right quarter|
|<kbd>Numpad 4</kbd> <br/> towards left half||<kbd>Numpad 6</kbd> <br/> towards right half|
|<kbd>Numpad 1</kbd> <br/> towards bottom-left quarter|<kbd>Numpad 2</kbd> <br/> towards bottom half|<kbd>Numpad 3</kbd> <br/> towards bottom-right quarter|

## Exhaustive Keyboard Shortcuts

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

### Activate Windows:
Hotkey | Behavior
------ | --------
<kbd>Numpad 7</kbd> | Activate window at the top-left **quarter** of the screen.
<kbd>Numpad 8</kbd> | Activate window at the top **half** of the screen.
<kbd>Numpad 9</kbd> | Activate window at the top-right **quarter** of the screen.
<kbd>Numpad 4</kbd> | Activate window at the left **half** of the screen.
<kbd>Numpad 6</kbd> | Activate window at the right **half** of the screen.
<kbd>Numpad 1</kbd> | Activate window at the bottom-left **quarter** of the screen.
<kbd>Numpad 2</kbd> | Activate window at the bottom **half** of the screen.
<kbd>Numpad 3</kbd> | Activate window at the bottom-right **quarter** of the screen.

### Shrink Windows:
<kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad</kbd> will shrink the active window in the direction of the keypad, either by half or quarter as applicable.

Hotkey | Behavior
------ | --------
<kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 7</kbd> | Window will shrink **up & left**.
<kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 8</kbd> | Window will shrink **up**.
<kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 9</kbd> | Window will shrink **up & right**.
<kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 4</kbd> | Window will shrink **left**.
<kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 6</kbd> | Window will shrink **right**.
<kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 1</kbd> | Window will shrink **down & left**.
<kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 2</kbd> | Window will shrink **down**.
<kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad 3</kbd> | Window will shrink **down & right**.

### "Scoot" Windows:
<kbd>Ctrl</kbd> + <kbd>Win</kbd> + <kbd>Numpad</kbd> will "scoot" windows in the specified direction, jumping one window width in the direction selected. This works alongside window shrinking, to create subquadrants. 

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

### Detach Browser Tab and Snap New Window:
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Win</kbd> + <kbd>Numpad</kbd> moves the current browser tab into a new window positioned according to the keypad direction chosen.

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

## Changelog

- **v1.00**, *19 Jan 2020*
    - Initial Version forked from Advanced Window Snap
