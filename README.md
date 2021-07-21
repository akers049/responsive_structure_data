# responsive_structure_data
This repository contains the .vtu and .vtk files of the converged responsive structures.

For the 2D structures in "rectangular_actuation_work/*" "rectangular_blocking_load/*", the .vtk files have a 
variable "phi" denoting the density variable that determines responsive (1) or passive material (0).

For the 2D structures with voids in "rectangular_blocking_load_with_voids/*", the .vtk files have two
density variables "phi_1" and "phi_2". These determine solid or void and responsive or passive material, respectivly. 
The variable "phi" is used for plotting purposes and is simply phi_1*(1 + phi_2),so values of 0 are void, 1 are passive solid, and 2 are responve solid.

The 3D structures in "torsional_*/*" are saved as .vtu files, and contain the save variables as described in the previous paragraph.
