# Introduction
The growing number of vehicles and limited space for parking is a major concern in 
urban areas. To manage the parking space effectively, we need an intelligent parking 
system that can monitor and allocate parking spots to vehicles. In this project, I
developed a car parking system using Verilog code that can detect the presence of a 
vehicle in a parking spot and display the occupancy status of each spot on a display.
## Project Description
The project can be implemented using an FPGA board, ultrasonic sensors, and a 
PmodOLED display. The ultrasonic sensors can be used to detect the presence of a 
vehicle in each parking spot, and the occupancy status of each spot will be displayed on 
the PmodOLED display.
## Ultrasonic Sensor
Ultrasonic sensors work by sending out high-frequency sound waves and measuring the 
time it takes for the sound waves to bounce back after hitting an object. In this project, 
I used four ultrasonic sensors to detect the presence of a vehicle in each parking 
spot. The ultrasonic sensors were connected to the input pins of the FPGA board.
### PmodOLED Display
The PmodOLED display is a small OLED display that can be easily connected to the FPGA 
board using the PMOD port. The display can be used to show the occupancy status of 
each parking spot in real-time.
### Verilog Code
The Verilog code for the car parking system was developed using Xilinx Vivado 
software. The code use the ultrasonic sensors to detect the presence of a vehicle in 
each parking spot and store the occupancy status of each spot in a register. The 
occupancy status of each spot will be displayed on the PmodOLED display using the 
binary format.
