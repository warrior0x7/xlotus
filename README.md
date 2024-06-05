# eXtended Lotus
A collection of shell scripts that extends the functionality of my system

> [!Warning]
>These scripts are still work in progress, so it's advisable not to use them
>in production. Use at your own risk. I am not responsible for any damage caused
>by scripts here.

## Scripts
|Script|Description|
|--|--|
|xl-yt|YouTube RSS feed aggregator using FZF|
|xl-rgb|Color converter to RGB, Hex or 0-255 index terminal color|
|xl-cmd|Runner for user-defined commands|
|xl-headd|Run commands on headphone jack plug/unplug|
|xl-prayer|(Islam) Print next prayer and its time|

## Dependencies
- a terminal with sixel support
- fzf
- chafa
- bat
- curl
- awk
- xclip (X11)
- wl-clipboard (Wayland)
- acpid
- jq

### Arch Linux
I personally use `konsole` because it supports both RTL and sixel
```Bash
sudo pacman -Sy --needed konsole
```
#### Xorg
```Bash
sudo pacman -Sy --needed fzf chafa bat curl gawk acpid jq xclip
```
#### Wayland
```Bash
sudo pacman -Sy --needed fzf chafa bat curl gawk acpid jq wl-clipboard
```

## Getting started
1. Clone the repo
```Bash
git clone https://github.com/warrior0x7/xlotus.git
cd xlotus
```
2. Scripts including the installer itself have help pages. Start by reading the help page of the installer
```Bash
./install --help
```

3. Invoking install script without arguments installs everything
```Bash
./install
```

## Support
[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.me/warrior0x7) | [![Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/Warrior0x7/donate)
|--|--|
