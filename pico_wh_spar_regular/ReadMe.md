**SPAR Joystick App Firmware**

Use the bootsel method to upload the firmware pico_wh_spar_regular.uf2 to the Pico WH.
No need to add any code, its already inbuilt in the uf2 file itself.
Power off the Pico WH and connect it to the robot using the circuit diagram shared.
It will connect to the SPAR Joystick App.
Both BLE or WiFi can be used to control the robot.
If any wheel is moving in the opposite direction than whats expected, just interchange the motors wires at the motor driver.
Turn off mobile data when using WiFi to connect, as it interferes with the IP address assignments.
