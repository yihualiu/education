# Educational outcomes

### Abstract

This project examines educational data (including student demographic information and academic records, school attributes, and teacher data) from kindergarten through third grade for a diverse cohort of students. In the exploratory phase, we find methods to reduce the minority achievement gap and to improve outcomes for all students. Next, we attempt to predict future test scores via several regression models. Finally, we predict whether students will graduate from high school and whether they will take a college entrance examination (SAT or ACT). Although these events occur nearly a decade after third grade for most students, we are able to perform relatively well, with ROC AUC (area under curve) scores between 0.7 and 0.8 on unseen test data.

### Data

Our data set was initially compiled for a research study conducted by the Tennessee Department of Education. The raw data file consists of 11601 rows (students) and 378 columns (features). It can be obtained [here](http://dataverse.harvard.edu/dataverse/star), along with supporting documentation.

### Files

The raw data file from the original source has been converted from .SAV (SPSS file format) to .CSV format for greater accessibility. It is included in this repository under [/data/rawdata.csv](/data/rawdata.csv).

Three annotated Jupyter notebooks cover each part of the project in detail. They contain all the code and print-outs along with explanatory analysis.

Throughout the project, cleaned and condensed data sets are produced from the original source file. These are included in the ["processed" directory](/processed/). The code that creates these CSV files has been commented out in the notebooks, but users can uncomment those lines if they wish to create new copies.
