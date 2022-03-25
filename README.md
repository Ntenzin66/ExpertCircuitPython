# ExpertCircuitPython


## Classes, Objects, and Modules

## Code and Description

```python
import time
import board
from rgb import LED   

blueLEDPin1 = board.D8
redLEDPin1 = board.D9
greenLEDPin1 = board.D10
blueLEDPin2 = board.D4
redLEDPin2 = board.D5
greenLEDPin2 = board.D7


myBlueLED1 = LED(blueLEDPin1)
myRedLED1 = LED(redLEDPin1)
myGreenLED1 = LED(greenLEDPin1)
myBlueLED2 = LED(blueLEDPin2)
myRedLED2 = LED(redLEDPin2)
myGreenLED2 = LED(greenLEDPin2)
while True:
    myBlueLED1.fade()
    time.sleep(1)
    myBlueLED2.fade()
    time.sleep(1)
    myRedLED1.fade()
    time.sleep(1)
    myRedLED2.fade()
    time.sleep(1)
    myGreenLED1.fade()
    time.sleep(1)
    myGreenLED2.fade()
    time.sleep(1)
    
 ```
The code above uses an RGB class to make the two RGB LEDs fade in and out from red, green, and blue.

## Reflection

At first I thought I needed to make another class in order to make the other RGB fade, but I was wrong. What I needed to do was just add another LED in the main.py code and label it as my second led. In order to do that, I needed to add either a one or a two at the end of each code that involved the LEDs to seperate them and to not get them mixed up. If I where not to label it, it would have not worked. 

## Evidence









 
 
 
   
   

