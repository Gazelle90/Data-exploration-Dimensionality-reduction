# Data-exploration-Dimensionality-reduction
This is a recent assignment where I used python libraries to explore the dataset, handle the missing values, and standardise the numerical values and reduce the dimensionality of the feature space.


The dataset I used for this assignment is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on specific diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
The dataset consists of several medical predictors (independent) variables and one target (dependent) variable, Outcome. Independent variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

# This is the outline of what this assignment consists of :


1. Reading the file: Load and explore the dataset structure, including features and target variable.
2. Missing Values : Identify missing values and analyze their distribution across features.
3. Impute with scikit-learn: Apply imputation techniques using scikit-learn to handle missing data efficiently.
4. Implement imputation : Perform the actual replacement of missing values using the selected imputation method.
5. Plotting : Create insightful plots to understand the data distributions, relationships, and patterns.
6. Standardization : Standardize numerical features to ensure uniform scaling, which is crucial for dimensionality reduction.
7. Dimensionality reduction : Use Principal Component Analysis (PCA) to reduce the feature space while retaining significant information.
8. Multi-Dimensional Scaling : Apply MDS to visualize high-dimensional data in a 2D or 3D space, making it easier to interpret.

# Technologies and Libraries Used
Python
NumPy: For numerical computations.
Pandas: For data manipulation and analysis.
Matplotlib & Seaborn: For visualization.
scikit-learn: For imputation, standardization, and dimensionality reduction.

