
Debian
====================
This directory contains files used to package tixoncashd/tixoncash-qt
for Debian-based Linux systems. If you compile tixoncashd/tixoncash-qt yourself, there are some useful files here.

## tixoncash: URI support ##


tixoncash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tixoncash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tixoncashqt binary to `/usr/bin`
and the `../../share/pixmaps/tixoncash128.png` to `/usr/share/pixmaps`

tixoncash-qt.protocol (KDE)

