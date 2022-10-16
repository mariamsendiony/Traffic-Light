# Traffic-Light
# Overview
An embedded system project based on real life traffic systems.There are two traffic lights one for the car and one for the pedestrian which both accomodate to the current needs of the external environment with perfect synchronization and fast response.
# Table of contents
-Normal Mode
-Pedestrian mode
###
Normal mode:
In the normal mode, the traffic light of the pedestrian is opposite to that of car pedestrian.Red in one is green in the other.Change from normal mode to pedestrian mode when the pedestrian button is pressed.
###
Pedestrian mode:
If pressed when the cars' Red LED is on, the pedestrian's Green LED and the cars' Red LEDs will be on for five seconds, this means that pedestrians can cross the street while the pedestrian's Green LED is on.If pressed when the cars' Green LED is on or the cars' Yellow LED is blinking, the pedestrian Red LED will be on then both Yellow LEDs start to blink for five seconds, then the cars' Red LED and pedestrian Green LEDs are on for five seconds, this means that pedestrian must wait until the Green LED is on.At the end of the two states, the cars' Red LED will be off and both Yellow LEDs start blinking for 5 seconds and the pedestrian's Green LED is still on.After the five seconds the pedestrian Green LED will be off, and both the pedestrian Red LED and the cars' Green LED will be on.Finally,Traffic lights signals are going to the normal mode again.The long press and double press shouldn’t affect the system.
#You can run this code on Gcc microchip and choose Avr32A as the desired microcontroller
#No license.
