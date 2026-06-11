<h1 align="center">
  <br>
  <img src="YOUR_LOGO_URL" alt="McQueen" width="250">
  <br>
  McQueen
  <br>
</h1>

<h4 align="center">
Built Like a Race Car. Powered Like a Drone.
</h4>

<div align="center">

<img src="https://img.shields.io/badge/KiCad-PCB-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/STM32-F411CEU6-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" />
<img src="https://img.shields.io/badge/Onshape-CAD-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/Blender-Renders-F5792A?style=for-the-badge&logo=blender&logoColor=white" />

</div>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#diy">DIY</a> •
  <a href="#custom-esc">Custom ESC</a> •
  <a href="#chassis">Chassis</a> •
  <a href="#zine">Zine</a> •
  <a href="#credits">Credits</a>
</p>

<img src="YOUR_BANNER_URL" alt="McQueen Banner" />

<p>&nbsp;</p>

McQueen is an AWD RC car powered by four drone hub motors and a fully custom ESC. Featuring a custom double-wishbone suspension system, aerodynamic bodywork, regenerative braking, and high-current power electronics, it pushes the boundary between hobby RC cars and real motorsport engineering.

Most RC cars are treated as toys. McQueen was designed as an engineering project that combines high-current electronics, aerodynamic design, suspension geometry, and custom firmware into a compact open-source platform.

To build your own, fabricate the ESC PCB, print the chassis components, assemble the suspension, and flash the firmware to the STM32-based ESC.

---

<h2 id="diy">DIY</h2>

McQueen consists of two major subsystems:

1. Custom ESC
2. 3D Printed Chassis

### ESC Assembly

1. Upload the provided Gerber files to your preferred PCB manufacturer.
2. Select **2oz copper** during fabrication.
3. Order the PCB.
4. Populate the board using the ESC BOM.

### Chassis Assembly

1. Download all STL files from the CAD section.
2. Print the parts using PETG or your preferred material.
3. Purchase all hardware listed in the chassis BOM.
4. Follow the circuit diagram for wiring.
5. Assemble using M3 screws and nuts.
6. Reference the main Onshape assembly.
7. Use cyanoacrylate adhesive where required.

---

<h2 id="key-features">Key Features</h2>

<ul>
  <li><strong>Double Wishbone Suspension</strong></li>
  <li><strong>Ackermann Steering Geometry</strong></li>
  <li><strong>Front and Rear Aerodynamic Wings</strong></li>
  <li><strong>Four High-Power Drone Hub Motors</strong></li>
  <li><strong>Custom ESC with Integrated Current Sensing</strong></li>
  <li><strong>Regenerative / Dynamic Braking</strong></li>
  <li><strong>STM32-Based Motor Control</strong></li>
  <li><strong>Temperature Monitoring and Protection</strong></li>
</ul>

---

<h2 id="custom-esc">Custom ESC</h2>

The drivetrain is powered by a custom ESC designed specifically for McQueen.

### ESC Specifications

<ul>
  <li>STM32F411CEU6 Microcontroller</li>
  <li>IR21084 MOSFET Driver</li>
  <li>AS5600 Magnetic Position Sensor Input</li>
  <li>SMCJ54CA TVS Protection</li>
  <li>Low-Side MOSFET Braking</li>
  <li>MOSFET Temperature Monitoring</li>
  <li>RGB Status LED</li>
  <li>INA180 Current Sense Amplifier</li>
</ul>

### Schematic

<img src="YOUR_SCHEMATIC_IMAGE" alt="ESC Schematic" />

---

### PCB Layers

#### Layer 1
<img src="YOUR_LAYER1_IMAGE" alt="Layer 1" />

#### Layer 2
<img src="YOUR_LAYER2_IMAGE" alt="Layer 2" />

#### Layer 3
<img src="YOUR_LAYER3_IMAGE" alt="Layer 3" />

#### Layer 4
<img src="YOUR_LAYER4_IMAGE" alt="Layer 4" />

#### Layer 5
<img src="YOUR_LAYER5_IMAGE" alt="Layer 5" />

#### Layer 6
<img src="YOUR_LAYER6_IMAGE" alt="Layer 6" />

---

### Board Views

#### Front
<img src="YOUR_FRONT_RENDER" alt="Front View" />

#### Back
<img src="YOUR_BACK_RENDER" alt="Back View" />

---

<h2 id="chassis">Chassis</h2>

Designed around performance and manufacturability, the chassis integrates aerodynamic elements with a fully custom suspension architecture.

### Suspension

<img src="YOUR_SUSPENSION_IMAGE" alt="Suspension" />

### Aerodynamics

<img src="YOUR_AERO_IMAGE" alt="Aerodynamics" />

---

<h2 id="zine">Zine</h2>

<img src="YOUR_ZINE_IMAGE" alt="McQueen Zine" />

---

<h2 id="credits">Credits</h2>

This project uses:

<ul>
  <li><a href="https://www.kicad.org/">KiCad</a> for PCB design</li>
  <li><a href="https://www.blender.org/">Blender</a> for renders</li>
  <li><a href="https://www.onshape.com/">Onshape</a> for CAD</li>
  <li><a href="https://www.figma.com/">Figma</a> for the project zine</li>
</ul>

---

<h2>License</h2>

GPL-3.0
```
