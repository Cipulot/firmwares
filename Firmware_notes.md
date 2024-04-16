# Firmware notes

* The EC Pro 2 and EC Pro X firmware files are NOT interchangeable. Flash the firmware based on the actual PCB model you have.
- The version in the firmware name, e.g. “board_1_0_0.bin” and “board_1_1_0.bin” mark the compatibility with different hardware revisions. Flash the .bin with the matching revision of your PCB. If no revision name is present then all boards will work with the firmware.
* Some firmware names have additions, like “proto”, “F401”, “F411” etc mark the specific firmware version for dedicated hardware changes or versions.
  - “Proto” is usually reserved for low unit run prototypes that might have differences from the final run. E.g. the EC980C protos
  - “F401” and “F411” marks specific MCU usage in case of specific revision that share the same general revision number (eg 2.1 or 1.1 etc) but have benefits in having MCU swap
Generally speaking the specified revision is the “uncommon one”, while the file w/o any specifications will be for the “most common” ones around.
In case of doubt contact me with pictures of the board and we’ll figure it out.
