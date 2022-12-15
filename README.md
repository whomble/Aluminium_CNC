# Budget CNC cutting alluminium

This cnc router is my third itteration, the two previous versions was only able to cut wood and plastic and barely engraving aluminum.
This version is capable of cutting any soft metal (aluminuim, copper, brass even silver) easly.
The total cost including the salvaged part from my previous CNC is around 300€, if you want to replicate the project the cost can change depending of what materials you have availlable.

The design is based on 45 * 45mm aluminium extrusions that i've recovered from the waste disposal. It is powered by 4 Nema 17 stepper motors from my previous CNC and an arduino cnc shield V3.

Depending of your supplys the total cost can varry from **300 to 450€** considering you have all the required tools
From the conception to the firsts good cuts it took me around **80h** of work (mistakes includes)

# Part list


| Part | Quantity | Cost |
|- | - | - |
| Arduino uno + CNC shield + DRV8825  | 1 | 15€ |
| M3 * 10mm screws | 100 | 4€ |
| M3 * 8mm screws| 50 | 2€ |
| Linear rail MGN12H 300mm | 4 | 60€ |
| Linear rail MGN12H 150mm | 2 | 20€ |
| Additionnal block for linear rail MGN12H | 2 | 15€ |
| T8 lead screw pitch 2mm lead 2mm 400mm with anty backlash | 1 | 10€ |
| T8 lead screw pitch 2mm lead 2mm 350mm with anty backlash | 2 | 15€ |
| T8 lead screw pitch 2mm lead 2mm 200mm with anty backlash | 1 | 5€ |
| Ball bearing KP08 | 4 | 6€ |
| Ball bearing KFL08 | 4 | 6€ |
| 3W warm white LED | 2 | 1€ |
| Nema 17 0.59N.m at least | 4 | 50€ |
| 5 * 8 aluminium coupler | 4 | 4€ |
| GT2 20 to 60 pulley kit with 200mm belt | 1 | 4€ |
| 500W spindle with controller | 1 | 80€ |
| M3 insert for plastic | 50 | 3€ |
| M4 wood insert | 50 | 2€ |
| 10mm cable sleeve | 5m | 5€ |
| 12V 150W power supply | 1 | 15€ |
| Lithium grease | 1 | 5€ |
| Total | a lot | 327€ |

In addition you need to find something to build the base on like aluminium extrusion, if you can found from second hand it can cost something like 40€ otherwise it's more like 80€. Even if it looks stiff 2020 extrusion from 3D printer can bend en vibrate with this type of machine so I'll recommand to use at least 30mm thick aluminuim extrusion.
You will also need 8mm thick aluminium plate about 200 * 200mm again if you can found some from second hand it can be really cheap.
T nut for aluminium extrusion could be added to the list (to fix the linear rails) but it's quite expensive and there isn't much load in this direction so i've 3D printed my own and add m3 inserts

Some more commun supply are also needed like heat shrink tube, solder, wires (I use wires from old RJ45 cable it can handle something like 5A without a problem, its free nd easly accessible).

A lots of tools are needed to work properly:

- Soldering iron
- Drill press
- Caliper
- Dial indicator
- Heat gun
- A good square rule
- Handed metal saw 
- Metal band saw (if your alumiun extrusions needed to be with a perfect 90° angle)
- Hand drill
- Center punch
- Marker for metal
- Hammer, clamps, screw drivers others hand tools
- 3D printer
- deburr tool


# Conception


# Cutting, drilling, tapping
 
# 3D printed parts

# Assembly

# Wirring

# Lights

# Ajustements

# Tool path

The easiest software to begin is fusion 360 even if you are using solidworks or something else teh toolpath generation is easy to understand with a good definition for eatch settings.



At the beggining the best way to learn is to use commun settings for this type of machine, so I've used the settings from the french webbsite [CNC fraises](https://www.cncfraises.fr/cloud/ParametresDeCoupe_CncFraises_V1.6.pdf)
Google translate can be really useful, otherwise here is a quick recap:
You can change 3 mains parameters, advance speed, cutting deph, and spindle speed. Since my spindle doesn't have an accurate control of the speed I just go full throttle which is 12000 rpm and I addapt the others settings.


# Results
## Wood
## Aluminium
## Copper
## Silver

<img src="img/VID_20220711_195236.mp4"  width="450">

# Microlubrification
