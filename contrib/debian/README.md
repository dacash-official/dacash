
Debian
====================
This directory contains files used to package dacashd/dacash-qt
for Debian-based Linux systems. If you compile dacashd/dacash-qt yourself, there are some useful files here.

## dacash: URI support ##


dacash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dacash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dacash-qt binary to `/usr/bin`
and the `../../share/pixmaps/dacash128.png` to `/usr/share/pixmaps`

dacash-qt.protocol (KDE)

