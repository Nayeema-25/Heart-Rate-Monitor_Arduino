# Arduino-Uno-Heart-Rate-Monitor_With-Oled-Display
A real-time heart rate monitoring system using HW827 sensor &amp; Arduino. Displays BPM on an OLED screen. Useful for healthcare &amp; fitness tracking

INTRODUCTION:


The purpose of this project was to develop a heart rate monitor using the HW827 sensor and Arduino microcontroller.
The project aimed to measure the user's heart rate in beats per minute (BPM) and display it in real-time on an OLED display.
The Pulse Rate Monitor project aims to provide a cost-effective and accessible solution for monitoring heart rate using Arduino microcontroller and a pulse sensor module.
This report outlines the components used, the setup process, working principle, and potential applications of the system.





COMPONENTS SETUP:

Hardware Components:
HW827 heart rate sensor
Arduino microcontroller board 
OLED display
Connecting wires
Software Components-
Arduino IDE 
Adafruit GFX library 
Adafruit_SSD1306 library
Pulse Sensor Playground library

CIRCUIT DIAGRAM:




WORKING PRINCIPLE:


The theory behind optical heart-rate sensors is very simple. If you’ve ever shined a flashlight through your fingers and observed your heartbeat pulsing, the concept of optical heart-rate pulse sensors can be easily grasped.
A pulse sensor, like any other optical heart-rate sensor, works by shining a green light (~ 550nm) on the finger and measuring the amount of reflected light with a photosensor.
This optical pulse detection technique is known as Photoplethysmogram (PPG).
The oxygenated hemoglobin in arterial blood has the property of absorbing green light.
With each heartbeat, blood is pumped through the finger, causing a change in the amount of reflected light, which in turn produces a waveform at the photosensor’s output.
As you keep shining light and taking photosensor readings, you quickly begin to obtain a heartbeat pulse reading.
The pulse sensor detects changes in blood volume in the fingertip caused by the pulsatile flow of blood.
The sensor generates an analog signal proportional to the detected pulse.
The Arduino microcontroller processes the analog signal and calculates the pulse rate using predefined algorithms.
The calculated pulse rate is then displayed on an output device, such as an LCD screen or serial monitor, for the user to view.

 

APPLICATION & FUTURE SCOPE: 

The Pulse Rate Monitor system has various applications, including:
Monitoring heart rate during exercise or physical activities.
Tracking health conditions such as hypertension or arrhythmias.
Integration with wearable devices for continuous health monitoring.
Future enhancements and potential applications of the system include:
Implementation of wireless connectivity for remote monitoring.
Integration with mobile apps for data visualization and analysis.
Enhancing the user interface for improved usability and accessibility.



CONCLUSION:

The heart rate monitor project utilizing the HW827 sensor and Arduino microcontroller was successfully implemented.
It demonstrated the feasibility of measuring and displaying heart rate data in real-time. 
With its low cost and versatility, this system has the potential to impact various domains, including healthcare, fitness, and wellness.
This project lays the foundation for further development and integration into wearable health monitoring devices.
Continued development and integration with emerging technologies will further enhance its capabilities and applications..


