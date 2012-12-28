#Arduino AVR Programming Shield

##No clue if this works. Haven't tested it yet.

Use an Arduino Uno to program other AVR chips by hooking up MOSI, MISO, SCK, RST, VCC, and GND for you so your fat fingers don't have to mess up the programming circuit while trying to pull out the programmed chip. 

Designed for the following, but will work with chips that have the same pin setup:
* ATMega328/ATMega168 (28 pin)
* ATTiny 24/44/84 (14 pin)
* ATTiny 25/45/85 (8 pin)

Things that it does (differently?) from other AVR programming shields:
* Has a protoboard
* Breaks out all the pins for programmed chips. In case you actually programmed the chip to do something. 
* Breaks out XTAL1 & 2 pins for programming with an external crystal ocsillator
* LED indicators on heartbeat/error/programming. The LEDs even include resistors so you won't get blinded watching for error signals.
* Reset button for resetting the programmed chip without a power cycle
* Slide switch to turn on/off the 10uF connecting cap between reset and ground. Because putting in and taking out a cap is too difficult.
