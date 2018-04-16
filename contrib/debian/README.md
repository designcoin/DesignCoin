
Debian
====================
This directory contains files used to package designcoind/designcoin-qt
for Debian-based Linux systems. If you compile designcoind/designcoin-qt yourself, there are some useful files here.

## designcoin: URI support ##


designcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install designcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your designcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/designcoin128.png` to `/usr/share/pixmaps`

designcoin-qt.protocol (KDE)

