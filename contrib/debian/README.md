
Debian
====================
This directory contains files used to package cesarcoind/cesarcoin-qt
for Debian-based Linux systems. If you compile cesarcoind/cesarcoin-qt yourself, there are some useful files here.

## cesarcoin: URI support ##


cesarcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cesarcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cesarcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/cesarcoin128.png` to `/usr/share/pixmaps`

cesarcoin-qt.protocol (KDE)

