# FPGAConfigurationSubsystem

It's a circuit which sets up an FPGA with a bitstream saved in SPI FLASH connected to MCU.



## What chips are used?

- STM32F103C8T6 MCU   
- W25Q32/W25Q64/W25Q128 SPI Flash   

## How does it work?

When FPGA board is powered on, You can choose one bitstream from a few saved on a SPI FLASH.   
Choosing bitstream can be done:   
- by pressing one of few buttons
or   
- by setting a DIP switch and pressing a button   
it is not defined Yet.
