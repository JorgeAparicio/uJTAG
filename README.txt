DESCRIPTION
===========

F4Dev is a small (3x2 cm) and minimalistic JTAG dongle. It provides a 6 pin
JTAG connector, pinout is shown below:

  TMS: Test Mode Select
  TDI: Test Data In
  TDO: Test Data Out
  TCK: Test Clock
  GND: Ground
  VDD: 3.3V output (150 mA + series diode)

There is no hardware reset signal, reset should be issued by software.

This JTAG dongle has been tested with STM32 microcontrollers and openOCD.

http://openocd.sourceforge.net/

DEPENDENCIES
============

This work uses the latest official KiCad library available at:

https://code.launchpad.net/~KiCad-lib-committers/KiCad/library

This work also uses the footprint from libKiCad available at:

https://github.com/JorgeAparicio/libKiCad

These libraries and this work must be in the same path, as shown below:

  <someFolder>
    F4Dev
      F4Dev.pro
      F4Dev.sch
      F4Dev.brd
      ...
    libKiCad
      3d
      footprint
      ...
    library (Official KiCad library)
      library
      module
      ...

LICENSE
=======

This work is licensed under the following license:

Creative Commons Attribution-ShareAlike 3.0 Unported (CC-BY-SA 3.0)

For more information see LICENSE.txt

