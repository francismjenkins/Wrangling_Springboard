# Capston Project - Data Wrangling
# Frank Jenkins - Springboard, Intermediate Python

This project will seek to predict the lifestyle factors which increase the risk of cancer. The dataset used was taken from The Cancer 
Genome Atlas (TCGA). The analytical techniques that will be used are a differential expression analysis and a coexpression analysis.

The first step was to set the working directory to the folder containing the dataset. Next, the dataset was read into the Jupyter 
Notebook and assigned to an object. The dataset was imported as a csv file using the python module pandas. 

Because the dataset contains gene expression values for both normal and cancer cells, the dataset was broken up into two objects. 
The last two digits in the column headers tell us whether a column contains expression values from cancer cells or normal cells.
Regular expressions were used to filter the data (and segregate cancer cells from normal cells).

For the purpose of gene expression analysis, outliers are normally retained in the dataset. However, low expression values may
ultimately need to be removed (there are various approaches used by geneticists). The approach that will be used in this case will 
be determined as the analysis proceeds, according to utility. 

After performing analytics (e.g. correlation analysis, clustering, etc.), a functional analysis will be done on genes which are discovered
to play an important role in oncogenesis. In this case, the analysis is limited to one cancer type (clear cell renal carcinoma).
