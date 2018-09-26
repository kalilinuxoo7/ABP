
Debian
====================
This directory contains files used to package breeksd/breeks-qt
for Debian-based Linux systems. If you compile breeksd/breeks-qt yourself, there are some useful files here.

## breeks: URI support ##


breeks-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install breeks-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your breeksqt binary to `/usr/bin`
and the `../../share/pixmaps/breeks128.png` to `/usr/share/pixmaps`

breeks-qt.protocol (KDE)

