
Debian
====================
This directory contains files used to package wined/wine-qt
for Debian-based Linux systems. If you compile wined/wine-qt yourself, there are some useful files here.

## wine: URI support ##


wine-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wine-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wine-qt binary to `/usr/bin`
and the `../../share/pixmaps/wine128.png` to `/usr/share/pixmaps`

wine-qt.protocol (KDE)

