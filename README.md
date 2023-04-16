# iberus_printer
a 3D printer designed to avoid shortcomings I've observed on the most popular kit 3D printers

Very much a work in progress, everything will change as I improve the design and reach optimized implementations of all the ideas I wish to put in this machine.

General design intentions:
- XYZ gantry referenced to a single reference piece (laser-cut 4mm aluminum plate with stacked stiffeners where needed)
  - Similar to E3D's toolchanger motion system but the Z axis is also referenced to the same plane.
- All the print bed should be entirely reachable by the nozzle easily
  - After configuring a Railcore II at work, I was very disappointed that the printhead would collide with the frame or the Z axis if we tried to use the full advertised 300x300mm print area.
- Reuse existing major components from other kit 3D printer when possible
  - Examples: Railcore bed, Voron Trident integrated leadscrew steppers, bed kinematic coupling
- Precision achieved by not being overconstrained
  - Examples: Y carriage fixed on left side but slotted on right side, bed kinematic coupling
- Electonics not mounted on the bottom of the printer
  - A heavy machine like a 3D printer should not need to flipped on its side to do maintenance

Note on the "iberus" name: it's a genus of land snails that have a flat shell. I thought it matched the overall design of having everything referenced to a flat top.
