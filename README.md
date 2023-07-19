# Agon light ORIGINS edition™

For software and firmware, plus related instructions, please go to the <a href="https://github.com/breakintoprogram/agon-docs/wiki">Agon Wiki</a> or visit the <a href="https://www.facebook.com/groups/agoncomputer">developers' group</a>. 

![IMG_0489 Background Removed small](https://github.com/TheByteAttic/AgonORIGINS/assets/69539226/ce5cd024-0671-4303-9a74-fef4bcb837c0)

Agon light ORIGINS edition™ is a new board revision of the earlier <a href="https://github.com/TheByteAttic/AgonLight">Agon light™</a>. It is 100% backward compatible and does not entail extra capabilities. The idea behind it is to create a cleaner, more optimal, premium design that excels in signal integrity and robustness; this thing will work stably even under quite adverse environmental conditions. And it looks great too!<br><br>
At the same time, this ORIGINS edition of Agon light™ deliberately preserves some of the quirks of the original design, such as a large USB socket for power and firmware programming, a real PS/2 connector for the keyboard, a linear through-hole LDO regulator, and two through-hole electrolytic capacitors.<br><br>
These are the improvements with respect to the original Agon light™:
<UL>
  <LI>Highly optimized routing, significantly reducing the number of VIA hopings and trace length;</LI>
  <LI>Optimized layer stack, with GND copper fill on top (the original had Vcc fill on top for heat dissipation, but that wasn't needed);</LI>
  <LI>Larger and less stitching VIAs;</LI>
  <LI>In-line resistor bank (33Ω) on the data bus to absorb reflections;</LI>
  <LI>USB-B power/firmware upload connector (instead of the non-standard USB-A of the earlier revision);</LI>
  <LI>Shrouded control port connector (eliminating the need for TVS diodes).</LI>
</UL>
You can use the Gerber files in this repository to make or order your own boards. You can then choose board thickness, finish and solder mask as you wish. In the photos in this repository, I have used 1 mm total board thickness (to maximize the distributed capacitance created by the inner Vcc and GND planes), gold finish (1 Oz), 1 Oz metal thickness in all four layers, and black solder mask.
<br><br>
Copyright © 2023 by Bernardo Kastrup. All rights reserved. <a href="https://github.com/TheByteAttic/AgonORIGINS/blob/main/LICENSE">License conditions</a> apply.
