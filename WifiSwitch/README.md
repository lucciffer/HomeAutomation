This is a simple Arduino based wireless switch mechanism, that operates via bluetooth. Since I needed a switch to turn my wifi plug on and off, I designed it to perform  
the same. This project is done using MATLAB simulink model on Arduino Mega 2560. 
In the mobile app, to send commands via bluetooth, ON corresponds to '1' and off corresponds to '0'. 
when 'ON' button is pressed on the mobile app, the servo motor arm rotates by 135 degrees,turning the switch ON, and again goes down to 110 degrees which is the stand-by mode for the arm,
and when the 'OFF' button is pressed, the motor arm rotates again by 135 degrees turning thw switch OFF and again goes back to 110 degrees in stand-by.
This mechanism can also be achieved by using a relay, as a switch to directly power the appliances and whatever the application is.

This MATLAB Simulink model is tested and works fine.  
In case of errors(if any) report to techh.engine@gmail.com
