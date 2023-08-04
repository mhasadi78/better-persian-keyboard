# Better Persian Keyboard for Linux
This is a customized keyboard layout symbol and rule file for Persian language in two major use cases:
1. When someone wants to have windows-like Persian keyboard layout
2. When someone wants to use Arabic Yeh (ي) by default, instead of Farsi Yeh (ی) in standard Persian keyboard
for some reason (i.e. some platforms like Adobe Connect doesn't support Farsi Yeh)
## How to use
First, backup your default configuration files
```
sudo cp /usr/share/X11/xkb/rules/evdev.xml /usr/share/X11/xkb/rules/original.evdev.xml 
sudo cp /usr/share/X11/xkb/symbols/ir /usr/share/X11/xkb/symbols/original.ir
```
Then, Substitute ``ir`` and ``evdev.xml`` files of this repository with your system defaults.

