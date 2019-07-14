# CC26xx Simple Peripheral Example
Striped down version of the "Simple Peripheral" Example for CC2650/40 using a Custom Board.

## Introduction

This is a modified version of the Simple Peripheral example that comes with the BLE Stack for TI's CC2650 and CC2640. 

The objective was to have a version of this example that would work out of the box with most custom hardware other than TI's development boards; or, at the very least be easy to configure. 

## The Board
Tested on a board with the following characteristics:

CC2640 RHB Package
LED on DIO_11
Button on DIO_12

A reference design for this board can be found [here](http://www.ti.com/tool/TIDC-CC2650-UTAG)

## Requirements
This example uses the Simple_Peripheral_CC26xxLP Stack provided for the CC2650 Launch Pad on the BLE Stack.

Regarding the application, only the modified files are included. You will need to import the Simple_Peripheral_CC26xxlp_app from the stack and replace the files with the ones on this repository

## Features

- Uses System_printf instead of LCD Display to show the application info
- Implements one button and one LED.
- Pins can be configured on board_key.h

## TBD

- Enable/Disable advertisement on button press
- Try OAD
- Include circuit design files
