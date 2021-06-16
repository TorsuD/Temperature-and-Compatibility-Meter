# Temperature-and-Compatibility-Meter

Switches and buttons are essential, but the physical world seems to have a lot more than just pressing buttons to perform an action. Arduino is a digital tool, but it can also read analog signals with its analog sensors that measure light or temperature.
With the help of the Arduino’s in-built Analog to Digital Converter also known as the ADC, this is made possible.
It has pins A0-A5 that reports back values ranging from 0-1023, which maps to a range from 0 volts to 5 volts.
In this project, a temperature sensor is used to measure how warm the skin is. 
The temperature sensor outputs a changing voltage that is dependent on the temperature it senses.
It consists of three pins: one that connects to the ground, another that connects to power, and a third that outputs a variable voltage to the Arduino. 
In this experiment, a temperature sensor is required, which, when touched, displays the temperature recorded from the person on a screen.
Upon touching the temperature sensor, the signals would be recognized from the lights coming from 3 red LEDs. 
In the program, there are temperatures that have been set for each LED that would light up one by one.
If the base temperature, which we set to -20°C,
climbed by 1°C, one LED would light up; if the base temperature grew by 3°C,
two LEDs would light up; and if the base temperature grew by 5°C, all LEDs would light up.
The experiment was set up in the same way as the schematic diagram below: 


![image](https://user-images.githubusercontent.com/65884749/122141208-5b4c0380-ce3c-11eb-9c44-6040cc36636f.png)


This directory is maintained by TorsuD, arabsannan, Djayappiah, Elsieann, Hilton-Blankson.
You can look up the main code of this project on the master branch on this repository.
You can learn more using this link https://youtu.be/UwTFfa_f4-0
You can also learn more using this link 
