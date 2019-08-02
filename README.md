## Adafruit PyRuler - Engineer Reference Ruler with CircuitPython PCB

<a href="http://www.adafruit.com/products/4319"><img src="assets/4319.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit PyRuler - Engineer Reference Ruler with CircuitPython. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4319

### Description

The first time you soldered up a surface mount component you may have been surprised "these are really small parts!" and there's dozens of different names too! QFN, TDFN, SOIC, SOP, J-Lead, what do they mean and how can you tell how big they are? Now you can have a reference board at your fingertips, with this snazzy PCB reference ruler.

Measuring approx 1" x 6", this standard-thickness FR4, this gold plated ruler has the most common component packages you'll encounter. It also has font size guide, trace-width diagram, and a set of AWG-sized drills so you can gauge your wire thicknesses.

That's not all, its even a fully featured microcontroller board! Embedded in the end is a Trinket M0, our little Cortex M0+ development board, and in addition, there's 4 capacitive touch pads with matching LEDs that our code will turn into a specialized engineer keyboard. We're always needing to type Ω and µ but we can never memorize the complex key-commands necessary. Thanks to CircuitPython, its super-easy to make a touch keyboard to solve this for you. Plug in the ruler into your computer, if its your first time using it, you'll need to open up the code.py file and set the Keyboard mode to "True". Now when you touch the pads, you'll get a Ω, µ,  π or, when the Digi-Key logo is touched, the URL for Digi-Key's Python on Hardware guide.

The PyRuler was designed as a great introduction to CircuitPython.While you can use it with the Arduino IDE, we are shipping it with CircuitPython on board. When you plug it in, it will show up as a very small disk drive with code.py on it. Edit code.py with your favorite text editor to build your project using Python, the most popular programming language. No installs, IDE or compiler needed, so you can use it on any computer, even ChromeBooks or computers you can't install software on. When you're done, unplug the PyRuler and your code will go with you. Please check out the Trinket M0 CircuitPython guide for a list of capabilities and quick-start code examples - CircuitPython is easier to code but not as low-level as Arduino.

Here are some of the updates you can look forward to when using PyRuler

* ATSAMD21E18 32-bit Cortex M0+ - 256KB Flash, 32 KB RAM, 48 MHz 32 bit processor
* Native USB supported by every OS - can be used in Arduino or CircuitPython as USB serial console, Keyboard/Mouse HID, even a little disk drive for storing Python scripts.
* Can be used with Arduino IDE or CircuitPython
* Four capacitive touch pads.
* Lots of LEDS - Built in green ON LED, red pin #13 LED, RGB DotStar LED, plus red/yellow/green/blue matching LEDs for each capacitive touch pad
* 5 GPIO header pins are available and are not shared with USB or the touch pads/LEDs - so you can use them for whatever you like! Digital I/O with pullup/down. 3 ADCs, 1 DAC, 2 PWM, 3 extra captouch sensors
* Can drive NeoPixels or DotStars on any pins, with enough memory to drive 8000+ pixels. DMA-NeoPixel support on one pin so you can drive pixels without having to spend any processor time on it.
* Native hardware SPI, I2C and Serial available on two pads so you can connect to any I2C or Serial device with true hardware support (no annoying bit-banging). You can have either one SPI device or both I2C and Serial.
* Reset switch for starting your project code over
* Power with either USB or external output (such as a battery) - it'll automatically switch over

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
