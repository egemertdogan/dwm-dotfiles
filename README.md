# Gruvbox DWM

![Screenshot](https://raw.githubusercontent.com/egemertdogan/dwm-dotfiles/main/screenshot.png)

### Dependencies

| Packge Name   | Needed For What |
| ------------- | ------------- |
| feh  | For setup wallpaper  |
| picom  | For compositing  |
| (Optional) numlockx | For auto enable numlock |
| kitty | As a terminal |
| flameshot | For screenshot tool |
| dmenu | For application launcher |
| (Optional) Qutebrowser | For browser |
| pulseaudio | For audio control |
| sysstat | For CPU monitoring |
| FantasqueSansMono Nerd Font | For statusbar font |

### How to Setup
```
cd /tmp
git clone https://github.com/egemertdogan/dwm-dotfiles
cd dwm-dotfiles
cp .xinitrc ~/ #This will override your xinitrc!
cp dwm* ~/.config/
cd ~/.config/dwm/
sudo make clean install
cd ~/.config/dwmblocks/
sudo make clean install
```
#### For vim-ide (Vim with pathogen plugin manager and some plugins) # Optional
###### Warning! This steps will override your vimrc file and vim directory
```
cp /tmp/.vimrc ~/ && cp /tmp/.vim ~/ -r
```
