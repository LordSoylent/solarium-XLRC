
Debian
====================
This directory contains files used to package solariumd/solarium-qt
for Debian-based Linux systems. If you compile solariumd/solarium-qt yourself, there are some useful files here.

## solarium: URI support ##


solarium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install solarium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your solariumqt binary to `/usr/bin`
and the `../../share/pixmaps/solarium128.png` to `/usr/share/pixmaps`

solarium-qt.protocol (KDE)

