# DLD-Project-Solar-Tracking-System-
Automatically orients a solar panel toward the sun throughout the day to maximize the amount of sunlight captured, improving energy efficiency compared to static solar panels.
# DLD Solar Tracking System

## Project Overview
The **DLD Solar Tracking System** is an automated solar panel system designed to **maximize solar energy capture** by following the sun’s movement throughout the day. The system uses **sensors and a microcontroller** to adjust the panel’s position along one or two axes, improving efficiency compared to a fixed solar panel.



##  Components Used
- **Microcontroller:** Arduino UNO / Arduino Mega  
- **Sensors:** Light Dependent Resistors (LDRs)  
- **Actuators:** Servo motors or DC motors  
- **Power Supply:** Solar panel and battery or external power  
- **Other Materials:** Jumper wires, resistors, mounting frame, breadboard/PCB  



##  How It Works
1. **Sensor Detection:** LDRs detect sunlight intensity from different directions.  
2. **Signal Processing:** Microcontroller compares sensor readings to determine the sun’s brightest direction.  
3. **Motor Control:** Servo motors rotate the solar panel horizontally and/or vertically.  
4. **Continuous Adjustment:** Panel continuously follows the sun throughout the day.  



## Features
- Automatic sun tracking for **maximum energy efficiency**  
- Dual-axis or single-axis movement  
- Simple sensor calibration  
- Easy integration with Arduino IDE  



## Circuit Diagram / Wiring
- Connect LDRs to analog pins of the Arduino.  
- Connect servo motors to PWM pins.  
- Provide power to Arduino and motors (check motor specs).  



## How to Run
1. Connect all sensors and motors as per wiring diagram.  
2. Upload `solar_tracker.ino` to your Arduino using Arduino IDE.  
3. Power the system and observe the solar panel adjusting toward the sunlight.  



## Results
- Increased energy capture compared to static panels  
- Smooth and responsive panel movement  
- Practical application of **Digital Logic Design principles**  



##  Notes / Improvements
- Use **stepper motors** for more precise movement  
- Implement **data logging** for energy efficiency analysis  
- Add **automatic sleep mode** during low sunlight  



## References
- Arduino official documentation  
- LDR sensor tutorials  
- Servo motor control guides  
- Solar tracking project tutorials on GitHub
