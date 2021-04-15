# Automated-EDA
Exploratory data analysis (EDA) is an approach to analyze the data and find patterns, visual insights, etc. that the data set is having, before proceeding to model. One spends a lot of time doing EDA to get a better understanding of data, that can be minimized by using auto visualizations tools such as Pandas-profiling, Sweetviz, Autoviz, or D-Tale

-> Data Quality Check: Can be done using pandas library functions like describe(), info(), dtypes(), etc. It is used to find several features, its datatypes, duplicate values,  missing value, etc.

-> Statistical Test: Some statistical tests like Pearson correlation, Spearman correlation, Kendall test, etc are done to get a correlation between the features. It can be implemented in python using the stats library.

-> Quantitative Test: Some quantitative test is used to find the spread of numerical features, count of categorical features. It can be implemented in python using the functions of the pandas library.

-> Visualization: Feature visualization is very essential to get an understanding of the data. Graphical techniques like bar plots, pie charts are used to get an understanding of categorical features, whereas scatter plots, histograms are used for numerical features.

Installation:- pip install pandas-profiling

-> Pandas-Profiling
-> Sweetviz
-> Autoviz
-> D-Tale

-> Pandas-Profiling:- Pandas profiling is an open-source python library that automates the EDA process and creates a detailed report. Pandas Profiling can be used easily for large datasets as it is blazingly fast and creates reports in a few seconds.

Report:-
1) The pandas-profiling library generates a report having:
2) An overview of the dataset
3) Variable properties
4) Interaction of variables
5) Correlation of variables
6) Missing values
7) Sample data

-> Sweetviz:- Sweetviz is an open-source python auto-visualization library that generates a report, exploring the data with the help of high-density plots. It not only automates the EDA but is also used for comparing datasets and drawing inferences from it. A comparison of two datasets can be done by treating one as training and the other as testing.

Installation:- pip install sweetviz

Report:-
1) The Sweetviz library generates a report having:
2) An overview of the dataset
3) Variable properties
4) Categorical associations
5) Numerical associations
6) Most frequent, smallest, largest values for numerical features

-> Autoviz:- Autoviz is an open-source python auto visualization library that mainly focuses on visualizing the relationship of the data by generating different types of plot.

Installation:- pip install autoviz

Report:-
1) The Autoviz library generates a report having:
2) An overview of the dataset
3) Pairwise scatter plot of continuous variables
4) Distribution of categorical variables
5) Heatmaps of continuous variables
6) Average numerical variable by each categorical variable

-> D-Tale:- D-Tale is an open-source python auto-visualization library. It is one of the best auto data-visualization libraries. D-Tale helps you to get a detailed EDA of the data. It also has a feature of code export, for every plot or analysis in the report.

Installation:- pip install dtale

Report:-
1) The dtale library generates a report having:
2) An overview of the dataset
3) Custom filters
4) Correlation, Charts, and Heatmaps
5) Highlight datatypes, missing values, ranges
6) Code export


Conclusion:
I prefer to do my EDA with self-defined functions using several python libraries. The above-discussed libraries should be used to speed up your work.
For beginners, it is good to start doing EDA using the pandas' library and writing python code before trying these libraries, as it is more important to be equipped with the fundamental knowledge and programming practices.
The best data auto-visualization amongst the above discussed is the DTale library, as it reports with detailed EDA, custom filters, and code export. Code export is the main highlight of this library that makes it better than others.
