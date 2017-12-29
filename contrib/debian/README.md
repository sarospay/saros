
Debian
====================
This directory contains files used to package sarosd/saros-qt
for Debian-based Linux systems. If you compile sarosd/saros-qt yourself, there are some useful files here.

## saros: URI support ##


saros-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install saros-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your saros-qt binary to `/usr/bin`
and the `../../share/pixmaps/saros128.png` to `/usr/share/pixmaps`

saros-qt.protocol (KDE)

