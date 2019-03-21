
Debian
====================
This directory contains files used to package cnscd/cnsc-qt
for Debian-based Linux systems. If you compile cnscd/cnsc-qt yourself, there are some useful files here.

## cnsc: URI support ##


cnsc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cnsc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cnscqt binary to `/usr/bin`
and the `../../share/pixmaps/cnsc128.png` to `/usr/share/pixmaps`

cnsc-qt.protocol (KDE)

