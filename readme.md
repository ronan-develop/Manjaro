# Manjaro

## Commands

|           Action            |                                               Command                                                |
|:---------------------------:|:----------------------------------------------------------------------------------------------------:|
|       save pckg name        |                                      pacman -Qqen > pkglist.txt                                      |
|     save AUR pckg name      |                                     pacman -Qqm > aurpkglist.txt                                     |
|   install saves packages    |                                   sudo pacman -S $(< pkglist.txt)                                    |
|          merge pdf          |                               pdfunite file1.pdf file2.pdf merged.pdf                                |
| compress pdf (ghost script) | gs -sDEVICE=pdfwrite -dPDFSETTINGS=/ebook   -dNOPAUSE -dBATCH -sOutputFile=output.pdf Image-0001.pdf |
|         convert pdf         |                                 convert file.png -quality 0 file.pdf                                 |

## Keyboard shortcuts

|     action     |         shortcut         |
|:--------------:|:------------------------:|
| change desktop | ctrl + alt + right arrow |