# gtranotify
Translate and Notify selected text with http://mymemory.translated.net/. Many thanks to "KarBoraN" for translation app idea.

## Prerequisites

### Debian based:
```
sudo apt install python3-pip xsel
sudo pip3 install translate
```

## Install
```
sudo mkdir -p /usr/share/gtranotify/
sudo cp gtranotify.py /usr/share/gtranotify/gtranotify.py
sudo chmod +x /usr/share/gtranotify/gtranotify.py
```

#### for XFCE shortcut :
```
xfconf-query -c xfce4-keyboard-shortcuts -p /commands/custom/<Primary>t -s python /usr/share/gtranotify/gtranotify.py
```
