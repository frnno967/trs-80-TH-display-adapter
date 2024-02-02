# Digital Video Display Adapter for the TRS-80 Model 3 or Model 4
A through-hole remix of [Matt Boytim's TRS-80 FPGA Digital Video display adapter.](https://github.com/maboytim/TRS-80_Display_Adapter/tree/main) Created with EasyEDA.

This remix removes the unused VGA connections, adds some handy powering options, adds additional silkscreen descriptions, and uses all through-hole parts for ease of assembly by the hobbyist.

![trs80DA front](https://github.com/frnno967/trs-80-TH-display-adapter/assets/73573576/df06c01c-6520-46e6-8814-4b09d0f34983)

![trs80DA back](https://github.com/frnno967/trs-80-TH-display-adapter/assets/73573576/58cda5c3-4972-4141-b251-43a9efbe860b)

# Minimum Required parts:
* QTY 1 Tang Nano 9K FPGA board with headers and programmed with bitstream from https://github.com/maboytim/TRS-80_Display_Adapter/tree/main/fpga for the appropriate Model, either 3 or 4.
* QTY 2 24 Pin Female to Male 2.54mm headers for attaching Tang Nano 9K to the PCB
* QTY 2 2 Position Male to Male 2.54mm Pin Headers for use with J3 and J5
* QTY 1 3 Position Male to Male 2.54mm Pin Headers for use with H1
* QTY 3 2.54mm Jumper Shunts like TE Connectivity 2-881545-2
* QTY 1 Texas Instruments SN74LV125AN Quad Bus Buff Gate With 3-State Outputs, or equivalent for U1. 
* QTY 1 L7805 Linear Voltage Regulator, or equivalent DC/DC voltage converter regulator for U3
* QTY 1 10uF Polarized Electrolytic Capacitor, Radial Leads for C1
* QTY 2 1uF Polarized Electrolytic Capacitor, Radial Leads for C3 and C4
* QTY 1 0.1uF Polarized Electrolytic Capacitor, Radial Leads for C2
* QTY 2 Axial 1K Ohm 1/4 Watt Resistors for R6 and R7

# Additional Optional Parts:
* QTY 2 6 Position Male to Male 2.54mm Pin Headers for use with H2 / H3 Video Input from Motherboard for direct connection without the CRT Harness, with pass-through connector
* QTY 1 16 Pin 2x8 Male to Male 2.54mm Pin Headers for use with J4 Option Jumpers for future settings
* QTY 1 Molex 22-05-1042 Male Right Angle 4 Pin Header for power via system power supply, or for use as pass-thru power. Do not operate power-hungry devices off of 5V output of this connector!

Special thanks to Matt Boytim and all of the TRS-80 community for creating awesome enhancements like these.
