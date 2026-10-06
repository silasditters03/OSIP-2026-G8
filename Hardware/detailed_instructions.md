This is the space for students of the course to produce their improved step-by-step instructions. 

This document shows the detailed step-by-step instruction for building the gearbox. 
It is split up into two segments. Segment 1: 3D-Printing and Segment 2: Assembly.

Segment 1: 3D-Printing
1. Load the correct fillament in the printer. For this project we recommend PLA as a fillament.
2. When the printer is ready to print, head over the the PC in LPL and open PrusaSlicer.
3. The .step files that need to be sliced can be found in the Hardware folder
4. When opening .step files in Prusaslicer, you can drag in multiple files at once. This is recommended to save time.
    We put all the gears in one slice and the box components in a seperate one.
5. When placing the objects in PrusaSlicer make sure they are oriented with the most surface area down. (driver_gear.step and top_plate_v2 must be flipped in z-axis to accomplish this, others are already fine_=)
6. Once the desired objects are placed, we can assign printing settings. First, on the right hand side, select the correct printer
7. Select the correct print settings. You want to select the distance that is about 1/2 the nozzle diameter of the printer you will use.
    Select STRUCTURAL for sturdier builds that take longer and SPEED for faster prints that are less sturdy.
8. Select the correct fillament (this can be found on the fillament role on hanging on the printer)
9. If needed, select the correct support and brim. A brim is recommended for prints with less surface area touching the bed, or prints that are taller than they are wide.
10. If all previous steps were successful, you can now slice (bottom right)
11. Transfer sliced .gcode to printer. The PCs in LPL are connected with the 3D-printers. You can transfer a sliced build to the printer with the button in the bottom right (next to the large "Export g-code" button)
12. Once its sent to the printer, head over to it. On the screen you will be prompted to start the print.
NOTE: If you are printing at temperatures above 170 °C, the nozzle will first calibrate and go to a temperature below your printing temperature. This will take a bit, but when done it will automatically go to the higher
        printing temperature, so do not panic!


Segment 2: Assembly
1. Collect all printed parts, you should have: A housing top plate, housing bottom plate, 4 housing pillars, 1 driving gear, 1 enganging hear, 3 24-tooth gears of different heights.
2. Get a motor from the storage in the workshop. Open the drawer which says Electronic components 4 and actuators and grab a 6 Volt motor (to the left). 
3. Leave the protolab and go the storage unit in the middle of the workplace and open the 'ball bearings' drawer and grab 1 bearing which is in a plastic casing called 'IBB  688-2RS NI25J'. This should fit perfectly in the topplate you printed. 
4. From the drawers at LPL (by the tables) collect the following: 4 bolts, 4 bolt screws (thin enough to pass through the pillars), 3 screws/pins (from 'Allen bolts, keys and pins' that fit through the gears and are long enough to go all the way through
5. In the map Documents -> Images you can find 5 images that'll help you. Open the box you see in
 <div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/IMG_5685.jpeg" alt="lpl sharing" style="width: 30%;"/>
  <figcaption>Figure: LPL shop front with current and future letters<figcaption>
</div> 
   (M1 tot en met M2,4). Ignore the lime box you see <div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/Imggeneral.jpg" alt="lpl sharing" style="width: 30%;"/>
  <figcaption>Figure: LPL shop front with current and future letters<figcaption>
</div>   and pick 2 screws out of the pink box you see in the image. 
   These 2 screws let you attach the motor to your baseplate. 
6. Next, open the 'M4' drawer and grab 5 spacers you see in the image </div> 
   (M1 tot en met M2,4). Ignore the lime box you see <div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/Imggeneral.jpg" alt="lpl sharing" style="width: 30%;"/>
  <figcaption>Figure: LPL shop front with current and future letters<figcaption>
</div>M4IMG.jpg surrounded by blue. You will need them to space out the cogs. 
7. Now use all the materials to build the gearbox. In the photos </div> 
   (M1 tot en met M2,4). Ignore the lime box you see <div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/Imggeneral.jpg" alt="lpl sharing" style="width: 30%;"/>
  <figcaption>Figure: LPL shop front with current and future letters<figcaption>
</div> </div> 
   (M1 tot en met M2,4). Ignore the lime box you see <div style="display: flex; justify-content: space-between;">
  <img src="/Documents/Images/Imggeneral.jpg" alt="lpl sharing" style="width: 30%;"/>
  <figcaption>Figure: LPL shop front with current and future letters<figcaption>
</div> you can see how we build the gearbox. The most important thing to see in the images is the order you place the gears in. The height of the small part of the 3 similar cogs should be the smallest for the fourth gear (seen from the motor).   There is 1 spacer between the base plate (motor side) and the 2nd gear (2nd from the motor side), 2 spacers between the base plat and the 3rd cog. 1 between the 2nd and 4th cog and 1 between the 3rd and 5th cog. We use the bolts to
   attach the pillars to both plates. We also used some tape to make sure the gears wouldnt get loose. 
8. Now test your built gearbox. The arduino code is in 'Software'. 

Good luck!

