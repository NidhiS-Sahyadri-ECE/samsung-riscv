# About my project
The ultrasonic sensor detects the object's distance and, if detected at a range of 10 cm, adjusts the servo motor (used as water pump) position and turns on an LED for proximity detection; otherwise, the servo repositions and turns off the LED. <br> 

The soil moisture sensor detects soil humidity and turns on an LED in the presence of moisture and off if the soil is dry.<br> 

The servo motor is driven with PWM signals from TIM1, which varies its position according to the measured distance. <br>

This arrangement can be utilized in an automatic plant monitoring or watering system, where the ultrasonic sensor measures movement and the moisture sensor decides whether watering is required.
