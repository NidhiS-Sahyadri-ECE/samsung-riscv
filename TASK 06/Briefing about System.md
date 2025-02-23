**Ultrasonic Distance Measurement:**

The distance of an object is measured using the ultrasonic sensor (TRIG on PD3, ECHO on PD4).<br>
The servo motor runs to one side and an LED (PD5) glows if the object distance is found to be under 10 cm.<br>
Else, the servo goes to the other side and the LED does not glow.<br>

---
**Moisture Sensor Monitoring**

PD0 is used to connect the moisture sensor.<br>
If the soil is dry (sensor output is LOW), an LED (PD6) is OFF.<br>
If the soil contains moisture (sensor output is HIGH), the LED is ON.<br>

---
**Servo Motor Control (PD2):**

Controls the servo motor with PWM signals provided by TIM1.<br>
Duty cycle is varied according to the measured distance to change the servo's angle.<br>

---
**Functions**<br>

The ultrasonic sensor senses an oncoming object (e.g., a human being or an animal).<br>
The moisture sensor checks for dryness in the soil or not.<br>
The servo-controlled valve can be installed to control the flow of water depending on soil moisture.<br>

---
