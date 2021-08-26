# Protein-antibody-interactions-in-SARS-CoV-2-Molecular-Visualization-and-Informatics
**Team:** Alexa Salsbury, Diya Dinesh, Kaitlin Abrantes, Wenyu Zeng, Anne-Sophie Fratzscher
## What is our problem?
The Covid-19 pandemic is a global health problem that has affected every facet of our lives. While the effects are evident, the science behind its cause can be inaccessible and lead to misconceptions. Additionally, people can be overwhelmed by the information that is available.

## What is our solution?
The **Website COVID-19 Variants:Structure and Effects on Human Health** aims to present information in a tangible way with structural visualizations. This allows users to engage with the material and help them understand how structure relates to function. 

## Methods

[CHARMM-GUI](https://www.charmm-gui.org/) was used to create structure files herein. The starting coordinates were taken from PDB Code 6vxx. PDB Manipulator was used to model missing residues in the system (residues -18-26 and 1148-1262) and to mimic point mutations in our delta (d6vxx.pdb) and gamma (g6vxx.pdb) structures. The mutations made were: 

Delta - T19R, V70F, T95I, G142D, R158G, A222V, W258L, K417N, L452R, T478K, D614G, P681R, D950N

Gamma- L18F, T20N, P26S, D138Y, R190S, K417T, E484K, N501Y, D614G, H655Y, T1027I

We acknowledge that the multiple substitutions made and modeling missing residues could generate implausible conformations in the spike protein. To mitigate these issues, energy minimization was carried out in CHARMM. We performed 500 steps of steepest descent minimization and 500 steps of adopted-basis Newton-Raphson minimization.

[iCn3D](https://www.ncbi.nlm.nih.gov/Structure/icn3d/full.html) (pronounced as "I see in 3D") is a web-based 3D visualization tool for protein structures that we used to map amino acid interactions. Users are able to load images using popular IDs, such as PDB ID and MMDB ID, or load images from local files. For this project, we start with PDB code 6VXX, apply mutation points L452R, (K417N*), and D614G for Delta variant, and K417T, N501Y, and D614G for Gamma variant. L452R is selected because it is one of the top 3 highest mutation concerns for Delta variant, similar reason for selecting K417T and N501Y for Gamma variants. D614G is selected because it appears in both variants. 

After making the mutations, a comparison between the original and mutated protein structure and 2D interaction networks are created for each mutation points. The results are shown in the Delta and Gamma variant pages, respectively. 

[Website Construction](https://www.w3schools.com/html/)
To package the information in an accessible and interactive manner, we created a website using HTML. The website includes the use of 3D images for interaction, alternating structure of text and images for ease of navigation, highlighted headings to draw reader attention, and (i.e. learn more and back to the top) buttons for ease of navigation.

## Ongoing Improvements
1) Finding a less performance exhausting way to display the 3D model
2) Make website layout suitable for all screens, browsers, and computers. 
