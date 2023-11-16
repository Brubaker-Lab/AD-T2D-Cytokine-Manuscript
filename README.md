# AD-T2D-Cytokine-Manuscript

The R Markdown file in this repository analyzes the observed cytokine concentrations collected from the Luminex assay. 
The required CSV file to run the code is also made available in this repository.

The data set is pre-processed and log2 normalizes each measurement with the respective vehicles.

Contained in the R Markdown file contains code that generates the following figures
1) Heatmap of the different metabolites with the quantified cytokines
2) Principal Component Analysis (PCA) results
3) Mann-Whitney and Kruskal-Wallis statistical tests
4) Partial Least Squares Discriminant Analysis (PLS-DA) for three different models. (Four-way, AD only, and T2D only)
