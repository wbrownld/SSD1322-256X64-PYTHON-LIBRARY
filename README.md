# SSD1322 PYTHON LIBRARY

Here's a python library to use with the SSD1322 256X64 display (ER-OLEDM032-1) and a Raspberry Pi2.

This library was created by [TopherCantrell](http://www.buydisplay.com/default/serial-oled-module-price-3-2-inch-display-256x64-screens-white-on-black)


Initially the project was to use an arduino and the time had to be retrieved by the DCF signal. But 1 : Arduino was not powerful enough to use a 256x64 display and 2 : DCF signal is too weak at my home. So arduino is replaced by a Pi2 and time is now retrieved par NTP (via wifi dongle) and i added possibility to ear some webradios to this little box, just for fun ;)

![](https://github.com/ScoobieSnax/SSD1322-256X64-PYTHON-LIBRARY/blob/master/Finished%20project.jpg)

## Hardware

### The Screen :

[ER-OLEDM032-1W display from Buydisplay](http://www.buydisplay.com/default/serial-oled-module-price-3-2-inch-display-256x64-screens-white-on-black).

The ER-OLEDM032-1 is a 256x64 graphical OLED display. Each pixel is a 4-bit gray-scale value. The display board has four different interface options (8-bit parallel for 6800 series microprocessor, 8-bit parallel for 8080 series microprocessor, 3-wire SPI interface and 4-wire SPI interface). I used the 4-wire SPI mode in this project to connect the display to the Pi2.

![](https://github.com/ScoobieSnax/SSD1322-Pi-Clock/blob/master/OLEDM032%20connect.jpg?raw=true)

### The Rotary Encoder :

