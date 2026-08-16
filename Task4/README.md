# Task 4: Applications of Machine Learning in Bioinformatics
### A Mini-Project Report

## Description
This task is a survey-style mini-project exploring how machine learning (ML) is applied across major areas of bioinformatics, using AlphaFold as a landmark case study, and discussing the benefits and limitations of ML-driven approaches in biological research.

## Topics Covered
- **What ML brings to bioinformatics**: supervised learning, unsupervised learning, and deep learning, and where each is used
- **Key application areas**: sequence analysis, protein structure prediction, genomics/variant calling, cancer genomics, drug discovery, medical imaging, and single-cell biology
- **Case study — AlphaFold**: how it combines deep learning with evolutionary information from multiple sequence alignments to predict protein structure, connecting directly to the sequence conservation (Task 2) and structure prediction (Task 3) work done earlier in this internship
- **Worked example**: a simplified walkthrough of how a sequence-based classifier (e.g. splice-site prediction) is built — data collection, feature representation, model training, and validation
- **Benefits and limitations**: speed/scale and pattern discovery vs. data dependency, interpretability ("black box" models), and the importance of confidence metrics
- **Future outlook**: foundation models, multi-omics integration, and growing focus on interpretability and uncertainty quantification

## Tools/References
- Literature review based on AlphaFold (Jumper et al., 2021, *Nature*) and related deep learning genomics research
- AlphaFold Protein Structure Database, Protein Data Bank (PDB)

## Conclusion
Machine learning has become a central part of the bioinformatics toolkit, spanning sequence analysis, structure prediction, genomics, drug discovery, and imaging. AlphaFold demonstrates that patterns conserved across biological data — whether identified manually via BLAST and MSA (Tasks 1–2) or learned automatically by a neural network — tend to encode real functional and structural importance, reinforcing the connection between classical bioinformatics methods and modern ML-driven approaches.
