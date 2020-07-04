# Herbstluftwm-config

This repo holds my personal config files for Herbstluftwm

It looks like this:

![Herbstluftwm on DragonflyBSD](https://github.com/Stargirl-chan/herbstluftwm-config/blob/master/dfly.png)

![Herbstluftwm on openSUSE](https://github.com/Stargirl-chan/herbstluftwm-config/blob/master/openSUSE.png)

## Keybinds

```
Mod=Super

# basic keybinds
$Mod-Shift-q		quit
$Mod-Shift-r		reload
$Mod-Shift-c		close
$Mod-Return		spawn st
$Mod-F3			spawn dmenu_run

# cycle through tags
$Mod-period		use_index +1
$Mod-comma		use_index -1

# layouting
$Mod-r			remove
$Mod-space		cycle_layout
$Mod-u			split vertical
$Mod-o			split horizontal
$Mod-s			floating toggle
$Mod-f			fullscreen toggle
$Mod-p			pseudotile toggle

# resizing
$Mod-Control-Left	resize left
$Mod-Control-Down	resize down
$Mod-Control-Up		resize up
$Mod-Control-Right	resize right

# mouse
$Mod-Button1		move
$Mod-Button2		resize
$Mod-Button3		zoom

# focus
$Mod-BackSpace		cycle_monitor
$Mod-Tab		cycle_all +1
$Mod-Shift-Tab		cycle_all -1
$Mod-c			cycle
$Mod-Left		focus left
$Mod-Down		focus down
$Mod-Up			focus up
$Mod-Right		focus right
$Mod-Shift-Left		shift left
$Mod-Shift-Down		shift down
$Mod-Shift-Up		shift up
$Mod-Shift-Right	shift right
```

## Q&A

**Can I use this?** *Maybe*

**How to install?** Instructions added when it's finished

**I love you!** Well thanks kind stanger that is totaly not me
