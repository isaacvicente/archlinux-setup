## Setup

The `pkglist.txt` file contains all the packages that can
be installed with the regular `pacman`. To do so:

> __NOTE__: Don't do that. Still, if you want to install
my packages, don't blame me for anything that happens to you.

```bash
sudo pacman -S --needed - < pkglist.txt
```

Likewise, the `aur_pkglist.txt` contains all the [AUR](https://aur.archlinux.org/) packages.
To install them, do:

```bash
paru -S --needed - < aur_pkglist.txt # or yay, maybe
```

## Restore `pacman` database

The database can be restored by moving the `pacman_database.tar.bz2` 
file into the `/` directory and executing the following command:

```bash
sudo tar -xjvf pacman_database.tar.bz2
```

> Taken from the [Arch Wiki](https://wiki.archlinux.org/title/Pacman/Tips_and_tricks#Back_up_the_pacman_database).
