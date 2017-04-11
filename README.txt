The following contains the source code of Cache Me Outside.

The main circuit is CPU.circ, which depends on all the remaining ones. We have two ROMs available, for adding with loops or for multiplying directly. The explanation for ROM_mult is detailed in Multiply.txt.

To use the ROM, enable the ROM overwrite input, tick the clock near the RAM once, and then disable ROM overwrite. You can then enable ticks for the entire program.

We've implemented all of the functionalities in the assignment as well as the bonus for multiply and ROM. We have portions for reset, but they are not fully implemented and will not work properly.

Further details can be found in the report, with components of it in the various txt files.