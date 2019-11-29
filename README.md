# Laird Connectivity Python Uwf Loader

## About

This python application can be used to upload .uwf firmware images to Laird Connectivity's range of wireless modules.

**No support is provided or offered for this**, it is provided as-is in the hopes that it will be helpful or useful but functionality is not guaranteed. This code does not work with the BT900 and has not been tested with any other modules.

## Requirements

This requires python version TBD

## Usage

`python btpa_firmware_loader <port> <baudrate> <Uwf> [device type]`

Where

    <port> is the serial port device, COMx on windows or /dev/ttyX on Linux
    <baudrate> is the baudrate of the module, typically 115200
    <Uwf> is the .uwf file to use

## License

TBD