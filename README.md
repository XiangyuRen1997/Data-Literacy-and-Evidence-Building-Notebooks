# Data-Literacy-and-Evidence-Building-Notebooks

## The Jupyter notebooks cover the following topics using Python (and SQL):
1.	Data Exploration: This notebook shows how to load datasets, conduct exploratory analysis, subset data, and generate descriptive statistics.
2.	Data Linkage: This notebook demonstrates different join operations using Python and SQL.
3.	Data Measurement: This notebook shows how to define degree completers, non-completers, and degree-pursuers, and develops several job quality measures.
4.	Data Visualization: This notebook covers how to create informative visualizations by using matplotlib and seaborn library, showcasing boxplots, countplots, lineplots, and barplots.
5.	Machine Learning Data Preparation: This notebook covers how to prepare the data for machine learning models, including how to generate the label and the features.
6.	Machine Learning Job Quality: This notebook covers how to develop supervised machine learning models and how to evaluate the models with metrics such as precision and recall. 

These notebooks will help readers gain a comprehensive understanding of data analysis and manipulation techniques.
 
### Data Exploration:
•	Loading python libraries <br>
•	Loading datasets <br>
•	Exploring data structure, using the example of the 2015 cohort <br>
•	Checking dataset variables and size <br>
•	Subsetting data, with examples of specific study majors <br>
•	Generating descriptive statistics, including mean, standard deviation, counts, and quantiles, illustrated with the "year7earnings" variable <br>
•	Identifying missing values in "year7earnings"
### Data Linkage Python & SQL - similar structure just with different languages!
•	Introducing cross-section data, consisting of three datasets: master, employment, and education <br>
•	Establishing database connection and loading data to the database <br>
•	Demonstrating how to left join master with employment in SQL language <br>
•	Performing the inner join of master with employment in SQL language, leading to missing entries for those without employment in the combined dataset <br>
•	Right merging master with education in Python
### Measurement:
•	Defining degree completers, non-completers, and degree pursuers<br>
•	Assessing the quality of work by examining year 7 earnings, the number of jobs, high-earning jobs, employment duration, average earnings per employment quarters under different completion status<br>
•	Analyzing year 7 earnings, the number of jobs, high earning jobs, employment duration, average earnings per employment quarters for different majors in different completion status<br>
### Data Visualization
•	Introducing the visualization packages: matplotlib and seaborn<br>
•	Explaining how to create simple and information visualizations<br>
•	Demonstrating how to create a boxplot with an example of earnings distributions by major<br>
•	Demonstrating how to create a count plot with an example of missingness in earnings by major<br>
•	Demonstrating how to create a line plot with an example of time trends in earnings by major<br>
•	Demonstrating how to create a bar chart with an example of median earnings by major and completion status<br>
### Machine Learning Data Preparation
•	Explore relationship between key variables (receiving pell grant and year 7 earnings)<br>
•	Create job quality label (label high earnings = 1 if a person earning equal to or above $30,000 in year 7)<br>
•	Create and clean categorical and numerical features, rescaling numeric features and converting categorical features into dummies<br>
### Machine Learning Job Quality
•	Separate the data into the training dataset and the testing dataset<br>
•	Run the Logistic Regression model<br>
•	Evaluate the Logistic Regression model using confusion matrix, accuracy at k, precision at k, and recall at k, where k means the percentage of students we will predict to have successful outcomes<br>
•	Run the Decision Tree model<br>
•	Compare multiple machine learning models (Logistic Regression, Decision Tree, and Random Forest) with two baseline models (randomly guess outcomes and guess everyone has a successful outcome), and evaluate the models using precision at k, accuracy at k, and recall at k<br>
