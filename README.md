*Nautilus Backspace*
-----------------------
Brings back the Backspace shortcut to Nautilus

How to Installation ?
-----------------------
1) Install [Nautilus Python](https://wiki.gnome.org/Projects/NautilusPython) 
-----------------------
(`apt install python-nautilus` in Debian-based distributions)
---
(`yam install python-nautilus` in Fedora and Centos based distributions)
---
(`pacman -S python-nautilus` in Arch Linux-based distributions)
 
2) Move `Backspace.py` to here: `.local/share/nautilus-python/extensions/`

if not existis directory please create this directory first :)

3) Restart Nautilus by command (`killall nautilus`)
