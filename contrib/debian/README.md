
Debian
====================
This directory contains files used to package argontokend/argontoken-qt
for Debian-based Linux systems. If you compile argontokend/argontoken-qt yourself, there are some useful files here.

## argontoken: URI support ##


argontoken-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install argontoken-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your argontoken-qt binary to `/usr/bin`
and the `../../share/pixmaps/argontoken128.png` to `/usr/share/pixmaps`

argontoken-qt.protocol (KDE)

