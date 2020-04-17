# displaylink-gentoo
Ebuilds and files for getting [DisplayLink Ubuntu drivers](https://www.displaylink.com/downloads/ubuntu) to work under Gentoo Linux

Live ebuild for [evdi](https://github.com/DisplayLink/evdi) kernel module, ebuild for latest version (5.2.14) of DisplayLinkManager, and required zipfile to be placed in distfiles (generally found under /var/cache/distfiles).

Supports both OpenRC and systemd.

Tested with an [HP USB-C Elitebook Dock](https://store.hp.com/us/en/pdp/hp-usb-c-dock) on a Lenovo T480 laptop.  Once evdi is installed and DisplayLinkManager is running, xrandr can be used to detect and bring up the display.
