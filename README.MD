# Atmel MCU Programming Notes  
## This repo contains codes for different Atmel MCUs
1. Only save simple test/experimental code when using any MCU for the first time
2. If MCU is used in a different project, a seperate repo is used

## Interrupt  
![Source 1](http://www.nongnu.org/avr-libc/user-manual/group__avr__interrupts.html)  
![Source 2](http://www.avrfreaks.net/forum/tut-newbies-guide-avr-interrupts?page=all)  
1. ISR() Macro  
2. interrupt vector table can be found in the datasheet  
3. When programming, pre-defined interrupt vector can be found in IO definition file; i.e C:\Program Files (x86)\Atmel\Studio\7.0\Packs\atmel\ATtiny_DFP\1.0.68\include\avr\iotn841.h
	* pre-defined vector uses address(found in the datasheet) for the lookup table  

