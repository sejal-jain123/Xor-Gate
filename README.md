# Xor-Gate

This project involves designing an XOR gate in Cadence Virtuoso, followed by creating a cellview for better visualization. The XOR gate, or exclusive OR gate, outputs a high signal (1) only when the inputs are different. Below is a breakdown of the design steps, including the schematic, layout, and simulation.

--> Schematic Design
In the schematic design phase, I used transistors to build the XOR gate. The key idea behind an XOR gate is that the output is high when one, and only one, of the inputs is high.

Components Used: NMOS and PMOS transistors.
Logic: The gate’s behavior was achieved by implementing the logic equation A ⊕ B = (A AND NOT B) OR (NOT A AND B).

--> Cellview Creation
To facilitate future design work and make the XOR gate easier to integrate, I created a cellview for the XOR gate.

Purpose: The cellview enables easy reuse in larger systems and provides an intuitive visual understanding of the XOR gate.
Hierarchy: This XOR gate cellview can be instantiated into more complex circuits, such as adders or multipliers.

--> Simulation
To ensure the design works correctly, I simulated the XOR gate. The simulations confirmed the expected functionality, where the output is high only when the inputs differ.

DC Analysis: Verified the voltage levels across different input conditions.
Transient Analysis: Checked the timing and behavior during switching events.