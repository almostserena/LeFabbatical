## Week 1: Moving to Fondation Suisse CIUP

I moved to Paris on 17th February. My temporary house ia cute room at [Fondation SUISSE](http://www.fondationsuisse.fr/).that is located at Cité Universitaire.
The room is in a Le Corbusier's building. Realized between 1931 and 1933 by Le Corbusier and his cousin Jean Pierre Jeanneret. Internal decoration are by [Charlotte Perriand](https://en.wikipedia.org/wiki/Charlotte_Perriand).

![Le Pavillion](http://www.fondationsuisse.fr/wp-content/uploads/2016/02/FS_Historique_Exterieur.jpg)

## Week 1: FabAcademy Module - Electronics production at FabLab Digiscope

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
- writing down a list of components and put a piece of tape to stick on the super hyper tiny components. Ff course we are using Surface mounted components (or SMD)
- selecting the components from the big catalogues/libraries of SMD and inc case there are components missing we choose the one that have the closes values (i.e. I took the 510 Ω because we did nto have the 499Ω).
- reading correctly the schematic and the board image of [FabTinyISP](http://fab.cba.mit.edu/classes/863.16/doc/projects/ftsmin/index.html). Quick note: learning how to read this image is already a great take away. Second note: the blue arrows indicate that the components have polarity. 
- LEDs have polarity, resistors do not have polarity, small capacitors have no polarity (bit ones have polarity)
- Soldering best practices: use fume extractor (always!), clean the soldering iron tip, relax your amrs if you have problems like the ones I have (shacking hands).
- soldering techniques: 


Resources and useful links (including the one from Neil Gershenfeld's lecture)



```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/almostserena/LeFabbatical/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
