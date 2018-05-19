# FblCtrl
RC Helicopter Flybarless Controller implemented in VHDL. 

UNDER DEVELOPMENT. NOT COMPLETE PROJECT YET. USING THIS PROJECT TO LEARN MORE ABOUT GIT/GITHUB

The design is general VHDL modules (not specific to any technology), tested on Xilinx Spartan6 LX6

# Build
- The design has been tested with Xilinx ISE 14.7
  - Simulated using isim
  - Future is to use UVVM (https://github.com/UVVM/UVVM) and Modelsim

# Code
- All technology specific code (such as multipliers, Softcore microcontrollers, etc.) must have a wrapper. 
- All Components have a specific folder structure:
'''
- design component
 - src
 - tb
 - scripts
 - doc
'''

# END 