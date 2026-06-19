# Variant Calling Pipeline

This project implements a germline variant calling pipeline 
following GATK Best Practices on NA12878 (HG001) WES data 
from NCBI SRA (SRR1518253).

## Tools Used
- FastQC, Trimmomatic, BWA-MEM
- GATK HaplotypeCaller
- ANNOVAR (ClinVar, gnomAD, dbSNP)
- Python + ReportLab (Clinical PDF Report)

## Results
- 62,817 high-confidence variants detected
- 47 Pathogenic / Likely Pathogenic variants identified
- Key genes: BRCA1, TP53, MLH1, BRCA2, CFTR, PTEN

## Report
Full analysis and results are documented in the project 
report (PDF) included in this repository.
