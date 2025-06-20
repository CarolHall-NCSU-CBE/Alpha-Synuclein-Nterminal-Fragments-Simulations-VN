# Alpha-Synuclein-Nterminal-Fragments-Simulations-VN
This repository contains the data, Fortran codes, and excel spreadsheets associated with the paper "In silico peptide self-assembly reveals the importance of 
N-terminal motifs and the inhibition mechanism of the mutation L38M in α-synuclein fibrillation" (Nguyen et al.), submitted to Protein Science.
# Requirement and Installation
The analysis codes are in Fortran that can be run using Intel Fortran ifort/ifx compiler. The coordinate files of the peptides can be visualized using VMD (Visual Molecular Dynamics). All of provided data are in text file format that can be access with any analysis tools. The movies are compatible with major video players.
# Data for paper
/movies/ - This directory contains five movies as examples of our simulations of peptide P1-WT, P2 (S- and U-shape beta-sheets), P3-WT, and P3Next-WT.
Besides the compelet movies, we also provide final PDB files and the trajectories from all simulations to generate movies using VMD.

/pdbfiles/ - This diretory contains final coordinates of the peptides in each simulations. PDB files can be visualized using VMD.

/trajectories/ - This directory contains trajectories from all simulations. The trajectories cannot be read individially but can be loaded with corresponding PDB files to VMD for visualizing aggregation process.

/energyfiles/ - This directory contains energy profiles of each simulations. The profiles recorded energy changes as time evovled. The files are in text format and can be open by any popular data analysis tools. 

/VMD-SecondaryStructures/ - This directory contains the secondary structure files exported from VMD as well as the Fortran code that was used for the calculation of beta-hairpins and beta-strand.

/spreadsheets/ - This directory contains the 3 excel spreadsheets that were used to calculate and plot Figure 3c, 5b and 6b in our paper.

/parallel_antiparallel/ - This directory contains the results from using our PRIME20 analysis code that applied DSSP method to calculate the numnber of parallel and antiparallel residues in a system. 
