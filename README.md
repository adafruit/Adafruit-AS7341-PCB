## Adafruit AS7341 10-Channel Light / Color Breakout PCB

<a href="http://www.adafruit.com/products/4698"><img src="assets/4698.png?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit AS7341 10-Channel Light / Color Breakout. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4698

### Description

INSERT PRODUCT COPY HERE
The AS7341 by AMS is a 11/10 channel spectrometer which is a special type of light sensor that is able to detect not only the amount of light present, but also the amounts of light within different wavelengths. This means that you can use it to detect, much better than the human eye is capable of, what color or colors of light is present. The AS7341 packs within its 3x2mm footprint 16 different sensors that can detect 8 separate, overlapping bands of colored light. As if that weren't enough, it also includes sensors for white light as well as Near Infra-red light, and even sensors made specifically for detecting light flicker at specific frequencies from things like indoor lighting.

The super-human color measuring capabilities of the AS7341 can be used to quantify the specific makeup of whatever interesting colors you can point it at, and can do so with more accuracy and specificity than a well trained artist. Now you don't need to go to art school to tell Pavo from Smalt, instead you can have the AS7341 can give you a clue how blue your blue is. This is possible thanks to the impressive collection of sensors in the AS7341 being routed through a 16-bit 6-channel ADC that takes the raw measurements and converts them to digital values that can be read out over I2C.

11 readable individual sensor elements don’t exactly fit through a 6-channel ADC all at once, so the chip includes a so-called Super MUX (SMUX) that allows you to route the signal from any sensor to any ADC channel. Now that’s some super multiplexing! The sensor also has GPIO and interrupt pins that can allow it to communicate directly with other sensors, or the microcontroller itself.


All of this capability is made accessible by mounting the sensor on a Stemma QT form factor breakout board, complete with level shifting circuitry and Sparkfun Qwiic compatible Stemma QT connectors. This means that you can, without needing to solder, connect our AS7341 breakout into your 3.3V or 5V microcontroller of choice be it an Arduino Uno, Raspberry Pi, or one of the many . While it certainly takes a bit of work to make all those different light sensors share their measurements, our Arduino and CircuitPython libraries take care of all of that hard work for you, and even include example code to help get you started. Read on and you'll find library installation instructions, as well as wiring diagrams that make using the AS7341 super easy.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
