# Glorious DWM

![DWM logo](dwm.png)

## Rice:
I use DWM with dwmblocks, st is my terminal and dmenu is my god.
This is my build of DWM with just enough patches to stay comfy.
Change my awful shortcuts if you have a QWERTY keyboard.

## Prerequisites:
I use arch btw,
```
pacman -Sy base-devel xorg-server xorg-xinit libxinerama libxft
```
You can already guess my dotfiles.

## Patches:

- [shiftview.c](https://lists.suckless.org/dev/att-7590/shiftview.c)
- [fullgaps](https://dwm.suckless.org/patches/fullgaps/)
- [scratchpad](https://dwm.suckless.org/patches/scratchpad/)
- [swallow](https://dwm.suckless.org/patches/swallow/)
- [centeredmaster](https://dwm.suckless.org/patches/centeredmaster/)
- [sticky](https://dwm.suckless.org/patches/sticky/)
- [statuscmd](https://dwm.suckless.org/patches/statuscmd/)
- [Xresources](https://dwm.suckless.org/patches/xresources/)

## Install:
```
cd gdwm/
sudo make clean install
```

## Credits:

- [dwm](https://dwm.suckless.org/) obviously
