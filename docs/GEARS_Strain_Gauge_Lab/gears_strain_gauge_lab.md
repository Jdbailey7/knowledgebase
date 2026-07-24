# GEARS Strain Gauge Lab Guide

<div style="text-align:center;">
  <img src="../product.png" alt="Instrument cover photo." style="height:400px">
</div>

### Required Equipment/Materials

<ul>
  <li>Superglue</li>
  <li>Scotch Tape</li>
  <li>Scalpels</li>
  <li>Prep/Cutting Plates</li>
  <li>Tweezers</li>
  <li>Calipers</li>
  <li>99% Alcohol</li>
  <li>Soldering Iron and Solder</li>
  <li>Q-Tips</li>
  <li>Weight Kit</li>
  <li>Gloves</li>
  <li>Wire Strippers/Cutters</li>
  <li>Scotch-Brite</li>
  <li>Small Screwdrivers</li>
  <li>Multimeters</li>
  <li>USB Microscope/Magnifier</li>
</ul>

### Kit Components

<ul>
  <li>3D Printed Fixture</li>
  <li>4” Aluminum Test Coupon</li>
  <li>2 Strain Gauges</li>
  <li>3 Pieces of Silicone Hookup Wire (8” each)</li>
  <li>Zip Tie</li>
  <li>4×4 Clean Room Wipe</li>
  <li>Solder Bow Ties ×4</li>
</ul>

<div>
  <img src="../contents.jpg" alt="Table of Contents" style="height:400px" />
</div>

### Safety Considerations

<ul>
  <li>Assembling this kit requires the use of hot and sharp tools.</li>
  <li>This kit and the solder you are using may contain lead. Wash hands thoroughly after assembling, and do not eat while working or ingest any kit materials.</li>
  <li>Always ensure your work area is clean and safe. Never leave a hot or sharp instrument unattended.</li>
</ul>

## Assembly

### Surface Preparation

Set your calipers to 1" and make a score line across the aluminum test coupon on both sides.

<div style="display: flex; gap: 10px;">
  <img src="../step1a.jpg" alt="Step 1A"
       style="width: 50%; height: auto; object-fit: contain;" />
  <img src="../step1b.jpg" alt="Step 1B"
       style="width: 50%; height: auto; object-fit: contain;" />
</div>

Now, just below that line, thoroughly abrade the surface on both sides with Scotch-Brite. Then wipe the surface clean with the included wipe and 99% alcohol.

### Strain Gauge Application

Tear off a roughly 1/2-inch strip of Scotch tape. With a single strain gauge lying flat on the table, use the tape to press over the gauge and peel it up. The tape will be used to position and secure the gauge before gluing.

Position the gauge as close to centered as possible, with its top edge aligned to the score mark. Begin with the concave side of the coupon. Complete the gluing process for that gauge before repeating the procedure on the flat side.

<div style="display: flex; gap: 10px;">
  <img src="../step2a.jpg" alt="Step 2A"
       style="width: 50%; height: auto; object-fit: contain;" />
  <img src="../step2b.jpg" alt="Step 2B"
       style="width: 50%; height: auto; object-fit: contain;" />
</div>

Once the desired position has been achieved, press the tape down firmly before gently peeling up one side again to expose the bottom of the gauge. Place a very small drop of super glue onto the metal where the gauge will sit, then fold the gauge back down into place and press firmly for 2–3 minutes.

**NOTE:** Wear gloves during this step to avoid gluing your fingers to the sample.

Once the first gauge has dried, repeat the process with the second gauge on the flat side of the test coupon.

<div style="display: flex; gap: 10px;">
  <img src="../step3a.jpg" alt="Step 3a"
       style="width: 50%; height: auto; object-fit: contain;" />
  <img src="../step3b.jpg" alt="Step 3b"
       style="width: 50%; height: auto; object-fit: contain;" />
</div>

<div style="display: flex; gap: 10px;">
  <img src="../step3d.jpg" alt="Step 3d"
       style="width: 50%; height: auto; object-fit: contain;" />
  <img src="../step3c.jpg" alt="Step 3c"
       style="width: 50%; height: auto; object-fit: contain;" />
</div>

### Wiring

Once both gauges are fully cured, take the two pairs of bowtie-shaped solder pads and remove the paper from the back side to expose the adhesive. Place one just below each of the strain gauges so the end of the leads overlaps one half of the bowtie, then solder each lead into place on both sides of the coupon.

<div style="display: flex; gap: 10px;">
  <img src="../step4a.jpg" alt="Step 4a"
       style="width: 50%; height: auto; object-fit: contain;" />
  <img src="../step4b.jpg" alt="Step 4b"
       style="width: 50%; height: auto; object-fit: contain;" />
</div>

Next, you will wire the strain gauges into a voltage divider configuration.

<div>
  <img src="../diagram.png" alt="Voltage divider diagram" style="height:400px" />
</div>

Take one color from your three 8-inch wire lengths and cut off roughly two inches. Strip one end of the cut piece and one end of the remaining six-inch section, then twist them together.

<div style="display: flex; gap: 10px;">
  <img src="../step5a.jpg" alt="Step 5a"
       style="width: 50%; height: auto; object-fit: contain;" />
  <img src="../step5b.jpg" alt="Step 5b"
       style="width: 50%; height: auto; object-fit: contain;" />
</div>

Solder that pair to the right pad on the flat side of the unit. Using a second wire color, solder the full-length wire to the left pad. Take the other end of the two-inch wire length, strip it, and wrap it around to the other side to be soldered to a pad on the second gauge. The final full-length wire can be soldered to the remaining pad.

<div style="display: flex; gap: 10px;">
  <img src="../step5c.jpg" alt="Step 5c"
       style="width: 50%; height: auto; object-fit: contain;" />
  <img src="../step5d.jpg" alt="Step 5d"
       style="width: 50%; height: auto; object-fit: contain;" />
</div>

### Final Assembly

Route all wires so they exit from the flat side, then secure them with the included zip tie to provide strain relief.

<div>
  <img src="../step6.jpg" alt="Step 6" style="height:400px" />
</div>

Slide the completed load sensor assembly into the provided 3D-printed base.

<div>
  <img src="../step7.jpg" alt="Step 7" style="height:400px" />
</div>

As a final preparation step before use, trim all the wires to the same length and strip roughly half an inch of insulation from each one.

<div>
  <img src="../step8.jpg" alt="Step 8" style="height:400px" />
</div>

### Hookup
This setup uses two strain gauges configured as a voltage divider. With one end connected to 5V, the other to GND, and no load applied to the bar, the output voltage should be approximately 2.5 V. When the bar bends, one strain gauge is placed in tension, increasing its resistance, while the other is placed in compression, decreasing its resistance. These opposing resistance changes alter the voltage divider ratio, causing the output voltage to vary in proportion to the applied load.
<div>
  <img src="../strain_gauge_diagram.png" alt="Schematic" style="height:400px" />
</div>
<table>
  <thead>
    <tr>
      <th>Lead</th>
      <th>Connection</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>V Supply</td>
      <td>5 V</td>
    </tr>
    <tr>
      <td>Ground</td>
      <td>GND</td>
    </tr>
    <tr>
      <td>Signal Output</td>
      <td>AIN0</td>
    </tr>
  </tbody>
</table>

## Revision History
<table>

  <tr bgcolor="gray">
    <td><b>Date</b></td>
    <td><b>Changes</b></td>
  </tr>

  <tr>
    <td>July 2026</td>
    <td>Initial Release</td>
  </tr>

</table>