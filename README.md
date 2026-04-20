
# Pre-compiled binary for niri intented to be one click install for Linux Mint 22.3 in mind

## Steps of compiling
* ```git clone https://github.com/niri-wm/niri.git```
* ```cargo install cargo-deb```
* In the niri directory we open the terminal and type ```cargo deb```
* Output will be located at **target/debian/**

### Important software to install berfore installing niri on Linux Mint

```bash
sudo apt update
sudo apt install gcc clang \
    libudev-dev libgbm-dev libxkbcommon-dev libegl1-mesa-dev \
    libwayland-dev libinput-dev libdbus-1-dev libsystemd-dev \
    libseat-dev libpipewire-0.3-dev libpango1.0-dev libdisplay-info-dev alacritty fuzzel
```

### Hope it is useful 

### Niri documentation

> Website https://niri-wm.github.io/niri/Configuration%3A-Introduction.html

### Useful Software to get started

> waybar https://github.com/Alexays/Waybar

> fuzzel https://codeberg.org/dnkl/fuzzel

> xwayland-satellite https://github.com/Supreeeme/xwayland-satellite

> swaybg https://github.com/swaywm/swaybg.git

> awesome-niri https://github.com/niri-wm/awesome-niri

### Showcase

![My Niri Setup](https://github.com/Agi0m/niri-mint/blob/main/My%20Niri%20Setup.png "Preview")

