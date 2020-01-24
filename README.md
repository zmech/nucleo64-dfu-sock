# nucleo64-dfu-sock
Stm Morpho Header MicroPython extention board

  Knitting Socks for (micro)Pythons
  
This small board connects to the bottom of STM32 Nucleo-64 boards trough STM Morpho Header
So fits like a sock. Board has microUSB, SD card socket and SPI flash memory chip. Clip the board to
any Nucleo64 board download corresponding DFU file and you have fully functional MicroPython board.

I made definitions for NucleoF401RE, NucleoF411RE, NucleoL476RG to use with DFU-SOCK board and tested them.

I have tested as well different spi memory chips. Adesto and Winbond from 8 Mbit to 128 Mbit work fine. 
