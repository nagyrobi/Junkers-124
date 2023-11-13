# SmartTherm
Controlling a Junkers heating (Eurostar ZWE24) with an IoT thermostat

* schematics (kiCAD)
* PCB (kiCAD)
* TouchScreen control (Nextion display)
* SmartPhone app (Blynk)
* 3D Printed enclosure (Fusion360)
* Alternative config with ESPHome and Home Assistant

[Interactive BOM](https://htmlpreview.github.io/?https://github.com/mtaberna/SmartTherm/blob/master/hardware/SmartTherm-v2-ibom-components.html)

Connection to Junkers 1-2-4 connector:
pin numberings on both sides:
Junkers heater 1 (24V) -> Board J1 connector 4
Junkers heater 2 (drive signal) -> Board J1 connector 2 or 3
Junkers heater 4 (GND) -> Board J1 connector 1
