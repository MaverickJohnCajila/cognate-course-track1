This circuit is an Arduino based digital counter which updates a 7 segment display using two pushbutton switches.
The main processor is the Arduino Uno , it also powers the breadboard through the 5V and ground rails . 

The two buttons are wired to digital pins 2 and 3, and they use pull-down resistors to keep a steady low 
signal until pressed, which then sends a 5V signal to the Arduino.
When the microcontroller receives this input , it changes its internal count either up or 
down and converts the data to a numeric format . 

It then routes power through digital pins 4 to 10, through protective current-limiting resistors 
to light up particular LED segments. The common pins of the display are grounded ,
so that this coordinated sequence nicely visualizes 0 - 9 .
