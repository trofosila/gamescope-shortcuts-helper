# gamescope-shortcuts-helper

### Clone
```
git clone https://aur.archlinux.org/gamescope-shortcuts.git
```

### Remotes
```
git remote add upstream https://gitlab.archlinux.org/archlinux/packaging/packages/gamescope.git

git remote add publish ssh://aur@aur.archlinux.org/gamescope-shortcuts.git
```

### Pull upstream
```
git pull upstream main
```

### Merge upstream
```
git merge upstream/main master
```

### Publish to AUR
```
git push -u publish master
```

### Remove official gamescope package without its dependencies
```
sudo pacman -Rd --nodeps gamescope
```

### Install gamescope-shortcuts
```
yay -S --needed gamescope-shortcuts
```