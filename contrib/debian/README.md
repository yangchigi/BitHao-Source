
Debian
====================
This directory contains files used to package bithaod/bithao-qt
for Debian-based Linux systems. If you compile bithaod/bithao-qt yourself, there are some useful files here.

## bithao: URI support ##


bithao-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bithao-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bithao-qt binary to `/usr/bin`
and the `../../share/pixmaps/bithao128.png` to `/usr/share/pixmaps`

bithao-qt.protocol (KDE)

