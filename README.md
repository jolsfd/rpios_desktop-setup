# Raspberry Pi OS Desktop Setup
Raspberry Pi OS 64bit setup by jolsfd

## Software
* Visual Studio Code
* Firefox ESR
* Passwordsafe
* Libre Office
* Audacity
* Gimp
* node.js, npm
* python3-matplotlib
* python3-pandas
* gnome-keyring
* dos2unix (Convert dos format to unix format)

## Theme

`sudo apt install arc-theme papirus-icon-theme`

change Theme by running `lxappearance`

* arc-dark
* papirus-icon-theme
* adwita

### Wallpaper

Download Wallpaper into Downloads and copy to /usr/share/rpd-wallpaper/

`sudo cp macish.jpg /usr/share/rpd-wallpaper/`

## config Files

`sudo nano /boot/config.txt`

`arm_freq_min=800`

## Default Apps

`sudo apt install lxsession-default-apps`

add `file_manager/command=nemo` in `/.config/lxsession/LXDE-pi/desktop.conf`

## Keyboard Hot Keys

File to change `/home/"username"/.config/openbox/lxde-pi-rc.xml`

File with old Hot keys `/etc/xdg/Openbox/lxde-pi-rc.xml`

add Terminal Hot Key

## Inspiration
[Novaspirit Tech Theme](https://www.youtube.com/watch?v=gHUjO6MK5fg)
[Novaspirit Tech Customization](https://www.youtube.com/watch?v=a_q87I4EpLM)
