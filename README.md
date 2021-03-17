# TALI (Telmo's Arch Linux Installer)

![](tali.png)

## Setup

First of all, boot your [Arch Linux live CD](https://www.archlinux.org/download/).

You'll need an internet connection to use this script, if you need to use Wi-Fi type `iwctl` to find your Wi-Fi network and connect to it.

Then, download the script and run it:

```
loadkeys br-abnt2
pacman -Sy git --noconfirm
git clone https://github.com/telmotrooper/tali
tali/install.py
```
