
Before you continue reading:
Both boards are relatively simple, both based on AtMega238p
and both running the same code. Both original board types
have the chip unlocked, meaning that with some programmer
or even just Arduino running the Example programmer sketch
you can read the code and flash it to another.

If you have a board that died you can first try to revive it
by flashing code downloaded from a working board. If that doesn't
work, try checking for component failure (caps shorted, ...),
replace the AtMega238p and flash again.

Please be careful, I am not responsible if you accidentally
damage, wipe or owerwrite your working boards!!!

If you are missing a board or want to make more continue reading.

## WHAT IS THIS?

In this archive you will find two KiCad 10 projects + all footprint
and symbol libraries. One project has the main EQ board and the other
the 3 light boards that are chained to the EQ board.

The connections were just traced by eye and multimeter.

The included schematics map out all the components as found on the original
boards. There are links to manufacturers websites of the connectors.

The PCB design should really only be used as a reference. The size
and mounting hole spacing has been checked and is correct. Component
layout is approximately the same as on the original board,
but the passives have whatever footprint I found, same as the dipswitch
and some other components. Basically if you want to make it,
make sure you change the footprints on the board to
what is actually available.

**PLEASE NOTE THAT YOU WILL NEED AT LEAST ONE OF THE ORIGINAL BOARDS
AND AT LEAST AN ARDUINO TO GET THE CODE OFF OF THE ORIGINAL BOARD.
I do not and will not share so i don't get in troubles.
This archive was made just for preservation purposes.**


# Other then the 2pin and 4pin power connectors, the footprint connectors are correct.

For the mini-fit: The footprint I have selected and the actual component I bought are slightly different, where the footprint is slightly rectangular, but the actual component I bought is square. I am not sure if there is different SKUs that differ or if it is straight up different connectors. Will update when I investigate some more.
