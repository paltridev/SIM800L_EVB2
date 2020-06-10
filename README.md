# SIM800L_EVB2

This is a modified library for the SIM800L EVB2.0 GSM module to operate with Arduino boards. Follow the steps mentioned below to fix the issues with the SIM800L EVB 2.0 GSM Module board. This Model of GSM module has an issue concerning voltage at which it should operate. This is because of the capacitor that is soldered on the module.

<h2>SIM800L EVB 2.0 Images</h2>

![](https://github.com/paltridev/SIM800L-EVB2.0/blob/master/images/Evb_front.jpg)

![](https://github.com/paltridev/SIM800L-EVB2.0/blob/master/images/Evb_back.jpg)

Equipments needed to fix the board issue
1. Soldering Iron
2. Some Rosin Flux
3. Some Soldering wires
4. A 1200uF to 1500uF 6.3V capacitor

Step 1: first unsolder the capacitor from the GSM module.

![](https://github.com/paltridev/SIM800L-EVB2.0/blob/master/images/Evb_capacitor.jpg)

Step 2: Apply some Rosin Flux and solder the new 1200uF Capacitor in the place of the old one.

![](https://github.com/paltridev/SIM800L-EVB2.0/blob/master/images/capacitor.jpg)


<h2> Fixing Library Issue </h2>

Step 1: Clone or Download this repository
Step 2: Paste the folder "SIM800L_EVB2" in the Arduino ide Library Folder
Step 3: Open Arduino IDE and go into Example to see the new examples and implementations of the library

Et Voila Done! Hope that this repo has helped you. Also, do support the repo by giving it a star if it has help you.
