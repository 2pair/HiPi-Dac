# HiPi-Dac

This is a little DAC board for the Raspberry Pi. The design should be HAT compliant and it also includes an on board power supply.

## Why Did I Do This?

The other DACs designed for the raspberry pi all seemed to lack one or more features I desired such as RCA output or onboard power supply or HAT compliance so I decided it would be easy enough to just make my own. Also, it's fun!
 
## Features

- TI PCM5101A DAC chip featuring 32bit and 384kHz limits, connected through I2S
- Independent low-noise positive and negative 3.3V supplies for the DAC
- Onboard power supply that powers the pi and everything else from 7-12V
- HAT spec compliance
- Onboard EEPROM
- Pushbutton connected to GPIO
- Power LED
- Bi-color LED connected to GPIO

## Usage

The chip is the same as the one featured on the hifiberry DAC so its easy enough to just follow their instructions on installing the driver.

## License

GPL v3 http://www.gnu.org/licenses/gpl-3.0.en.html