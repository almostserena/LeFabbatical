## Moving to Fondation Suisse CIUP

I moved to Paris on 17th February. My temporary house ia cute room at [Fondation SUISSE](http://www.fondationsuisse.fr/).that is located at Cité Universitaire.
The room is in a Le Corbusier's building. Realized between 1931 and 1933 by Le Corbusier and his cousin Jean Pierre Jeanneret. Internal decoration are by [Charlotte Perriand](https://en.wikipedia.org/wiki/Charlotte_Perriand).

![Le Pavillion](http://www.fondationsuisse.fr/wp-content/uploads/2016/02/FS_Historique_Exterieur.jpg)

## Fabbing at FabLab Digiscope
Fablab Digiscope is the fabrication laboratory of Université Paris Saclay. All info about the lab are here
![here](https://fablabdigiscope.gitlab.io/)
This is one of the few labs in France running a complete fabacademy, the distributed academy of the FabLab Network.
Head of the lab is Romain di Vozzo. Jonah Marss is the fabmanager and fabacademy instructor. Jonah is a great tutor. 

## Week 1: FabAcademy Module - Electronics production 

Overall goal of the week is to manufacture a PCB through a complete DIY process. The final assignment is to make a programmer, a device that allows to program other circuits. There is a bit o idealogy in the definition of this final project: if you make DIY circuits, you should be able to skip the use of commercial programmers that are stable, but expensive.
Even if I got the point of the DIY approach to circuit making, I confirm that the learning outcome could be achieved without going through this hypertechnicality.

However, I learned many things:
1. Fiber Glass Laser cutting
2. Soldering (and soldering management process)
3. Testing a PCB
4. Alternative manufacturing processes: copper tape cut

**1. Fiber Glass Laser cutting**
- Operating a laser cutter Epilog to engrave the circuit (fiberglass function) and cut its outline (CO2 function)
- Cleaning the PCB
- Removing the little hair generated during the engraving process (2 passes engraving would help with that)
- checking that there are not connections between traces that are not supposed to be connected (use the multimeter with the bip on)

**1. Soldering (and soldering management process)**
- writing down a list of components and put a piece of tape to stick on the super hyper tiny components. For this course we are using Surface mounted components (or SMD) 12o6 (PICT 1)
- selecting the components from the big catalogues/libraries of SMD and inc case there are components missing we choose the one that have the closes values (i.e. I took the 510 Ω because we did nto have the 499Ω).
- reading correctly the schematic and the board image of [FabTinyISP](http://fab.cba.mit.edu/classes/863.16/doc/projects/ftsmin/index.html). Quick note: learning how to read this image is already a great take away. Second note: the blue arrows indicate that the components have polarity. 
- LEDs have polarity, resistors do not have polarity, small capacitors have no polarity (bit ones have polarity)
- Soldering best practices: use fume extractor (always!), clean the soldering iron tip, relax your amrs if you have problems like the ones I have (shacking hands).
- soldering sequence: 1. put the tip 2. put the solder 3. remove the solder 4. remove the tip
- soldering techniques: when solderin the chip, solder the uepper left leg and then the bottom right leg (to have it stable). More in general: put some solder on the trace, then solder one side of the component to attach it to the trace. Afterwards, stick the other side and add solder until it is not covering the entire copper trace (the one for that specific side/leg)
- Start from inside to outside of the board, from small components to bigger and taller components, start from the chip.  
- Component after component, check if there are shorts (always using the multimeter with the bip on) (PICT 2)
- Final soldering: the usb traces. Put a lot of solder, but avoid to have traces with differt heights othewise it will not connect into the port. (PICT 3)

[Pict 1](https://drive.switch.ch/index.php/s/vAfRGCf0qe5Q96C)
[Pict 2](https://drive.switch.ch/index.php/s/9pT83aq1AhgUk8H)
[Pict 3](https://drive.switch.ch/index.php/s/vAfRGCf0qe5Q96C)


**3.Testing the Programmer**
- In theory I got all steps. In practice, I did not install the software on my mac.
- In conclusion, my PCB works nevertheless all components look burned.

**4. Alternative manufacturing processes: copper tape and vynil cutter**
- It is possible to make circuite with a vynil cutter. We used a vynil cutter Roland GS24
- First prepare the support for cutting: a plastic foil (height 1m), double side tape (not too strong), large copper tape. Stick the double side tape on the plastic piece, then the copper tape
- Set the machine: measure foil, set the zero, send file with the following settings: Pressure 90, Speed 10, pen force -1 (or 1.5)
- Problems: removing the copper without damaging the circuit

**Resources and useful links (including the notes from Neil Gershenfeld's lecture on Wednesday 19th Feb)**
Emergingobjects.com
Onshape
http://digitalgastronomy.co/
Hilbert curve recursive 
algoMods.cba.mit.eduhttp://fab.cba.mit.edu/classes/863.17/Harvard/people/HonghaoDeng/
Autoleveller.co.uk
Suggestion techniquesjoint: non farli a 90gradi ma arrontondare sui lati
1/10 of mm is good for a joint
Materials (according to Neil is mandatory to have and use this:-))https://www.uline.com/BL_1855/Heavy-Duty-Corrugated-Pads






