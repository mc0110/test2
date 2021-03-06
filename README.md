# ESP Breadboard Testkit

> First trial of presentation with GitHub Pages - under construction. I would therefore like to apologise in advance if something is not presented correctly. But I am very interested in constantly improving my presentation. Therefore, all comments are very welcome.

## Motivation

Protoyping a circuit makes the breadboard an indispensable helper. When building circuits around an ESP32, it is essential to use a DEVKIT. Most DEVKITs have their own USB port and can therefore also provide the power supply (5V and 3V3). 
But there is a problem with that. The designs I know are using 2.54 PINHEAD, but unfortunately they only fit on the standard breadboards in such a way that all the holes are occupied. They are therefore not usable. As a consequence, cable bridges are often used. However, these have the major disadvantage that they make circuits very susceptible to interference. For example, when trying to power an ESP-DEVKIT externally and not via USB, I just observed the crash due to the chip-internal BROWNOUT detection when initialising the WiFi connection.

[Webpresentation of this work](https://mc0110.github.io/test2/)