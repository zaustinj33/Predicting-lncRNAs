# lncRNA-locations-Python
Prediction of lncRNAs in FASTA sequence files. Based on ORF prediction and length of ORF


Uses Python3 in Jupyter Notebook (Linux)


Credit: Zac Johnson, Alaina Werbernerfenefdsf, Liang Jiang, Xiaolin. 

ALS5224 Group 1 Fall 2018

Steps: 
- 0.1 Setup file directories and path variable names 
- 0.2 Convert GTF and Raw sequence file to FASTA sequence file
- 1 Convert Sequence file to ORF nucleotide file
- 2 Convert ORF file to Protein ORF file
- 3 Find lncRNAs by metric: >200nt, <100aa, or no ORF
- 4 Sort lncRNAs by size & <100, find longest lncRNA <100 amino acids


