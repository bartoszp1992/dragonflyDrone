# parts
Battery holder contacts: pulled from Keystone 1042P
VTX: P1 Air unit
FC: BETAFPV Matrix 4IN1
GNSS: FlyFishRC M10 Mini

# filament
PETG

# electronics
use MCU pin 45(B07) as Rx for GNSS

# firmware
If you are building remotely:
> choose analog OSD Protocol and type **OSD_HD** in custom defines, to build firmware with both- digital and analog OSD 
> In other options add **Magnetometers**, **Position Hold**, **Altitude Hold** and **Soft Serial**

Firmware notice

This repository may include firmware binaries and configuration files for flight controllers and ESCs.

Betaflight firmware is licensed under the GNU General Public License v3.0 (GPL-3.0).
Source code is available at: https://github.com/betaflight/betaflight

Bluejay ESC firmware is an open-source project.
Source code is available at: https://github.com/bird-sanctuary/bluejay

All respective rights belong to the original authors.
This repository does not claim ownership of these projects and only redistributes unmodified binaries for convenience.