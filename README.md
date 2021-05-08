# GTK-Mixer

[![Build-macOS-latest Actions Status](https://github.com/rozhuk-im/gtk-mixer/workflows/build-macos-latest/badge.svg)](https://github.com/rozhuk-im/gtk-mixer/actions)
[![Build-Ubuntu-latest Actions Status](https://github.com/rozhuk-im/gtk-mixer/workflows/build-ubuntu-latest/badge.svg)](https://github.com/rozhuk-im/gtk-mixer/actions)


Rozhuk Ivan <rozhuk.im@gmail.com> 2020 - 2021

GTK-Mixer is GTK based volume control tool ("mixer").\
GUI from xfce4-mixer: https://gitlab.xfce.org/apps/xfce4-mixer
but xfce4 and gstreamer does not used.


## Licence
GPL2 licence.


## Features
* plugins for support different sound backens
* change system default sound card
* set volume per line/channel
* enable/disable lines (mute/unmute)
* detect sound cards connect/disconnect
* detect default sound card change


## Compilation

### Linux
```
sudo apt-get install build-essential git cmake libgtk-3-dev libasound2-dev fakeroot
git clone https://github.com/rozhuk-im/gtk-mixer.git
cd gtk-mixer
mkdir build
cd build
cmake ..
make -j 4
```

### FreeBSD/DragonFlyBSD
```
sudo pkg install git cmake x11-toolkits/gtk30
git clone https://github.com/rozhuk-im/gtk-mixer.git
cd gtk-mixer
mkdir build
cd build
cmake ..
make -j 4
```
