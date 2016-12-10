# STM8L051F3-STM8-SDCC-Template
Template for using SDCC for the STM8L051F3 microcontroller with comprehensive definitions

The std_periph library from ST is great, but sdcc linker will throw all unused code into the binary.
Using bit/mask manipulation with the provided definition macros makes things a lot smaller and easier to understand IMO.

Example is UART/GPIO code

 The code is meant to test the UART connection and the chip.
 Works for STM8L051F3 on custom PCB breakout, where: PB0 is an LED, PB3 is a PU switch, PC5 is TX (pin1) and goes to 'TX' on arduino as a UART bridge
  
 Props to	
 * ST for the std periph libraries
 * the SDCC team for the compiler
 * Valentin Dudouyt for stm8flash & 'puts' routine
 * you for trying to read my code. 
 
 
 
 -- some dude with YOLO coding styles
