# Capston Project - Data Wrangling
# Frank Jenkins - Springboard, Intermediate Python

This project will seek to predict lifestyle factors which increase the risk of cancer. The dataset used was taken from The Cancer 
Genome Atlas (TCGA). The analytical techniques will include a differential expression and coexpression analysis. The cancer type under investigation is clear cell renal carcinoma.

The first step was to set the working directory to the folder containing the dataset. Next, the dataset was read into a Jupyter 
Notebook and assigned to an object. The dataset was imported as a csv file using the python module pandas. 

Because the dataset contains gene expression values for both normal and cancer cells, the dataset was broken up into two objects. 
The last two digits in the column headers tells us whether a column contains expression values from cancer or normal cells.
Regular expressions were used to filter the data (and segregate cancer from normal cells).

After performing analytics (e.g. correlation analysis, clustering, and other tests), a functional analysis will be done on genes 
which are predicted to play a role in cancer. The original dataset has been log2 transformed and normalized, which reduces the 
number of steps needed to preprocess the data. 
