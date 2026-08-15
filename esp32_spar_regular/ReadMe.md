**SPAR Joystick App Firmware**

Use https://adafruit.github.io/Adafruit_WebSerial_ESPTool/ to upload the precompiled firmware to your ESP boards at address 0x0.
Connect the ESP32 to the robot using the circuit diagram shared. It will connect to the SPAR Joystick App.
Both BLE or WiFi can be used to control the robot. 
If any wheel is moving in the opposite direction than whats expected, just interchange the motors wires at the motor driver.
Turn off mobile data when using WiFi to connect, as it interferes with the IP address assignments.
