# Leeman Geophysical SMT Soldering Challenge

<div style="text-align:center;">
  <img src="../product.png" alt="Instrument cover photo." style="height:400px">
</div>

### Required Equipment
<ul>
  <li>Soldering Iron</li>
  <li>Solder</li>
  <li>Tweezers</li>
  <li>Safety glasses</li>
  <li>Optional: Flux</li>
  <li>Optional: Microscope (recommended)</li>
</ul>

### Kit Components
<ol>
  <li>x1 - Challenge Printed Circuit Board (PCB)</li>
  <li>x1 - (R1) 1206 150ohm Resistor</li>
  <li>x1 - (R2) 0805 150ohm Resistor</li>
  <li>x1 - (R3) 0603 150ohm Resistor</li>
  <li>x1 - (R4) 0402 150ohm Resistor</li>
  <li>x1 - (D1) 1206 Green LED</li>
  <li>x1 - (D2) 0805 Green LED</li>
  <li>x1 - (D3) 0603 Green LED</li>
  <li>x1 - (D4) 0402 Green LED</li>
</ol>

<div>
  <img src="../ToC.png" alt="Table of Contents" style="height:400px" />
</div>

### Safety Considerations
<ul>
  <li>Assembling this kit requires the use of hot tools and small components.</li>
  <li>Wear safety glasses when assembling this kit.</li>
  <li>This kit and the solder you are using may contain lead. Wash hands thoroughly after assembling and do not eat or drink while working or handling kit materials.</li>
  <li>Always ensure your work area is clean and safe. Never leave a hot or sharp instrument unattended.</li>
</ul>

## Before you Begin
Using the kit contents checklist, lay out and inventory your kit. Make sure you have all parts before beginning. This kit contains only surface mount technology (SMT) components that will be soldered by hand.

## What is SMT?
SMT (Surface Mount Technology) is a type of component mounting and soldering method used in modern high-volume circuit production. It differs from TH (through-hole) soldering, which you may be more accustomed to, in that the component does not pass through the PCB via wire leads. Instead, it sits on top of copper pads and is held in place and electrically connected through solder.<br>

In production, finely ground solder mixed with flux is formed into a paste and screen-printed onto the board so that every exposed pad is covered. Components are then placed onto these pads either by hand or via an automated pick-and-place machine. Once all components are loosely positioned, the board is passed through a multi-stage reflow oven where the flux is activated and cleans the electrical connections, followed by melting of the solder paste, which bonds the components to the board both mechanically and electrically once cooled.<br>

Although this process is typically automated, SMT soldering can also be done by hand using standard solder and a soldering iron. This is often required for repairing electronics and replacing components.

## Basic Guide for Hand-Soldering SMT Components
<ol>
  <li>Before starting any SMT hand soldering work, thoroughly clean the tip of your iron to remove any debris or old solder.<br>
  <b>Tip:</b><br>
  Good lighting and magnification can make SMT soldering significantly easier, especially when working with 0603 and smaller components.
  </li>


  <li>With a clean iron tip, melt a small amount of solder onto one pad. Do this quickly to avoid burning off all of the flux from inside the solder. If the tinned pad appears spiky or dull, apply some more flux and reflow the pad again until shiny and round.
    <div>
    <img src="../example1.jpg" style="height:200px" />
    <img src="../example1a.jpg" style="height:200px" />
    </div>
  </li>

  <li>With tweezers, hold the LED or resistor in position just behind the tinned pad. Carefully melt and slide the component into position so that the tinned pad bonds to the edge of the component and the pad, tacking it into place. Adding more flux before doing so will make this process more forgiving.
    <div>
    <img src="../example2.jpg" style="height:200px" />
    <img src="../example2a.jpg" style="height:200px" />
    <img src="../example2c.jpg" style="height:200px" />
    </div>
  </li>

  <li>Now that the component is tacked in place on one side, gently apply a moderate amount of solder and heat to the other side of the component. Once the joint is properly soldered, you can touch up the first side with a small amount of fresh solder if needed.<br>
  <b>Tip:</b><br>
  If you accidentally create a solder bridge, apply additional flux and use a clean iron tip to pull the excess solder away from the connection.
    <div>
    <img src="../example3.jpg" style="height:200px" />
    <img src="../example3a.jpg" style="height:200px" />
    </div>
  </li>
</ol>

## Challenge Board Assembly Guide
Using the techniques shown in the basic guide, we challenge you to see how small you can go! This challenge PCB is designed to start off easy and progressively become more difficult. SMT resistors and LEDs come in standard sizes ranging from the hobby-friendly 2512 package (0.25") down to the incredibly small 0201 package (0.02"), commonly found in modern smartphones and other compact electronics.<br>

Although SMT packages are available in both larger and smaller sizes, for this challenge you will start with 1206 components and work your way down to 0402. After completing each resistor/LED pair, we encourage you to apply 3.3V and Ground to the PCB to check your work. If everything has been soldered correctly, a bright green LED will illuminate, indicating that size has been completed successfully. <b>ALWAYS</b> remove power before continuing to the next size.<br>

<b>Important Details:</b><br>

Each resistor in the kit is labeled with an R followed by its package size, and each LED is labeled with a D followed by its package size. Start with the largest components and work your way down. While resistors are non-polar and can be installed in either orientation, LEDs are polarized. Each LED has a small green mark indicating the cathode, which should align with the silkscreen line on the PCB footprint.<br>

Start with 1206 and work your way down. Good luck!

## Revision History
<table>
  <tr bgcolor="gray">
    <td><b>Date</b></td>
    <td><b>Changes</b></td>
  </tr>

  <tr>
    <td>June 2026</td>
    <td>Initial Release</td>
  </tr> 
</table>