# Task 2: Multiple Sequence Alignment
### Cross-Species Comparison of the Insulin Protein Family

## Description
This task applied Multiple Sequence Alignment (MSA) to the insulin protein family using five reviewed sequences from different vertebrate species (human, cattle, dog, pig, and chicken). The goal was to identify conserved regions (essential to insulin's biological function) versus variable regions (reflecting evolutionary divergence).

## Methodology
- Retrieved five reviewed (Swiss-Prot) insulin sequences from UniProt in FASTA format, covering four mammalian species and one bird species
- Combined the sequences into a single input file
- Submitted the file to Clustal Omega (EMBL-EBI) using default alignment parameters
- Reviewed the alignment in both plain-text and colour-coded formats, along with the generated guide tree

## Tools/Technologies Used
- UniProt (UniProtKB)
- Clustal Omega (EMBL-EBI Job Dispatcher)

## Results
- A long, highly conserved stretch was found at the start of the sequence (signal peptide and B-chain region), marked by near-continuous conservation across all five species
- The linker region joining the B-chain and A-chain (roughly positions 60–107) showed much greater variation, including gaps in cattle and chicken sequences
- Conservation rose again toward the A-chain region, which — together with the B-chain — forms the mature, functional insulin molecule
- The guide tree showed chicken as the most evolutionarily diverged sequence, consistent with the earlier split between birds and mammals
- Full details, figures, and alignment outputs are available in the attached report (Task2_Bioinformatics_Insulin_MSA_Report.pdf)

## Conclusion
The alignment confirmed that functionally essential regions of insulin (B-chain and A-chain) are strongly conserved across species, while the non-functional linker region — removed during hormone maturation — shows far greater variability. This demonstrates how MSA connects sequence-level conservation patterns to biological function.
