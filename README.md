# Case for little backup box

This project provides a housing for little backup box based on a Raspberry Pi 4.<br>
It is based on a 3D drawing on the <a href="https://www.freecad.org">freeCAD</a> platform. This drawing can be easily adjusted using an integrated table of dimensions.<br>
<br>
**Attention: The drawing has not yet been printed and tested. If you still want to do a test print, please post your experiences!**<br>
<br>
##The standard drawing assumes the following components:
1. Raspberry Pi 4 Model B
2. Display ssd1331 (RGB color display with 96x64 pixels)
3. Fan having external dimensions 30x30mm, hole spacing 24mm
4. Micro key buttons 6x6 mm2, mounted on a board
5. 15 pieces of jumper wire, female
6. 4 screws M2.5 x 20 mm for the case
7. 8 screws M2.0 x 8 mm and nuts for the buttons
8. Hot glue to stick the display

##Customize drawing
If you use different hardware components, you can adapt the drawing.<br>
It's (relatively) easy to adjust dimensions:
1. Open the FCStd file with freeCAD
2. Open the "dim" spreadsheet in the tree view
3. Change the appropriate dimensions
4. Mark the respective body in the tree view (e.g. "Bottom")
5. Export the stl file (File - export...)

<br>
<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/case-full.png" align="center" width="90%">
	<figcaption>The whole case</figcaption>
</figure>

<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/case-bottom.png" align="center" width="90%">
	<figcaption>The bottom</figcaption>
</figure>

<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/case-top-inner.png" align="center" width="90%">
	<figcaption>Inside view of the top</figcaption>
</figure>

<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/fan.webp" align="center" width="50%">
	<figcaption>Fan, look for &quot;<a href="https://thepihut.com/products/highpi-pro-5v-fan-software-controlled">5V Fan - Software-Controlled</a>&quot;</figcaption>
</figure>

<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/micro-buttons-6x6.png" align="center" width="50%">
	<figcaption>Mico buttons, look for &quot;<a href="https://eckstein-shop.de/10xMicroKeyTaster6x6mmButtonsModuleRastermaC39F22C54mm12V2F50mA">Micro key button</a>&quot;</figcaption>
</figure>
