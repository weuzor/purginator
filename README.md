# Voron 2 Modifications for multi material printing with ERCF and Stealthburner with Filametrix Cutter

![All Mods](https://github.com/weuzor/purginator/blob/main/all_mods_render.png)

## The Purginator

<img src="https://github.com/weuzor/purginator/blob/main/purginator_crossection.png" width="600">

The purginator is a gantry mounted mechanized purge bucket driven by a MG90S Servo.
In extended position a strip of silicone with a hole is bent into a loop like shape nestling the hole to the nozzle for purging. 
When retracting the silicone strip gets stretched out. This motion wipes the nozzle tip and drops the purged filament.
Installing a purginator enables multi material printing without purge/prime tower thus keeping the entire printbed available for model files. 
[Watch a proof of concept video of a short 3 colour testprint with the purginator, brushinator and gantry servo mount](https://youtu.be/IaCVgWm7dVc). 
It also provides a place to park the toolhead for warmup/cooldown where oozing is no problem.

## The Excarvator

<img src="https://github.com/weuzor/purginator/blob/main/excarvator_crossection.png" width="600">
The excarvator is a collecting tray for the purged filament dropped by the purginator. It has a built in screw conveyor which drags the purged material out of the printer through a small heat trap.
The screw conveyor is powered by a MG90S 360deg Servo.
Once outside the material can either be collected in a suitable container at the back of the printer or if the printer is placed at the rear of a table directly droped into a waste basket on the floor.
This modification requires a cutout in the backpanel!

## The Brushinator

<img src="https://github.com/weuzor/purginator/purginator2/blob/main/brushinator_crossection.png" width="500">
The brushinator is a cheap copy of [this gantry mounted nozzle cleaner](https://www.printables.com/de/model/269412-voron-v24-300-gantry-mounted-nozzle-cleaner) matching the purginator design.

## Gantry Servo Mount + Pin
<img src="https://github.com/weuzor/purginator/blob/main/gantry_servo_holder.png" width="250">

After installing the Filametrix Cutting Mod I realized that the fixed pin interferes with the Stealthburner when moving around the top left corner of the printbed which is something I could not live with.
Since there is a config option for a retracting [Filametrix Cutting Mod](https://github.com/sorted01/Filametrix) pin in the [Happy Hare Software](https://github.com/moggieuk/Happy-Hare) I began my search for the appropriate STL files.
A few hours later I gave up and built my own. It is adjustable in all axes and fits the gantry with or without backers.

## Purginator 2

<img src="https://github.com/weuzor/purginator/blob/main/purginator2.png" width="600">
In order to 

## Bill of Materials:

### Purginator 
* [1mm high temperature silicone sheet](https://www.amazon.de/gp/product/B08KFTPTG9/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&th=1)
* [1 ea silicone O-Ring 10x14x2mm](https://www.amazon.de/gp/product/B07NQD6KCJ/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&th=1)
* [1ea MG90s 180deg Servo](https://www.amazon.de/gp/product/B086V3VP72/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&th=1)
* [2ea Ballbearings 3x10x4mm](https://www.amazon.de/stücke-623-2RS-Kugellager-Doppel-Rillenkugellager/dp/B07CWLGNJ5/ref=sr_1_1_sspa?dib=eyJ2IjoiMSJ9.9woqqwQjTq-p6iPwrUffi2d2bsHJw6UycUsB92_u3q-Smt9jMfxYufze3yMLa8dVCcguvt3fg-eWgwVzRmbCx6OBDLn50Iqe8E2cVwwDzqe9K4E6B9IgL00jBknB56GO1ZkXVQhbH0jbnrGV-QxXVfFCnwxjZPuh-A0WkN2nheVrjfzndKp1NyEEW4B8PbHB0m_gXTPkrTWZJLG8WaGOHKBgCCyeGjlpAJjDO7ynSQw.av6AitDux3gb7yG6LLjvQHgYDzAzVkIL2xda3fSPe5c&dib_tag=se&keywords=Kugellager+3x10x4&qid=1710786944&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)
* 2ea brass heat insert 4mm
* 2ea M3x10 button head screw
* [1ea 20mm M3 brass standoff](https://www.amazon.de/AMZANDY-NEW-Abstandshalter-Abstandsbolzen-Motherboard-120/dp/B0825XY6VD/ref=sr_1_7?crid=3TITDI5TLOEGC&dib=eyJ2IjoiMSJ9.Lkey_yXQ8r6hCAH6FFWw5okOneqPTCSUP8t_yb0lMtPJLWKaB11n3_tK6P5iaGANIG5UnW6m949uoysijHjPMpoX3HULD8GrWlblwMRx7Q-5_ZeYL9oYqm35cjq1qeqp5CGv6OPeQoozvjhXZ9FaHxSD4GP4VnOVWlB2F2HYQHN90KLqVSrJ3lSJUASCDusTpiwSzIw25-1eFvopz5q1H9xc6379X1k6_oGgFUENuLVuG0YvzloBLdCLJeDJ5b6EpO7Etbycj9Qk3-8aL6k3gwPVumwaHsfkmjy78CIZKbw.dDZao0cnR60cPkmA0iYp5-txgPim3ksjU0daOCAcIV0&dib_tag=se&keywords=standoff+m3&qid=1710792950&sprefix=standoff+m3%2Caps%2C98&sr=8-7)
* 1ea M3x10 countersunk screw
* 1ea M3x20 countersunk screw
* 2ea M2x10 button head screw
* 4ea M2x5 button head screw
* 3ea 2x10 self tapping screw
* 2ea M5x10 button head screw
* 2ea M5 hex nut
* 2ea M5x12 screw
* 2ea M5 roll in T-nuts

### Brushinator 
* 1ea [Brush](https://www.amazon.de/Reinigung-Drahtbürste-Kunststoffgriffe-Edelstahl-Reinigungswerkzeug/dp/B0895GCSH7/ref=sxts_b2b_sx_reorder_acb_customer?content-id=amzn1.sym.f4e69c76-7f1e-4be9-a990-6de7d07aaf6a%3Aamzn1.sym.f4e69c76-7f1e-4be9-a990-6de7d07aaf6a&crid=20N7CF5QOWQE5&cv_ct_cx=messingbürste&dib=eyJ2IjoiMSJ9.z7TWS4HkcxDzHbvJIgCPzA.Y7QLxHE9fQSL7NgeJQ0xp0zurahyunnSiQJpj-z_JAI&dib_tag=se&keywords=messingbürste&pd_rd_i=B0895GCSH7&pd_rd_r=83d5e4a9-06be-4864-90a7-eb933d223a5d&pd_rd_w=HD1Tp&pd_rd_wg=Qrf1B&pf_rd_p=f4e69c76-7f1e-4be9-a990-6de7d07aaf6a&pf_rd_r=70E8QH3QH7KNRC2K66PZ&qid=1710793370&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=messingbürste%2Caps%2C100&sr=1-1-c8a51df4-6015-4603-b82a-8c2c24cf7e97&th=1)
* 4ea brass heat insert 4mm
* 4ea M3x10 button head screw
* 2ea M5x10 button head screw
* 2ea M5 hex nut
* 2ea M5x12 button head screw
* 2ea M5 roll in T-nuts

### Excarvator
* 1ea M3x30 button head screw
* [2 ea silicone O-Ring 10x14x2mm](https://www.amazon.de/gp/product/B07NQD6KCJ/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&th=1)
* 1ea MG90s 360deg Servo (Aliexpress)
* 2ea brass heat insert 4mm
* 1ea M3x10 button head screw
* 1ea ballbearing 3x10x4mm
* 1ea ballbearing 10x22x6mm
* 2ea 2x10 self tapping screw
* 2ea M2.5x16 button head screw
* 2ea M3x16 button head screw

### Gantry Servo Mount & Pin for Filametrix Filament Cutter.
* 1ea 15mm M3 brass standoff
* 1ea M3x16 button head screw
* 1ea MG90s 180deg Servo
* 1ea brass heat insert 4mm
* 1ea M3x10 button head screw

## Building Instructions
### Purginator
* With a ruler and a scalpel cut out a 82x20 mm strip of 1mm thick silicone sheet and punch 2.5 mm holes according to the template. This ist best done with [punch pliers](https://www.amazon.de/AmazonBasics-Leder-Lochzangen-Set-Drehlochzange-verschiedene-Aufweitwerkzeug/dp/B07W48YG15/ref=sr_1_1_ffob_sspa?crid=Q96VTO20Z6JF&dib=eyJ2IjoiMSJ9.HWjcpEgpXCPkTwFn7Ex3hMQVKTF8OVhrfR7BBim0AXNtrP4Doypsq9iqnog-XIyfIdXdWmZXm5eAmspMH-17IQhGMJ4RgyXJRH3qj4_gQ3bJLZOiAskIPYWs-z18LgVfhQdsucgHDHeOROjCnV8fbx_5tbQipQh_mngMIqCHn3XKTLn09DdfxjHAMntypskkf1c5OUrXmWF0YJBniCbq8tjya1m33LWLyLyblHhAWnE.RNZpz3uQqhsoqXTNV4xxpJ1DEOtU8145AU8xL-e6cCY&dib_tag=se&keywords=lochzange&qid=1710811490&sprefix=lochzange%2Caps%2C102&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1) and the jig which can be found amongst the stl files.
* Mount the 4 armed servo horn that came with the MG90s servo to the retraction drum using the screws which were included as well and cut the protruding arm flush
* Insert a heat insert in each of the bearing levers
* Mount the ballbearings to the bearing levers
* Fix the 20mm brass standoff to one of the bearing levers using a M3x10 countersunk screw.
* Insert into the main body and the lid
* Mount the second bearing lever and the torque inducer using a M3x20 countersunk screw. Tighten so that the torque inducer does not slip.
* Stretch the silicone O-ring over the torque inducer and fix it to the hook on the main body.
* Mount the silicone strip to the retraction drum using the drum clamp and two M2x10 screws. Make sure the strip is perpendicular to the drum.
* Place the drum in the main body and run the silicone strip in a loop around the bearings.
* Slide the cover in place and secure with three 2x10mm tapping screws.
* Fix the silicone strip end to the housing bottom using the fwd clamp and 4 M2x5 screws. Make sure not to overtighten.
* Check for smooth action.
* Place the M5 hex nuts in the gantry mount (and maybe secure them with some glue)
* Mount the assembly to the gantry mount using two M5x10 button head screws
* The servo should be inserted in position ANGLE=180 and the purginator drum in fully retracted position.
* Mount to the left gantry corner flush to the aluminium extrusion.





