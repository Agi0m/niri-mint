
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

## On the clone repo we have to move some files to in order to make niri work properly

* ``` sudo cp resources/niri-session /usr/local/bin/ ```
* ``` sudo cp resources/niri.desktop /usr/share/wayland-sessions/ ```
* ``` sudo cp resources/niri-portals.conf /usr/local/share/xdg-desktop-portal/ ```
* ``` sudo cp resources/niri.service /etc/systemd/user/ ```
* ``` sudo cp resources/niri-shutdown.target /etc/systemd/user/ ```


### Hope it is useful 

### Niri documentation

> Website https://niri-wm.github.io/niri/Configuration%3A-Introduction.html

### Useful Software to get started

> waybar https://github.com/Alexays/Waybar

> fuzzel https://codeberg.org/dnkl/fuzzel

> xwayland-satellite https://github.com/Supreeeme/xwayland-satellite

> swaybg https://github.com/swaywm/swaybg.git

> awesome-niri https://github.com/niri-wm/awesome-niri
