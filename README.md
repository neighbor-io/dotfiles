# Reproduce package list across devices
Generate list of installed packages to text file:
```
paru -Qeq > packages.txt
```

Use [paru](https://github.com/Morganamilo/paru) as it handles pacman and AUR packages to install everything from generated text file:
```
paru -S --needed - < packages.txt
```

## Example
List from Framework 13
```
amd-ucode
base
base-devel
bash-completion
bluez
bluez-utils
brightnessctl
chromium
code
easyeffects
efibootmgr
fastfetch
firefox
foot
fzf
git
grim
gst-plugin-pipewire
htop
i3status-rust
imv
iwd
kanshi
libpulse
libreoffice-fresh
lightdm
lightdm-gtk-greeter
linux
linux-firmware
lvm2
mako
mpv
nano
neovim
network-manager-applet
networkmanager
notesnook-bin
paru
paru-debug
pavucontrol
pipewire
pipewire-alsa
pipewire-jack
pipewire-pulse
polkit-gnome
power-profiles-daemon
python-gobject
shortwave
slurp
smartmontools
sof-firmware
spotify
swappy
sway
swaybg
swayidle
swaylock
thunar
thunar-archive-plugin
thunar-volman
ttf-dejavu
vim
vulkan-radeon
waybar
wget
wireless_tools
wireplumber
wmenu
woff2-font-awesome
xdg-user-dirs
xdg-utils
xf86-video-amdgpu
xf86-video-ati
xorg-server
xorg-xinit
xorg-xwayland
zram-generator
```