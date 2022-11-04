# Channel_network-mesh
This repository contains the initial mesh file for the numerical example: "Example 4: Flow through a 2D porous media with channel network" of the work entitled "A posteriori error analysis of a Banach spaces-based fully mixed FEM for double-diffusive convection in a fluid-saturated porous medium".


To load the mesh in FreeFem++, use the code:

mesh Th = readmesh("Channel_network-mesh.msh");
