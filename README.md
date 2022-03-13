# Breast-Cancer-EDA-And-Clustering
Exploratory Data analysis, Clustering and diagnosis of Breast Cancer using the Wisconsin Dataset. 
Data availabile at https://ftp.cs.wisc.edu/math-prog/cpo-dataset/machine-learn/cancer/WDBC/


![image](https://user-images.githubusercontent.com/12696541/158061106-a371b6c5-ebe9-400b-920f-e0131fde3dc8.png)

The dataset is composed as follows:

  Total observations of the dataset: 557;
  Malignant Class: 205;
  Benign Class: 352.
  The proportion is maintained

![image](https://user-images.githubusercontent.com/12696541/158061118-d716394d-3a7c-4acd-875f-6f1058c61d72.png)

radius, area and perimeter (mean, the wrost, and the error standard) are closely correlated to each other, the same for the characteristics of compactness, concave points and concavity.

![image](https://user-images.githubusercontent.com/12696541/158061131-b0cd9d85-39d1-46f9-b1c5-a77455bbe666.png)

From a first observation of the results of the plots, it can be deduced that the data are linearly separable and therefore a linear model could be an excellent solution to solve a classification problem.

![image](https://user-images.githubusercontent.com/12696541/158069888-2b68ec7a-d194-4a01-9d40-4c3a13a5671d.png)

![image](https://user-images.githubusercontent.com/12696541/158061161-4f1f60c6-6076-4821-8060-26bad1721e0d.png)

In our example, the analysis of the silhouette is used to choose an optimal value for the number of clusters. The silhouette plot shows that a n_clusters value of 5 and 6 is not good because they have clusters with lower than average scores, many negative values and also large fluctuations in the size of the silhouette plot. From the analysis of the silhouette, a good number of k clusters appears to be 2, 3 or 4
