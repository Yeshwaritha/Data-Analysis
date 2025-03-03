NUCLEAR SHAPE, TEXTURE, AND DIAGNOSIS: UNRAVELING THE LINK
Project proposal
We have chosen Wisconsin cancer data for the analysis. After a thorough examination of the dataset, we aim to find the following (research questions)
1. Is there a relationship between the shape of the nucleus (compactness, concavity, fractal dimension) and the diagnosis?
2. Do texture-related features (smoothness, symmetry) have an impact on the diagnosis?
3. Is there any significant correlations between the various nuclei characteristics and the diagnosis?
Data source
	https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic
Data is obtained from the UCI Machine Learning Repository where the Breast Cancer Wisconsin (Diagnostic) dataset has been chosen under the subject area of health and medicine. (UCI Machine Learning Repository, n.d.)
Data set Summary 
The dataset describes the various characteristic features of the nuclei of a breast cell in a cancer individual. The boundaries of the cell nuclei are examined and analyzed for size, shape, contour, texture, smoothness, symmetry, and other features. The mean values, standard error, and the largest value of each characteristic feature are described. These characteristics of the nuclei and diagnosis as Malignant or Benign tumors make complete data that is used for our study. (Street et al., 1993)
Target variable - “Diagnosis” 
Variables in detail 
1.	Id- It is a unique number given to each patient in the dataset. It is a nominal kind of variable.
2.	Diagnosis- This describes if the patient has a benign or malignant tumor. It is referred to as ‘M’ for malignant and ‘B’ for benign. This describes the severity of the cancer in an individual. It is an ordinal variable. This also acts as a target variable.
The below variables are given in 3 calculative statistics in the data set as mean, standard error, and worst of each parameter.
3.	Radius - This describes the mean distances from the center of the cell nucleus to the perimeter. It has a measurable value and has a continuous type of data. 
4.	Texture - It is a numerical value describing the texture of the cell nucleus in terms of the standard deviation of gray-scale values continuous type of data.
5.	Perimeter - Describes the total length of the boundary of the cell nucleus overall. It has a measurable value and has a continuous type of data.
6.	Area - This section describes the total area covered by the cell nucleus in a patient. It is a numerical value. It has a measurable value and has a continuous type of data.
7.	Smoothness - This section describes the variation in the lengths of the radius of the cell nucleus. It is a ratio datatype. 
8.	Compactness - Calculated as (perimeter^2) / area - 1.0. It is a ratio datatype and is a measurable type of data.
9.	Concavity - This part describes the severity of the concave portions of the nuclei contour. It is a ratio datatype and describes the characteristic feature of the cancer cell.
10.	Concave points - This section describes the number of concave portions of the nuclei contour. It is a ratio datatype having a continuous value.
11.	Symmetry - This describes the mean symmetry of the benign or malignant cell nuclei. It is a ratio datatype that differs for each patient.
12.	Fractal_dimension – Describes the coastline approximation. It is a ratio datatype. 

References
Nick Street, W., Wolberg, W. H., & Mangasarian, O. L. (1993, July 29). Nuclear feature extraction for breast tumor diagnosis. Spie Digital Library. https://doi.org/10.1117/12.148698
UCI Machine Learning Repository. (n.d.). https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic


