WebGarageDoor
=============

An arduino sketch to control a garage door though a web interface. The garage door is controlled through a relay and two hall effect sensors detect whether the door is open or closed. An RGB LED is used to indicate the door state.

The sketch was tested on an [EtherTen](http://www.freetronics.com/products/etherten) and an [EtherMega](http://www.freetronics.com/products/ethermega-arduino-mega-2560-compatible-with-onboard-ethernet). It should also work with an Arduino Ethernet shield.

This sketch uses the [Webduino](https://github.com/sirleech/Webduino) library to respond to HTTP requests.

Details on the hardware are available in an associated [article](http://www.gregington.com/2013/09/web-controlled-garage-door.html).
