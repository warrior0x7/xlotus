# Extended Lotus
A collection of shell scripts that extends the functionality of my system

> [!Warning]
>These scripts are still work in progress, so it's advisable not to use them
>in production. Use at your own risk. I am not responsible for any damage caused
>by scripts here

## Dependencies
- a terminal with sixel support
- fzf
- cliphist
- chafa
- bat
- curl

### Arch Linux
I personally use `konsole` because it supports both RTL and sixel
```Bash
sudo pacman -Sy --needed konsole
```
Other dependencies:
```Bash
sudo pacman -Sy --needed fzf cliphist chafa bat curl
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
