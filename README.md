# Gal3 Binding Analysis Project - [Protein Science Journal Article](https://doi.org/10.1002/pro.70143)
A place to store initial structure and parameter files for the simulations used in the Galectin-3 paper published May 2025 in Protein Science.

**Contents** 
All inputs are included for the 5 ligand/inhibitors. The bound replicates are kept in 3 separate directories alongside a directory for the free molecule in water. Within replicate 1 the "equilibration" directory contains the files for the longer dynamics trajectories that were generated between smaller binding free energy windows. 

All files are original inputs except for the .dyn files within the "Step" folders are the final coordinates/velocites. To restart a thermodynamic "Step" the .dyn file will need to be replaced with the .dyn located a directory back.

**Parameters:** 
All poltype output parameter sets were combined with amoebabio18.prm which includes water parameters

**Trajectory files stored on Zenodo:** 
[Natural Ligand Trajectories and BAR Data 10.1039/D4CC04415K](https://zenodo.org/records/15318911)
[Synthetic Inhibitor Trajectories and BAR Data 10.1039/D4CC04415K](https://zenodo.org/records/15320202)

