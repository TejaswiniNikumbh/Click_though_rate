# Click_Through_Rate_Predictor
Our team of two competed in the data science hackathon ("datahack ") in which <strong>we ranked under 500</strong>.

# EDA and Model Building :
The task was to determine the <strong>click-through rate of various email campaigns</strong> by considering a number of features
My method for predicting CTR consisted of various steps
* 1.Understanding the data using various <strong>Pandas features such as describes, info, shapes, isnull, unique, valuecounts
* 2.I utilized <strong>pandasprofiling and sweetviz reports</strong> to gain a better understanding of the dataset
* 3.Using matplotlib and seaborn, I ran the univariate analysis, which allowed me to determine correlations between the features and to eliminate irrelevant ones. In     order to analyze bivariate data, heatmaps were created
* 4.Used label encoding to assign numerical values to categorical data
* 5.Detected outliers using IQR, made boxplots, and defined various functions to remove them
* 6.Optimized r2 score through hyperparameter tuning
* 7.In the end, testcsv was used to predict the final results
