# Task 1: DNA/Protein Sequence Analysis
### BLAST-Based Homology Study of Human Insulin

## Description
This task involved retrieving the human insulin protein sequence (isoform 2 precursor, NCBI Accession: NP_001035835.1) from the NCBI Protein database and performing a BLASTP (Basic Local Alignment Search Tool) analysis to identify homologous sequences across other species. The goal was to study the evolutionary conservation of insulin across the animal kingdom.

## Methodology
- Retrieved the human insulin amino acid sequence in FASTA format from NCBI
- Ran a Protein BLAST (blastp) search against the ClusteredNR database
- Recorded key metrics (Percent Identity, E-value, Query Coverage, Alignment Score) for top-scoring hits across multiple species

## Tools/Technologies Used
- NCBI Protein Database
- NCBI BLASTP (blast.ncbi.nlm.nih.gov)

## Results
- BLAST returned significant hits (E-values ranging from 2e-140 to 7e-21) spanning primates, other placental mammals, birds, reptiles, and a distantly related bacterial protein
- Identity was highest in primates (e.g., gelada, 84.26%), moderate in other placental mammals (60–80%), and low in non-mammalian species (~30%)
- Full details, figures, and tables are available in the attached report (Task1_Bioinformatics.pdf)

## Conclusion
The analysis confirmed that insulin is a highly conserved protein among mammals, with identity decreasing progressively in more distantly related species — demonstrating the practical workflow of sequence retrieval and BLAST-based homology searching.
