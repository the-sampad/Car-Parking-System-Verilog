# Design Testing
The testing of the car parking system will involve the following steps:
1. Testing the ultrasonic sensors
2. Testing the PmodOLED display
3. Testing the Verilog code
4. Testing the overall system
## Testing the Ultrasonic Sensors
To test the ultrasonic sensors, we will perform the following steps:
1. Connect one of the ultrasonic sensors to the input pins of the FPGA board.
2. Run a test code on the FPGA board that sends out a sound wave and measures 
the time it takes for the sound wave to bounce back from an object (e.g. a wall).
3. Verify that the measured distance is correct and matches the distance between 
the sensor and the object.
We will repeat these steps for all four ultrasonic sensors to ensure that they are working 
correctly.
## Testing the PmodOLED Display
To test the PmodOLED display, we will perform the following steps:
1. Connect the PmodOLED display to the PMOD port of the FPGA board.
2. Run a test code on the FPGA board that displays a message on the PmodOLED 
display.
3. Verify that the message is displayed correctly on the PmodOLED display.
## Testing the Verilog Code
To test the Verilog code, we will perform the following steps:
1. Synthesize and implement the Verilog code using Xilinx Vivado software.
2. Connect the ultrasonic sensors and the PmodOLED display to the FPGA board.
3. Run the Verilog code on the FPGA board.
4. Verify that the occupancy status of each parking spot is displayed correctly on 
the PmodOLED display.
5. Place a vehicle in one of the parking spots and verify that the occupancy status of 
that spot changes to "occupied" on the PmodOLED display.
6. Remove the vehicle from the parking spot and verify that the occupancy status of 
that spot changes back to "available" on the PmodOLED display.
## Testing the Overall System
To test the overall system, we will perform the following steps:
1. Connect the ultrasonic sensors and the PmodOLED display to the FPGA board.
2. Run the Verilog code on the FPGA board.
3. Place a vehicle in each of the parking spots and verify that the occupancy status 
of each spot changes to "occupied" on the PmodOLED display.
4. Remove the vehicles from the parking spots and verify that the occupancy status 
of each spot changes back to "available" on the PmodOLED display.
<h3> By performing these tests, we can ensure that the car parking system is functioning 
correctly and can accurately detect the presence of a vehicle in each parking spot and 
display the occupancy status of each spot on the PmodOLED display.</h3>
