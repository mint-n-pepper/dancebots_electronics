# Dancebots Electronics HW and Firmware Repository

Here, you will find the PCB design data, ATTiny firmware, and additional hardware information, such as the BOM below.

For the Desktop Dancebots Editor source code, please refer to [its repository](https://github.com/philippReist/dancebots_gui).

## Hardware BOM
The bill of materials is available [here](https://drive.google.com/open?id=1H4aylC6xcZu8uulw1L1Zao0gHDbFx3T0). The folder also contains an example baseplate design.

## Dancebots PCB
In the subfolder ```dancebots_pcb```, you will find the [KiCAD](https://www.kicad-pcb.org/) design files, along with the Gerber files that you may use to manufacture the PCBs.

## Firmware
The move and LED commands embedded in the right channel of the MP3 files generated with the Dancebots Editor are parsed by an Microchip ATTinyX61A running the firmware in ```DancebotsFirmware```. Refer to the readme contained in that folder for more information.

## Programming PCB
The subfolder ```ATTiny-ProgrammingBoard``` contains the design files for a simple PCB that helps programming ATTiny microcontrollers in larger quantities.

## Solder Exercise PCB
The subfolder ```solder-ex-pcb``` contains the design files for a simple PCB that can be used as a soldering exercise board for children/people wanting to learn how to solder. It may also allow learning to infer a very simple schematic from a PCB by looking at traces or running conductivity tests on the PCB. Finally, it provides inputs for the battery pack and an output header that may be used for intermediate PCB testing when teaching the Dancebots workshop.

## License and Credits
Copyright 2019 mint & pepper

The Dancebots hard- and software was originally developed by Raymond Oung and Philipp Reist during their PhD at the [Institute for Dynamic Systems and Control](https://idsc.ethz.ch/) for use in the [Sportferienlager Fiesch of the City of Zürich](https://zuerifiesch.ch/).

You can find more information on the [Dancebots website](http://www.dancebots.ch/).

The workshop's continued existence is due to the educational outreach program [mint & pepper](https://www.mintpepper.ch/) at the [Wyss Zurich](https://www.wysszurich.uzh.ch/).

The firmware source code is distributed under the terms of the [GNU General Public License 3.0](https://spdx.org/licenses/GPL-3.0.html). See the LICENSE.txt file in the ```DancebotsFirmware``` subfolder for more information.

The PCB sources and all hardware documentation are licensed under the
CERN OHL v. 1.2.

You may redistribute and modify this documentation under the terms of the
CERN OHL v.1.2. (http://ohwr.org/cernohl). This documentation is distributed
WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF
MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable
conditions.
