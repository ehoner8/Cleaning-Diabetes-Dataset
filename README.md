# Cleaning-Diabetes-Dataset
A project that focuses on cleaning a large dataset from diabetes patients and attempts to create a model from it.


Dataset: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008 

This dataset contains information about one hundred thousand diabetes patients across 130 hospitals. Each row contains records about the patient's physical attributes, such as height, weight and gender, and the results of some tests done on them. The label was how many days until the patient was readmitted. It was either >30 days, <30 days, or "no" for never readmitted. 


The real test of this project was cleaning up the dataset. There were many missing values, so I had to take it case-by-case and go through the documentation to see what to do with each kind of missing value. The IDs could be dropped, as could things like the payer codes, which both have lots of missing values and intuitively have no effect on the outcome. For whatever reason, the 'weight' column had 98% missing values, so that needed to be dropped.
