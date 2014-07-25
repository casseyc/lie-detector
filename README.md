lie-detector
============

Circuit created for a first year digital systems project that uses an Arduino Uno and the nature of the galvanic skin response (changes in resistance) to detect lies. 

Uses x1 Arduino Uno, x1 potentiometer as a variable resistor, x1 tri-colour LED, x1 piezotransducer as a buzzer, x1 470kΩ resistor, x3 100Ω resistors, x2 200Ω resistors, x2 thumb tacks, and x2 buttons.

The resistance of the subject is compared to the resistance set by the potentiometer. The potentiometer is used as a variable resistor in order to "match" the resistance of the subject before being questioned. When people tell a lie, moisture forms at their fingertips which lowers the resistance; the LED will turn red and the buzzer will sound. The potentiometer should be used to ensure the LED is green before each question is asked. The green LED indicates that the subject and the variable resistor are within an acceptable range and the subject is telling the truth. The LED turns blue when the resistance of the potentiometer needs to be adjusted. 

