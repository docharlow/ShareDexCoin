
Debian
====================
This directory contains files used to package sharedexcoind/sharedexcoin-qt
for Debian-based Linux systems. If you compile sharedexcoind/sharedexcoin-qt yourself, there are some useful files here.

## sharedexcoin: URI support ##


sharedexcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sharedexcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sharedexcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/sharedexcoin128.png` to `/usr/share/pixmaps`

sharedexcoin-qt.protocol (KDE)

