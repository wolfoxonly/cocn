
Debian
====================
This directory contains files used to package CloudComputingChaind/CloudComputingChain-qt
for Debian-based Linux systems. If you compile CloudComputingChaind/CloudComputingChain-qt yourself, there are some useful files here.

## CloudComputingChain: URI support ##


CloudComputingChain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install CloudComputingChain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your CloudComputingChain-qt binary to `/usr/bin`
and the `../../share/pixmaps/CloudComputingChain128.png` to `/usr/share/pixmaps`

CloudComputingChain-qt.protocol (KDE)

