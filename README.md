# Data Information Quality Project - Comune di Milano Pubblici Esercizi

Project of the course Data and Information Quality

- Each group is assigned a different dirty dataset.
- A complete Data Preparation Pipeline on the assigned dataset must be executed with the following steps:

  1. Data Profiling and Data Quality Assessment
  2. Data Cleaning
     - Data Transformation/Standardization (bringing everything to the same format, detecting and correcting typos, performing wrangling operations, etc.)
     - Error Detection and Correction (dealing with missing values and the detection and correction of potential outliers)
     - Data Deduplication (detecting and handling non-exact duplicates)
  3. Data Analysis [only for 3-people groups]

     - Choose the type of analysis (classification-regression-clustering):

       i. Choose one column as the target column (categorical = classification OR numerical = regression)

       OR

       ii. Perform unsupervised clustering analysis

     - Perform a data analysis pipeline on (1) the dirty dataset and (2) the cleaned dataset (model selection, training and testing)
     - Compare the results using the right performance metrics (Precision, Recall, F1, etc. [Classification], MSE, RMSE, etc. [Regression], Silhouette, etc. [Clustering])

N.B. Some of the assigned datasets are not specifically made for machine-learning analysis! It is OK if the performance is very low. The important thing is that the dataset is cleaned properly and the pipeline is complete.

**Complete spec**: [doc](guidelinesProjects.pdf) and [slides](slidesProjects.pdf)

**The Fras**:

- [Francesco Riccardi](https://github.com/FrancescoRiccardi)
- [Francesco Spangaro](https://github.com/francescospangaro/)
- [Francesco Ferlin](https://github.com/Furrrlo/)

**Assigned dataset**: [11](Comune-di-Milano-Pubblici-esercizi.csv)

**Other datasets**: [here](datasets.xlsx)

There's no commits here 'cause we used Google Colab (no way I'm downloading all those python libraries locally)

The report was done on Overleaf (no way I'm installing all of LateX locally), can be still be found in the [report folder](report/)
