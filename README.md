# manjaro
My learning notes with Manjaro Linux

## configuration

## pacman packages

```bash
pacman -S git dkms wireless_tools keepassxc bitwarden yay
```

## some AUR
```bash
yay -S icaclient
yay -S zoom-citrix-plugin
```

## for laptop power saving
```bash
pacman -S tlp
systemctl enable tlp --now
```

## chinese input method
```bash
pacman -S fcitx5 fcitx5-qt fcitx5-gtk
```

### for plasma5/KDE
```bash
pacman -S fcitx5-table-extra fcitx5-configtool
```

Go to System Settings > Input Devices > Virtual Keyboard, select "Fcitx 5"

Go to System Settings > Region & Language > Input Method, add "Quick Classic"

Open
> ~/.xprofile

Add
```bash
XMODIFIERS=@im=fcitx
```


## tweaking Citrix icaclient for XenDesktop

## network/wifi
For MacBookAir6,2 with Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter
```bash
sudo pacman -S broadcom-wl
```

## references
