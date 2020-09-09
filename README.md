# Pancreatic Adenocarcinoma
Pancreatic Adenocarcinoma (PAAD) is the third most common cause of death from cancer, with an overall 5-year survival rate of less than 5%, and is predicted to become the second leading cause of cancer mortality in the United States by 2030.

Here we had a dataset of normalized RNA Sequencing reads for pancreatic cancer tumors. The measurement consists of ~20,000 genes for 185
pancreatic cancer tumors.

### Data cleaning and check the distribution of gene expression across samples
* Read data from GCT file, a tab-delimited file used for sharing gene expression data and metadata (details for each sample) for samples.
* Remove genes with NaNs
* Generate gene expression distribution for all samples.

### Identifying the Exocrine(adenocarcinoma) tumors and remove Neuroendocrine tumors
* Visualize the data whole data using PCA and analyze the variance of PCA
* Analyse the general behavior of the different samples
* Remove the neuroendocrine tumors from the dataset so that it contains only the adenocarcinoma tumor samples

### Understand the effect of Interferons in Pancreatic Adenocarcinoma and Unsupervised analysis
* Plot the gene expression values for these genes for pancreatic adenocarcinoma
* Unsupervised clustering on the gene expression data

### Refferences 
[EDA on Titanic dataset](https://www.kaggle.com/harshkothari21/100-accurate-results-with-eda-all-ml-models)

[Dimensionality Reduction](https://www.kaggle.com/shivangi03/data-visualisations-dimensionality-reduction)

[Unsupervised Clustering Algorithms](https://www.kaggle.com/fazilbtopal/popular-unsupervised-clustering-algorithms)

*If Github shows an error while loading the notebook please view it on nbviewer by Jupyter [here](https://nbviewer.jupyter.org/github/Erikishiru/PancreaticAdenocarcinomaAnalysis/blob/master/notebook.ipynb)*
