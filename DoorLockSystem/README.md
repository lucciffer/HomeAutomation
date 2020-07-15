This is a simple Arduino based door locking mechanism, that operates via IR sensors mounted one on each side of the door.  This project is done using MATLAB simulink model on Arduino Mega 2560. 
When the IR sensor on one side of the door, detects any human presence, it sends signals, and the servo motor rotates by 90 degrees clearing obstacles for the door to open,
and after a delay of few seconds, the motor rotates back to its 'lock' position, creating obstacles for the door to open, and thus locking the door.
The same process happens over and over, when IR sensors on either sides, detect human motion in front of it(at a distance of about 3cm from the sensor to eliminate unnecessary activation of motor)
This can even be encorporated with electronic door locks instead of servo motors.

This MATLAB Simulink model is tested and works fine.  
In case of errors(if any) report to techh.engine@gmail.com
