# Aurora
Audio-responsive LED strip for Girls Who Code SIP final project.

#### Materials used: ####
* Arduino UNO 
* LEDMO LED strip 12v 4 pins (we cut it shorter to reduce current bc we didn't have 12v power)
* Microphone sensor with 3 pins 
* 3 N-channel MOSFET transistors 
* additional 9v battery (outside energy source for the led strip)
* 3 1k resistor

#### To do's: #### 

- [x] Test Microphone sensor                                   
- [x] Wire and test LED strip                           
- [x] Light up when a certain threshold is reached  
- [ ] Light up a single LED from the strip (problem: LED's from a 4pin strip can't be addressed individually)
- [ ] Shift the color of one LED to the next one on the strip  

#### References: ####
* [Adafruit library](https://github.com/adafruit/Adafruit_NeoPixel/ "Named link title") 
* [Ultimate guide to connect LED strip to Arduino](https://www.makeuseof.com/tag/connect-led-light-strips-arduino// "Named link title") 
* [Guide for Microphone Sound Sensor with Arduino](https://randomnerdtutorials.com/guide-for-microphone-sound-sensor-with-arduino/ "Named link title")
