# UltrawideWindows

My own fork to make it run using Fx buttons instead Numpad due compact key board.

Updates made from tag 4.2 to work with KDE 5.27 and Ubuntu 24.04

F1 -> down-left </br>
F2 -> center-left</br>
F3 -> up-left</br>
</br>
F4 -> down-center</br>
F5 -> center-center</br>
F6 -> up-center</br>
</br>
F7 -> down-right</br>
F8 -> center-right</br>
F9 -> up-center</br>

It also works with the combination of CTRL and ALT keys (ALT+F4 is disabled)


# Pre Installation

You have to disable shortcuts with Meta+Fx, Ctrl+Fx and Alt+Fx before run the installation or the keys here will not be added properly

# Installation

```bash
$ git clone git@github.com:felipepossari/UltrawideWindows.git
$ cd UltrawideWindows
$ plasmapkg2 --type=kwinscript -i .
$ kwin_x11 --replace &
```


# Update


```bash
$ cd UltrawideWindows
$ ./scripts/update.sh
```

# Remove

```bash
$ cd UltrawideWindows
$ plasmapkg2 --type=kwinscript -r .
```
