# DL4YHF-FrequencyCounterVK5Mods
Additional clocking options for the DL4YHF frequency counter firmware by Erich Heinzle VK5HSE

Modifications to the DL4YHF 16F628 firmware allow other clock speeds to be used for the 16F628...

original firmware supports the following 16F628 clocks:

	4MHz
	20MHz

the modified firmware supports the following 16F628 clocks:

	4MHz
	8MHz
	9.6MHz
	10MHz
	12MHz
	13MHz
	14.4MHZ
	16MHz
	19.4MHz
	20MHz

The assembler source needs to be compiled in Microchip's MPLAB with the appropriate #DEFINE for the desired clock speed and a #DEFINE is also needed to select either common anode or common cathode LED display support.

Support for 4, 8, 10, 12 16 and 20MHz have been tested at the time of publication.

v1.02 gerbers in a zip file can be downloaded and can be used to order PCBs.

The PCBs shown in AR magazine were made by hackvana.com with the gerbers in this repository. Consider getting a bunch of them for a club construction night!

The PCB designs are compatible with the cheap surplus Aztronic, 40 pin, 4 digit common anode displays described in the WIA Amateur Radio magazine August 2015 edition. Aztronics may have v1.02 PCBs from time to time if you do not roll your own or have some made using the zipped gerber files.

The PCB is also compatible with DL4YHF's original common anode firmware for 4 and 20MHz MCU clock frequencies.

The PCB design is licenced under the TAPR open hardware licence - see http://www.tapr.org/OHL

The PCB layout design file has been added to the repository. It is in gEDA PCB format, which can be read, of course, by gEDA PCB, and also by pcb-rnd - see repo.hu/projects/pcb-rnd

The bill of materials is on the gerber file silkscreen layers, and can also be viiewed on the top and bottom silk text of the layout file in your chosen layout editor.

No warranties express or implied, particularly in relation to the functionality of the optional 5th digit!!!
