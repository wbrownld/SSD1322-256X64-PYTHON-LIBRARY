# SSD1322 PYTHON LIBRARY

Here's a python library to use with the SSD1322 256X64 display (ER-OLEDM032-1) and a Raspberry Pi2.

This library was originally created by [TopherCantrell](https://github.com/topherCantrell/ER-OLEDM032-1), i just added some enhancements (with his permission), drawing shapes, fonts added, etc...

[Reference Manual](https://github.com/ScoobieSnax/SSD1322-256X64-PYTHON-LIBRARY/wiki)

### The Screen :

[ER-OLEDM032-1W display from Buydisplay](http://www.buydisplay.com/default/serial-oled-module-price-3-2-inch-display-256x64-screens-white-on-black).

The ER-OLEDM032-1 is a 256x64 graphical OLED display. Each pixel is a 4-bit gray-scale value. The display board has four different interface options (8-bit parallel for 6800 series microprocessor, 8-bit parallel for 8080 series microprocessor, 3-wire SPI interface and 4-wire SPI interface), the default interface is 8-bit 8080 parallel. I used the 4-wire SPI mode in this project to connect the display to the Pi2.

![](https://github.com/ScoobieSnax/SSD1322-256X64-PYTHON-LIBRARY/blob/master/Img/SPI4.jpg)
![](https://github.com/ScoobieSnax/SSD1322-256X64-PYTHON-LIBRARY/blob/master/Img/Datasheet%20SPI4.png)
![](https://github.com/ScoobieSnax/SSD1322-Pi-Clock/blob/master/OLEDM032%20connect.jpg?raw=true)

### Personnal project with this library :

![](https://github.com/ScoobieSnax/SSD1322-256X64-PYTHON-LIBRARY/blob/master/Finished%20project.jpg)
