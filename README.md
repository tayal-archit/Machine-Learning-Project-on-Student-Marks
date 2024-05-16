This project is a complete Machine Learning Model based on kaggle dataset of students performance in exams (https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977) using both Jupyter notebooks(.ipynb) and Python(.py). 
Score in maths (<b>math_score</b>) column is the target column predicted by all the other columns : <b>gender, race_ethnicity, parental_level_of_education,	lunch, test_preparation_course,	reading_score,	writing_score</b>

The model performs:
- <b>Data Collection</b> from kaggle
- <b>Data Checks</b> for missing values, duplicate values, data types and statistics of the data set in Jupyter notebooks
- <b>Exploratory data analysis(EDA)</b>: Univariate, bivariate and multivariate analysis using histograms, Kernel Distribution Function (KDE), piecharts, scatterplots, barplots, pairplots, etc in Jupyter notebooks
- <b>Data Pre-Processing</b>: One hot encoding for categorical columns, Scaling of numeric columns, imputing missing values, spliting train-test data
- <b>Model Training</b>: Using Linear Regression, Lasso, Ridge, K-Neighbors Regressor, Decision Trees, Random Forest Regressor, XGBRegressor, CatBoosting Regressor and AdaBoost Regressor
- <b>Choosing the best model</b> by evaulating Mean absolute error, RMS Error, R2 Square

The modules and packages required are listed in <b>requirements.txt</b>

  

