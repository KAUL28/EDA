# Project Objectives
### The project aims to:

#### Perform data visualization and analysis to uncover patterns, relationships, and outliers.
#### Employ statistical and visualization techniques to conduct EDA across univariate, bivariate, and multivariate dimensions.
#### Preprocess and transform datasets to make them suitable for modeling and analysis.

## Technical Approach
### Data Visualization
#### Data visualization was conducted using three Python libraries:

#### Seaborn: 
Used for creating statistical visualizations such as relational, categorical, and distribution plots.
#### Matplotlib:
A foundational library employed for custom 2D plotting to support and enhance Seaborn visualizations.
#### Plotly: 
Used to create interactive visualizations, facilitating dynamic analysis for user engagement.

Visualization focused on:

#### Relational Analysis:
Scatter plots and line charts for analyzing correlations between continuous variables.
#### Categorical Analysis:
Count plots and box plots to visualize distribution among categorical variables.
#### Distribution Analysis:
Histogram and KDE plots to examine the distribution of data points.
#### Regression Analysis:
Used for visualizing linear relationships and identifying trends within the data.
### Exploratory Data Analysis (EDA)
The EDA was segmented into three main analyses:

#### 1. Univariate Analysis: Analyzed each feature individually.

##### *Continuous Variables*:
Histograms and KDE plots were generated to observe skewness, kurtosis, and the presence of outliers.
##### *Categorical Variables*:
Bar plots and count plots were created to examine frequency distributions.
#### 2. Bivariate Analysis: Assessed relationships between pairs of variables.

##### *Continuous-Continuous*: 
Correlation matrices and scatter plots to evaluate linear relationships.
##### *Continuous-Categorical*: 
Box plots and violin plots to observe how categorical variables influence continuous ones.
##### *Categorical-Categorical*: 
Grouped bar charts to examine dependencies among categorical variables.
#### 3. Multivariate Analysis:

##### *Pair Plot Analysis*:
Conducted to assess relationships across multiple variables.
##### *Heatmap Analysis*: 
Visualized correlation across features to identify highly correlated variables, which can inform feature engineering.
### Data Preprocessing
Preprocessing was performed to improve data quality, with the following steps:

##### *Duplicate Removal*: 
Identified and removed duplicate records.
##### *Missing Value Imputation*: 
Employed various imputation techniques, based on feature type, to handle missing data.
##### *Outlier Detection*: 
Used both visual (box plots, scatter plots) and statistical techniques (IQR, Z-scores) to identify and handle outliers.
##### *Data Transformation*: 
Applied scaling (standardization, normalization) to ensure data uniformity across features, facilitating reliable model performance.
##### *Encoding of Categorical Variables*: 
Implemented One-Hot Encoding and Label Encoding to convert categorical variables to numerical format.
## Results
### NHL Dataset Insights:

##### Observed correlations between variables such as shots, goals, and time-on-ice, which are predictive of offensive performance.
##### Positional analysis indicated that specific player roles are associated with higher goal and assist counts, guiding performance metrics by player position.
### Amazon Smartphones & Accessories Dataset Insights:

##### Identified pricing and feature trends across top-rated products, highlighting consumer preferences.
##### Analyzed the relationship between product rating, review count, and pricing, revealing that high-rated products with specific features tend to attract more reviews.
### Data Quality Improvement:

##### Enhanced dataset integrity by handling missing data and outliers, ensuring the datasets were analysis-ready and suitable for model training.
##### Prepared transformed datasets that comply with standard machine learning model input requirements.

## References
##### Seaborn Documentation
##### Matplotlib Documentation
##### Plotly Documentation
