# LiPo-3S-BMS
Battery Management System based on bq78350R1 and bq79620 - Designed for 3S LiPo batteries

- Originally created for the [INSA Rennes robot club](https://github.com/clubrobot)
- Schematics and PCB made with Autodesk Eagle
- FETs controlled on the low-side (communication based on ground connection not possible outside the BMS)
- Allow the atmega on the pcb to get the SoC, the voltage, current, remaining time and all the information available from the bq78350R1 (small C++ class using Arduino Wire provided)
- Version 1.1 removes the temperature sensor connector, has a smaller footprint and add a SMB connector for the EV2400 which is the development module necessary to interface the BMS with bqStudio on PC.

## TODO
Reduce footprint even further / Change FET control to high-side / Look for alternatives to the atmega to get battery status
