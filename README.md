# Simulation Code for "Direct Laser Cooling of a Symmetric Top Molecule" by Mitra et al.
This is a repository for the code associated with simulating optical Bloch equations in the scientific paper "Direct Laser Cooling of a Symmetric Top Molecule" (specifically, Fig. S6 in Supplemental Text). 

Details of the simulation as well as references can be found in the main text. There are two types of files in this repository:

1. Mathematica notebooks to calculate force profiles. These have prefixes "ForceProfiles_CaOCH3_J32...".
2. Mathematica notebooks that incorporate the computed laser cooling force profiles into a simulation of the molecular beam trajectory in the experimental setup. These have prefixes "TrajectoryMonteCarlo_CaOCH3...".

Each file has a suffix to denote which of the subplots, A, B, or C, of Fig. S5 they are associated with (namely, "DetuningScan", "IntensityScan_Cooling", "IntensityScan_Heating", and "BFieldScan").
