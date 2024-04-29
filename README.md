# dot

Dotfiles for i3+urxvt with minimal dependencies.

## Main files

Move the following files to ~:
 - `.Xdefaults`
 - `.xinitrc`
 
Move the following file to `.config/i3/config` or wherever the i3 config file lives:
 - `i3config`


## Common fixes

### Stop middle mouse button pasting from clipboard

Install `xbindkeys`, and put `.xbindkeysrc` in ~.

Uncomment the `xbindkeys` line in `.xinitrc`.

### Brightness keys

Install `xev`. Run `xev` and press the key you want to use to set brightness to min.
TODO

### Volume keys

Install `amixer` for Volume Up, Volume Down, and Mute keys on most keyboards.

### Screenshot with PrintSc key

Install `scrot`. Pressing PrintSc will let you select an area. Screenshot will be saved to ~.

### Nicer font

Install Input Mono font. Good luck. 
Then uncomment the lines mentioning Input Mono in the i3 config and .Xdefaults.

### Terminal font size

Cannot be adjusted for open terminal windows, but to open a "large-print" terminal press $mod+Ctrl+Return.

Set for all urxvt windows in `.Xdefaults`.
