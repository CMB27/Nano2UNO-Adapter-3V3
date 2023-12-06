# Nano2UNO Adapter 3V3

![Nano2UNO Adapter 3V3 Top View](https://github.com/CMB27/Nano2UNO-Adapter-3V3/blob/main/extras/Nano2UNO-Adapter-3V3-Top-View.png)

![Nano2UNO Adapter 3V3 Angled View](https://github.com/CMB27/Nano2UNO-Adapter-3V3/blob/main/extras/Nano2UNO-Adapter-3V3-Angled-View.png)

![Nano2UNO Adapter 3V3 Bottom View](https://github.com/CMB27/Nano2UNO-Adapter-3V3/blob/main/extras/Nano2UNO-Adapter-3V3-Bottom-View.png)



## Overview

The Nano2UNO Adapter 3V3 is a circuit board to adapt 3.3V Nano boards the the UNO form factor.

__Warning: when using a 3.3V Nano board with this adapter, applying voltages higher than 3.3V to any I/O pin could damage the Nano board.__

This adapter maintains the pin numbering from the Nano board: e.g. pin 0 on the Nano is connected to pin 0 of the UNO interface.
Note, pins A6 and A7 of the Nano are not connected; these pins are not present on the UNO interface.

This adapter provides a 5V switching voltage regulator.
This is included to ensure that 5V power is available whether the board is powered through USB, Barrel Jack, or the VIN pin.



## Tech Specs

| Property                | Value                |
|-------------------------|----------------------|
| Board Name              | Nano2UNO Adapter 3V3 |
| Operating Voltage       | 3.3V                 |
| Input Voltage           | 6.5-36V              |
| Length                  | 68.58mm              |
| Width                   | 53.34mm              |
| Thickness (recommended) | 1.6mm |



## Compatibility

The Nano2UNO Adapter 3V3 should, in theory, be compatible with the following Nano boards:
- Arduino Nano 33 IoT
- Arduino Nano 33 BLE
- Arduino Nano 33 BLE Sense
- Arduino Nano 33 BLE Sense Rev2
- Arduino Nano RP2040 Connect
- Arduino Nano ESP32



## Fabrication

### Circuit Board Specifications
Board Length: __68.58mm__  
Board Width: __53.34mm__  
Board Thickness: __1.6mm__  
Substrate Material: __FR4__  
Copper Layers: __2__  
Copper Thickness: __1oz__  
Soldermask Color: __Any__ (Blue Suggested)  

Smallest Hole Diameter: __0.8mm__  
Smallest Trace Width: __0.2mm__ (7.8mil)  
Smallest Trace Spacing: __0.2mm__ (7.8mil)


### Purchase Components

| References | Quantity | Manufacturer | Part Number    | Description                     |
|------------|---------:|--------------|----------------|---------------------------------|
| C1, C2     |        2 | Panasonic    | ECEA1HKS100    | 10uF X7R Through-Hole Capacitor |
| D1         |        1 | Vishay       | SB260S-E3/54   | DO-41 Diode                     |
| J1         |        1 | Samtec       | ESW-106-33-L-S | 1x6 Socket Header               |
| J2, J3     |        2 | Samtek       | ESW-108-33-L-S | 1x8 Socket Header               |
| J4         |        1 | Samtec       | ESW-110-33-L-S | 1x10 Socket Header              |
| J5, J6     |        2 | Sullins      | PPPC151LFBN-RC	| 1x15 Socket Header              |
| J7         |        1 | TSW/Samtec   | TSW-103-15-L-D | 2x3 Pin Header                  |
| J8         |        1 | CUI          | PJ-102A        | 2.0mm ID, 5.5mm OD Barrel Jack  |
| SW1        |        1 | TE           | 1825910-6      | 6mm Pushbutton Switch           |
| U1         |        1 | Recom        | R-78K5.0-0.5   | 5V DC DC Converter              |

C1 and C2 are decoupling capacitors for the 5V DC DC converter.

J1 - J4 are extended socket headers. They are a bit more expensive and harder to find than the usual variety, but they are needed to give enough clearance for the Nano board when a shield is used.

J5 and J6 are typical 8.5mm tall socket headers.

J7 is an extended pin header.

SW1 is a generic 6mm pushbutton.

U1 is the 5V DC DC converter.


### Assembly

All of the components are through hole soldered.
