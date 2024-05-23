# Analog Volt Clock



![](./img/crazy_watch_1307.jpg)



## LICENSE
Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation files
(the "Software"). For more info see [LICENSE](https://github.com/MichMich/AnalogVoltMeterClock/blob/master/LICENSE).

## CONNECTIONS

### TinyRTC
* GND > Arduino GND
* VCC > Arduino 5V
* SDA > Arduino A4
* SCL > Arduino A5

### Button Adjust Hour
* [] > Arduino D7
* [] > Arduino GND

### Button Adjust Minute
* [] > Arduino D8
* [] > Arduino GND

### Meter HOURS
* [-] > Arduino GND
* [+] > Arduino D3

### Meter MINUTES
* [-] > Arduino GND
* [+] > Arduino D5

### Meter SECONDS
* [-] > Arduino GND
* [+] > Arduino D6

### Meter LEDS
All LEDs are connected in parallel, with one 33 Ohm resistor.

* LEDS [+] > RESISTOR > Arduino 5V
* LEDS [-] > Arduino GND
