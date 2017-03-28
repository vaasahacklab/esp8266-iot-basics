# esp8266-iot-basics

# Hacklab ESP / IoT
https://kirjoitusalusta.fi/hacklab-esp8266

Basics of IoT

Wifi: VaasaHacklab* 
Wifikey:

Start with installing 
* Arduino IDE, https://www.arduino.cc/en/Main/Software
* Board definitions, https://github.com/esp8266/Arduino#installing-with-boards-manager

***

Demo: http://10.10.0.122/rgb

https://github.com/vaasahacklab/esp_mini_rgb_blink_web

https://vaasa.hacklab.fi/category/esp8266/
light logger: https://vaasa.hacklab.fi/2017/01/17/esp8266-witty-cloud-ldr-arduinoide-thingspeak-iot-light-sensor/
temperature logger: https://vaasa.hacklab.fi/2016/02/06/esp8266-on-nodemcu-board-ds18b20-arduinoide-thingspeak/

https://github.com/esp8266/Arduino

Witty dev boards
RGB-LED, ldr, button

// LDR = A0;
// GREEN = 12;
// BLUE = 13;
// RED = 15;
// BUTTON = 4;

* Intro
* ESP8266
* IoT device
* http, html, server, AP, Client
* Hardware
* Analog input, output
* Digital, PWM
* pull-up, pull-down
* DS18B20


* ArduinoIDE
* Boards Manager
* Libraries
* Code
* Webupdater
* Sketch -> Export Compiled Binary
* thingspeak
* API, http

# ESP8266 Arduino examples:
* ESP8266 --> Blink
  * Vilkuttaa lediä LED_BUILTIN-portissa. 1s pois päältä, 2s päällä
* ESP8266 --> BlinkWithoutDelay
  * Kuten yllä mutta käyttää Elapsedmillis eli ohjelma ei jää kiinni viive-komentoon
* ESP8266 --> CheckFlashConfig
  * Syöttää ESP-piirin EEPROM:ssa olevat asetukset sarjaporttiin
  * Technical data and nonsense if you are not into it

* **Very advanced (do not try ;):**
  * ESP8266 --> Arduino_Wifi_AVRISP
  * Arduino AVR-ISP over TCP



## Kurssin etenemissuunnitelma/puheet:
* Mitä olemme tekemässä täällä kurssilla (Miksi, Mitä)
* IOT-termi, mitä se tarkoittaa käytännössä
* Internet of things
* Miksi se on nyt noussut pintaan
* Valmiiden moduulien hinnat ovat painuneet alas.
* Avoimen lähdekoodin yhteisön avulla koodin kirjoittaminen on helpottunut
* Valmiita esimerkkejä, valmiita kirjastoja
* ESP8266-moduulin tarina
* Kuka bongasi ensimmäisenä kyseisen moduulin
* Miten sen käyttöönotto eteni, dokumentoinnin kääntäminen
* Aikajana miten asiat eteni?
* ESP8266-moduulin läpikäynti
* 3.3V käyttöjännite, mitä se tarkoittaa
* anturit, yhteensopivuus
* Mitä IO-portteja kyseisessä moduulissa on

## ESP8266-kehitysalustan läpikäynti
* WittyBoard
* NodeMCU devboard (Lua)
* ArduinoIDE

 http://www.w3schools.com/html/tryit.asp?filename=tryhtml_form_radio
 


