
<h1 align="center">
  <br>
  <img src="https://github.com/0BitsnBytes/McQueen/blob/f5faa1284b62473a97b7975d7ed7a54be45dc578/WhatsApp_Image_2026-06-10_at_20.42.08-removebg-preview.png" alt="McQueen" width="220">
  <br>
  McQueen
  <br>
</h1>

<h4 align="center">
AWD RC Car • Custom ESC
</h4>

<div align="center">

</div>

<p align="center">
  <a href="#specifications">Specifications</a> •
  <a href="#links">Links</a> •
  <a href="#custom-esc">Custom ESC</a> •
  <a href="#chassis">Chassis</a> •
  <a href="#build-guide">Build Guide</a> •
  <a href="#zine">Zine</a> •
  <a href="#credits">Credits</a>
</p>

<img src="https://github.com/0BitsnBytes/McQueen/blob/1a9e9249de90259f2130f4d14ed35b0f7860ea54/Mcqueen.png" alt="McQueen Banner">

<p>&nbsp;</p>

McQueen is an AWD RC car with 4 drone-hub-motors. Featuring a DIY 80A ESC with current sense and braking. A fully custom double wishbone suspension with an aerodynamic chassis all powered by 2 6S Lipo batteries. 

Most RC cars are seen as toys, McQueen is definitely not one of those. It is an attempt to combine high current electronics, aerodynamic bodies, and complex suspension geometries into a small RC Car. 

---

<h2 id="specifications">Specifications</h2>

<table>
<tr>
<td><b>Drive System</b></td>
<td>All Wheel Drive (AWD)</td>
</tr>

<tr>
<td><b>Motors</b></td>
<td>4× Drone Hub Motors</td>
</tr>

<tr>
<td><b>Battery</b></td>
<td>2× 6S LiPo Batteries</td>
</tr>

<tr>
<td><b>Motor Controller</b></td>
<td>Custom STM32 ESC</td>
</tr>

<tr>
<td><b>Suspension</b></td>
<td>Double Wishbone</td>
</tr>

<tr>
<td><b>Steering</b></td>
<td>Ackermann Geometry</td>
</tr>

<tr>
<td><b>Braking</b></td>
<td>Electronic Dynamic Braking</td>
</tr>

<tr>
<td><b>Chassis</b></td>
<td>Fully Custom 3D Printed Design</td>
</tr>
</table>

---

<h2 id="links">Links</h2>

| Resource | Link |
|-----------|-----------|
| CAD Assembly | <a href="https://cad.onshape.com/documents/fc565ca3851146bee43ab660/w/08fa01b8b529e8822f765509/e/27cf93230e8926e0ab4158b0?renderMode=0&uiState=6a2c09f89a93076bf06deb47">Onshape Assembly</a> |
| PCB Files | ADD_KICAD_LINK |
| Bill of Materials | ADD_BOM_LINK |
| Firmware | ADD_FIRMWARE_LINK |

---

<h2 id="custom-esc">Custom ESC</h2>

The ESC combines current sensing, protection circuitry, braking, and motor feedback into a compact high-current first PCB :).

<h3>Features</h3>

<ul>
<li>STM32F411CEU6 Microcontroller</li>
<li>IR21084 MOSFET Driver</li>
<li>AS5600 Position Sensor Interface</li>
<li>INA180 Current Sense Amplifier</li>
<li>MOSFET Temperature Monitoring</li>
<li>SMCJ54CA TVS Protection</li>
<li>RGB Status LED</li>
<li>Electronic Braking</li>
</ul>

<h3>Schematic</h3>

<iframe src="Media/Custom ESC.pdf" width="100%" height="600px"></table>

---

<h3>PCB Layers</h3>

<h4>Layer 1</h4>

<img src="https://github.com/0BitsnBytes/McQueen/blob/7a6298bfbef7ddecca315248bd9f0d4562a126f2/Media/Layers/Fcu.png">

<h4>Layer 2</h4>

<img src="https://github.com/0BitsnBytes/McQueen/blob/7a6298bfbef7ddecca315248bd9f0d4562a126f2/Media/Layers/INcu-1.png">

<h4>Layer 3</h4>

<img src="https://github.com/0BitsnBytes/McQueen/blob/7a6298bfbef7ddecca315248bd9f0d4562a126f2/Media/Layers/INcu-2.png">

<h4>Layer 4</h4>

<img src="https://github.com/0BitsnBytes/McQueen/blob/7a6298bfbef7ddecca315248bd9f0d4562a126f2/Media/Layers/INcu-3.png">

<h4>Layer 5</h4>

<img src="https://github.com/0BitsnBytes/McQueen/blob/7a6298bfbef7ddecca315248bd9f0d4562a126f2/Media/Layers/INcu-4.png">

<h4>Layer 6</h4>

<img src="https://github.com/0BitsnBytes/McQueen/blob/7a6298bfbef7ddecca315248bd9f0d4562a126f2/Media/Layers/Bcu.png">

---

<h3>Board Views</h3>

<h4>Front</h4>

<img src="FRONT_RENDER">

<h4>Back</h4>

<img src="BACK_RENDER">

---

<h2 id="chassis">Chassis</h2>

The Chassis features a fully custom double wishbone suspension system, Ackermann steering, aerodynamic chassis, and front and rear wings.

<h3>Suspension</h3>

<img src="SUSPENSION_IMAGE">

<h3>Aerodynamics</h3>

<img src="AERO_IMAGE">

---

<h2 id="build-guide">Build Guide</h2>

McQueen consists of two major assemblies:

1. Custom ESC
2. 3D Printed Chassis

<h3>ESC</h3>

<ol>
<li>Upload the Gerber files to your preferred PCB manufacturer.</li>
<li>Select 2oz copper during fabrication.</li>
<li>Order the PCB.</li>
<li>Populate using the ESC BOM.</li>
<li>Flash the firmware.</li>
</ol>

<h3>Chassis</h3>

<ol>
<li>Download the STL files.</li>
<li>Print all components in PETG or equivalent material.</li>
<li>Purchase hardware from the chassis BOM.</li>
<li>Follow the Onshape assembly.</li>
<li>Install electronics and drivetrain.</li>
<li>Secure components using M3 hardware.</li>
<li>Use cyanoacrylate adhesive where necessary.</li>
</ol>

---

<h2 id="zine">Zine</h2>

<img src="https://github.com/0BitsnBytes/McQueen/blob/82557c4706811a055dfce3bde01ab351c2c9ccda/Zine/Mcqueen.png">

---

<h2 id="credits">Credits</h2>

This project uses:

<ul>
<li>KiCad for PCB Design</li>
<li>Onshape for CAD</li>
<li>Blender for Rendering</li>
<li>Figma for Documentation & Zine Design</li>
</ul>

---

<h2>License</h2>

GPL-3.0

