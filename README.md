# dotfiles
For a simple but clean i3-gaps setup

## Xorg Dependencies:
* xorg-server
* xorg-server-xephyr
* xorg-twm
* xorg-xclock
* xorg-xinit
* xorg-xmodmap
* xterm

## DE Dependencies
* lightdm
* lightdm-mini-greeter AUR
* i3
* dmenu
* i3-gaps
* networkmanager
* networkmanager-applet
* compton
* terminator
* polybar AUR
* feh
* i3lock

## Adjust
* DPI Scaling in .Xresources and .config/i3/config
* Adjust height, dpi, and border size in .config/polybar/config
* LightDM mini greeter colors and login size in lightdm-mini-greeter.conf
* Fonts and text size in .config/{terminator/config, i3/config, i3status/config}

## Notes
Make sure i3.desktop file makes it into /usr/share/xsessions/

Lightdm configs go in: /etc/lightdm/

Top level dotfiles go in ~

.config gets merged into ~/.config

![Desktop Screenshot](https://raw.githubusercontent.com/kobrient/dotfiles/master/2018-01-18-142926_scrot.png)
