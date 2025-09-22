# Data-Cleaning-and-Preprocessing
**Project Overview**
This project demonstrates how to clean and preprocess raw data for machine learning using the Titanic dataset. The main objective is to handle missing values, encode categorical variables, standardize numerical features, and detect/remove outliers.

**Tools and Libraries**
1. Python
2. Pandas – data manipulation
3. NumPy – numerical operations
4. Matplotlib / Seaborn – visualization
5. Scikit-learn – preprocessing (StandardScaler, etc.)

**Steps Done**
1. Import & Explore Dataset
2. Handle Missing Values
3. Encode Categorical Features
4. Normalize / Standardize Numerical Features
5. Detect & Remove Outliers

**Visualization**
Used boxplots to visualize features like Age and Fare. Also used distribution plots to inspect the effect of outlier removal.

Additionally, Outliers were only removed for Age and Fare because these are continuous numeric features with wide ranges, making them prone to extreme values. Other columns are categorical or discrete, so outlier removal is not necessary for them. 
Columns like Name and Ticket were not used for modeling. Names are  mostly unique strings, not directly predictive. Use only extracted parts like titles. And Tickets are mostly random, with no predictive pattern. So ignored.
