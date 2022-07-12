# PS2USBConverter
Arduino PS/2 to USB keyboard converter sketch with bongo cat on 128x32 i2c display. There is an addition feature named "troll mode" which can be turned on or off. You can toggle this feature by typing "trollon" or "trolloff" into the serial console. I it's turned on a counter will appear and starts count a defined second which can be set by "trollmaxcount" and a number after this word, this is represented in seconds. After the counter finished it will wait 1-10 second randomly and than disable the keyboard and start typing from the most usual game control commands (w,a,s,d,space) for 2 sec, then the process starts again. I made this mode for a lan party where the one who was the best got this ps2 keyboard with the troll mode on. The settings stored in the EEPROM so you don't have to make the changes every time.

To upload the sketch with Arduino IDE you only need the .ino and .h file.

This project based on [DorianRudolph's work](https://gist.github.com/DorianRudolph/ca283dfdfd185bc812b7) with some fixes.

Tested on Arduino Pro Mini borad.
![](https://raw.githubusercontent.com/ASDosjani/PS2USBConverterBongo/master/IMG_20220712_194358.jpg)
