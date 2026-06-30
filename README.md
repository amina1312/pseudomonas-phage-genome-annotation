# pseudomonas-phage-genome-annotation
Genome annotation of a Pseudomonas bacteriophage using PHASTER and RASTtk
# Pseudomonas Phage LUZ19 — Genome Annotation

## Overview
Independent bioinformatics project to annotate the genome of 
*Pseudomonas* bacteriophage LUZ19 using two complementary 
annotation platforms: PHASTER and RASTtk.

## Genome
- **Phage:** Pseudomonas phage LUZ19
- **Host:** *Pseudomonas aeruginosa*
- **Source:** NCBI Nucleotide database
- **Genome type:** Linear double-stranded DNA

## Tools Used
- **PHASTER** (phaster.ca) — prophage identification and 
  lifestyle prediction
- **RASTtk** (rast.nmpdr.org) — functional genome annotation 
  and gene calling

## Key Findings
- **60 predicted coding sequences (PEGs)** identified by RASTtk
- **No prophage or lysogenic elements detected** by PHASTER, 
  consistent with LUZ19's confirmed obligately lytic lifestyle
- Results support LUZ19 as a candidate for phage therapy 
  applications targeting *P. aeruginosa*

## Files
- `Original FASTA file.fasta` — raw genome sequence (NCBI)
- `PHASTEST result (PNG).png ` — PHASTER annotation output
- `RAST GenBank file.gbk` — RASTtk GenBank annotation file
- `RAST Excel spreadsheet.xls` — RASTtk feature table with functional 
  assignments

## Background
This project was completed as an independent skills development 
exercise following an MSc thesis on phage therapy against 
biofilm-forming *Pseudomonas aeruginosa*. Bioinformatics 
analysis complements prior wetlab work in phage isolation, 
biofilm inhibition assays, and phage-antibiotic synergy testing.
