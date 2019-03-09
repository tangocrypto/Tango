
Debian
====================
This directory contains files used to package tangod/tango-qt
for Debian-based Linux systems. If you compile tangod/tango-qt yourself, there are some useful files here.

## tango: URI support ##


tango-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tango-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tangoqt binary to `/usr/bin`
and the `../../share/pixmaps/tango128.png` to `/usr/share/pixmaps`

tango-qt.protocol (KDE)

