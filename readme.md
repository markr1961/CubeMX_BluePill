
## A BluePill project build using CubeMX.

## Build IDE
CubeMX  
IAR 7.80.4  

### Processor
SYSCLK/AHB/HCLK/PCLK2 = 72 MHz.  
APB1/PClk1 = 36 MHz.
RTC 32KHz.  

## I/O
PC13    LED  
no button.  
Vbat on header, no cap  
Not all boards have correct USB resistors  
Boot0/Boot1 jumpers.  
SWIO/SWCLK pins (also need reset)  

## Design info
[STM32 Blue Pill](https://www.land-boards.com/blwiki/index.php?title=STM32_Blue_Pill) at Land Boards.  
[original schematic](https://stm32-base.org/assets/pdf/boards/original-schematic-STM32F103C8T6-Blue_Pill.pdf) at stm32-base.org.  
