## Setup

The `pkglist.txt` file contains all the packages that can
be installed with the regular `pacman`. To do so:

> __NOTE__: Don't do that. Still, if you want to install
my packages, don't blame me for anything that happens to you.

```bash
sudo pacman -S --needed - < pkglist.txt
```

Likewise, the `aur_pkglist.txt` contains all the [AUR](https://aur.archlinux.org/) packages. To install them, do:

```bash
paru -S --needed - < aur_pkglist.txt # or yay, maybe
```
