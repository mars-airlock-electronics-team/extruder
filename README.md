# extruder
## About
This is where all files, code, and teamwork will be kept pertaining to the 3D printing set up will be. The biggest obstacle right now is to choose what 3D arm to base our system off of. In the rest of the document what is needed will be described and some information will be presented.

## What is it we are trying to accomplish?
Building this printer is a small but crucial part of building the airlock. The vast majority of the parts for the airlock are to be 3D printed. A regular 3D printer will not work for all the parts. The endcaps are 3 m in diameter which is much larger than the print size of conventional 3D printers. To print these endcaps it has been determined that a robotic arm with a print head attached would be the best way to go. Thankfully this type of setup has been done many times before, so we know it is possible.

## What is needed?
1. A Robotic Arm
- This arm will have to have a reach of at least 1.5 m but more is better (I'd say around 1.8 m to be safe)
- The arm will have to have a payload capacity that is at least the weight of the print head

2. Print head
- a print head has been given to us by Roman, however if we want to change it should not take that much adjusting.

3. Code
- need to control both the arm and the print head.

So, basically everything needs to be done.

## Preliminary research
### 3D printing basics
If you have not work in 3D printing before I would recommend the following resources to get up to speed.
1. https://reprap.org/wiki/RepRap
- this is the wiki of an open source community dedicated to making self replicating machines
2. https://all3dp.com/3d-printing-3d-printer-guide-101-questions/
- a bunch of Q and A s about 3D printing
3. https://3dinsider.com/3d-printer-parts/
- a list of all the basic parts of a 3D printer
4. https://en.wikipedia.org/wiki/G-code
- wikipedia page of the most popular language used to control 3D printers
- many programs automatically generate G-code from 3D files, but we will still have to translate those commands

### Research papers of similar projects
1. http://eps.novia.fi/assets/Sidor/2/1545/Final-Report-3D-Printing-with-Robotic-Arm.pdf
- A European project
- used a proprietary printer and had some trouble getting documentation about it
- lots of good code outlines that will likely help us
2. https://www.researchgate.net/publication/262218756_Compound_fabrication_A_multi-functional_robotic_platform_for_digital_design_and_fabrication
- made a similar system to what we need again with a proprietary arm (KUKA)
- did a few different things as well
- reached out but have not heard back
3. https://web.wpi.edu/Pubs/E-project/Available/E-project-032516-143806/unrestricted/3D_Printing_Robot_Arm_MQP_Report_3-24-25_v2.pdf
- another student project
- it is very descriptive of the mounts and their print head / extruder design.

### Some Videos Of a Robotic 3D Printer in Action
1. https://www.youtube.com/watch?v=NxgeESWS3z0
2. https://www.theverge.com/2017/4/27/15447578/autonomous-robot-3d-printers-mit-homes-planets
- much bigger than needed
- builds entire homes :astonished:
- this are the people who wrote the second paper
3. https://www.geek.com/news/ai-spacefactory-wins-nasas-mars-3d-printed-habitat-competition-1786892/
- This is just a cool project
- towards the end of the video (minute 4 or so) a robotic arm on a crane is shown 3D printing
- not exactly what we are planing but it is somewhat close
