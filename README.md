# Adaptive Mesh Refinement (Pseudo 2D)

* Version: OpenFOAM® 6.x
* License: GPL v3
* Original Author: Tobias Holzmann
* Email: Tobias[dot]Holzmann[at]Holzmann-cfd[dot]de
* Date:04 November 2017

## Adaptive Mesh Refinement (Pseudo 2D)

This example provides an automatic mesh refinement tutorial in a pseudo 2D case. The mesh is refined during the simulation due to the value of the passive scalar S. Pseude 2D means that OpenFOAM does not provide a 2D arbitrary mesh refinement library. The refinement supports only 3D refinement. A new library to the OpenFOAM Foundation repository which supports 2D refinement is under development and discussion.

This case was orinally created for OpenFOAM version 5.x and was updated to OpenFOAM 6.x by Tom van den Brink