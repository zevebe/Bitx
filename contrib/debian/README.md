
Debian
====================
This directory contains files used to package bitxd/bitx-qt
for Debian-based Linux systems. If you compile bitxd/bitx-qt yourself, there are some useful files here.

## bitx: URI support ##


bitx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitx-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitx128.png` to `/usr/share/pixmaps`

bitx-qt.protocol (KDE)

