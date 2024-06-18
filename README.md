# CH32V003 based Wedding Invites

![Screencast](/images/final.jpeg "photo")
![Screencast](/images/demo.webm?raw=true "display!")

Schematics originally based on [Christmas LED ball](https://www.hackster.io/fabiosouza/christmas-ornament-based-on-ch32v003-riscv-mcu-2793db) .

![photo](/images/front.jpeg "Front Render")
![photo](/images/back.jpeg "Back Render")


## Features

+ USB C 6 pin connector with TP4057 for charging
+ 3.7V battery
+ CH32V003 processor
+ 14 LEDs
+ 1 RGB LED
+ IR Receiver
+ Reed switch for timing the POV display
+ footprints for BMP280 ( not tested yet )

## Software features

+ RGB LED control
+ PWM fading of LEDs
+ IR receiver via interrupt
+ Interrupt wake up and deep sleep
+ Persistence of vision display using 8 LEDs


## Author links

[Jithin BP](https://github.com/jithinbp/)
[CSpark Research](https://github.com/csparkresearch/)

## Credits

+ [Fábio Souza](https://github.com/FBSeletronica) for the CH32v003 layout .
+ [CNLohr] (https://github.com/cnlohr/) for the many examples on [ch32v003fun](https://github.com/cnlohr/ch32v003fun) 
 
