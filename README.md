# eXtended Lotus
A collection of shell scripts that extends the functionality of my system.

> [!Warning]
>These scripts are still work in progress, so it's advisable not to use them
>in production. Use at your own risk. I am not responsible for any damage caused
>by scripts here.

## Scripts
|Script|Description|
|--|--|
|xl-yt|YouTube RSS feed aggregator using fzf.|
|xl-rgb|Color converter to RGB, Hex or nearest 0-255 terminal index color.|
|xl-cmd|Run user-defined command presets.|
|xl-daemon|Run custom daemons in background.|
|xl-prayer|(Islam) Print next prayer and its time.|
|xl-jump|Faster cd and file editing with fzf.|
|xl-virt|Launch qemu virtual machines.|

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
- fd

### Arch Linux
1. Install a terminal. I use `konsole` because it supports both RTL and sixel.
    ```Bash
    sudo pacman -Sy --needed konsole
    ```
2. Install a clipboard manager
    - X11
        ```Bash
        sudo pacman -Sy --needed xclip
        ```
    - Wayland
        ```Bash
        sudo pacman -Sy --needed wl-clipboard
        ```
3. Install the rest of dependencies
    ```Bash
    sudo pacman -Sy --needed fzf chafa bat curl gawk acpid jq fd 
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
|Paypal|Liberapay|
|--|--|
[![paypal](assets/paypal.png)](https://www.paypal.me/warrior0x7) | [![Liberapay](assets/liberapay.png)](https://liberapay.com/Warrior0x7/donate)
