# nucleo64-dfu-sock
Stm Morpho Header MicroPython extention board

  # Knitting Socks for (micro)Pythons
  
This small board connects to the bottom of STM32 Nucleo-64 boards trough STM Morpho Header.

 ![DFU SOCK BOARD](https://github.com/zmech/nucleo64-dfu-sock/blob/master/dfu-sock%20board.jpg)
 
 ![sock_is_on](https://github.com/zmech/nucleo64-dfu-sock/blob/master/sock_is_on.jpg)
 
So fits like a sock. Board has microUSB, SD card socket and SPI flash memory chip. Clip the board to
any Nucleo64 board download corresponding DFU file and you have fully functional MicroPython board.

I made definitions for [NucleoF401RE](https://github.com/zmech/NUCLEO_F401RE_DFU_SOCK), [NucleoF411RE](https://github.com/zmech/NUCLEO_F411RE_DFU_SOCK), [NucleoL476RG](https://github.com/zmech/NUCLEO_L476RG_DFU_SOCK) to use with DFU-SOCK board and tested them.

I have tested as well different spi memory chips. Adesto and Winbond from 8 Mbit to 128 Mbit work fine. 

Order the pcb [here](https://easyeda.com/azhirov/nucleo64-v2-0)
