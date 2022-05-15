# EKEN-FIRMWARE
Old and Hard to find firmware for EKEN Action Cameras

***WARNING***
I make no guarantees about these firmware files.  I will do my best to document each file, but there are plenty of forum posts about flashing gone wrong that can brick
these cheap action cameras. I am posting these firmware files on github because the Eken FTP server is down, and most download links have expired.  If you have any 
additional information about the firmware (or additional firmware files to add) please submit a pull request!

The "R" camera versions come with a remote control.

Some camera models (like the H9) have multiple possible firmwares, because there is more than one version of the camera, using different LCD chipsets.

The Eken H9 comes in "Type 1" using the ST7789S chipset, and "Type 2" using the ST9341 chipset.

To determine your camera's type, you can either crack it open and look at the screen driver, or use a site like Eken H9 Bricked which lists a mapping between firmware versions and camera types.

Type 1 H9 cameras, came delivered with Firmware Version: 150826, 150910, 150910SJ, 150928, 150928SJ, 151005, 151005SJ, 151009, 151103, 151103SJ, 151128, 151128SJ, 151204, 151208, 151208SJ, 151229, 151229SJ, 160108, 160108SJ, 160421SY Type 2 H9 cameras, came delivered with Firmware Version: 150911, 150911RJ, 150914, 150914LY, 151010, 151015, 151127, 151207, 151228LY, 151230, 160106, 160108, 160108LY, 160222, 160304, 160309LY, 160309LY(4k25), 160326, 160421LY http://www.eken-h9-bricked.co.uk/SelectType1Type2Unknown.html

If in doubt, you can proceed with the Type 1 firmware, which will either work (because you have Type 1) or white the screen of your Type 2 camera. If this happens, just flash the Type 2 firmware and the display will be restored.

This is displayed in the camera's settings menu. There's a "Version" option. It will look something like:

ActionCam H9 151230

Which is a Type 2, Eken H9.


***Update Instructions***
There's a risk that the camera may brick if the update process is not executed properly, please use with caution or contact us for more support.

1. Format the micro SD card. Unzip the files and copy the SPHOST.BRN on to the micro SD card.  

2. Please update it when the battery is at 80% or more, or connect it to the charger before updating.  

3. Turn off the camera, plug the micro SD card into the camera.  

4. Press the on/off (mode) button, the camera will automatically start the update (screen will display "FW Update"). After the update completes, the red light will shut off.  

5. Take out the micro SD card and then reboot the camera.

6. Go to settings and select RESET. This is an important step.

7. Turn off the camera and turn on the camera to make sure update has been successful.

8. Remember to reformat the micro SD card before using it again. Reformat it on the computer before using.

