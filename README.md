# GWAS-Assignment

This project performs a Genome-Wide Association Study (GWAS) using the Genome Association and Prediction Integrated Tool (GAPIT) and a Memory-efficient, Visualization-enhanced, and Parallel-accelerated tool (rMVP) to find associations between identified genes and particular diseases (or traits). These studies search for single nucleotide polymorphisms (SNPs) through an entire genome of an organism. Running the following two scripts requires the installation of R/RStudio. 

1. GAPIT

To run the script, __GAPIT__, requires the package 'devtools' to be installed in the R library. To properly run the script, it is prerequisite to import the data file and change the working directory. The script is divided into five analyses. The first analysis (__analysis1__) uses the Mixed Linear Model (MLM) in which the data is not compressed. The second analysis (__analysis2__) applies compression of the data by grouping in 10; this follows the Compressed Mixed Linear Model (CMLM). The third analysis (__analysis3__) uses a kinship clustering method that groups data into kinships. The fourth (__analysis4__) and fifth analyses (__analysis5__) implement the Multiple Locus Mixed Linear Model (MLMM) and the Fixed and random model Circulating Probability Unification (FarmCPU) respectively. The results for each analysis get placed in a directory created by the script. The results obtained in each analysis is a heat map of a kinship matrix, a density R square, a principal component analysis (PCA) and its eigenvalues.

2. rMVP

The script, __rMVP__, installs the rMVP package. The working directory must be changed for the user. The data used is the same data file used in the GAPIT analysis. The script takes the data and evaluates the population structure and estimates the variance components. Quantile-Quantile plot (QQ plot), Manhattan plots, SNP density plot, PCA and Phenotype distribution are produced as visual representation of the results.
