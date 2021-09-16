# 6. 3D Scanning and Printing

## Group Assignment
&nbsp;

- Test the design rules for your printer(s).
- Document your work and explain what are the limits of your printer(s) (in a group or individually).

&nbsp;

### 3D Printing
&nbsp;

***Explicação do processo de fabricação e do arquivo Gcode.

&nbsp;

### 3D Printer - Ultimaker 2+ 
&nbsp;

The Insper Fab Lab is equipped with two models of 3D printers, the **Ultimaker 2+** and a **Zmorph 2.0 SX**. For this group assignment we used the Ultimaker printer to test the design rules and document its limits.

Here are the equipment specifications:

- **Print technology:** Fused Deposition Modeling (FDM) 
- **Build volume :** 230 x 225 x 205mm
- **Filament diameter:** 2.85 mm
- **Nozzle diameter:** 0.4mm
- **Print speed:** 30 mm/s - 300 mm/s
- **Supported Filaments:** PLA and ABS.
- **Overall Size:** 357 x 342 x 388mm
- **File Transfer:** Standard SD card
- **Printing Software:** Cura

&nbsp;

### Preparing for printing in the Cura 
&nbsp;

To fulfill the requirements of this assignment, I used the [3D Printer Test Models](https://www.thingiverse.com/thing:533472/files) created by [Make Magazine](https://makezine.com/). It is possible to download the files [here](4Downloads/3D_printing_testers.zip).

I imported the files into [Cura](https://ultimaker.com/software/ultimaker-cura), a software developed by [Ultimaker](https://ultimaker.com/) where is possible to set up the printing configurations and parameters.

&nbsp;

![Cura Screenshot 1](imgs/cura_screenshot_1.jpg){.center style="width:950px"}
&nbsp;

I set up the printing for ABS material and with the following parameters:

- **Layer Height:** 0.15mm
- **Wall Line Count:** 4
- **Top Layers:** 6
- **Bottom Layers:** 6
- **Infill Density:** 15%
- **Infill Pattern:** Grid
- **Print Speed:** 45mm/s
- **Build Plate Adhesion Type:** Raft

&nbsp;

![Cura Screenshot 2](imgs/cura_screenshot_2.jpg){.center style="width:950px"}

&nbsp;

Here is a preview from Cura of the printing showing that it going to take almost 10 hours of printing.

&nbsp;

![Cura Screenshot 3](imgs/cura_screenshot_3.jpg){.center style="width:950px"}

&nbsp;

I exported a `.gcode` file to a SD Card and pluged in it into the printer. 

&nbsp;

![Cura Screenshot 4](imgs/cura_screenshot_4.jpg){.center style="width:950px"}

&nbsp;

From the main menu I selected the "print" option followed by the selection of the `.gcode` file.

&nbsp;

![Cura Screenshot 5](imgs/cura_screenshot_5.jpg){.center style="width:950px"}

&nbsp;

![Cura Screenshot 6](imgs/cura_screenshot_6.jpg){.center style="width:950px"}

&nbsp;

The buildplate and the hotend will start to heat up until **100°C** and **230°C** respectively (temperatures set up for ABS material) and as soon the temperature is reached, the printing process will start.

&nbsp;

![Cura Screenshot 7](imgs/cura_screenshot_7.gif){.center style="width:950px"}

&nbsp;

***Describe the results of the printing

&nbsp;

## Individual Assignment
&nbsp;

- Design and 3D print an object (small, few cm3, limited by printer time) that could not be easily made subtractively
- 3D scan an object, try to prepare it for printing (and optionally print it)

&nbsp;
