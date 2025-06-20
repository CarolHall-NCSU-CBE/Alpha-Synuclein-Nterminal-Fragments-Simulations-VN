# Alpha-Synuclein-Nterminal-Fragments-Simulations-VN

This repository contains the data, Fortran codes, and Excel spreadsheets associated with the manuscript:  
**"In silico peptide self-assembly reveals the importance of N-terminal motifs and the inhibition mechanism of the mutation L38M in α-synuclein fibrillation"** (Nguyen et al.), submitted to *Protein Science*.

---

## Requirements & Installation

- Analysis codes are written in **Fortran** and can be compiled using the **Intel Fortran compiler** (`ifort` or `ifx`).
- Peptide structure and trajectory files can be visualized using **VMD (Visual Molecular Dynamics)**.
- All data files are in plain text format and can be opened with standard analysis tools.
- Simulation movies are in standard video formats compatible with most media players.

---

## Repository Contents

### `/movies/`
Contains five simulation movies of:
- P1-WT
- P2 (S- and U-shaped β-sheets)
- P3-WT
- P3Next-WT

---

### `/pdbfiles/`
- Final peptide coordinates in **PDB** format
- Visualizable with VMD

---

### `/trajectories/`
- Trajectories from all simulations
- **Note:** Must be loaded with their corresponding PDB files in VMD to properly visualize aggregation

---

### `/energyfiles/`
- Energy profiles tracking changes over simulation time
- Files are plain text and compatible with tools like Excel, MATLAB, Python, etc.

---

### `/VMD-SecondaryStructures/`
- VMD-exported secondary structure files
- Fortran source code used to calculate β-hairpins and β-strands

---

### `/spreadsheets/`
- Three Excel spreadsheets used for generating:
  - **Figure 3c**
  - **Figure 5b**
  - **Figure 6b**  
  from the manuscript

---

### `/parallel_antiparallel/`
- Results from **PRIME20** analysis code
- Uses **DSSP** method to calculate number of parallel and antiparallel residues

---
