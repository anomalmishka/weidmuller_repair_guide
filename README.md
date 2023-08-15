# weidmuller

##Weidmuller PRINTJET ADVANCED 230V

##![Weidmuller PRINTJET ADVANCED 230V](https://cdn.pressebox.de/a/030d574ca176c798/attachments/0576552.attachment/filename/Photo+PJA_1.jpg)

##How To Repair Weidmuller Printjet

###If, after replacing the original cartridges or after a malfunction of the print head cleaning system, you have a non-resettable error "Contact the service", follow the instructions
###You will need a screwdriver, a programmer, smooth hands and a little luck)
###**--**
###-Carefully disassemble the printer
###-Remove the printer board
###-Carefully remove the 24c32 DIP8 chip
###-Use the programmer to read the program and save it
###-Clean the eeprom completely
###-Insert the chip back onto the printer board
###-Minimally assemble the printer by connecting all cables and connectors
###-Turn on the printer 
###You should see the printer attempt to read its data from the eeprom, the amount of ink, the software version, etc.
###The message "update" will appear on the screen. The printer will not be able to boot completely!!!
###After a failed boot, disassemble the printer again and remove the 24c32 chip.
###Use the programmer to read and save the second program.
###Compare two files.
###A copy of the second program needs to be modified.
###For example, I attach three files, with an error, after erasing, and a working one.
