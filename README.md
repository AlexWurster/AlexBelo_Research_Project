# AlexBelo_Research_Project
This is the repository for the code used to query and analyse the data in my research project.

<ins> Research Project: </ins>

The goal of this project is to find if the total number of side chain rotatable bonds in a protein is a good parameter to evaluate protein designs stability.

This was performed in several steps:

- Create a function to count the number of rotatable bonds in a protein with their amino acid sequence as input (**Creating_Function.ipynb** file)

- Accessing the [DE-STRESS](https://academic.oup.com/peds/article/doi/10.1093/protein/gzab029/6462357) database, importing several evaluating parameters of protein stability, and compare them to the number of rotatable bonds. (**Access_DE-STRESS.ipynb** file)

- Accessing the [CATH](https://www.cathdb.info/) database, importing information about protein families and structural homology, and analyse relations between the number of rotatable bonds and specific protein structures. (**Access_CATH.ipynb** file)

- Accessing the [PDB](https://www.rcsb.org/) database, importing information about the source organism of the proteins, and analyse the relation between the number of rotatable bonds and the specific protein source organism. (**Access_PDB.ipynb** file)

- Accessing the [files](https://www.science.org/doi/10.1126/science.aan0693) involving protein stability for *de novo* designed protein models, importing information about the stability for each protein peptide chain, and analyse the relation between the number of rotatable bonds and the stability of the designs.(**Acces_Proteinstability.ipynb** file)

- All the analysis for each dataset was performed and save in file: **Data_Analysis.ipynb**

- The outcome graphs from the data analysis where saved in file: **Data_Figures.pdf**
