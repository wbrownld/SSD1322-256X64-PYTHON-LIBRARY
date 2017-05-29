SSD1322-Pi-Clock
================

Here's my Pi2 clock with a 256x64 oled display.

Initially the project was to use an arduino and the time had to be retrieved by the DCF signal. But 1 : Arduino was not powerful enough to use a 256x64 display and 2 : DCF signal is too weak at my home. So arduino is replaced by a Pi2 and time is now retrieved par NTP (via wifi dongle) and i added possibility to ear some webradios to this little box, just for fun ;)

![](https://github.com/ScoobieSnax/SSD1322-Pi-Clock/blob/master/Finished%20project.jpg?raw=true)

## Hardware

### The Screen : 
[ER-OLEDM032-1W display from Buydisplay](http://www.buydisplay.com/default/serial-oled-module-price-3-2-inch-display-256x64-screens-white-on-black).

The ER-OLEDM032-1 is a 256x64 graphical OLED display. Each pixel is a 4-bit gray-scale value. The display board has four different interface options (8-bit parallel for 6800 series microprocessor, 8-bit parallel for 8080 series microprocessor, 3-wire SPI interface and 4-wire SPI interface). I used the 4-wire SPI mode in this project to connect
the display to a Raspberry Pi.



