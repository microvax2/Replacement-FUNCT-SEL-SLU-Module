# Replacement-FUNCT-SEL-SLU-Module
A Replacement For DEC's 5416744-0-1, 5016743-01-01 Rear BA23 Module

A replacement for the original MicroVAX II (KA630) CPU patch panel, also known as the “FUNCT SEL/SLU MODULE”.
The original DEC part numbers are 5416744-0-1, 5016743-01-01, and it can also replace 5417016-0-0 (KA650/KA655 SLU) and perhaps others as well.
 
Based on a PIC microcontroller, that drives a 5X7 LED matrix display and indicator LEDs, handles two user pushbuttons for setting MODE and BAUD, and provides the appropriate signals to the KA630 CPU.
Settings are saved in the microcontrollers’ non-volatile memory and immediately restored at power-up.

Two DB9 serial port connectors are provided, a male DB9 which is identical to the original connector, and a female DB9 with a modern PC pinout, to make life easier. Either one can be used.
A slide switch is used for setting HALT_EN.

A battery header is provided, for connecting an external NiCad battery pack.

A blank PCB, is used as a bracket/holder for attaching to the BA23 chassis. It makes the original metal bracket redundant. 
The SLU PCB is fixed to the bracket PCB, and the bracket PCB is fixed to the metal chassis, using standard 6-32 screws and nuts.

Note: selecting the LOOPBACK mode requires physically shorting (jumper) together two pins on the PCB. Not a very often used feature, so not a serious limitation.
