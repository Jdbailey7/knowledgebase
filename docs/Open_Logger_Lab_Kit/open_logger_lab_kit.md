# Open Logger Lab Kit Assembly Guide

<div style="text-align:center;">
  <img src="../product.png" alt="Instrument cover photo." style="height:400px">
</div>

### Required Equipment
<ul>
  <li>Soldering Iron</li>
  <li>Solder</li>
  <li>Flush cutters</li>
  <li>Safety glasses</li>
</ul>

### Kit Components
<ol>
  <li>x1 - Circuit Board Assembly (PCB) w/ SMT Components</li>
  <li>x1 - CR2032 Battery Holder</li>
  <li>x1 - ESP32 Dev Kit PCBA</li>
  <li>x2 - 19 Position Female Header (2.45mm)</li>
  <li>x1 - Green LED</li>
  <li>x1 - 5V DC-DC Converter</li>
  <li>x1 - MCP7940 Real Time Clock (RTC)</li>
  <li>x2 - Automotive Fuse Clip</li>
  <li>x1 - 1A Automotive Fuse</li>
  <li>x1 - Reverse Polarity (RP) Protection Diode</li>
  <li>x6 - 2 Position Terminal Block</li>
  <li>x1 - 10k Thermistor (B = 3950k)</li>
</ol>

<div>
  <img src="../ToC.png" alt="Table of Contents" style="height:400px" />
</div>

### Safety Considerations
<ul>
  <li>Assembling this kit requires the use of hot and sharp tools.</li>
  <li>Wear safety glasses when assembling this kit. Clipped leads can shoot away quickly and cause eye injury.</li>
  <li>This kit and the solder you are using may contain lead. Wash hands thoroughly after assembling and do not eat or drink while working or handling kit materials.</li>
  <li>Always ensure your work area is clean and safe. Never leave a hot or sharp instrument unattended.</li>
</ul>

## Before you Begin
Using the kit contents checklist, lay out and inventory your kit. Make sure you have all parts before beginning. This kit contains only through-hole components that will be soldered by hand.

For a quick refresher on the basics of through-hole soldering, see our [Introduction to Through-Hole Soldering](https://leemangeophysical.com/introduction-to-through-hole-soldering/) guide.

## Assembly 
<ol>
  <li>To begin this project, locate the CR2032 Battery Clip. Place the component in the correct position so that the square-notched end aligns with the matching shape on the PCB silkscreen. While holding the component in place, flip the board over and solder each pin in place.
  <img src="../cr2032_ibom.png">
  <!-- Add example photos -->
  </li> 
  
  <li>Locate the green LED. This component is polarized like the CR2032 battery, so orientation is important. Notice that one wire lead is shorter than the other. This shorter lead is called the cathode and is also identified by a small flat edge on the side of the LED.  
  Place the LED in the Power LED position so that the short lead and flat edge align with the flat edge and square pad of the silkscreen circle. Once positioned, flip the board over and solder the two connections.<br>
  NOTE: It can be helpful to bend the leads in opposite directions to hold the LED in place before soldering.
  <img src="../green_led_ibom.png">
  <!-- Add example photos -->
  </li>

  <li>The next component is a DC-DC converter that steps the incoming 12V supply down to a regulated 5V to power most of the components on the logger. Place the converter into the PCB and solder its three connections.<br>
  Ensure that the outline of the component aligns with the silkscreen rectangle to avoid installing it backwards.
  <img src="../dcdc_converter_ibom.png">
  <!-- Add example photos -->
  </li>

  <li>Diodes are polarized components, so orientation is important. The cathode is identified by a thin ring around one end of the diode's body.  
  Bend the leads into a U-shape and place the diode into the RP Diode position. Ensure that the ring on the diode aligns with the matching line marked on the PCB footprint.
  <img src="../rp_diode_ibom.png">
  <!-- Add example photos -->
  </li>

  <li>The thermistor is a temperature-sensitive resistor. Like a standard resistor, it is non-polar and can be installed in either orientation.<br>
  Place it into the PCB as you did with the diode, then solder it into place.
  <img src="../thermistor_ibom.png">
  <!-- Add example photos -->
  </li>

  <li>Next, solder the two automotive fuse clips onto the PCB. Each clip forms one half of the full fuse holder assembly.<br>
  To ensure proper alignment and help protect your hands from heat conducted through the metal clips, first slide each clip onto the legs of a 1A automotive fuse. This is a non-polar component, so orientation does not matter.<br>
  Insert the assembled clips into the four PCB holes as a unit, hold them in place, then flip the board over and solder them as straight as possible.
  <img src="../autofuse_clip_ibom.png">
  <!-- Add example photos -->
  </li>

  <li>Let’s add the 2-position terminal blocks. Ensure the wire entry openings on each block face outward from the PCB edge.<br>
  Hold each terminal block in place and solder them one at a time.
  <img src="../terminals_ibom.png">
  <!-- Add example photos -->
  </li>

  <li>Let’s step up the challenge! Next, you'll solder an 8-pin RTC (Real-Time Clock) integrated circuit. This package style is very common, and its pins are numbered 1 through 8. To ensure proper installation, both the chip and the PCB include markings that indicate the location of Pin 1.<br>
  On the top of the chip, look for a small dot near one of the corners. This dot marks Pin 1. Align this mark with the small semicircle shown on the PCB silkscreen, then place the chip into position.<br>
  While holding the chip in place, carefully flip the PCB over and solder all eight pins.
  <img src="../rtc_ibom.png">
  <!-- Add example photos -->
  </li>

  <li>For our final component, you will add the 38-pin microcontroller. For this, we will use female headers to allow the ESP32 Dev Kit to be easily removed and replaced.<br>
  As with the fuse assembly, slide each 19-pin header onto the corresponding row of pins on the Dev Kit. Once both headers are attached, place the entire assembly into the PCB, ensuring the USB port aligns with the edge of the board.<br>
  Hold it in place, flip the board over, and solder all 38 pins.
  <img src="../esp32_ibom.png">
  <!-- Add example photos -->
  </li>
</ol>

The Open Field Logger Kit is now complete. Take a moment to inspect each solder joint.<br>
For each joint, the following should be true:
<ul>
  <li>The pad is fully covered with no exposed copper</li>
  <li>Smooth, cone-like shape</li>
  <li>Even shine (not dull in color)</li>
  <li>No solder connecting adjacent joints (solder bridges)</li>
</ul>
<img src="../solder_joint.png">

## Documentation
<ul>
  <li><a href="../schematic.pdf">Schematic</a></li>
  <li><a href="../layout.pdf">Layout</a></li>
</ul>
