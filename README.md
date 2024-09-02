# gamescope-shortcuts-helper

Official `gamescope` package:  
https://archlinux.org/packages/extra/x86_64/gamescope/

`gamescope-shortcuts` in AUR:  
https://aur.archlinux.org/packages/gamescope-shortcuts

v3-0001-always-send-ctrl-1-2-to-steam-s-wayland-session.patch:  
https://github.com/hhd-dev/handheld-gamescope/blob/master/v3-0001-always-send-ctrl-1-2-to-steam-s-wayland-session.patch

### Clone `gamescope-shortcuts` PKGBUILD repo
```
git clone https://aur.archlinux.org/gamescope-shortcuts.git
```

### Remotes
```
git remote add upstream https://gitlab.archlinux.org/archlinux/packaging/packages/gamescope.git

git remote add publish ssh://aur@aur.archlinux.org/gamescope-shortcuts.git
```

### Pull upstream `gamescope` repo
```
git pull upstream main
```

### Merge upstream `gamescope` repo
```
git merge upstream/main master
```

### Publish to AUR
```
git push -u publish master
```

### Remove official `gamescope` package without dependencies
```
sudo pacman -Rd --nodeps gamescope
```

### Install `gamescope-shortcuts`
```
yay -S --needed gamescope-shortcuts
```