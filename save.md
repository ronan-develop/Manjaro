# Manjaro

# Save and restore

|        Command         |             action              |
|:----------------------:|:-------------------------------:|
|     save pckg name     |   pacman -Qqen > pkglist.txt    |
|   save AUR pckg name   |  pacman -Qqm > aurpkglist.txt   |
| install saves packages | sudo pacman -S $(< pkglist.txt) |