# GWAS-Assignment

This project performs a Genome-Wide Association Study (GWAS) using the Genome Association and Prediction Integrated Tool (GAPIT) and a Memory-efficient, Visualization-enhanced, and Parallel-accelerated tool (rMVP) to finds associations between identified genes and particular diseases (or trait). This type of studies searches for single nucleotide polymorphisms (SNPs) through an entire genome of an organism. Runing the following two scipts requires the installation of R/RStudio. 

1. GAPIT

To run the script, it requires the package 'devtools' to be installed in the R library. Another requirement is to import the data file. The script is set up in five analyses. The first analysis uses the Mixed Linear Model (MLM) where there is no compression of the data. The second analysis applies a compression of the data; this follows the Compressed Mixed Linear Model (CMLM). The third analysis uses a kinship clusting method that groups data into kinships. The fourth and fifth analyses implements the Multiple Locus Mixed Linear Model (MLMM) and the Fixed and random model Circulating Probability Unification (FarmCPU) respectively. Each 
