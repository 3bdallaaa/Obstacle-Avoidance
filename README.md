# Car's Obstacle Avoidance Sensor
The idea of the project is the gradual change in the output duty   
It starts from rest at 20% in the first 3 seconds and then increases by 10% each second till reaching the max. duty   
If the IR sensor detected an obstacle, it starts to decrease the duty by 10% each second till the obstacle is removed   

The Frequency is set to 50 HZ for the motor used in this project and may differ from a motor to another   

This project uses STM32F103C8 arm
