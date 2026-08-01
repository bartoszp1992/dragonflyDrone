# parts
- Battery holder contacts: pulled from Keystone 1043/1042
- VTX: P1 Air unit
- FC: BETAFPV Matrix 4IN1
- GNSS: FlyFishRC M10 Mini

# filament
PETG

# electronics
## FC 4in1
- use MCU pin 45(B07) as FC Tx -> GNSS Rx(solder directly)
- use T1 pin as FC Rx <- GNSS Tx



# firmware
If you are building remotely:
> choose analog OSD Protocol and type **OSD_HD** in custom defines, to build firmware with both- digital and analog OSD 
> In other options add **Magnetometers**, **Position Hold** and **Altitude Hold**

## notice
This repository includes third-party firmware binaries used by this FPV drone.

### Betaflight

Version: `2025.12.2`

Included firmware:

- `betaflight_2025.12.2_STM32G474_BETAFPVG473_ccb6e7f3.hex`
- `betaflight_2025.12.2_STM32G474_BETAFPVG473_V2_aa260427.hex`

These firmware files were generated using the official Betaflight Cloud
Build service from Betaflight `2025.12.2`.

Flight controller targets:

- `BETAFPVG473`
- `BETAFPVG473_V2`

Additional build options used for this project:

- Analog OSD
- `OSD_HD`
- Magnetometers (`MAG`)
- Position Hold (`POSITION_HOLD`)
- Altitude Hold (`ALTITUDE_HOLD`)

No modifications were made to the Betaflight source code by this repository.
The options listed above are compile-time options supported by the official
Betaflight build system.

Corresponding source:

Betaflight repository, tag `2025.12.2`
(including the `src/config` target configuration submodule referenced by
that source version).

Betaflight is distributed under the GNU General Public License version 3.
A copy of the GNU GPL v3 is included in this repository as `LICENSE.txt`.

### Bluejay

Version: `v0.19.2`

Included firmware:

- `A_X_5_96_v0.19.2.hex`
- `A_X_5_48_v0.19.2.hex`
- `A_X_5_24_v0.19.2.hex`

This is an unmodified Bluejay firmware binary from the upstream
`v0.19.2` release.

Corresponding source:

Bluejay repository, tag `v0.19.2`.

Bluejay is distributed under the GNU General Public License version 3.
A copy of the GNU GPL v3 is included in this repository as `GPL-3.0.txt`.

### Copyright and attribution

Betaflight and Bluejay are independent open-source projects.
Copyright remains with their respective authors and contributors.

This repository does not claim ownership of Betaflight or Bluejay and is
not affiliated with or endorsed by either project.

[Betaflight](https://github.com/betaflight/betaflight/tree/2025.12.2)

[Bluejay](https://github.com/bird-sanctuary/bluejay/tree/v0.19.2)
