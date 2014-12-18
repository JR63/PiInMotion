PiInMotion
==========

More will follow here and at http://www.swat-drones.de/index.php/hd-fpv/einleitung


Teaser:

This project will describe how to use 2 Raspberry Pi B+ or A+ and 2 Arduino Pro Mini to realize a RC link to a vehicle over WLAN.

Telemetry back channel will follow in a second step.


It's mainly for FPV usage in combination with a HD video stream.

At the ground side it takes the PPM signal of a standard RC transmitter with up to 12 channel.

At the air side it gives 8 PWM and a PPM with up to 12 channel simultaniously with a resolution of one micro second using the Arduino Pro Mini IO.

It also realizes failsafe in case of link loss.

Usage of up to 6 ADC, 2 PWM in and a serial port for telemetry data like GPS will follow.
