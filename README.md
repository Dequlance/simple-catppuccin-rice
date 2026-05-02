# simple-catppuccin-rice
Simple Hyprland catppuccin rice. Mostly made this repo for myself just to keep all the stuff organized and easily reproducable from a fresh Arch install, but feel free to use it as you wish! 
## Screenshots
![Hello:)](https://raw.githubusercontent.com/Dequlance/simple-catppuccin-rice/refs/heads/main/2026-04-14-100427_hyprshot.png)
### Apps we love to rice
```
sudo pacman -S dunst kitty nemo waybar wofi
```
Make sure to change .config file for `hyprland waybar and dunst` for your screen resolution

All the configs were changed to my preferences. Clone original repositories from the `credits` if you want original look

### Fonts
```
sudo pacman -S noto-fonts nerd-fonts noto-fonts-emoji ttf-noto-fonts ttf-nerd-fonts-symbols noto-fonts-extra noto-fonts-cjk otf-font-awesome
```
Necessary for correctly displayed fonts / emojis / special symbols / JP CN characters
### GTK theming (<=3.2)
```
sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si
```
```
sudo pacman -S dconf-editor
```
``` 
yay -S themix-full-git
```
GTK theme should go in to `.themes` folder. Enable it by typing `gtk-theme` in dconf-editor and selecting it by it is name
## Other apps
```
sudo pacman -S hyprpaper hyprshot ark vlc vlc-plugins-all btop geany hyprpolkitagent kio-admin pavucontrol steam telegram-desktop nwg-look qbittorrent git fastfetch
```
```
yay -S protonplus faugus-launcher vesktop
```
[Osu! install](https://github.com/NelloKudo/osu-winello#installation)
### Credits
Dunst colors [link](https://github.com/catppuccin/dunst/blob/main/themes/mocha.conf)

Dunst rules [link](https://github.com/Yutsuten/linux-config/blob/f371d907e1d00c633b9d0da1579bef8802e3c0c3/desktop/dunstrc.conf)

Kitty [link](https://github.com/catppuccin/kitty)

Waybar config [link](https://github.com/hajosattila/dotfiles/blob/main/config.jsonc)

Waybar style.css [link](https://github.com/hajosattila/dotfiles/blob/main/style.css)

Wofi [link](https://github.com/quantumfate/wofi)
