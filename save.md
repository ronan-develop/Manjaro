# Manjaro

# Save and restore

|        Command         |             action              |
|:----------------------:|:-------------------------------:|
|   save packages name   |   pacman -Qqen > pkglist.txt    |
| install saves packages | sudo pacman -S $(< pkglist.txt) |