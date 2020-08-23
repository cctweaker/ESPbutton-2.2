# ESPbutton 2.2
Special version of ESPbutton, oprimized for size and current consumption.
It can be powered by one CR2032 battery for 1 year at 1 push/hour or 2xAAA batteries for 5 years at 1 push/hour or 1 1/2 years at 10 pushes per hour.
It is designed to send toggle commands through ESP-Now to a MQTT server to control anything that you connect it to through Node Red, for example lights, blinds, etc.

# Features
- encrypted ESP-Now connection
- 2 touch buttons (up/down or left/right depending on how you position the unit).
- due to requiring the smallest power consumption possible, the setup is done by flashing the firmware, there is no webpage or phone setup on this model


# Hardware
Roll your own or get one from <a href="https://3dstar.ro/proiecte/espbutton">3DStar shop</a> in PCB, kit (PCB + components) or fully assembled form.

The ESP-12S from AI Thinker is used to send the state of the 2 touch sensors. You can assign lights, shutters/blinds, doors/gates, irrigation or any other action that you wish.
The number of boards you can use is unlimited. The trick here is that when using ESP-Now, all button boards share the same MAC address.

# Build & upload
Download, change the settings, build & upload

# Libraries
- no external libraries

# PCB example
<img src="https://github.com/cctweaker/espbutton-2.2/blob/master/Hardware/ESPbutton v2.2 top example.jpg?raw=true">
<img src="https://github.com/cctweaker/espbutton-2.2/blob/master/Hardware/ESPbutton v2.2 bottom example.jpg?raw=true">