# Rice BSPWM

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
- [Fonts](https://damieng.com/blog/2008/05/26/envy-code-r-preview-7-coding-font-released/)
- [firefox theme](https://addons.mozilla.org/en-US/firefox/addon/arctic-nord-theme/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)

## Catppuccin
- [Polybar](https://github.com/miscellaneous-mice/polybar)
- [Alacritty](https://github.com/catppuccin/alacritty)
- [Firefox](https://addons.mozilla.org/en-GB/firefox/addon/catppuccin/)
- [Rofi](https://github.com/catppuccin/rofi/tree/main)
- [Wallpaper](https://github.com/Gingeh/wallpapers/tree/main)
- [Theme](https://github.com/catppuccin/gtk)
- [Icon](https://github.com/catppuccin/papirus-folders)
- [Others](https://github.com/catppuccin/catppuccin)
