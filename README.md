# ExpertCircuitPython


## Classes, Objects, and Modules

## Code

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
    time.sleep(1)```




 
 
 
   
   

