# Gene Expression Analysis using PCA and Sparse PCA

This project involves the analysis of gene expression data using Principal Component Analysis (PCA) and Sparse PCA to uncover low-dimensional structures and patterns associated with different cancer types. Through visualizations and statistical summaries, we aim to determine whether PCA and Sparse PCA reveal different low-dimensional structures for gene expressions across various cancer types.
## Project Structure
# Analysis of Gene Expression Data
1. Data Preprocessing
- Removed missing values.
- Identified and filtered out highly correlated features.
  
2. PCA and Sparse PCA Application
- Applied PCA and Sparse PCA to uncover low-dimensional structures and patterns in the gene expression data.
- Created visualizations to provide insights into the variability and clustering of gene expressions across different cancer types.
  
# Comparing PCA and Sparse PCA
PCA captures the overall variance in the data, providing a broad view of the gene expression landscape.
Sparse PCA emphasizes specific components with higher sparsity, potentially highlighting more informative features relevant to cancer types.
Differences in the low-dimensional representations were observed, with Sparse PCA offering a more focused approach for identifying key genes or pathways relevant to specific cancer phenotypes.

# Uses

- Identification of Key Genes: Sparse PCA has highlighted specific genes that contribute significantly to the variation in gene expression across different cancer types. These key genes can be studied further to understand their roles in cancer progression and used as biomarkers for early detection and prognosis.

- Cancer Classification: The low-dimensional representations from PCA and Sparse PCA revealed distinct clusters corresponding to different cancer types. This clustering can enhance cancer classification, helping clinicians to accurately diagnose the type of cancer a patient has, which is crucial for determining the most effective treatment plan.

- Personalized Treatment: By identifying the principal components and specific genes associated with various cancers, this project provides a foundation for personalized medicine. Oncologists can use this information to develop treatment plans tailored to the genetic profile of an individual's tumor, potentially improving the efficacy of treatments and minimizing side effects.

- Targeted Drug Development: The genes and pathways identified as significant through Sparse PCA can serve as targets for new drug development. Pharmaceutical companies can focus their efforts on these targets to create drugs that specifically address the genetic abnormalities found in different cancers, leading to more effective and less toxic treatments.

- Research Prioritization: The insights gained from this project can guide future research efforts by highlighting the most promising genes and pathways for further investigation. This prioritization can help allocate research funding and resources more efficiently, accelerating the discovery of novel cancer therapies and improving our overall understanding of cancer biology.

# NOTES:

The csv files used were too large for Github. You can download the dataset  the data set “TCGA-PANCAN-HiSeq-801x20531.tar.gz” from the website https: //archive.ics.uci.edu/ml/machine-learning-databases/00401
