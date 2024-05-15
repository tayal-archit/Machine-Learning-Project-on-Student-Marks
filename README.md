This project is a complete Machine Learning Model based on kaggle dataset of students performance in exams (https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977). 
Score in maths ~math_score~ column is the target column predicted by all the other columns : ~gender~ ~race_ethnicity~	~parental_level_of_education~	~lunch~	~test_preparation_course~	~reading_score~	~writing_score~

The model performs:
- Data Collection from kaggle
- Data Checks for missing values, duplicate values, data types and statistics of the data set in Jupyter notebooks
- Exploratory data analysis(EDA): Univariate, bivariate and multivariate analysis using histograms, Kernel Distribution Function (KDE), piecharts, scatterplots, barplots, pairplots, etc in Jupyter notebooks
- Data Pre-Processing: One hot encoding for categorical columns, Scaling of numeric columns, imputing missing values, spliting train-test data
- Model Training: Using Linear Regression, Lasso, Ridge, K-Neighbors Regressor, Decision Trees, Random Forest Regressor, XGBRegressor, CatBoosting Regressor and AdaBoost Regressor
- Choosing the best model by evaulating Mean absolute error, RMS Error, R2 Square

  

