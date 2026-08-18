**SPAR Joystick App Firmware**

Use https://adafruit.github.io/Adafruit_WebSerial_ESPTool/ to upload the precompiled firmware to your ESP32C3 board at address 0x0.
Connect the ESP32C3 to the robot using the circuit diagram shared. It will connect to the SPAR Joystick App.
Both BLE or WiFi can be used to control the robot. 
If any wheel is moving in the opposite direction than whats expected, just interchange the motors wires at the motor driver.
Turn off mobile data when using WiFi to connect, as it interferes with the IP address assignments.
Enable bluetooth on your mobile, before starting the app, if you want to use the BLE option to connect. You can use both BLE as well as WiFi in this ESP32C3 board.
