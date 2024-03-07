Project Name: "Comparative Analysis of Machine learning models for Financial Loan approval prediction dataset".

Project Stages:

Load the dataset:

Start by loading essential Python libraries such as NumPy, SciKit, Seaborn ,Matplotlib, Pandas etc. Read the .csv file (loan_sanction_dataset) and loan the dataset. 

Exploratory Data Analysis:
	
Begin by showcasing the initial rows of the data, reviewing column names, and capturing summary statistics. Detect potential outliers through correlation analysis and visualize them using scatter plots. Analyze the distribution of the target variable, 'Loan_Status,' to understand its spread. Identify both numerical and categorical features present in the dataset. Investigate the top numerical features correlated with 'Loan_Status' to understand their impact. Additionally, pinpoint significant categorical variables that may influence the target variable. Finally, visualize the relationships and correlations among variables to gain deeper insights into the dataset.

Experimental Design:

The dataset exhibits class imbalance, prompting the utilization of SMOTE to address this issue. SMOTE, which stands for Synthetic Minority Over-sampling Technique, is a method used to address class imbalance in datasets by generating synthetic samples of the minority class. This technique helps to balance the distribution of classes and improve the performance of machine learning models. Additionally, k-fold cross-validation is employed as an experimental design to tackle this classification problem.

Model Building:


