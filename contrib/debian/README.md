
Debian
====================
This directory contains files used to package rizd/riz-qt
for Debian-based Linux systems. If you compile rizd/riz-qt yourself, there are some useful files here.

## riz: URI support ##


riz-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install riz-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rizqt binary to `/usr/bin`
and the `../../share/pixmaps/riz128.png` to `/usr/share/pixmaps`

riz-qt.protocol (KDE)

