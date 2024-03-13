# manjaro
My learning notes with Manjaro Linux

## configuration

## basic packages

## some AUR
> yay -S icaclient

> yay -S zoom-citrix-plugin

## chinese input method
> pacman -S fcitx5 fcitx5-qt fcitx5-gtk

### for plasma5/KDE
> pacman -S fcitx5-table-extra fcitx5-configtool

Go to System Settings > Virtual Keyboard, select "Fcitx 5"

Go to System Settings > Region & Language > Input Method, add "Quick Classic"

Open
> ~/.xprofile

Add
> XMODIFIERS=@im=fcitx


## tweaking Citrix icaclient for XenDesktop

## network/wifi
For MacBookAir6,2 with Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter
> sudo pacman -S broadcom-wl

## references
