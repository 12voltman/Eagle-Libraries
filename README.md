# Eagle-Libraries
### Eagle libraries of parts I've created over the years.  Hopefully you find something you need.

The goal here is to eventually split the library up into different categories for ease of use, but for now I'm cleaning the place up and getting rid of redundant packages and whatnot.  Once EAGLE adds the ability to share managed libraries I'll also add that link here.


#### Brief rundown of my favorite parts:
* SAMD21J - I haven't found a good part for this anywhere, and its a great piece, its the larger version of the SAMD21G (commonly found in the Arduino Zero and similar) and I really want to see Cortex based Arduino Mega eventually
* SAMD11 - The cheapest USB-native microcontrollers I've found that natively work with the Arduino IDE
* ACS711 & ACS712 - Highly integrated current sesnsors that allow super easy current monitoring from a microcontroller
* ATSHA204A - Great little part for crypto authentication thats great for secure IoT, but I haven't found any good parts for it online, especially for the I2C version
* Card outline - IEC-7810 (worldwide standard shape for credit cards) compliant outline, good for wallet sized boards
* ESP32-PICO-D4 - ESP32 and 4Mbytes flash plus various passives all in one tiny QFN, perfect for those times you don't want to deal with choosing a flash chip and knowing what RF passives to use 
* HLK-PM01 - Awesome cheap power supplies for line voltage, only about $3
* NRF24L01 - Super common and cheap RF modules, but now there's a way to add wireless to your board with no RF designing necessary
* PCIe-x1 - Matching set of connectors, one female socket, and one male card edge connector, I find these great for programming, as no parts are needed on the target board
* PIC16F145X - One of the cheapest USB-native microcontrollers, and one of the very few that is available in a through-hole package
