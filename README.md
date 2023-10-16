# BSPWM_Rice

**All the necessary stuff can be found [here](https://github.com/VaughnValle/blue-sky/blob/master/README.md) and [here](https://github.com/miscellaneous-mice/Linux_Rice)**


![Rice_1](https://github.com/miscellaneous-mice/BSPWM_Rice/assets/79500624/63345835-d6e7-4000-a39e-003ad16191ea)

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
