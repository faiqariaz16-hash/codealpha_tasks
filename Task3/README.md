# Task 3: Protein Structure Prediction
### AlphaFold-Predicted 3D Structure of Human Insulin

## Description
This task used AlphaFold to examine the predicted three-dimensional structure of human insulin (UniProt: P01308), building on the sequence-level analysis from Tasks 1 and 2. The aim was to visualize the predicted 3D structure, interpret AlphaFold's per-residue confidence scores, and relate the structural features to insulin's known biology.

## Methodology
- Searched UniProt accession P01308 (human insulin) in the AlphaFold Protein Structure Database
- Filtered results to "Monomers" to isolate the standalone AlphaFold model (AF-P01308-F1)
- Used the interactive 3D structure viewer to inspect the model from multiple angles
- Reviewed the per-residue confidence (pLDDT) colouring and the Predicted Aligned Error (PAE) plot to assess model reliability

## Tools/Technologies Used
- AlphaFold Protein Structure Database (Google DeepMind / EMBL-EBI)
- UniProt (UniProtKB)

## Results
- The model (Average pLDDT 52.91, Low) showed two short alpha-helices — one high-confidence segment corresponding to part of the B-chain, and lower-confidence helical segments corresponding to the A-chain — connected by a long, largely unstructured coil representing the C-peptide
- The PAE plot showed a tight, confident diagonal band for the B-chain and A-chain regions, while the C-peptide region showed low positional confidence
- Full details, figures, and the PAE plot are available in the attached report (Task3_Bioinformatics_Insulin_Structure_Report.pdf)

## Conclusion
The low overall confidence score correctly reflects the intrinsically disordered nature of the C-peptide in the unprocessed insulin precursor, rather than indicating a poor prediction. The B-chain and A-chain — which form the compact, functional mature hormone — were predicted with higher confidence, reinforcing at the structural level the same B-chain/A-chain versus C-peptide distinction observed through sequence conservation in Task 2.
