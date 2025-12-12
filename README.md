# Reproduce package list across devices
Generate list of installed packages to text file:
```
paru -Qeq > packages.txt
```

Use [paru](https://github.com/Morganamilo/paru) as it handles pacman and AUR packages to install everything from generated text file:
```
paru -S --needed - < packages.txt
```

Example `packages.txt` file can be found in repo for easy setup.

# Updated config files
Move all config folders to `~/.config/` and reload Sway with `mod+shift+c`.