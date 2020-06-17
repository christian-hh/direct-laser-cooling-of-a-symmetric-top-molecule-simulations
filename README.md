# Simulation Code for "Direct Laser Cooling of a Symmetric Top Molecule" by Mitra et al. (Science, 2020)
This is a repository for the code associated with simulating optical Bloch equations in the scientific paper "Direct Laser Cooling of a Symmetric Top Molecule" (specifically, Fig. S5 in Supplemental Text). 

Details of the simulation as well as references may be found in the main text.

There are two types of files:

1. Mathematica notebooks to calculate force profiles. These have prefixes "ForceProfiles_CaOCH3_J12..." or "ForceProfiles_CaOCH3_J32..." for each ground state considered (J = 1/2 and J = 3/2). 
2. Mathematica notebooks that incorporate the computed laser cooling force profiles into a simulation of the molecular beam trajectory in the experimental setup. These have prefixes "TrajectoryMonteCarlo_CaOCH3...".

Each file has a suffix to denote which of the subplots, A, B, or C, of Fig. S5 they are associated with (namely, "DetuningScan", "IntensityScan", and "BFieldScan").
