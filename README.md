# BSPWM_Rice

**Credit** : https://github.com/VaughnValle/blue-sky/

**All the necessary stuff can be found [here](https://github.com/VaughnValle/blue-sky/blob/master/README.md) and [here](https://github.com/miscellaneous-mice/Linux_Rice)**


![4](https://github.com/miscellaneous-mice/BSPWM_Rice/assets/79500624/acff8caf-239f-4642-bb71-18ddc49fe4b3)


## Polybar configuration
- First replace the ```~/.config/bspwm/bspwmrc```
```
$ mv ~/.config/bspwm/bspwmrc ~/Backup
$ cp ~/BSPWM_Rice/.config/bspwm/bspwmrc ~/.config/bspwm/
$ chmod +x ~/.config/bspwm/bspwmrc
```
- Replace the polybar config files and install necessary fonts.
```
$ mv ~/.config/polybar/* ~/Backup/
$ cp -r ~/BSPWM_Rice/.config/polybar/* ~/.config/polybar/
$ cp -r ~/.config/polybar/fonts/* ~/.fonts/
```
- Next make all the files executable
```
$ chmod +x ~/.config/polybar/scripts/launcher
$ chmod +x ~/.config/polybar/scripts/powermenu_alt
```
## Changes
- You have to change with current repo
  - ```~/.config/alacritty/alacritty.yml```
  - ```~/.config/rofi/*```
  
## Theme
- [Theme](https://www.xfce-look.org/p/1267246/)
- [Icons](https://www.xfce-look.org/p/1937741)
