Difference in Turn-on Voltage:
The ideal diode is simplified to turn on at ~0.5–0.6V.
The 1N4148 turns on gradually starting around ~0.3–0.5V due to real semiconductor physics (built-in potential, temperature, doping, current level).

Difference in Current Behavior:
Ideal diode we usually talk about: It has zero current below turn-on, infinite current above (vertical I-V line).
Ideal diode in the comparison: It requires higher turn-on voltage, so it has lower current then the real one.
1N4148: It has exponential current rise when the voltage is larger than turn-on voltage, and has resistance at high current.

Why Ideal Models Are Still Used:
They simplify hand calculations, initial circuit design, and understanding of circuit functionality without complex maths. 
It can be useful for teaching, quick sketches, and large-scale simulations where precision isn’t needed.

When Ideal Models Become Inaccurate:
Low-voltage circuits (near 0.6V), high-precision analog design (log amplifiers, sensors), power circuits (losses, heating), high-frequency/RF applications (junction capacitance matters) 
and temperature-sensitive designs.
