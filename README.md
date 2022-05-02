# u-blox NEO-6M GPS Raw Data Logger based on Raspberry Pi Zero W / RTKLIB

## Hardware Requirements

### Raspberry Pi Zero / Zero W

![Raspberry Pi Zero W](https://github.com/Nanich87/raspberry-pi-zero-w-base-rover-u-blox-neo-6m/blob/master/images/raspberry-pi-zero-w.jpg "Raspberry Pi Zero W")

![Raspberry Pi Zero](https://github.com/Nanich87/raspberry-pi-zero-w-base-rover-u-blox-neo-6m/blob/master/images/raspberry-pi-zero.jpg "Raspberry Pi Zero")

### u-blox NEO-6M

![u-blox NEO-6M](https://github.com/Nanich87/raspberry-pi-zero-w-base-rover-u-blox-neo-6m/blob/master/images/u-blox.jpg "u-blox NEO-6M")

### SparkFun 9DoF Sensor Stick

![SparkFun 9DoF Sensor Stick](https://github.com/Nanich87/raspberry-pi-zero-w-base-rover-u-blox-neo-6m/blob/master/images/sparkfun-9dof-sensor-stick.jpg "SparkFun 9DoF Sensor Stick")

1. Raspberry Pi Zero W https://www.raspberrypi.org/products/raspberry-pi-zero-w/

2. u-blox NEO-6M https://www.u-blox.com/en/product/neo-6-series

3. SparkFun 9DoF Sensor Stick https://www.sparkfun.com/products/13944 (Optional)

## Wiring

- Raspberry Pi GPIO14 (Pin #08) -> u-blox NEO-6M RX
- Raspberry Pi GPIO15 (Pin #10) -> u-blox NEO-6M TX
- Raspberry Pi DC Power 5v (Pin #04) -> u-blox NEO-6M +5v
- Raspberry Pi Ground (Pin #06) -> u-blox NEO-6M Ground

## Software Requirements

1. Raspberry Zero GNSS Logger https://github.com/Nanich87/raspberry-zero-gnss-logger

## STL

### Version 2

![Part 1 V2](https://raw.githubusercontent.com/Nanich87/raspberry-gnss-rtk-ublox-neo-6m/master/images/3d/part_1_v2.png)
![Part 2 V2](https://raw.githubusercontent.com/Nanich87/raspberry-gnss-rtk-ublox-neo-6m/master/images/3d/part_2_v2.png)

### Version 1

![Part 1 V2](https://raw.githubusercontent.com/Nanich87/raspberry-gnss-rtk-ublox-neo-6m/master/images/3d/part_1_v1.png)
![Part 2 V2](https://raw.githubusercontent.com/Nanich87/raspberry-gnss-rtk-ublox-neo-6m/master/images/3d/part_2_v1.png)

## RTKLIB Startup Commands

https://wiki.openstreetmap.org/wiki/UbloxRAW#U-BLOX6

!HEX b5 62 09 01 10 00 c8 16 00 00 00 00 00 00 97 69 21 00 00 00 02 10 2b 22

!HEX b5 62 09 01 10 00 0c 19 00 00 00 00 00 00 83 69 21 00 00 00 02 11 5f f0

!HEX b5 62 06 01 08 00 02 10 00 01 00 00 00 00 22 28

!HEX b5 62 06 01 08 00 02 11 00 01 00 00 00 00 23 2f
