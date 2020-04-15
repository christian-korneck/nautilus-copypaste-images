nautilus-copypaste-images
=========================

Provides a context menu entry in Nautilus (Gnome3 File Browser) to copy/paste the contents of an image file to the clipboard. 

Fork of [nautilus-copypaste-images](https://github.com/atareao/nautilus-copypaste-images) with minimal fixes for Fedora 31.

Installation (Fedora 31)
------------------------

```
sudo dnf -y install nautilus-python
curl -L https://raw.githubusercontent.com/christian-korneck/nautilus-copypaste-images/master/src/nautilus-copypaste-images.py -o /usr/share/nautilus-python/extensions/nautilus-copypaste-images.py
nautilus -q
```

