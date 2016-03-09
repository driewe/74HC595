Serial to Parallel Shifting-Out with a 74HC595
---------


[logo]: https://github.com/driewe/74HC595/blob/master/project_photo.jpg "My Implementation of 74HC595 circuit"

Note: The shift register is not what gives the appearance of the led going back and foth...ie shifting. All the shifting happens prior to the output states changing. The led appears to be shifting because it is in a loop writing int 1, 2, 4, 8, 16, 32, 64, 128, 64, 32, 16, 8, 4, and 2.

Video
https://youtu.be/-JyDOHiEaF0

74HC595 Tutorial
https://learn.adafruit.com/adafruit-arduino-lesson-4-eight-leds/overview
