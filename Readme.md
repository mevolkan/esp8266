# ESP8266 temp and humidity monitor with DHT22 and LM35
Article coming soon

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/mevolkan/esp8266)

Powered by [![N|Solid](https://warefab.com/wp-content/uploads/2018/07/cropped-logo_site-32x32.png)](https://warefab.com/)



Warefab is an electronics kits and modules for education, makers and engineers. PCBA services, 3D printing, CNC miling, Laser cutting shop

## ESP8266 Developer board

  - Intergrated DHT22 sensor
  - Intergrated LED display


You can also:
  - Add more sensors on the pinouts
  
Currently at revision 1


### Libraries used

This demo uses the following libaries

- [Wire.h]
- [SSD1306Ascii]
- [SSD1306AsciiWire]
- [ESP8266WiFi]
- [Hash.h]
- [ESPAsyncTCP]
- [ESPAsyncWebServer]
- [DHT]

### Installation

Download the above libraries and place them in the libaries folder
Download this repo and run the .ino file
Flash to your Devkit, after changing the values accordingly
Copy the contents in flow .txt to your nodered



### Development

Fork this repo, add changes and I will be sure to merge them, cheers

### Todos
- Utilise indexdb
- Add grraphing using library and db above
- Add function to add AP over the air
- Add LM35

Deviated from the initial plan, hence this branch currently uses nodered and mqtt to transmit and plot the diagrams
Therefore thre new #### Todos are
- Display the temperature and humidity values on the screen
- Display the reading directly via the ESP8266 on port 80
- Hook the other 3 sensors
- Fit them all together in a tiny transparent box


License
----

MIT


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [wire.h]: <#>
   [SSD1306Ascii]: <#>
   [SSD1306AsciiWire]: <#>
   [ESP8266WiFi]: <#>
   [Hash.h]: <#>
   [ESPAsyncTCP]: <#>
   [ESPAsyncWebServer]: <#>
   [DHT]: <#>

