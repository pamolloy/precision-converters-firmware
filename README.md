# Precision Converters Firmware

This repository contains an embedded firmware applications for Analog Devices
Precision Converters. The firmware applications are developed to interface with
Precision Converters (ADCs/DACs) in order to configure/access device parameters
and capture device data over a serial communication link. These applications
are primarily targeted for the Mbed (SDP-K1) platform, however they can easily
target other platforms as well (see [Understanding No-OS and
Platform Drivers](https://www.analog.com/en/analog-dialogue/articles/understanding-and-using-the-no-os-and-platform-drivers.html)).

For more information about Precision Converters software support see the [ADI Wiki](https://wiki.analog.com/resources/tools-software/product-support-software).

## Build

- When using the Keil Studio Web IDE follow the [Build Guide for Mbed
Platform](https://wiki.analog.com/resources/tools-software/product-support-software/pcg-fw-mbed-build-guide)
- When using the STM32CubeIDE follow the [Build Guide for STM32
  Platform](https://wiki.analog.com/resources/tools-software/product-support-software/pcg-fw-stm32-build-guide)
- When building on the command-line see
  [`build-no-os.yaml`](.github/workflows/build-no-os.yaml) or
  [`build-mbed-cli-1.yaml`](.github/workflows/build-mbed-cli-1.yaml)

## Code Style

When writing code, please follow the [style guidelines](https://github.com/analogdevicesinc/no-OS/wiki/Code-Style-guidelines).

## Contribution

* If you want to use the most stable code base, always use the latest release
  branch.
* If you want to use the latest and greatest, check out the 'main' branch.

## Support

Feel free to ask questions in the [EngineerZone](https://ez.analog.com/data_converters).
