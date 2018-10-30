
Debian
====================
This directory contains files used to package adultchaind/adultchain-qt
for Debian-based Linux systems. If you compile adultchaind/adultchain-qt yourself, there are some useful files here.

## adultchain: URI support ##


adultchain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install adultchain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your adultchainqt binary to `/usr/bin`
and the `../../share/pixmaps/adultchain128.png` to `/usr/share/pixmaps`

adultchain-qt.protocol (KDE)

