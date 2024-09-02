# gamescope-shortcuts-helper

Official `gamescope` package:  
https://archlinux.org/packages/extra/x86_64/gamescope/

`gamescope-shortcuts` in AUR:  
https://aur.archlinux.org/packages/gamescope-shortcuts

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