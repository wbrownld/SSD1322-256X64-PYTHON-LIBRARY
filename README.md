# SSD1322-Pi-Clock

Here's my Pi2 clock with a [ER-OLEDM032-1W display from Buydisplay](http://www.buydisplay.com/default/serial-oled-module-price-3-2-inch-display-256x64-screens-white-on-black).

Initially the project was to use an arduino and the time had to be retrieved by the DCF signal. But 1 : Arduino was not powerful enough to use a 256x64 display and 2 : DCF signal is too weak at my home. So time is now retrieved par NTP (via wifi dongle) and i added possibility to ear some webradios to this little box, just for fun ;)

![](https://github.com/ScoobieSnax/SSD1322-Pi-Clock/blob/master/Finished%20project.jpg?raw=true)





