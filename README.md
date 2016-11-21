# gimp-git
Unofficial Arch Linux repository building the latest GIMP every now and then.

Add this at the end of your `/etc/pacman.conf`:  
```ini
[gimp-git]
Server = https://swyter.github.io/$repo/
SigLevel = Optional
```

Refresh your local database with `pacman -Sy` and install packages like this: `pacman -S gimp-git`.
