# ATSHA204 Breakout Repository
Here you'll find the hardware design files for the [SparkFun ATSHA204 Breakout](https://www.sparkfun.com/products/11551). You'll also find example Arduino code, including a library for this powerful little chip.

## What's here?
In the *hardware* directory, you'll find the Eagle design files - board and schematic - as well as a pdf version of the schematic.

In the *firmware* directory, you'll find an Arduino directory. In that directory you'll find a *libraries* directory which houses the **ATSHA204 Arduino Library** as well as example code to demo what it can do. 

## What is the Atmel ATSHA204?
The Atmel ATSHA204 is an optimized authentication chip that includes a 4.5Kb EEPROM. This array can be used for storage of keys, miscellaneous read/write, read-only, password or secret data, and consumption tracking. Access to the various sections of memory can be restricted in a variety of ways and then the configuration locked to prevent changes.

Each ATSHA204 ships with a guaranteed unique 72-bit serial number. Using the cryptographic protocols supported by the chip, a host system or remote server can prove that the serial number is both authentic and not a copy. The ATSHA204 can generate high-quality random numbers and employ them for any purpose, including usage as part of the crypto protocols of this chip.

Here's a link to the [datasheet](http://www.atmel.com/Images/doc8740.pdf).

- Jim Lindblom @ SparkFun Electronics