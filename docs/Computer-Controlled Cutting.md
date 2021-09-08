## Group Assignment

&nbsp;

Characterize your lasercutter's focus, power, speed, rate, kerf, joint clearance and types

&nbsp;

### Material
&nbsp;

- 3mm MDF (Medium-density fibreboard) sheet.

&nbsp;

<center>
![Laser Focus 1](imgs/laser_focus_1.jpg){.center style="width:950px"}
</center>
&nbsp;

### Sofware
&nbsp;

The laser cutter machine is [Duplotech 1080](https://www.insper.edu.br/fab-lab/equipamentos/) from [Duplo J](http://www.duploj.com.br/) and its software is called [RDWorks (RDCAM)](http://www.duploj.com.br/suporte). It can support `.dxf` and `.bitmap` files. 

&nbsp;

<center>
![RDWorks](imgs/RDWorks.jpg){.center style="width:950px"}
</center>
&nbsp;

### Focus
The laser cutter has a manual focus. According to the manufacturer's instructions, the distance between the material surface and the laser nozzle must be 6 mm. Therefore, we placed a 6 mm thickness piece of acrylic between the MDF sheet and the laser nozzle (the two screws highlighted in the picture below can be handled to allow the cannon to be free or fixed).

&nbsp;

<center>
![Laser Focus 2](imgs/laser_focus_2.jpg){.center style="width:950px"}
</center>
&nbsp;

### Setting Test (power, speed, rate)
To get a better sense of what the best parameters are for cutting and engraving we developed two tests, one of power(%) vs speed(mm/s) for testing cutting parameters and another one with interval(mm) vs power(%) using a fixed speed of 350mm/s to test engraving parameters. We set different parameters up divided by colors.

You can download the setting test file [here](4Downloads/Setting_test.dxf).

&nbsp;

<center>
![Setting test 1](imgs/setting_test_1.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Setting test 2](imgs/setting_test_2.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Setting test 3](imgs/setting_test_3.gif){.center style="width:480px"}
</center>
&nbsp;

|**The results after cutting and engraving in 3mm MDF**|
|:------------------------------------------------:|
|![Setting test 5](imgs/setting_test_5.jpg){.center style="width:950px"}|

&nbsp;

### Kerf Test
&nbsp;

In this file were drawn some 15 mm diameter circles. Each color was set up with a different power (%). And the first row was cut with a speed of 5 mm/s and the second 15 mm/s.

You can download the kerf test file [here](4Downloads/Kerf_test.dxf).
&nbsp;

<center>
![Kerf test 1](imgs/kerf_test_1.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Kerf test 2](imgs/kerf_test_2.jpg){.center style="width:950px"}
</center>
&nbsp;

There isn’t that much of difference changing the parameters. The calculated kerf is around ***0.225mm*** and ***0.275mm***.
&nbsp;

<center>
![Kerf test 3](imgs/kerf_test_3.jpg){.center}
</center>
&nbsp;

### Joint Clearance Test
&nbsp;

Setting Values: power 70%, speed 15mm/s.

You can download the joint clearance test file [here](4Downloads/Join test.dxf).
&nbsp;

<center>
![Joint Clearance 1](imgs/joint_clearance_1.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Joint Clearance 2](imgs/joint_clearance_2.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Joint Clearance 3](imgs/joint_clearance_3.gif){.center style="width:480px"}
</center>
&nbsp;

<center>
![Joint Clerance 4](imgs/joint_clearance_4.jpg){.center style="width:950px"}
</center>
&nbsp;

The gap which had the best fit was 2.75mm (kerf around 0,25mm).
&nbsp;

<center>
![Joint Clearance 5](imgs/joint_clearance_5.jpg){.center style="width:950px"}
</center>
&nbsp;


<style>
td, th {
  border: 1px solid #dddddd;
  text-align: center;
}
</style>


## Individual Assignment

&nbsp;

- Design, lasercut, and document a parametric **press-fit construction kit**, which can be assembled in multiple ways. Account for the lasercutter kerf.

- Cut something on the vinylcutter.
&nbsp;

### Press-fit Construction Kit
&nbsp;

My kit is based on [Kellie Dunn's press-fit construction kit](https://kelliead.github.io/assignment1.html). Through her files I could import her design in Fusion 360 and work over it.

&nbsp;

<center>
![Press-fit construction kit 1](imgs/construction_kit_1.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Press-fit construction kit 2](imgs/construction_kit_2.jpg){.center style="width:950px"}
</center>
&nbsp;

Kellie Dunn's used cardboard sheet to produce the pieces that constitute her kit. In my case, since I used 3mm MDF sheets, I needed to adjust the cuts for the press-fit. To create the cuts according to what I planned, I modeled and positioned all the pieces as I had envisioned.

&nbsp;

<center>
![Press-fit construction kit 3](imgs/construction_kit_3.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Press-fit construction kit 4](imgs/construction_kit_4.jpg){.center style="width:950px"}
</center>
&nbsp;

After modeling the pieces, I exported its sketch as a `.dxf` file and brought it in **RDWorks**. I positioned all the 32 pieces according to the size of MDF sheets I had avaiable. Since I was using scraps of sheets, I organized it in small groups like the image below:

&nbsp;

<center>
![Press-fit construction kit 5](imgs/construction_kit_5.jpg){.center style="width:950px"}
</center>
&nbsp;

From **RDWorks** I sent the drawings as a cut file to the laser cutter and started the process of fabrication of the pieces. The images below show the results and the kit assembling process. 

&nbsp;

<center>
![Press-fit construction kit 6](imgs/construction_kit_6.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Press-fit construction kit 7](imgs/construction_kit_7.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Press-fit construction kit 8](imgs/construction_kit_8.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Press-fit construction kit 9](imgs/construction_kit_9.jpg){.center style="width:950px"}
</center>
&nbsp;


### Vinyl Cutter Assignment
&nbsp;

For the vinyl cutter exercise, I used the logo developed through Inkscape in the [Computer-Aided Design assingment](https://leonrosa.github.io/FabAcademy/Computer-Aided%20Design/#inkscape) to create a sticker . But before sending the logo to the machine, I needed to adjust the size of the image according to the size I wanted for the sticker. I did it changing the values, in millimeters, described in the boxes in the upper side of the Inkscape interface. The **H** means "height" and the **W** means "width".

&nbsp;

<center>
![Vinyl Cutter 1](imgs/vinylcutter_1.jpg){.center style="width:950px"}
</center>
&nbsp;

After rezising the logo as I wanted, I saved it in a `.pdf`file.

&nbsp;

<center>
![Vinyl Cutter 2](imgs/vinylcutter_2.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Vinyl Cutter 3](imgs/vinylcutter_3.jpg){.center style="width:950px"}
</center>
&nbsp;

I connected my lap top with the vinyl cutter machine using a USB cable and placed a scrap of vinyl in the machine.

&nbsp;

<center>
![Vinyl Cutter 4](imgs/vinylcutter_4.jpg){.center style="width:950px"}
</center>
&nbsp;

<center>
![Vinyl Cutter 5](imgs/vinylcutter_5.jpg){.center style="width:950px"}
</center>
&nbsp;

Then I ran a routine in the machine called "piece" which makes the machine identify the material and display the dimension avaiable for cuts, what in this case was 114 x 157mm.

&nbsp;

<center>
![Vinyl Cutter 6](imgs/vinylcutter_6.jpg){.center style="height:650px"} &nbsp;&nbsp;&nbsp; ![Vinyl Cutter 7](imgs/vinylcutter_7.jpg){.center style="height:650px"}
</center>
&nbsp;
