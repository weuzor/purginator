# The Purginator - a purge bucket for the Voron2

The purginator, extractor and depressor are modifications for Voron 2 Printers fitted with Voron Tap, umbilical Stealthburner with E3D Revo hotend (other hotends probably work as well), Filametrix Cutter Mod and Enraged Rabbit Carrot Feeder using sensorless homing and running Happy Hare.
In combination they enable multi material printing without purge tower.

## Purginator

<img src="https://github.com/weuzor/purginator/blob/main/PIX/Purginator_v1.1.png" width="600">


([15 min Testprint showing toolchanges and after print nozzle treatment with the purginator](https://youtu.be/EkpkXMRFAnM)). 


## Extractor

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

As an alternative to the gantry mounted depressor this [bowden actuated filament cutter](https://github.com/weuzor/bowden_cutter) can also be used instead to cut any time anywhere :-)

<img width="500" alt="hot1" src="https://github.com/user-attachments/assets/fde41d2f-a4a4-4c1e-86de-19fbdbc90dd4" />
<img width="500" alt="ex2" src="https://github.com/user-attachments/assets/24e83e39-cab6-4066-85c1-ef2cb1eb5e8f" />


