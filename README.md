# Voron 2 Modifications for multi material printing with ERCF and Stealthburner with Filametrix Cutter


## The Purginator

<img src="https://github.com/weuzor/purginator/blob/main/PIX/Purginator.png" width="600">



The purginator is a mechanized purge bucket for Voron 2 3d Printers.

In extended position a strip of silicone with a hole is bent into a loop like shape nestling the hole to the nozzle for purging. 
When retracting the silicone strip gets stretched out. This motion wipes the nozzle tip and drops the purged filament.
Installing a purginator enables multi material printing without purge/prime tower thus keeping the entire printbed available for model files. 
[Watch a proof of concept video of a short 3 colour testprint with the purginator, brushinator and gantry servo mount](https://youtu.be/IaCVgWm7dVc). 
It also provides a place to park the toolhead for warmup/cooldown where oozing is no problem.

## The Excarvator

<img src="https://github.com/weuzor/purginator/blob/main/PIX/Excarvator.png" width="600">
The excarvator is a collecting tray for the purged filament dropped by the purginator. It has a built in screw conveyor which drags the purged material out of the printer through a small heat trap.
The screw conveyor is powered by a MG90S 360deg Servo.
Once outside the material can either be collected in a suitable container at the back of the printer or if the printer is placed at the rear of a table directly droped into a waste basket on the floor.
This modification requires a cutout in the backpanel!


## [Filametrix Cutting Mod](https://github.com/sorted01/Filametrix) Depressor 
<img src="https://github.com/weuzor/purginator/blob/main/PIX/Depressor.png" width="600">

After installing the Filametrix Cutting Mod I realized that the fixed pin interferes with the Stealthburner when moving around the top left corner of the printbed which is something I could not live with.
Since there is a config option for a retracting [Filametrix Cutting Mod](https://github.com/sorted01/Filametrix) pin in the [Happy Hare Software](https://github.com/moggieuk/Happy-Hare) I began my search for the appropriate STL files.
A few hours later I gave up and built my own. It is adjustable in all axes and fits the gantry with or without backers.

## Purginator 2 + Excarvator 2
<img src="https://github.com/weuzor/purginator/blob/main/p2+e2.png" width="500"> <img src="https://github.com/weuzor/purginator/blob/main/p2installed.png" width="500">

These are the latest versions of the purginator and excarvator.

The purginator 2 is now mounted to the B Drive Stepper Motor which places the purge hole at roughly 2mm on the x axis.
In succession the parked toolhead is now close enough to depress the filametrix filament cutter lever with a powerful enough gantry servo instead of moving the toolhead against a pin so the nozzle can remain parked for the entire toolchange.
The new design is more rigid and features a MGN7 Rail to allow for independent z movement. The spring loaded Z position can be adjusted by thumb screw. 
With an optional push down servo it is now possible to lower the purginator before docking. This is an attempt to reduce or eliminate wear of the silicone strip which is caused by the nozzle rubbing against the silicone strip during the docking process.

The excarvator 2 has a lower profile and wider tray than the previous version to acommodate the purginator 2.
Installing this mod limits the gantry movement to 4mm below printbed surface.
For normal operation this is irrelevant, however if the gantry is moved by hand when motors are off and left with the rear left corner being the lowest point by more than 4mm
and a z-homing or quad gantry levelling is triggered the purginator collides with the excarvator. 
To prevent this a safety microswitch has been added to trigger an emergency shutdown in this case. 

