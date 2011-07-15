grump is a very simple program for interacting over a serial port.

I use it at work to communicate with boards that I am developing on.

Basically, all it does is pass characters up and down the serial port. It has
one obvious restriction, which is that if you type CTRL-C at it, it both sends
CTRL-C and also exits. In most cases, CTRL-/ can be used to the same effect,
without exiting grump.

Since I use the program to my own purposes, its defaults are set up to my
convenience. In particular, the default speed and serial device are those
values that tend to work locally (working with beagleboards and a USB serial
connection on a PC running Ubuntu).

Use ``grump -h`` to find out details of its usage.

So far as I am concerned, this program is available as public domain code -
use it as you wish, but it has no guarantees of being fit for use by anyone
else.

.. vim: set filetype=rst tabstop=8 softtabstop=2 shiftwidth=2 expandtab:
