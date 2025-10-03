# FORMULA
Building a vehicle that can run itself ( autonomously ) or be controlled by a person. 


# DRIVE SYSTEM
## GEARBOX 

Reasoning: 

Why have we decided to go with a gearbox. It is simple. Considering it is harder for the vehicle to start moving forward from being in stop, we need more torque on the start, but we want speed later on. 
We didn't go with PWM ( Pulse - width modulation ) because we thought that it wasn't good to control with voltage. Reason for that is that we were worried that voltage itself wouldn't be enough to start the vehicle.

The gearbox:

Currently we have three shifts. They are in ratios 1:4 ( 8 : 32 ) for torque, start ( 1st shift). Then there is  2:3 ( 16 :24 ) (2nd shift) and 4:1 (32:8) for speed (3rd shift). The gear schedule is so that no two pairs of gears can be in conatact at once. 

![mjenjač](https://github.com/user-attachments/assets/645c8922-8318-4c6a-a98d-ce6201f7d89e)

### Dimensions: 

32 teeth gear - internal diameter - 59mm,

24 teeth gear - internal diameter - 43mm,

16 teeth gear - internal diamter - 27mm,

8 teeth gear - internal diameter - 11mm.

Height - 10mm - ALL gears

Pressure angle - 14.5°  - ALL gears



Drive shaft - 7mm diameter, 150mm lenght
Other shaft - 7mm diameter, 175mm lenght

### How the gears change: 

So to change gears you have to pull or push the shaft.

<img width="670" height="584" alt="image" src="https://github.com/user-attachments/assets/d9214cad-f9ce-4bd1-8713-ced882b1cc64" />

Thats what this servo does. It rotates the gear under it, that then pushed or pulls the motor holder closer or further away. The motor holder is designed so that it has a rack gear on the bottom that servo spins. 




### Dimensions: 

MOTOR:

Lenght: 56mm

Diamater: 36mm

Holes for screwes: 6 x M3


