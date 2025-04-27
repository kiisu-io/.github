# Kiisu
Multipurpose development board in size of credit card with Flipper Zero compatibility.
- [Kiisu.io website](https://kiisu.io)
- [Store](https://store.rainwalker.ee)
- [Documentation, schematics and binaries for Kiisu V4](https://github.com/kiisu-io/kiisu4-companion-fw)
- [Aux MCU firmware to support Flipper Zero firmwares](https://github.com/kiisu-io/kiisu4-companion-fw)
- [Fork of Flipper Zero official firmware for Kiisu](https://github.com/kiisu-io/kiisu-firmware)
  
## Interfaces:
- SubGhz transceiver CC1101 with ability to install external antenna
- NFC reader and emulator ST25R3916, built-in antenna
- RFID reader and emulator, built-in antenna
- Infrared receiver and transmitter
- GPIO, pin compatible with Flipper Zero
- Bluetooth Low Energy
- USB Type C

## Cores:
- Main MCU STM32WB55RGV6 up to 80 MHz
- Aux MCU STM32G431CBU6 up to 170 MHz

## Sensors:
- Digital accelerometer and compass LSM303AGR
- Temperature and humidity sensor GXHTC3C
- Ambient light sensor
- Gas sensor measuring relative humidity, barometric pressure, ambient temperature and gas (VOC) BME680 can be installed by user
- Digital ranger VL53xxx can be installed by user

## Power:
- LIR2032 rechargeable
- Primary via USB Type C
