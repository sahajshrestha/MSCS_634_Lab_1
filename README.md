# MSCS_634_Lab_1# Lab 1: Data Exploration, Visualization, and Preprocessing

## Purpose
To apply foundational data science techniques such as data visualization, cleaning, and statistical analysis using a real-world dataset.

## Key Insights From Visualization and Statistical Measures
- Weekly sales are influenced by unemployement.
- Not conclusive, but it seems like if the temperature is lower than 20F, the fuel price drops as well. 
- Line plots reveal periodic spikes likely due to holidays.
- Detected and removed outliers to improve analysis accuracy.

## Challenges
- Setting up the environment for Jupyter Notebook. Installation and dependency issues. 
- Deciding which columns were less relevant for reduction.


Assessment content
Overview: 
In this lab, you will apply data visualization, data preprocessing, and statistical analysis techniques using Jupyter Notebook. This lab will help you explore data, clean it, and prepare it for deeper analysis. 



Lab Instructions: 


Step 1: Data Collection  


Create a new Jupyter Notebook and include a Markdown cell at the top with your name, course title, and lab assignment title. 
Select or create a dataset of your choice. Possible sources include: 
Open data repositories such as Kaggle, Data.gov, or Google Dataset Search. 
Datasets containing sales data, weather data, or product performance are recommended. 
Load your dataset into a Pandas DataFrame. 
Screenshot Required: Display the first five rows of your dataset using .head() or .sample(). 
 
Step 2: Data Visualization 


Create meaningful visualizations to explore your dataset. Use the techniques demonstrated in the provided examples: 
Scatter Plots: Show relationships between numeric variables. 
Line Plots: Visualize trends over time or sequences. 
Bar Charts: Compare categorical data. 
Histograms: Display the distribution of numerical data. 
Box Plots: Visualize data spread and identify outliers. 
Pie Charts: Represent proportions for categorical data. 
Screenshot Required: Include at least two visualizations from the list above and provide descriptions of insights for each one. 
 

Step 3: Data Preprocessing 


Perform data preprocessing steps following the provided examples: 

1. Handling Missing Values: 
Detect and report missing values. 
Apply techniques such as: 
Filling with constants, forward fill, backward fill, or mean/mode replacement. 
Dropping rows or columns based on conditions. 
Screenshot Required: Display the dataset before and after handling missing values. 
2. Outlier Detection and Removal: 
Use IQR (Interquartile Range) or Standard Deviation techniques to identify and manage outliers. 
Screenshot Required: Display the IQR calculation, identified outliers, and the dataset after outlier handling. 
3. Data Reduction: 
Apply sampling (by number or percentage) to reduce data size. 
Perform dimension elimination by dropping less relevant columns. 
Screenshot Required: Display the dataset before and after applying data reduction techniques. 
4. Data Scaling and Discretization: 
Use techniques such as Min-Max Scaling, Z-score Standardization, or Decimal Scaling. 
Discretize continuous data into meaningful categories. 
Screenshot Required: Display the dataset before and after scaling or discretization. 
 

Step 4: Statistical Analysis 


Perform the following statistical analysis techniques on your dataset: 

1. General Overview of Data: 
Use .info() and .describe() to explore dataset characteristics. 
Screenshot Required: Display .info() and .describe() outputs. 
2. Central Tendency Measures: 
Calculate Minimum, Maximum, Mean, Median, and Mode. 
Screenshot Required: Display results of central tendency calculations. 
3. Dispersion Measures: 
Compute Range, Quartiles, Interquartile Range (IQR), Variance, and Standard Deviation. 
Screenshot Required: Display results of dispersion calculations. 
4. Correlation Analysis: 
Compute the correlation matrix for numerical columns using .corr(). 
Screenshot Required: Display the correlation matrix output. 
 

Submission Instructions: 



Create a GitHub repository for this lab (e.g. MSCS_634_Lab_1). 
Add the following files to your repository: 
Your Jupyter Notebook file (.ipynb). 
Any .csv or dataset files you used or modified. 
All required screenshots (consider placing them in a dedicated folder named /screenshots for better organization). 
A README.md file that briefly explains: 
The purpose of your lab work. 
Key insights from your visualizations and statistical measures. 
Any challenges faced or decisions made during the lab. 
Submit your GitHub repository link and ensure the repository is public or that you have granted instructor access. 
