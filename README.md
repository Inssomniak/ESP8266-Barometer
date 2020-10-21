# ESP8266-Barometer
ESP8266 Based Barometer on HUB75 LED Matrix with external sensor.  See https://github.com/2dom/PxMatrix for wiring, and information on the Library.
Arduino IDE

LED Matrix barometer on an AliExpress P5 Led Matrix 1/16 scan. Uses pxMatrix library.  BMP280 Pressure/temp sensor.
PCB Designed and made by me with onboard nodemcu style TTL serial converter, ESP-07 type module, 3v3 voltage, support for all scan types.
PCB Gerber is missing a pulldown resistor 10k on GPIO15, I soldered it across to ground right on the ESP-07 module
Depending on your LED Matrix, you have to cut a trace for E Scan line or remove the pins from the header before assembly so the flash GPIOs arent accidentally pulled LOW. 
