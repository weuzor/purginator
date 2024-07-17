# Voron 2 Modifications for multi material printing with ERCF and Stealthburner with Filametrix Cutter

All modifications are designed for a Voron 2.4 350mm sized 3d Printer fitted with Voron Tap, sensorless homing and umbilical CW2 toolhead with Filametrix Mod. 


## The Purginator

<img src="https://github.com/weuzor/purginator/blob/main/PIX/Purginator.png" width="600">


The purginator is a retractable purging device intended for multi material printing without purge tower.

[Watch a proof of concept video of a short 3 colour testprint with the previous version of the purginator, brushinator and gantry servo mount](https://youtu.be/IaCVgWm7dVc). 


## The Extractor

<img src="https://github.com/weuzor/purginator/blob/main/PIX/Excarvator.png" width="600">

The extractor is a collecting tray for the purged filament dropped by the purginator.
It has a built in screw conveyor which drags the purged material out of the printer through a small heat trap.
The screw conveyor is powered by a MG90S 360deg Servo.
Once outside the material can either be collected in a suitable container at the back of the printer or if the printer is placed at the rear of a table directly droped into a waste basket on the floor.
This modification requires a cutout in the backpanel. It also restricts z movement to 4 mm below print surface. 
For normal operation this is irrelevant, however if a Z-Homing or Quad Gantry Levelling is performed and the rear left gantry corner is lower than the others by more than 4 mm (e. g. after motors were off and the gantry was moved by whatever cause) the purginator mount would collide with the excarvator. 
To prevent this the extractor has mounting holes for a safety microswitch to trigger an emergency shutdown in this case.

## [Filametrix](https://github.com/sorted01/Filametrix) Depressor 
<img src="https://github.com/weuzor/purginator/blob/main/PIX/Depressor.png" width="500">

https://github.com/user-attachments/assets/b3596728-9525-4a37-93d0-bf73759ecd00

This mod places a strong enough MG996R Servo at a location where it does not interfere with the toolhead but can depress the filametrix cutter lever with its servo arm.
Thereby the toolhead can remain docked to the purginator during the cutting sequence which eliminates oozing.
Comes with two mounting options for gantries with backers or without.

