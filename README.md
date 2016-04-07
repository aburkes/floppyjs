# floppyjs

Current Status: Dreaming
------------------------

Floppy disk drive emulator in node.js
-------------------------------------

This is an experimental floppy disk drive emulator. At the moment, development is being done on the Beaglebone Black via the Beaglebone library, but porting to other hardware systems such as the Raspberry Pi should theoretically be trivial.

This project is not designed to be an end onto itself; rather, it's a testbed to use for the eventual development of a floppy drive emulator for microcontrollers that can be made cheaply and easily. Such devices already exist, but they are either require propriatary firmware or leave much to be desired.

The inspiration for this project is actually an existing series of "homebrew" devices by Jean-Francois del Nero. He has opened up much of his developments. In fact, his early CPLD version is completely open source, both in hardware and software, as are a number of supporting software utilities (the repository for these are actually here on GitHub).

The only reason why this project exists is simply that his current PIC18-based emulator is closed-source. I appreciate all of the work he has done, and I am not doing this to hurt his project in any way. I just believe that a libre implementation of the concept might be able to grow in ways that an individual-led project could not.
