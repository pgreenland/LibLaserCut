# LibLaserCut #
This is a library intended to provide suppport
for Lasercutters on any platform.

It was created for VisiCut (http://visicut.org)
but you are invited to use it for your own programs.

Currently it supports older Epilog Lasers (Zing/Mini/Helix),
the current LAOS board. (www.laoslaser.org),
the SmoothieBoard (www.smoothieware.org),
K40,
generic GRBL based boards,
LTT iLaser 4000,
and some untested work-in-progress drivers like the Roland iModela and the Lasersaur.

A detailed list of tested devices can be found in the VisiCut wiki:
https://github.com/t-oster/VisiCut/wiki/Supported-Hardware

If your Lasercutter is not supported, please contribute by implementing
your driver as a subclass of the LaserCutter.java class.
