# Manjaro

## scripts

### Prevent frozen or blocked network
[wifi and network disabled after waking up computer](./scripts/network-restart.service)

## Commands

|           Action            |                                               Command                                                |
|:---------------------------:|:----------------------------------------------------------------------------------------------------:|
|       save pckg name        |                                      pacman -Qqen > pkglist.txt                                      |
|     save AUR pckg name      |                                     pacman -Qqm > aurpkglist.txt                                     |
|   install saves packages    |                                   sudo pacman -S $(< pkglist.txt)                                    |
|          merge pdf          |                               pdfunite file1.pdf file2.pdf merged.pdf                                |
| compress pdf (ghost script) | gs -sDEVICE=pdfwrite -dPDFSETTINGS=/ebook   -dNOPAUSE -dBATCH -sOutputFile=output.pdf Image-0001.pdf |
|         convert pdf         |                                 convert file.png -quality 0 file.pdf                                 |
|     Updating the system     |    (check)                             pamac checkupdates -a                                         |
|     Updating the system     |    (apply)                               pamac upgrade -a                                            |
|  mettre à jour les paquets  |                                  sudo pacman -Syu | pamac update                                     |
|  gestionnaires des taches   |                           ctrl + esc -> accéssoires/gestionnaire de tâches                           |

## Keyboard shortcuts

|     action     |         shortcut         |
|:--------------:|:------------------------:|
| change desktop | ctrl + alt + right arrow |
