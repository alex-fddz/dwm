# alex-fddz/suckless/dwm

See dwm's [README](./README) for requirements, installation, running, and configuration.
*TLDR*: Run `sudo make clean install`, add `exec dwm` to `.xinitrc` and run it with `startx`.

## Keybindings

Freely inspired by pop-shell.

### Navigation
* `Super`+`j`: Focus next window in the stack.
    * +`Shift`: Move active window down the stack.
* `Super`+`k`: Focus previous window in the stack.
    * +`Shift`: Move active window up the stack.
* `Super`+`q`: Close window.

### Master
* `Super`+`Enter`: Make active window master.
* `Super`+`[`: Decrease number of windows on master.
* `Super`+`]`: Increase number of windows on master.
* `Super`+`h`: Decrease master size.
* `Super`+`l`: Increase master size.

### Tags (Workspaces)
* `Super`+`1-9`: Focus to tag *n*.
    * +`Shift`: Move active window to tag *n*.
* `Super`+`0`: View all windows on screen.
    * +`Shift`: Make active window appear on all tags.

### Multi-monitor setup
* `Super`+`.`: Focus next screen (`>`).
    * +`Shift`: Move active window to next screen.
* `Super`+`,`: Focus previous screen (`<`).
    * +`Shift`: Move active window to previous screen.

### Layouts
* `Super`+`g`: Float and un-float window.
* `Super`+`y`: Toggle Floating layout.
    * +`Shift`: Set Tiling (Master-Stack) layout.
* `Super`+`m`: Toggle Monocle layout.
* `Super`+`\`: Cycle through (extra) layouts.

### Applications
* `Super`+`t`: Terminal.
* `Super`+`f`: File manager.
* `Super`+`b`: Internet Browser.
* `Super`+`e`: Email client.
* `Super`+`c`: Calendar.

### Utilities
* `Alt`+`Space`: Application launcher (dmenu).
* `Super`+`v`: Clipboard manager.
* `Super`+`p`: Display configuration (arandr).
* `Alt`+`.`: Emoji selector.
* `Super`+`Space`: Keyboard layout switcher.

### dwm
* `Super`+`Shift`+`Q`: Quit dwm cleanly.
* `Super`+`Shift`+`B`: Show/hide top bar.

## Patches
`#movestack` `#uselessgaps` `#threecolumn` `cyclelayouts*`

## TODO
* [x] Set Keybindings
* [ ] Enable laptop controls
    * [ ] Volume
    * [ ] Screen Brightness
* [ ] Patch / additional functionality
    * [x] Move windows
    * [x] Gaps + smart gaps option
    * [ ] Alt-Tab (no-preview)
    * [ ] Directional navigation
    * [ ] Status/Systray
    * [x] Monocle and Floating layout toggles
    * [x] Cycle layouts
    * [x] Three-column layout
    * [ ] Spiral/Fibonacci layout
    * [ ] Hide empty tags/workspaces
    * [ ] Colors/pywal
    * [ ] Top bar color

