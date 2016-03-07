Using the 74HC595 to control 8 leds (outputs) without giving up 8 ports on the arduino uno. Three outputs from the arduino are used to shift the data out in serial to the 74HC595 were it is then parceled out to each of its individual pins. You can link multiple registers together to extend your output even more, without giving up any more pins on the arduino.
Note: The shift register is not what gives the appearance of the led going back and foth...ie shifting. All the shifting happens prior to the output states changing. The led appears to be shifting because it is in a loop writing int 1, 2, 4, 8, 16, 32, 64, 128, 64, 32, 16, 8, 4, and 2.

Video
https://youtu.be/-JyDOHiEaF0

74HC595 Tutorial
https://learn.adafruit.com/adafruit-arduino-lesson-4-eight-leds/overview

