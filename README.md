## Wallpapers. 
This repository contains the wallpapers I prefer for my window manager setup. The wallpapers best suite with colorschemes such as The Dracula theme. 
I use hsetroot as my X wallpaper setter as it is very minimal, fast, and kind of respects one of suckless' Philosophies: Software should do one thing, and one thing only. 
You should probably use hsetroot as well. Even if you use feh, or nitrogen it is way superior than the wallpaper setters on those Dreaded Desktop 
Environments. If you are new to Window Managers, You can set wallpapers like this: 

If You Want to Use My Wallpapers: 
```bash
git clone https://github.com/dcodecrzft/Wallpapers.git
``` 
Install Hsetroot with your system's package manager, On Arch Systems:  
```bash
sudo pacman -S hsetroot
```
On Debian-based systems: 
```bash
sudo apt install hsetroot
```
On Gentoo Systems: 
```bash
sudo emerge --ask --quiet x11-misc/hsetroot
```
Actually Set The Wallpaper:
```bash
hsetroot -cover /path/to/the/picture/
```
For the wallpaper to persist on all your sessions with your preferred window manager, if you're using Xinit/Startx:
```bash
echo "hsetroot -cover /path/to/the/picture/ &" >> ~/.xinitrc
```
Credit:
Grabbed most of off reddit. r/unixporn for the win!
https://mocah.org
