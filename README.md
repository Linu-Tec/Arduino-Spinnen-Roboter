# Arduino-Spinnen-Roboter
Arduino Spinnen Roboter

Hier ist der Link zu den Platinen: https://www.pcbway.com/project/shareproject/

Und hier könnt ihr selber Platinen bestellen: [PCBWay](https://www.pcbway.com/)

![PCBWay-logo](https://github.com/user-attachments/assets/f7c905fa-edf6-4745-9900-ceeaef771a5f)

[Anleitung auf Bau Programmierung](https://www.instructables.com/DIY-Spider-RobotQuad-robot-Quadruped/)
[Anleitung Bluetooth Control](https://www.instructables.com/DIY-Spider-Robot-PART-II-Remote-control/)



Link zum Video: 


Benötigte Library:
- [FlexiTimer2](https://playground.arduino.cc/Main/FlexiTimer2/)
- 


Benötigte Bauteile:
- 1x [Arduino Nano](https://funduinoshop.com/elektronische-module/sonstige/mikrocontroller/funduino-nano-r3-ch340-chip-ungeloetet)
- 




Aus der [Anleitung](https://www.instructables.com/DIY-Spider-RobotQuad-robot-Quadruped/)

![image](https://github.com/user-attachments/assets/7fb1b636-9eaa-4e1b-ac8c-60895d216240)

![image](https://github.com/user-attachments/assets/0bb091c5-55e0-48a1-96be-d137af29d8eb)

![image](https://github.com/user-attachments/assets/d8bd37f0-bc56-43b8-93a9-f525ff2ec553)

Programm Ablauf:
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


[Vor-und-zurueck-laufen-v2.ino](https://github.com/Linu-Tec/Arduino-Spinnen-Roboter/blob/main/Vor-und-zurueck-laufen-v2.ino)


[Vor-und-zurueck-laufen-v3.ino](https://github.com/Linu-Tec/Arduino-Spinnen-Roboter/blob/main/Vor-und-zurueck-laufen-v3.ino)


Aus der [Anleitung Bluetooth Control](https://www.instructables.com/DIY-Spider-Robot-PART-II-Remote-control/)


Aktionsbefehl 0-6
- w 0 1: stehen
- w 0 0: sitzen
- w 1 x: vorwärts x Schritt
- w 2 x: zurück x Schritt
- w 3 x: rechts abbiegen x Schritt
- w 4 x: links abbiegen x Schritt
- w 5 x: x-mal die Hand schütteln
- w 6 x: x-mal mit der Hand winken
