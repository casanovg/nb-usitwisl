# nb-usitwisl
USI-based TWI (I2C) slave driver for ATtiny microcontrollers

This driver is for Microchip (ex Atmel) [ATtiny devices](https://en.wikipedia.org/wiki/ATtiny_microcontroller_comparison_chart) that implement the I2C protocol by using the Universal Serial Interface (USI) peripheral, that is, microcontrollers that are not equipped with I2C-specific hardware.

This version is for standard I2C applications that can use the microcontroller interrupt vectors. For special applications, such as bootloaders and the like, it is recommended to use a [version that does not use interrupts](https://github.com/casanovg/nb-usitwisl-if).

