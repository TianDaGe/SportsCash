
Debian
====================
This directory contains files used to package sportscashd/sportscash-qt
for Debian-based Linux systems. If you compile sportscashd/sportscash-qt yourself, there are some useful files here.

## sportscash: URI support ##


sportscash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sportscash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sportscashqt binary to `/usr/bin`
and the `../../share/pixmaps/sportscash128.png` to `/usr/share/pixmaps`

sportscash-qt.protocol (KDE)

