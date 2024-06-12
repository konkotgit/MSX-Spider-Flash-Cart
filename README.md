# MSX Spider Flash Cartridge
Very Simple Cartridge for MSX Computers

With this PCB you can build your own MSX ROM cartridges.

You can use 8, 16, 32 or 48kB ROM file.


## Programming Spider Flash Cartridge

1. Power off your MSX computer.
2. Switch the cartridge to the "off" position.
3. Insert the cartridge into the cartridge slot.
4. Power on your MSX computer and boot into MSX-DOS.
5. Switch the cartridge to the "on" position.
6. Use the `WRTSST.COM` utility to program the cartridge:
    ```sh
    WRTSST.COM <rom_file>
    ```
7. Power cycle the computer. Your cartridge is ready for use.


This program uses flashing software written by [HRA!](https://github.com/hra1129).


You can access the `WRTSST.COM` utility here: [WRTSST.COM](https://github.com/hra1129/MSX_MegaSCC_for_SST39SF040/blob/main/tools/wrtsst/WRTSST.COM).


![Spider Flash Cart](/photos/spider_flash_02.jpg)

### Look at YouTube:
[![Spider Flash Cartridge Youtube Video](https://img.youtube.com/vi/3AW7ACw8Hgg/0.jpg)](https://www.youtube.com/watch?v=3AW7ACw8Hgg)
