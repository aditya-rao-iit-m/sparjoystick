**SPAR Joystick App Firmware**

In Windows 10 or 11, download the spar_flasher_arduino_uno_r4_wifi_windows.zip first, to upload the precompiled firmware to your Arduino UNO R4 Wifi board.
In Linux, download the spar_flasher_arduino_uno_r4_wifi_linux.zip, to upload the precompiled firmware to your Arduino UNO R4 Wifi board.
After downloading the zip file, extract it to your desktop.
If you are flashing the firmware in Windows, just connect the board using a proper USB cable that supports data transfer, open a command terminal window in this extracted folder, and run the spar_flash.bat batch file.
If you are flashing the firmware in Linux, just connect the board using a proper USB cable that supports data transfer, open a terminal window in this extracted folder, run "chmod +x spar_flash.sh" to make it executable, then run "./spar_flash.sh" to flash the firmware.
Both BLE or WiFi can be used to control the robot. 
If any wheel is moving in the opposite direction than whats expected, just interchange the motors wires at the motor driver.
Turn off mobile data when using WiFi to connect, as it interferes with the IP address assignments.
