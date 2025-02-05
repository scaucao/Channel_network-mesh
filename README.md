# Channel_network-mesh
This repository contains the initial mesh file for the numerical example: "Example 4: Flow through a 2D porous media with channel network" of the work:

S. Caucao, G.N. Gatica, and J.P. Ortega: A posteriori error analysis of a Banach spaces-based fully mixed FEM for double-diffusive convection in a fluid-saturated porous medium. Computational Geosciences, vol. 27, 2, pp. 289-316, (2023).  

Available in DOI: <a href="https://doi.org/10.1007/s10596-023-10195-5" target="_blank">10.1007/s10596-023-10195-5</a>


To load the mesh in FreeFEM, use the code:

mesh Th = readmesh("Channel_network-mesh.msh");


Labels setting:

33: region outside the channel

34: region inside the channel

71: bottom boundary

72, 82: right boundary

73, 83: top boundary

74, 84: left boundary
