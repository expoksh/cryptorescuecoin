
Debian
====================
This directory contains files used to package cryptorescuecoind/cryptorescuecoin-qt
for Debian-based Linux systems. If you compile cryptorescuecoind/cryptorescuecoin-qt yourself, there are some useful files here.

## cryptorescuecoin: URI support ##


cryptorescuecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cryptorescuecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cryptorescuecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/cryptorescuecoin128.png` to `/usr/share/pixmaps`

cryptorescuecoin-qt.protocol (KDE)

