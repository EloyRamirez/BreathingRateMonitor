# BreathingRateMonitor
Final project for Digital Signals Processing class.

An Arduino Uno with a ATMEL MEGA 328P microcontroller was used to create a breathing rate detection system used to detect pneumonia in infants and young children. 
A LM61 temperature sensor was used to capture the breathing rate in real time. 
This signal was then filtered and the active filter was determined by comparing the standard deviations of the signals, with the highest energy indicating what was active. 
Based on the filter that was active, an alarm would output a tone or not play anything at all. 
There were three specific alarm tones. One for a low breathing rate, one for a high breathing rate and lastly one for a non-functional system
