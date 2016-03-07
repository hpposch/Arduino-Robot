#Arduino-Robot Projects
##Ultrasonic Sensor Array

Demonstrate how the Pin Interrupt mechanism is used to monitor the echo signal from ultrasonic sensors.
The delta time between the rising and falling edge of the signal is used to calculate the delta time which is directly proportional to the distance.

A timer interrupt is used to provide a delay between the channels in the sensor array.
In practice the whole sensor interface is implemented in the interrupt routines done in the background at maximal speed and efficiency.