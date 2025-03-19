# GWAS Workshop Project Design Document
Aaron Juco, Yusef Golzar, Rumyr Sobrepena, and Evelyn Umana

# Overview 
Genome Wide Association Studies (GWAS) are studies that are extremely important in helping scientists identify what genes are associated with certain phenotypes. They have become more widely used in the past ten years as the technology has improved and become more popular. The method uses Single Nucleotide Polymorphisms (SNPs), which are small variations in the genome, as the variable being studied. Researchers gather the genomes of a large group of subjects, then identify SNPs that occur more frequently in the genomes of people with the desired phenotype. GWAS is extremely efficient in that it can observe hundreds of thousands of SNPs at the same time. Once SNPs identified with certain diseases have been identified, this information can be used to help determine an individual's likelihood of developing a disease. GWAS has also been used to assess what an individual's response to a drug may be (Medline Genetics). An important statistic in GWAS is Linkage Disequilibrium (LD), which can be used to pre-screen the genome and select SNPs for genotyping. Linkage disequilibrium simply refers to how often two alleles are observed together within a population (Pritchard and Przeworski). 

# References 

# Context 
We were presented with a 10+ year old tutorial that trains new students from Dr. Wheeler’s lab to use GWAS research methods essential for her lab. Genome-wide association studies (GWAS) is a fundamental tool in genetics. It allows researchers to identify genetic variants associated with traits or diseases. Conducting GWAS correctly requires an updated workflow, proper data formats, and modernized tools to ensure reproducible results. The current GWAS workshop in Dr. Wheeler’s lab has not been updated in over 10+ years and relies on older SNP genotypes and an old version of software. To modernize and improve the GWAS workshop we are going to update the genotype data, use PLINK2, improve documentation, and add demos on PCA plots. Many students enter Dr. Wheeler’s lab with limited computational experience. By structuring the GWAS workshop as a guided tutorial we can ensure that students can conduct GWAS effectively. By updating the genotype data, analysis tool, documentation, and visualization pipeline we will create a structured and effective training resource for students.

# Goals
- To revamp the existing GWAS Workshop repository to become more user-friendly by:

    - Use the newer and denser SNP genotypes (Genome Build: hg38)

    - Teaching the user RStudio and PLINK2 functions by guiding them through phenotype change stories with LUWolf

    - Updated demos of PLINK2 file formats (map/pd, bed/bim/fam, and pgen/pvar/psam)

    - Freshly formatted Github wiki with step-by-step screenshots, which will include locuszoom directions and interpretation
 
    - Add demo for PCA plots. 


# Non-Goals 

- To not make it specific towards any IDE

- To not diverge too far from the simplicity in the original tutorial


# Proposed Solution 

# Workflow 

![GWAS Workflow Diagram](https://github.com/user-attachments/assets/ee51b652-24f6-48c6-b875-5add208d3cd6)

1. Update Data Files
- Convert genotype data to a denser SNP set (hg38)
- Create new phenotype files that align with new story
- Instructing users on how to check the data they are running.
2. Modernize the GWAS Analysis Pipeline
- Replace outdated tools with PLINK2 to support .pgen, .pvar, and .psam format.
3. Improve Documentation
- Move instructions from .Rmd/.html files to a structured Github Wiki.
- Include step by step guide for Windows and Mac users with screenshots
4. Improve Data Visualization and Interpretation
- Provide a LocusZoom tutorial for regional association plots.
- Generate Manhattan and QQ plots for GWAS results.
5. Complete Problem Set With New Data
- Make new answer key. 


# Importance of Tasks 

1. Preparing data to ensure genotyping accuracy by filtering low quality SNPS, removing genotyping errors, low MAF variants, and deviations from Hardy-Weinberg equilibrium.
2. Run GWAS analysis and get results for downstream interpretation and train users in using PLINK2.
3. Update documentation and Github Wiki so that future users can quickly understand how to run the tools.
4. Visualize plots to make results more interpretable.

#  Milestones 

<img width="724" alt="Screen Shot 2025-03-18 at 9 47 18 AM" src="https://github.com/user-attachments/assets/23c95180-31a0-41ca-8fec-81b253c21d91" />
