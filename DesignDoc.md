# GWAS Workshop Project Design Document
Aaron Juco, Yusef Golzar, Rumyr Sobrepena, and Evelyn Umana

# Overview 

# References 

# Context 

# Goals
- To revamp the existing GWAS Workshop repository to become more user-friendly by:

    - Use the newer and denser SNP genotypes (Genome Build: hg38)

    - Teaching the user RStudio and PLINK2 functions by guiding them through phenotype change stories with LUWolf

    - Updated demos of PLINK2 file formats (map/pd, bed/bim/fam, and pgen/pvar/psam)

    - Freshly formatted Github wiki with step-by-step screenshots, which will include locuszoom directions and interpretation


# Non-Goals 

-To not make it specific towards any IDE

-To not diverge too far from the simplicity in the original tutorial


# Proposed Solution 

# Workflow 

![GWAS Workflow Diagram](https://github.com/user-attachments/assets/ee51b652-24f6-48c6-b875-5add208d3cd6)

1. Update Data Files
   a. 	Convert genotype data to a denser SNP set (hg38)
   b. 	Create new phenotype files that align with new story
   c. 	Instructing users on how to check the data they are running.
2. Modernize the GWAS Analysis Pipeline
   a. 	Replace outdated tools with PLINK2 to support .pgen, .pvar, and .psam format.
3. Improve Documentation
   a. 	Move instructions from .Rmd/.html files to a structured Github Wiki.
   b. 	Include step by step guide for Windows and Mac users with screenshots
4. Improve Data Visualization and Interpretation
   a. 	Provide a LocusZoom tutorial for regional association plots.
   b. 	Generate Manhattan and QQ plots for GWAS results.
5. Complete Problem Set With New Data
    a. Make new answer key. 


# Importance of Tasks 

#  Milestones 

<img width="724" alt="Screen Shot 2025-03-18 at 9 47 18 AM" src="https://github.com/user-attachments/assets/23c95180-31a0-41ca-8fec-81b253c21d91" />
