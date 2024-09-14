# Arduino-Spinnen-Roboter
Arduino Spinnen Roboter

Hier ist der Link zu den Platinen:
- [Arduino-Spinnen-Roboter Pro Mini](https://www.pcbway.com/project/shareproject/Arduino_Spinnen_Roboter_5e67cf5d.html)
- [Arduino-Spinnen-Roboter Nano](https://www.pcbway.com/project/shareproject/Arduino_Spinnen_Roboter_Nano_7bf1c600.html)

Und hier könnt ihr selber Platinen bestellen: [PCBWay](https://www.pcbway.com/)

![PCBWay-logo](https://github.com/user-attachments/assets/f7c905fa-edf6-4745-9900-ceeaef771a5f)

[Anleitung auf Bau Programmierung](https://www.instructables.com/DIY-Spider-RobotQuad-robot-Quadruped/)

[Anleitung Bluetooth Control](https://www.instructables.com/DIY-Spider-Robot-PART-II-Remote-control/)



Link zum Video: 


Benötigte Library:
- [wimleers-flexitimer2-v1.1](https://github.com/Linu-Tec/Arduino-Spinnen-Roboter/blob/main/wimleers-flexitimer2-v1.1.zip)
- [Arduino-SerialCommand-master](https://github.com/Linu-Tec/Arduino-Spinnen-Roboter/blob/main/Arduino-SerialCommand-master.zip)



Benötigte Bauteile:
- 1x [Arduino Nano](https://funduinoshop.com/elektronische-module/sonstige/mikrocontroller/funduino-nano-r3-ch340-chip-ungeloetet)
- 1x LED 5mm
- 1x 270 Ohm Widerstand
- 1x HC-05 / HC-06
- 1x [Mini Taster Drucktaster Mikroschalter Rastend Push Button 3,6Pin](https://www.ebay.de/itm/374548828237?var=643525456852)
- 1x [Mini Step Down Spannungsregler Modul 3A 1,8/2,5/3,3/5/9/12V Power DC-DC Wandler](https://www.ebay.de/itm/375611362378)
- [Stiftleiste](https://funduinoshop.com/bauelemente/steckverbinder/stift-und-buchsenleisten/40-pin-pinleiste-schwarz/2.54mm-raster-standard-im-bereich-arduino)
- 2x [Buchsenleiste, gerade, 15pol, 2,54mm](https://funduinoshop.com/bauelemente/steckverbinder/stift-und-buchsenleisten/buchsenleiste-1-x-15p-2.54mm-rastermass-11mm-pinlaenge)
- 4x [Buchsenleiste, gerade, 8pol, 2,54mm](https://funduinoshop.com/bauelemente/steckverbinder/stift-und-buchsenleisten/buchsenleiste/header-pin-female-1-x-8p-2.54mm-1cm-pinlaenge)




## Aus der [Anleitung](https://www.instructables.com/DIY-Spider-RobotQuad-robot-Quadruped/)

![image](https://github.com/user-attachments/assets/7fb1b636-9eaa-4e1b-ac8c-60895d216240)

![image](https://github.com/user-attachments/assets/0bb091c5-55e0-48a1-96be-d137af29d8eb)

![image](https://github.com/user-attachments/assets/d8bd37f0-bc56-43b8-93a9-f525ff2ec553)

## Programm Ablauf:
### V1
[Vor-und-zurueck-laufen-v1.ino](https://github.com/Linu-Tec/Arduino-Spinnen-Roboter/blob/main/Vor-und-zurueck-laufen-v1.ino)

1. Aufstehen, 2 Sekunden warten
2. 5 Schritte vorwärts gehen, 2 Sekunden warten
3. 5 Schritte rückwärts gehen, 2 Sekunden warten
4. Nach rechts drehen, 2 Sekunden warten
5. Nach links drehen, 2 Sekunden warten
6. Mit der Hand winken, 2 Sekunden warten
7. Die Hand schütteln, 2 Sekunden warten
8. Hinsetzen, 2 Sekunden warten
9. Zurück zu 1.

### V2
[Vor-und-zurueck-laufen-v2.ino](https://github.com/Linu-Tec/Arduino-Spinnen-Roboter/blob/main/Vor-und-zurueck-laufen-v2.ino)

1. Aufstehen, 2 Sekunden warten
2. 5 Schritte vorwärts gehen, 2 Sekunden warten
3. 5 Schritte rückwärts gehen, 2 Sekunden warten
4. Nach rechts drehen, 2 Sekunden warten
5. Nach links drehen, 2 Sekunden warten
6. , 2 Sekunden warten
7. , 2 Sekunden warten
8. , 2 Sekunden warten
9. Zurück zu 1.

### V3
[Vor-und-zurueck-laufen-v3.ino](https://github.com/Linu-Tec/Arduino-Spinnen-Roboter/blob/main/Vor-und-zurueck-laufen-v3.ino)

1. Aufstehen, 2 Sekunden warten
2. 5 Schritte vorwärts gehen, 2 Sekunden warten
3. 5 Schritte rückwärts gehen, 2 Sekunden warten
4. Nach rechts drehen, 2 Sekunden warten
5. Nach links drehen, 2 Sekunden warten
6. , 2 Sekunden warten
7. , 2 Sekunden warten
8. , 2 Sekunden warten
9. Zurück zu 1.




## Aus der [Anleitung Bluetooth Control](https://www.instructables.com/DIY-Spider-Robot-PART-II-Remote-control/)


Aktionsbefehl 0-6
- w 0 1: stehen
- w 0 0: sitzen
- w 1 x: vorwärts x Schritt
- w 2 x: zurück x Schritt
- w 3 x: rechts abbiegen x Schritt
- w 4 x: links abbiegen x Schritt
- w 5 x: x-mal die Hand schütteln
- w 6 x: x-mal mit der Hand winken
