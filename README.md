# code-nautilus

This repo provides a visual studio code extension for Nautilus. This is forked from cra0zy/code-nautilus with following changes:
- instead of "Open Code here" when clicking on empty space, this will show "Open in Code". This is more consistent with the approach that Gnome 3.34+ uses with "Open in Terminal" command instead of "Open Terminal here". The casing is also altered to closely match Gnome files style.
- the install script is changed to use my script instead of pulling the file from cra0zy's repo.

## Install Extension

```
wget -qO- https://raw.githubusercontent.com/shaoormunir/code-nautilus/master/install.sh | bash
```

## Uninstall Extension

```
rm -f ~/.local/share/nautilus-python/extensions/code-nautilus.py
```
