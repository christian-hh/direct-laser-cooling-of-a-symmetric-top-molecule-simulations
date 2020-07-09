### Simulation code for "Direct Laser Cooling of a Symmetric Top Molecule" by Mitra et al.
This is a repository for the code associated with simulating optical Bloch equations in the scientific paper "Direct Laser Cooling of a Symmetric Top Molecule" (specifically, Fig. S6 in Supplemental Text). The arXiv version of the paper can be found at https://arxiv.org/pdf/2004.02848.pdf (Fig. 4 in this version).

Details of the simulation and references can be found in the main text. There are two types of files in this repository:

1. Mathematica notebooks (.nb files) to calculate force profiles. These have prefixes "ForceProfiles_J32toJ12_...".
2. Mathematica notebooks (.nb files) that incorporate the computed laser cooling force profiles into a simulation of the molecular beam trajectory in the experimental setup. These have prefixes "TrajectoryMonteCarlo_...".

Each file has a suffix to denote which of the subplots (A, B, or C) of Fig. S6 they are associated with, namely, "DetuningScan", "IntensityScan_Cooling", "IntensityScan_Heating", and "BFieldScan".
