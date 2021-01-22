## gcc-pi-bcd-counter - Displays a binary count.

Written in C. 

Demonstrates how to write data to the GPIO pins of a MCP23017 I2C I/O port
expander.

Note: Do NOT use this code to drive LEDs directly from the MCP23017 as the 
total output current could easily exceed the maximum current rating for the
device.  If you want to drive multiple LEDs at the same time you need to use
a display driver or a transistor to switch the current.
