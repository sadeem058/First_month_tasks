# Servo Mount / Bracket Design
![servoo.stl]( https://cad.onshape.com/documents/47b90e8b9b30aeae85d9cbd0/w/55404adffd032e70682d5f98/e/c9ef950c02eee2a5e3d4d93b )
This repository contains a 3D CAD design for a servo mounting bracket, created with consideration for servo fitting constraints such as screw alignment and charger clearance.

## Design Steps

- On the Top Plane, a rectangle with dimensions (40.3 × 27.1) was created.
- The sketch was extruded in two directions (right and left) by 10.5.
- Front and back ledges were added using:
  - The same cover length
  - A width of 7.168
- A center connection was added for measurement reference only.
- On each ledge:
  - Two holes with a diameter of Ø 4.25 were created.
  - Each hole was positioned 4.3 mm away from the center connection.
- Bottom ledges were added with:
  - A width of 7.566
  - The same cover length
  - A fillet applied to smooth the edges.
- A new sketch was created to add two holes identical to the top holes.
- The cover color was changed to grass green.
- After completing the model, servo fitting constraints were reviewed:
  - Top screw locations
  - Bottom charger clearance
- A full rectangular section was removed to provide sufficient space for the charger.

## Files

- servoo.stl – Final 3D model ready for 3D printing or further modification.

## Notes

This design prioritizes proper clearance, accurate alignment, and ease of assembly for servo integration.
