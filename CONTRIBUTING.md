When contributing to Precision Converters Firmware please consider the
following checklist:

- [ ] Copyright header has been added to source and header files
- [ ] Artistic Style (`astyle`) has been run to lint new code
  ```
  astyle --options=../no-OS/ci/astyle_config \
         projects/foobar/app/*.c \
         projects/foobar/app/*.h
  ```
- [ ] Add EEPROM validation code
- [ ] Add all context attributes (e.g. `fw_version`, `hw_carrier`,
      `hw_mezzanine`, `hw_name`, `hw_mezzanine_status`)
- [ ] IIO attributes match the corresponding Linux driver
- [ ] Create a `readme.md` in the project directory explaining how to use the
      project

- [ ] Validate EEPROM detection and context attributes creation using IIO
      clients (e.g. ACE, IIO Oscilloscope)
- [ ] Capture and verify ADC data using an IIO client
- [ ] Test on the SDP-K1 with `USE_SDRAM` and `NO_SDRAM` where applicable
- [ ] Test on the SDP-K1 with physical and virtual serial ports where
      applicable
- [ ] Test using the STM32 HAL where applicable
- [ ] Validate attributes, calibration, temperature sensing, etc using a client

- [ ] Update corresponding ADI Wiki pages
- [ ] Request links to those pages on the product page

- [ ] Open a pull request on Github
