You can now wire in the JTAG and test the CPU. Connect the JTAG pins, VCC+GND and power the board from USB by sliding S1 down. Do not use any automatic modes as TRST isn't exposed on the JTAG. The 7 pin IDC header at the bottom of the board is the JTAG socket. This is a Xilinx style connector.

The pins from left to right are

> VCC, GND, TCK, TDO, TDI, TMS

These connect with a standard ARM 20 pin JTAG as such

VCC = Pin 1
GND = Pin 20
TCK = Pin 9
TDO = Pin 13
TDI   = Pin 5
TMS = Pin 7

The ARM 20 Pin header is as follows


![http://wiki.032.la/images/Ulink_arm20pin.gif](http://wiki.032.la/images/Ulink_arm20pin.gif)