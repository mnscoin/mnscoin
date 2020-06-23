
Debian
====================
This directory contains files used to package mnscoind/mnscoin-qt
for Debian-based Linux systems. If you compile mnscoind/mnscoin-qt yourself, there are some useful files here.

## mnscoin: URI support ##


mnscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mnscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mnscoinqt binary to `/usr/bin`
and the `../../share/pixmaps/mnscoin128.png` to `/usr/share/pixmaps`

mnscoin-qt.protocol (KDE)

