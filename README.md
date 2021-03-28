# CPU-4bit-simulation
21 march 2021

The source of this project is https://www.bigmessowires.com/nibbler/ and where the schematic and the data files can be found:
"Download the Nibbler file archive containing all the design files and tools".

I use the schematic from pong74ls so the names of tunnel/labels etc. can be a little bit different, see 

https://github.com/pong74ls/Nibbler/blob/master/Documentation/Nibbler%20-%20Schematic.pdf

The simulation is made with 

https://www.simulide.com/p/home.html

Simu files can be opened and run with SimulIDE software and is available for download here :

https://www.simulide.com/p/downloads.html

I use version 0.4.14

*****************************

24 march - Cpu4-Part5 is my first attempt with the Roms uploaded with bin-files taken from the Nibbler File Archive here:

https://www.bigmessowires.com/nibbler/

The display shows no sign of life. ProgRom contains the guess-a-number file.
The bin files get the extension .data when saved in Simulide.

**************************

In Part6 I changed the ProgRom to mastermind.data and the display becomes active.

**************************************

25 march - Cpu4 Part8 is the final version, the push buttons are replaced with switches. The simulation does not respond very well to the input switches, it takes several minutes before something changes in the display so playing a game is not possible. Has to do something with the clock, originally at 2.46 MHz the simulation is at 10 kHz and is only 9% of real time.

More details about this Nibbler (and ALU 74HC181) simulation are here and here:
https://simulide.forumotion.com/t125-nibbler-4-bit-cpu
https://simulide.forumotion.com/t143-74hc181-alu-8-bit



