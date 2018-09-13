
Debian
====================
This directory contains files used to package dcoinsd/dcoins-qt
for Debian-based Linux systems. If you compile dcoinsd/dcoins-qt yourself, there are some useful files here.

## dcoins: URI support ##


dcoins-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dcoins-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dcoinsqt binary to `/usr/bin`
and the `../../share/pixmaps/dcoins128.png` to `/usr/share/pixmaps`

dcoins-qt.protocol (KDE)

