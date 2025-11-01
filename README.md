# Transcriptomic and Variant Analysis of the APOE Gene
## Integrative RNA-Seq and Variant Analysis Pipeline in R, Python, and Bash

This project integrates RNA-Seq differential expression and variant calling to study the role of the Apolipoprotein E (APOE) gene in neurodegeneration.
Using publicly available human brain RNA-Seq and WGS data, I quantify APOE expression, identify key allelic variants (ε2, ε3, ε4), and explore enriched biological pathways related to Alzheimer’s disease.

### Objective
1. Quantify APOE gene expression in human brain tissue.
2. Detect functional variants (SNPs / indels) within the APOE locus.
3. Perform pathway enrichment to contextualize APOE’s role in neurodegenerative processes.

### Biological Background
1. APOE encodes apolipoprotein E, essential for lipid transport and neuronal repair.
2. The ε4 allele (Cys→Arg at rs429358) increases Alzheimer’s risk; ε2 appears protective.
3. Investigating both expression and variants can uncover multi-omic insights into APOE-driven pathology.

### Disease Design
| Condition     | Example SRR IDs       | Purpose             |
| ------------- | --------------------- | ------------------- |
| Alzheimer’s   | SRR1215813–SRR1215822 | disease group       |
| Old Control   | SRR1215823–SRR1215833 | age-matched control |
| Young Control | SRR1215834–SRR1215843 | baseline            |
