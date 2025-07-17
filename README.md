# Functional_Scenic_in_2025

Having trouble with Scenic in 2025? I've isolated dependencies and input structure to get this working in 3 simple commands, on both Windows and Linux (HPC) command line interfaces (CLIs).

This code assumes that you have processed your data and have an expression_matrix in loom format (for now).

Resources are located at:
https://resources.aertslab.org/cistarget/

GRNBoost2 requires arboreto_with_multiprocessing.py script to circumvent pyscenic incompatibilities.

The CTX/AUC Environment state works for grnboost2 on Linux, haven't gone back and tested Windows yet. - July 17, 2025
