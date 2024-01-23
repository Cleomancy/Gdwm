# Glorious DWM

![DWM logo](dwm.png)

## Rice:
I use DWM with dwmblocks as my status bar, st is my terminal and dmenu is my god.
This is my build of DWM with just enough patches to stay comfy.
Change my awful shortcuts if you have a QWERTY keyboard.

## Prerequisites:
I use arch btw,
```
pacman -Sy base-devel xorg-server xorg-xinit libxinerama libxft feh unclutter ttf-font-awesome ttf-hack
```
You can already guess my dotfiles.

## Patches:

- [shiftview.c](https://lists.suckless.org/dev/att-7590/shiftview.c)
- [fullgaps](https://dwm.suckless.org/patches/fullgaps/)
- [scratchpad](https://dwm.suckless.org/patches/scratchpad/)
- [swallow](https://dwm.suckless.org/patches/swallow/)
- [centeredmaster](https://dwm.suckless.org/patches/centeredmaster/)
- [statuscmd](https://dwm.suckless.org/patches/statuscmd/)

## Install:
```
cd Gdwm/
sudo make clean install
```

## Credits:

- [dwm](https://dwm.suckless.org/) obviously
- and Mental Outlaw for his [patching tutorial](https://odysee.com/@AlphaNerd:8/patching-suckless-programs-made-easy:3)

## To do:

better config.h, unused fucntions still.\
more rice?
