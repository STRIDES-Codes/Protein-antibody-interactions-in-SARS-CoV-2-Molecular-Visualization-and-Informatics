# Protein-antibody-interactions-in-SARS-CoV-2-Molecular-Visualization-and-Informatics
**Team:** Alexa Salsbury, Diya Dinesh, Kaitlin Abrantes, Wenyu Zeng, Anne-Sophie Fratzscher
## What is our problem?
The Covid-19 pandemic is a global health problem that has affected every facet of our lives. While the effects are evident, the science behind its cause can be inaccessible and lead to misconceptions. Additionally, people can be overwhelmed by the information that is available.

## What is our solution?
The **Website COVID-19 Variants:Structure and Effects on Human Health** aims to present information in a tangible way with structural visualizations. This allows users to engage with the material and help them understand how structure relates to function. 

## Methods
Generating Structure files:

CHARMM-GUI was used to create structure files herein. The starting coordinates were taken from PDB Code 6vxx. PDB Manipulator was used to model missing residues in the system (residues -18-26 and 1148-1262) and to mimic point mutations in our delta (d6vxx.pdb) and gamma (g6vxx.pdb) structures. The mutations made were: 

Delta - T19R, V70F, T95I, G142D, R158G, A222V, W258L, K417N, L452R, T478K, D614G, P681R, D950N
Gamma- L18F, T20N, P26S, D138Y, R190S, K417T, E484K, N501Y, D614G, H655Y, T1027I

We acknowledge that the multiple substitutions made and modeling missing residues could generate implausible conformations in the spike protein. To mitigate these issues, energy minimization was carried out in CHARMM. We performed 500 steps of steepest descent minimization and 500 steps of adopted-basis Newton-Raphson minimization.

Mapping AA interactions

iCN3D - 3D visualization tool to find interactions between protein structures. (Wenyu is responsible for filling in these methods)

Website Construction


Diya is responsible for filling in these methods. Should we deposit this code in repository?

## Forthcoming Features

## References
[1] 	https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7337391/#S3
[2] 	
[3] 	
[4] 	
[5] 	
[6]
[7]
