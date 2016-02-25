#NAME

disable-zigbee - when installed, this package disables the zigbee related components of the Ninja Sphere stack.

#HOW IT WORKS
This file installs a marker file /etc/disable-zigbee which is checked by the other zigbee related components
to alter their operation.

Effects of this package:

* zigbee firmware will not be flashed
* the zigbee gateway process will not start
* the zigbee driver will start, but not access the hardware
