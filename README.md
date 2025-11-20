# MeshtasticMini-ultimate-
An improved and updated variant of the original Meshtastic Mini

A user on Discord pointed me to a PCB design on a chinese website (https://oshwhub.com/shenye894/meshtastic-mini), intrigqued by the form factor and the almost identical used parts from a FakeTec board I ordered a bunch of them. 
After I received the parts I started building it right away and it worked flawless for the most part. Some issues with wrong hole diameters, wrong and confusing labeling, a missing short pad for boost charging were quickly fixed. 
Driving the board to its max potential there is now a 3rd mosfet for an additional rumble motor, as well 3 exposed more gpios for a navigation switch and also a notification LED, the board now pretty much offering evereyhting meshtastic has to offer. 
The already implemented buzzer and GPS mosfet worked perfectly fine.  
<img width="326" height="447" alt="image" src="https://github.com/user-attachments/assets/48aa2a11-1194-44bb-b469-f11e1eab6c8e" />
<img width="322" height="444" alt="image" src="https://github.com/user-attachments/assets/a5cea63f-3459-4ae5-a99d-e68ce1ddca04" />
The corrected and updated version is on the way to me and once I can confirm it working accordingly I will relase the files for it here. 

Bill of Materials: 

Part	Source	Cost (€)	Note
ProMicro (aka NiceNano)	AliExpress
AliExpress	5€
2x for 5€	⚠️Please read it before buying red ProMicros⚠️
HT-RA62	AliExpress	5€	You can also use RA-01SH
SMD resistor	AliExpress	3€ pack
0.1€/resistor	You can buy a package of multiple values for a few €.
Choose depending on material you already have &/or soldering skills. I'm using 2x 1M ohms
OLED SSD1306 i2c (optional)	AliExpress	1.5€	No need to solder, just be careful and add some tape in between the boards to avoid a short.
Antenna pigtail (recommended)	AliExpress	2€	I saw that it underperformed with a cheap black pigtail, after using one of these, it worked fine.
PCB		2€ pack of 5
0.4€/unit	Use your favourite company to get the PCB.
2x Buttons	AliExpress	1.8€ pack
0.1€/button	You can buy a package of 100 for a few €.
I couldn't find a part code, search for "3*4*2.0 2 Pin Button"
#16 lupusworax's v4
Mosfets SI2312	AliExpress	9€ pack of 200
---
#16 lupusworax's v4
Resistors	AliExpress	2.4€ pack of 100
---




