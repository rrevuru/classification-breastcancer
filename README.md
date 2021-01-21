## Breast Cancer : University of Wisconsin
Will be working on a binary classification use case of machine learning. Here in this workbook, will be working on using a dataset from University of wisconsin, which has published breast cancer diagnostic data from digitized images of breast-mass. Since this is a classification problem, we will be using accuracy as a training metric to develop a machine learning model.

### Amazon Sagemaker
Amazon Sagemaker provides an end-to-end AI/ML platform to build, train, deploy and manage machine learning models in an easy form.
Sagemaker facilitates wide range of built-in aglorithms to solve common business use cases.

### Problem statement
This notebook reviews a very well known breast cancer tumor prediction use case. University of wisconsin has published a dataset in a tabular format which was derived from a ultrasound images. Tabular data includes a target variable "Diagnosis" which is labeled as M for malignant and B for beingin. Dataset also includes various features which are explained below which will influence the Diagnosis.

#### Data Set
Attribute Information:

- ID number
- Diagnosis (M = malignant, B = benign) 3-32)
Ten real-valued features are computed for each cell nucleus:

- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension ("coastline approximation" - 1)

### Solution Approach
In the machine learning arena, this problem is categorized as typical binary classification.
Sagemaker provides variety of built-in algorightm for most common use cases. This notebook leverages Linear Learner built-in algorightm from Sagemaker. Next sections will review

- Exploratory Data Analysis
- Training a sagemaker model
