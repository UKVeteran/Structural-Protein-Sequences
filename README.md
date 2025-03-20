# ⚓ Structural Protein Sequences Project ⚓

Link To The Kaggle Dataset: <a href="https://www.kaggle.com/datasets/shahir/protein-data-set">The Dataset</a>

![proteinstructureseq](https://github.com/user-attachments/assets/45cc88d5-b43d-4039-9e02-5c308dcdd719)


# Overview

This dataset contains protein information sourced from the Research Collaboratory for Structural Bioinformatics (RCSB) Protein Data Bank (PDB).

The PDB archive serves as a comprehensive repository of atomic coordinates and related data that describe the structures of proteins and other essential biological macromolecules. Structural biologists employ techniques like X-ray crystallography, NMR spectroscopy, and cryo-electron microscopy to map the positions of atoms within these molecules. Once determined, this structural information is submitted to the archive, where it is annotated and made publicly accessible by the Worldwide Protein Data Bank (wwPDB).

As the PDB continues to expand, it reflects the ongoing advancements in laboratories worldwide. While this growth offers exciting opportunities for research and education, it can also present challenges. The extensive database contains numerous variations of molecular structures, including multiple representations of the same molecule, partial structures, and modified or inactive forms. Navigating this wealth of information requires careful selection to ensure the data best suits your research needs.

# Content

There are two data files. Both are arranged on "structureId" of the protein:

## File 1
pdb_data_no_dups.csv contains protein meta data which includes details on protein classification, extraction methods, etc.

## File 2
data_seq.csv contains >400,000 protein structure sequences.


# Aim
Create an automated classification system that predicts protein categories by analyzing structural and experimental variables. This system will streamline protein screening, accelerating the discovery of candidate proteins for novel drugs and therapeutic solutions.

# Benefits
1) Reduction in Time and Cost of Drug Discovery: By automating protein classification, researchers can focus on proteins with the highest potential for specific treatments, saving time and resources.

2) Increased Precision in Candidate Selection: With an accurate classification model, it’s possible to identify proteins that share structural characteristics with disease target proteins, improving the precision of viable proteins for laboratory testing.

3) Scalable Application to Broaden Scientific Knowledge: The model allows the categorization of large volumes of protein data, contributing to new insights on unexplored proteins and promoting advancements in biotechnology and healthcare.

# EDA
![ProteinClasses](https://github.com/user-attachments/assets/4019c815-4478-49af-9c94-c1eee7d8ed90)

![Macromolecule Type](https://github.com/user-attachments/assets/d76077e2-5033-4076-921b-043c6607bd64)

![Histos](https://github.com/user-attachments/assets/dc903ac6-65ac-473d-a11c-943751088fb1)

![DistributionofClassifications](https://github.com/user-attachments/assets/962dddc6-7eae-40f6-99f4-06da527c97c4)

![Publication Trends of Protein Structures Over Time](https://github.com/user-attachments/assets/75d51c49-c7e8-427d-abf6-c5a62b714e2f)

