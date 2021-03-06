# USB Morse Keyer
![Platform](https://img.shields.io/badge/platform-PIC16-blue) ![License](https://img.shields.io/github/license/dilshan/usb-morse-keyer) ![Release Version](https://img.shields.io/github/v/release/dilshan/usb-morse-keyer) ![Release Date](https://img.shields.io/github/release-date/dilshan/usb-morse-keyer) 

![Morse Keyer Final Prototype](https://raw.githubusercontent.com/dilshan/usb-morse-keyer/master/resource/morse-keyer-final.jpg)

USB Morse Keyer is microcontroller based keyer with following features:

- USB / straight key / iambic key inputs.
- Support for both *standalone* and *USB* operating modes.
- 64-character USB typeahead buffer and 6-character Morse key typeahead buffer.
- Support 5, 10, 15 WPM.
- 6-page message memory.
- 1W Audio output.
- Audio and PTT output interfaces.
- 32 character display

To reduce the dimension of the PCB this unit is designed with combining both through-hole and surface mount components. To facilitate future upgrades and modifications, the *PIC16F886* MCU sticks with the standard 28-pin DIP package.

The USB interface of this unit is designed to work with most of the operating systems. It emulates a virtual serial terminal to transfer keystrokes to the keyer. In most of the operating systems, this interface works without installing any additional device drivers. To submit keystrokes user can use any serial terminal software such as [PuTTY](https://www.putty.org), *Hyper Terminal*, [Minicom](https://salsa.debian.org/minicom-team/minicom), etc. 

This keyer is designed to work with 7V to 16V DC input voltage. The most recommended working voltage is 9V.

[All the details related to this project are available at project documentation.](https://github.com/dilshan/usb-morse-keyer/wiki)

## Licenses

This is a [certified](https://certification.oshwa.org/lk000004.html) open hardware project and all it's design files, firmware source codes, [documentation](https://github.com/dilshan/usb-morse-keyer/wiki), and other resource files are available at the project source repository. All the content of this project are distributed under the terms of the following license:

- Hardware License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Software License: [MIT](https://github.com/dilshan/usb-morse-keyer/blob/master/LICENSE)
- Documentation License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

[![OSHW-LK000004](https://raw.githubusercontent.com/wiki/dilshan/usb-morse-keyer/images/OSHW-LK000004.png)](https://certification.oshwa.org/lk000004.html)

