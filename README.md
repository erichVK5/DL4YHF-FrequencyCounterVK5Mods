# DL4YHF-FrequencyCounterVK5Mods
Additional clocking options for the DL4YHF frequency counter firmware by Erich Heinzle VK5HSE

Modifications to the 16F628 firmware to allow other clock speeds to be used for the 16F628

original firmware
4MHz
20MHz

modified firmware
4MHz
8MHz
10MHz
12MHz
13MHz
16MHz
20MHz

The assembler source needs to be compiled with the appropriate #DEFINE for the desired clock speed and a #DEFINE is also needed to select either common anode or common cathode LED display support.
