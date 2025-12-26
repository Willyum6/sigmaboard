# sigmaboard
My hackclub blueprint keyboard 

Contains:
- 3 separate printed parts
- 4 M3 bolts and 4 inserts
- 6 keys total
- 128x32 OLED screen
- 2 WS2812B RGB LEDs as underglow beneath the keys and the slits on the right
- 1 XIAO RP2040
- 6 diodes
- a very cool name

  ______________

  CAD:
  3 parts: a bottom case, a middle plate to define the keyholes, and a top cover which has slits to let LEDs shine through, keyspaces, and an opening for the OLED
  <img width="936" height="751" alt="Screenshot 2025-12-26 001733" src="https://github.com/user-attachments/assets/b61d53b6-d6a3-4b99-a9e9-db27aee3f2df" />
  (made in fusion360)

  ________________

  PCB and Schematic:

  PCB:
<img width="870" height="565" alt="Screenshot 2025-12-26 003030" src="https://github.com/user-attachments/assets/16fd1cb5-b15e-4e4c-8082-3f61f259fdff" />

Schematic:
<img width="970" height="877" alt="Screenshot 2025-12-26 003132" src="https://github.com/user-attachments/assets/b8641061-f5e9-419e-8c1a-25a3b239f0bd" />

__________________

FIRMWARE:
Sigmaboard uses QMK.
Keys act as arrow keys, with the two oriented on the right in a stack operate as "enter" and "shift"(to play games)
OLED screen should display an animation of bones moving across the screen:
![bone-animation-2](https://github.com/user-attachments/assets/f9d26aa6-c2f0-4068-8655-ee297aae3466)

_______________

BOM:
- 6 Cherry MX Switches
- 6 DSA Keycaps
- 4 M3x12mm SHCS Bolts
- 4 M3x5x4 Heatset inserts
- 1 XIAO RP2040
- 1 0.91" 128x32 OLED Display
- 2 WS2812B LEDs
- 6 DO-35 diodes

_______________________
Final notes:
I spent a long time on this project and am very proud of it, I would love to get it approved and test it out in person! 
I learnt a lot about the cadding process, as well as about PCB and the parts needed for projects like keyboards. 
I will say I feel I didn't learn enough about understanding the code, but it is something I definitely will do once I can test out my keyboard. 

