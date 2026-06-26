My Arch India
=======
Your arch live distro for [MyPayIndia](https://mypayindia.com) banking everywere!

![MyArchIndia Logo](https://github.com/Spebelgenenst/MyArchIndia/blob/main/assets/myarchindia-logo.png?raw=true)

Build your own
=======
1. clone the repo
```
git clone https://github.com/Spebelgenenst/MyArchIndia
```

2. install archiso
```
sudo pacman -S archiso
```
or
```
yay -S archiso
```

3. select the default website in iso/airootfs/home/mpi/.config/autostart/firefox_mpi.desktop (default is [mypayindia.sbs](https://mypayindia.sbs))

4. select the package list
- if you want the smallest iso that works for banking, just leave it
- if you want to do anything else rename packages_for_usable_system.x86_64

5. build the iso
```
sudo mkarchiso -v -r -w /tmp/myarchindia -o MyArchIndiaIso MyArchIndia/iso
```

Attributions
=======
This is a modified version of the releng config from [archiso](https://github.com/archlinux/archiso). Archiso is licensed as GPL-3.0

License
=======

MyArchIndia is licensed under the terms of the **GPL-3.0-or-later** (see `LICENSE <LICENSE>`_).
