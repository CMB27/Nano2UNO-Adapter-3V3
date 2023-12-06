# Nano2UNO Adapter 3V3

![Nano2UNO Adapter 3V3 Top View](https://github.com/CMB27/Nano2UNO-Adapter-3V3/blob/main/extras/Nano2UNO-Adapter-3V3-Top-View.png)

![Nano2UNO Adapter 3V3 Angled View](https://github.com/CMB27/Nano2UNO-Adapter-3V3/blob/main/extras/Nano2UNO-Adapter-3V3-Angled-View.png)

![Nano2UNO Adapter 3V3 Bottom View](https://github.com/CMB27/Nano2UNO-Adapter-3V3/blob/main/extras/Nano2UNO-Adapter-3V3-Bottom-View.png)

## Overview
The `Nano2UNO Adapter 3V3` is a circuit board to adapt 3.3V Nano boards the the UNO form factor.

__Warning: when using a 3.3V Nano board with this adapter, applying voltages higher than 3.3V to any I/O pin could damage the Nano board.__

This adapter maintains the pin numbering from the Nano board: e.g. pin 0 on the Nano is connected to pin 0 of the UNO interface.
Note, pins A6 and A7 of the Nano are not connected; these pins are not present on the UNO interface.

This adapted does provides a 5V switching voltage regulator.
This is included to ensure that 5V power is available whether the board is powered through USB, Barrel Jack, or the VIN pin.

## Tech Specs

| Property          | Value                |
|-------------------|----------------------|
| Board Name        | Nano2UNO Adapter 3V3 |
| Operating Voltage | 3.3V                 |
| Input Voltage     | 6.5-36V[^1]          |
| Length            | 68.58mm              |
| Width             | 53.34mm              |
| Thickness (recommended) | 1.6mm |

[^1]: according to the [Recom R-78K-0.5 datasheet](https://recom-power.com/pdf/Innoline/R-78K-0.5.pdf) for R-78K5.0-0.5


## Compatibility

### Nano
The `Nano2UNO Adapter 3V3` should, in theory, be compatible with the following Nano boards:
- Arduino Nano 33 IoT
- Arduino Nano 33 BLE
- Arduino Nano 33 BLE Sense
- Arduino Nano 33 BLE Sense Rev2
- Arduino Nano RP2040 Connect
- Arduino Nano ESP32

