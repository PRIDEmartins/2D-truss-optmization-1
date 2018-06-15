# 2D-truss-optmization-1
Code for sizing optimization of 2D trusserd structures subjected to external and self-weight load (2018)

This code perfoms size optimization of 2D truss. Variables are the cross-section areas. Constraints are the minimum and maximum admissible stresses.

The "Main Code" is the only the needed to produce the results of this project. Open it with MATLAB and run it. The sizing optimization of the cross-section areas of a 1240-elements truss will be automatically performed.

Finite Element Code: constaints the representation of the structure in finite-element 
PP: is the post-processing code. Is must be called using "PP(x)" in the MATLAB terminal.
Stiffness: builds 4x4 global-coordinate stiffness matrix for 2D bar elements.
ObjFun: the mass of the structure, the function that is minimized in the process.
