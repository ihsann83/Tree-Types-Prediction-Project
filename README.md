# Tree-Types-Prediction-Project

Dataset contains tree observations from four areas of one national forest district. This dataset includes information on tree type, shadow coverage, distance to nearby landmarks, soil type, and local topography. The goal of the project is to build a model that predicts what types of trees grow in an area. The Forest Dataset contains approximately 600 thousand lines, also you can easily find many information about it on the web (especially Kaggle).

Firstly, I tried to understand the dataset column by column using pandas module. I did research within the scope of domain (forest, trees) knowledge on the internet to get to know the data set in the fastest way.

I implemented cleaning, handling with outliers and missing values using Pandas, NumPy for the best result in modeling.

After that, my final dataset with the new variables I have created was ready for model building. I implemented Support Vector Machine, XGBoost, Random Forest, Desicion Tree and K-Nearest Neighbors (KNN) algorithms. Also, I evaluated the success of my models with appropriate performance metrics and visualized them using Yellowbrick, Seaborn or Matplotlib modules.

At the end of the project, I created a chart comparing the performance of all models and chose the most successful model.

# Tasks

#### 1. Exploratory Data Analysis (EDA)
- Import Libraries, Load Dataset, Exploring Data

    *i. Import Libraries*
    
    *ii. Load Dataset*
    
    *iii. Explore Data*

#### 2.  Data Cleaning
- Detect Missing Values and Outliers 

    *i. Missing Value Detection*
    
    *ii. Outlier Detection*
    
- Deal with Outliers
    
    *i. Visualize Zscore Tresholds (how many times IQR) by Continuous Variables*
    
    *ii. Drop Outliers*

#### 3. Prediction (Multi-class Classification)
- Import libraries
- Data Preprocessing
- Implement XGBoost Classifer
- Implement SVM Classifer
- Implement Decision Tree Classifier
- Implement KNN Classifer
- Implement Random Forest Classifer
- Compare The Models
