# Little benchmark for the Micro:bit

One of the nice things about the [Micro:bit](http://microbit.org), is that it supports different languages:
* Flashing it with the [Espruino](http://www.espruino.com/MicroBit) firmware, lets you program it with javascript, with the added bonus of the excellent Espruino WebIDE.
* [MicroPython](http://microbit-micropython.readthedocs.io/en/latest/), a python implementation for microcontrollers, is also supported.
* Last but not least, you can use the Arduino IDE and it's C-like language to program the Micro:bit.  
Here is a [nice guide from Adafruit](https://learn.adafruit.com/use-micro-bit-with-arduino/overview) on how to set this all up.

### MicroBench is a simple little benchmark implemented in these 3 languages, to see how each one behaves on this neat little board.

First run finds the first 250 prime numbers lighting up a led every 10 primes, second run calculates first 250 digits of Pi, visualizing them coded as 9 levels of brightness (0 led is off, 9 led is full on).
Finally the elapsed time scrolls on the "display".

### Install
(...)

### Source
(...)
