# BreastCancer-Analysis-and-Prediction
Dataset: https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

About the Dataset:

About this Kernel
The Breast Cancer datasets is available UCI machine learning repository maintained by the University of California, Irvine.
The dataset contains 569 samples of malignant and benign tumor cells.

The first two columns in the dataset store the unique ID numbers of the samples and the corresponding diagnosis (M=malignant, B=benign), respectively.

The columns 3-32 contain 30 real-value features that have been computed from digitized images of the cell nuclei, which can be used to build a model to predict whether a tumor is benign or malignant.

1= Malignant (Cancerous) - Present (M)
0= Benign (Not Cancerous) -Absent (B)

Ten real-valued features are computed for each cell nucleus:

radius (mean of distances from center to points on the perimeter)
texture (standard deviation of gray-scale values)
perimeter
area
smoothness (local variation in radius lengths)
compactness (perimeter^2 / area - 1.0)
concavity (severity of concave portions of the contour)
concave points (number of concave portions of the contour)
symmetry
fractal dimension ("coastline approximation" - 1)
The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius

# What we wanted to do
In this project we wanted to analyze the dataset and then have the possibility to predict whether a person has had benign cancer or a benign cancer based on the properties of the cancer.
To do this we decided to use two ML Models and then compare them and see which of the two was the best
Decision Tree (default and tuned parameters)
Random Forest (default and tuned parameters)

>Structure of the project: Read and Correct the dataset -> Data Observation -> Execute ML models -> Comparisons

# Results
**AUC Values**

![image](https://user-images.githubusercontent.com/62283139/154303524-48df6d4a-433c-49ae-b377-bc0cd742ac68.png)

**Comparison between the two models**

![image](https://user-images.githubusercontent.com/62283139/154303636-781f67b6-7a8c-496b-879d-d04260a137be.png)

# Conclusions
At the end of the project we can say that these two algorithms can predict quite well who has had benign cancer or malignant cancer. But the RandomForest performed slightly better than the DecisionTree

>NB: see the .ipynb file for full report with some explanations and the results of each model with and without tuning of the hyperparameters and .pdf file for a simple presentation of the work

Work done by:
  - Matteo Raffo (https://github.com/Buffless24)
  - Paolo Patrone (https://github.com/Patpa99)
