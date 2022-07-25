
Debian
====================
This directory contains files used to package hiberad/hibera-qt
for Debian-based Linux systems. If you compile hiberad/hibera-qt yourself, there are some useful files here.

## hibera: URI support ##


hibera-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hibera-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hibera-qt binary to `/usr/bin`
and the `../../share/pixmaps/hibera128.png` to `/usr/share/pixmaps`

hibera-qt.protocol (KDE)

