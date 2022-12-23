Documentation, tutorials, ... can be found on https://www.aircrack-ng.org
See also manpages and the forum.

Installing
==========

This version has more dependencies/libraries required than previous versions to be compiled. 
See INSTALLING file for more information

OpenWrt Devices
===============

You can use airodump-ng on OpenWrt devices. You'll have to use specify
prism0 as interface. Airodump-ng will automatically create it.
Rq: Aireplay DOESN'T work on OpenWrt (2.4 kernel) with broadcom chipset since the driver doesn't support injection. It *may* work with 2.6 kernels >= 2.6.24 (kamikaze 8.09+ custom-built).

