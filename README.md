# 386ex Firmware Prototyping/Design Board
386EX-target firmware design board based on the design from Ed Nisley and his Firmware Furnace column
in Circuit Cellar. The article series spanned Issues 31 to 65 (roughly 1993 to 1995). The hardware
design -- a short ISA card built on a Jameco prototyping card -- provided an easy way to interface
to the ISA bus and had memory (EEPROM/ROM/NVRAM). a timer, watchdog, LED and switch inputs, and two
types of LCD displays. 

The first part of the series (Issues 31- 46) dealt with the hardware design, while later articles
discussed something Ed called the "Firmware Furnace Task Switcher", a functional protected-mode
software platform. The software discussion began in Issue 48 and ended with Issue 65. Issue 65
seems to point to future columns on the topic, but they never seemed to appear.

## Status
The schematics have been converted and the board plotted. It has not been built yet. Of the
design elements, the only feature I didn't redraw was the bitmapped graphics LCD panel, the
discission of which began in Issue 42. Options were the Optrex (Kyocera) DMF651 640x200 or the 
Matsushita EDM-LG64AA44D 640x400 panel.

