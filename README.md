# Arduino-as-serial-to-usb-converter
Sketch from https://petervanhoyweghen.wordpress.com/2012/11/08/using-the-leonardo-as-usb-to-serial-converter/ to create usb to serial converter from Arduino Leonard / Teensy

Replaced with sketch from Arduino discussion https://github.com/arduino/Arduino/pull/3343

Leonardo pinouts:

USB - USB in/out 

RX pin 0 -> RX (connect to TX pin on remote device)
TX pin 1 -> TX (connect to RX pin on remote device)

