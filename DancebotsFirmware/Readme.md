## Device Support
ATTinyX61A. The firmware fits onto the 261A version.

## Programming
Program muP using, for example, the AVRISP-MK2 or another suitable tool. A programming adapter PCB is available in the repo subfolder ```ATTiny-ProgrammingBoard```.

Another great option is to buy the microcontrollers pre-programmed from the [Microchip website](https://www.microchip.com/).

## Fuse configuration
| Byte | Value|
|------|------|
| Extended byte| 0xFF|
| High byte | 0xDF |
| Low byte | 0xE2 |

## Production File
You may use the production file in this folder with Atmel Studio V7 to program flash and fuses at the same time. Can be recreated easily in the device programming dialogue.
