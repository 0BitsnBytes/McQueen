
<h1 align="center">
  <img src="YOUR_LOGO_URL" width="220">
  <br>
  McQueen
</h1>

<p align="center">
  High-current electronics, race-inspired suspension, and four drone motors packed into a fully custom AWD platform.
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#specifications">Specifications</a> •
  <a href="#links">Links</a> •
  <a href="#esc">ESC</a> •
  <a href="#chassis">Chassis</a> •
  <a href="#build-guide">Build Guide</a> •
  <a href="#zine">Zine</a> •
  <a href="#credits">Credits</a>
</p>

<img src="YOUR_BANNER_URL">

<br>

<h2 id="overview">Overview</h2>

McQueen is an all-wheel-drive RC car powered by four drone hub motors and a fully custom motor controller.

The project combines:

<ul>
  <li>High-current power electronics</li>
  <li>Custom ESC firmware</li>
  <li>Double wishbone suspension</li>
  <li>Aerodynamic bodywork</li>
  <li>Custom CAD and manufacturing workflows</li>
</ul>

Unlike traditional RC platforms, McQueen was designed from the ground up around performance, manufacturability, and learning.

<hr>

<h2 id="specifications">Specifications</h2>

<table>
<tr>
<td><b>Drive System</b></td>
<td>AWD</td>
</tr>

<tr>
<td><b>Motors</b></td>
<td>4× Drone Hub Motors</td>
</tr>

<tr>
<td><b>Battery</b></td>
<td>2× 6S LiPo</td>
</tr>

<tr>
<td><b>ESC</b></td>
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
<td><b>Chassis</b></td>
<td>Fully Custom 3D Printed Design</td>
</tr>

<tr>
<td><b>Braking</b></td>
<td>Electronic Dynamic Braking</td>
</tr>
</table>

<hr>

<h2 id="links">Links</h2>

<table>
<tr>
<td><b>Onshape CAD</b></td>
<td>
<a href="https://cad.onshape.com/documents/fc565ca3851146bee43ab660/w/08fa01b8b529e8822f765509/e/27cf93230e8926e0ab4158b0?renderMode=0&uiState=6a2ad1b4ef163228e83211c1">
View Assembly
</a>
</td>
</tr>

<tr>
<td><b>KiCad Project</b></td>
<td>
<a href="ADD_KICAD_LINK_HERE">
PCB Files
</a>
</td>
</tr>

<tr>
<td><b>BOM</b></td>
<td>
<a href="ADD_BOM_LINK">
Bill of Materials
</a>
</td>
</tr>

<tr>
<td><b>Firmware</b></td>
<td>
<a href="ADD_FIRMWARE_LINK">
Source Code
</a>
</td>
</tr>
</table>

<hr>

<h2 id="esc">Custom ESC</h2>

The drivetrain is powered by a custom ESC designed specifically for high-current drone motors.

<h3>Features</h3>

<ul>
<li>STM32F411CEU6 MCU</li>
<li>IR21084 Gate Driver</li>
<li>AS5600 Position Sensor Input</li>
<li>Current Sensing</li>
<li>MOSFET Temperature Monitoring</li>
<li>RGB Debug LED</li>
<li>TVS Protection</li>
<li>Electronic Braking</li>
</ul>

<h3>Schematic</h3>

<img src="YOUR_SCHEMATIC_IMAGE">

<h3>PCB Layers</h3>

<img src="LAYER1_IMAGE">
<img src="LAYER2_IMAGE">
<img src="LAYER3_IMAGE">
<img src="LAYER4_IMAGE">
<img src="LAYER5_IMAGE">
<img src="LAYER6_IMAGE">

<h3>Board Views</h3>

<img src="FRONT_RENDER">
<img src="BACK_RENDER">

<hr>

<h2 id="chassis">Chassis</h2>

The chassis was designed around suspension kinematics, packaging constraints, and aerodynamic performance.

<h3>Suspension</h3>

<img src="SUSPENSION_IMAGE">

<h3>Aerodynamics</h3>

<img src="AERO_IMAGE">

<hr>

<h2 id="build-guide">Build Guide</h2>

<h3>ESC</h3>

<ol>
<li>Manufacture PCB using provided Gerbers.</li>
<li>Select 2oz copper.</li>
<li>Populate components according to BOM.</li>
<li>Flash firmware to STM32.</li>
</ol>

<h3>Chassis</h3>

<ol>
<li>Print all STL files.</li>
<li>Acquire hardware from BOM.</li>
<li>Assemble according to Onshape assembly.</li>
<li>Install electronics.</li>
<li>Verify steering and suspension movement.</li>
</ol>

<hr>

<h2 id="zine">Zine</h2>

<img src="YOUR_ZINE_IMAGE">

<hr>

<h2 id="credits">Credits</h2>

<ul>
<li>KiCad — PCB Design</li>
<li>Onshape — CAD</li>
<li>Blender — Rendering</li>
<li>Figma — Documentation & Zine</li>
</ul>

<hr>

<h2>License</h2>

GPL-3.0

