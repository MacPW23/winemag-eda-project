# winemag-eda-project
This is my first full Python EDA project. I wanted to take a real dataset, clean it properly, explore it visually, and build a workflow I can reuse for future analysis projects. I focused on understanding price behaviour, rating distribution, and the most common wine varieties and countries. 

Overview
This project is a structured exploratory data analysis (EDA) of the WineMag dataset, containing over 130,000 wine reviews. The aim was to build a clean, reproducible workflow using Python and develop strong foundations in data cleaning, univariate analysis, and visual insight generation. This is my first portfolio project as I continue progressing into data analysis and financial modelling.
Dataset
The dataset includes:
Wine ratings (points)
Price information
Country of origin
Grape variety
Winery
Tasting notes and descriptions
The raw dataset required cleaning, handling missing values, and removing extreme outliers before meaningful analysis could begin.
Objectives
Clean and prepare a large real‑world dataset
Explore key variables through structured univariate analysis
Produce clear, readable visualisations
Build a workflow suitable for future EDA and modelling projects
Strengthen Python skills (pandas, seaborn, matplotlib)
Methods
Data Cleaning
Removed missing values in critical fields
Handled price outliers using upper‑bound filtering
Standardised categorical fields
Ensured numeric fields were correctly typed
Univariate Analysis
Distribution of wine ratings (points)
Distribution of wine prices
Top countries by number of reviews
Top grape varieties
Top wineries
These steps provide a clear understanding of the dataset’s composition and highlight where deeper analysis would be most meaningful.
Visualisations
The project includes:
Histogram of wine ratings
Histogram of wine prices (including log‑scaled version)
Bar charts for top countries, varieties, and wineries
These visualisations help reveal trends, biases, and dominant categories within the dataset.
Key Insights
Wine ratings cluster tightly around the mid‑80s to low‑90s
Price distribution is heavily right‑skewed, with most wines priced affordably
A small number of countries dominate the dataset
Certain grape varieties appear far more frequently than others
Wineries show strong concentration, with a few producing a large share of reviewed wines
These insights form the foundation for future bivariate and multivariate analysis.
Tools Used
Python
pandas
seaborn
matplotlib
Google Colab
