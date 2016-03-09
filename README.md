Serial to Parallel Shifting-Out with a 74HC595
---------
The 74HC595 is a serial to parallel shift register.  This IC will allow you to expand the number of output pins on the Arduino.  For a complete tutorial on how to use it please refer to the [Arduino ShiftOut Tutorial.](https://www.arduino.cc/en/Tutorial/ShiftOut).  If you live near Denton you could also [attend one of our Meetups.](http://www.davidriewe.com/p/arduino-meetups.html).

The Tutorial gives a number of coding examples.  Below is one I did to give the Night Rider appearance.  Note: The shift register is not what gives the appearance of the led going back and foth...ie shifting. All the shifting happens prior to the output states changing. The led appears to be shifting because it is in a loop writing int 1, 2, 4, 8, 16, 32, 64, 128, 64, 32, 16, 8, 4, and 2.

Click Image Below To Watch Video
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/-JyDOHiEaF0/0.jpg)](http://www.youtube.com/watch?v=-JyDOHiEaF0)

[Source Code.](https://github.com/driewe/74HC595/blob/master/SourceCode/shiftregister-nightrider.ino)
