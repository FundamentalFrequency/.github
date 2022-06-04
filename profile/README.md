# Fundamental Frequency

## Projects

### LMN-3
![Final Assembly](profile/images/fully_assembled.JPEG)

The LMN-3 is an open source DAW-in-a-box. The project is composed of the following repositories:
- [LMN-3-Build-Guide](https://github.com/FundamentalFrequency/LMN-3-Build-Guide)
- [LMN-3-DAW](https://github.com/FundamentalFrequency/LMN-3-DAW)
- [LMN-3-MCAD](https://github.com/FundamentalFrequency/LMN-3-MCAD)
- [LMN-3-ECAD](https://github.com/FundamentalFrequency/LMN-3-ECAD)
- [LMN-3-Firmware](https://github.com/FundamentalFrequency/LMN-3-Firmware)
- [LMN-3-Emulator](https://github.com/FundamentalFrequency/LMN-3-Emulator)
- [LMN-3-Keycaps](https://github.com/FundamentalFrequency/LMN-3-Keycaps)

#### [LMN-3-Build-Guide](https://github.com/FundamentalFrequency/LMN-3-Build-Guide)
The build guide explains everything concerning the configuration and assembly of the LMN-3. It will guide you through the process of flashing the
firmware, soldering the PCB, assembling the case, and configuring the Raspberry Pi for use with the LMN-3 DAW.

#### [LMN-3-DAW](https://github.com/FundamentalFrequency/LMN-3-DAW)
The LMN-3 DAW is the heart of the LMN-3 project. It is the software that contains the core functionality of the LMN-3 and provides DAW capabilties 
such as recording, editing, and mixing. It is powered by an open-source audio engine called the 
[Tracktion Engine](https://github.com/Tracktion/tracktion_engine). It runs on a Raspberry Pi.


#### [LMN-3-MCAD](https://github.com/FundamentalFrequency/LMN-3-MCAD)
The LMN-3-MCAD repository contains the FreeCAD project files for the LMN-3 case. The releases contained in this repostory contain files that can be 
used to lasercut (or 3-D print) the enclosure for the LMN-3. 

#### [LMN-3-ECAD](https://github.com/FundamentalFrequency/LMN-3-ECAD)
The LMN-3-ECAD repository contains the KiCad project files for the LMN-3 PCB. The releases contained in this repository contain gerber files 
that can be sent to a board house for manufacturing of the PCB. 

#### [LMN-3-Firmware](https://github.com/FundamentalFrequency/LMN-3-Firmware)
The LMN-3-Firmware is the software that runs on the Teensy microcontroller that is soldered to the PCB. All the switches and encoders are connected
to the Teensy, which communicates with the Raspberry Pi running the LMN-3-DAW via MIDI. 

#### [LMN-3-Emulator](https://github.com/FundamentalFrequency/LMN-3-Emulator)
The LMN-3-Emulator emulates the physical LMN-3 hardware. It is software that sends the same MIDI information that the hardware sends, and is 
controllable via a graphical user interface. It can be very useful for developers wanting to test out the DAW without
needing a physical LMN-3 device. 

#### [LMN-3-Keycaps](https://github.com/FundamentalFrequency/LMN-3-Keycaps)
The LMN-3-Keycaps repository contains OpenSCAD files for creating the keycap models used in the FreeCAD assembly found in the 
[LMN-3-MCAD](https://github.com/FundamentalFrequency/LMN-3-MCAD) repository. It also contains keycap icons that can be printed and attached to
the keys themselves. 




