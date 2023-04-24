File was downloaded from the Sovol Download Page and here is what their instructions say they changed and what to do (I do not offer support for this just added it to make it easier to find.):

1. Improved auto leveling function.
2. Added the function of saving z offset automatically.
3. Adjusted the driver parameter of the motors.
4. Activated the SENSORLESS_ BACKOFF_MM function, reduced the risk of X axis hitting y axis.
5. According to the customer’s suggestions, changed the G28 XY command to G27, so that the bed will move forward after prints finished, which is more convenient to remove the prints.

Update firmware method: 
1. Drag the downloaded firmware into the TF card and delete other files.
2. When the machine is turned off, insert the TF card into the card slot 5. After powering on, the screen will be blue for a short time. At this time, the firmware is being flashed, and the logo will be displayed on the screen to enter the main interface menu. 
3. Shut down, take out the card, and the firmware update complete.

Tips: 
1. If the firmware wasn’t flashed successfully, take out the TF card, and rename the firmware name to firmware.bin on PC, and then try to flash the firmware again, if still failed, you can repeat to rename the firmware name randomly.
2. Make sure the card is formatted fat32 with 4096 allocation size. 
