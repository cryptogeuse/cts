
Debian
====================
This directory contains files used to package ctsd/cts-qt
for Debian-based Linux systems. If you compile ctsd/cts-qt yourself, there are some useful files here.

## cts: URI support ##


cts-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cts-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ctsqt binary to `/usr/bin`
and the `../../share/pixmaps/cts128.png` to `/usr/share/pixmaps`

cts-qt.protocol (KDE)

