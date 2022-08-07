# Click_though_rate
Our team of two competed in the data science hackathon ("datahack ") in which we ranked under 150.
Click Through Rate Predictor
EDA and Model Building :
The task was to determine the click-through rate of various email campaigns by considering a number of features
My method for predicting CTR consisted of various steps
A. Understanding the data using various Pandas features such as describes, info, shapes, isnull, unique, valuecounts
B. I utilized pandasprofiling and sweetviz reports to gain a better understanding of the dataset
C. Using matplotlib and seaborn, I ran the univariate analysis, which allowed me to determine correlations between the features and to eliminate irrelevant ones. In order to analyze bivariate data, heatmaps were created
D. Used label encoding to assign numerical values to categorical data
E.  Detected outliers using IQR, made boxplots, and defined various functions to remove them
F. Optimized r2 score through hyperparameter tuning
In the end, testcsv was used to predict the final results
