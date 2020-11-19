---
template: BlogPost
path: /SetConfigureBit
date: 2020-11-19T07:42:07.534Z
title: 02 Set Configure bit of PIC controller
metaDescription: Here we Configure Bit of PIC Controller
thumbnail: /assets/02MPLAB.jpg
---
# Configuration Bit:-

Configuration Bits are a collection of binary data located in the Flash program memory of a PIC microcontroller (MCU). Configuration bits are programmed into the PIC MCU with the application code. These bits are not executable code as their addresses are not accessible by the program counter. Configuration bits are derived from compiler directives placed into the code by the application developer.

Configuration bits are read by the MCU when exiting a reset and cannot be modified during run-time. Upon exiting reset, the configuration bits are used to complete circuitry which enables or disables hardware features of the MCU.

# How to set the Configure Bits in MPLAB:-

MPLAB users can edit these configuration bits by using Configuration Bits tool.

In the top menu bar click Production>>Set Configuration Bits as shown down below

![Production](/assets/2.png)

![Set bit Config](/assets/3.PNG)

![generate code](/assets/4.PNG)

   

![Generated Code](/assets/5.PNG)

The features controlled by configuration bits are:

1. Oscillator Selection Bits
2. Watchdog Timer Enable Bits
3. Power-up Timer Enable Bits
4. Brown-out Reset Enable Bits
5. Low-Voltage (Single-Supply)
6. Data [](https://microcontrollerslab.com/eeprom-working-interfacing-with-microcontroller/)EEPROMCode Protection Bit
7. Flash Program Memory Write Enable Bit
8. Flash Program Memory Code Protection Bit
