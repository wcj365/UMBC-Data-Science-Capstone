# The Template and Guideline for the Final Report

- This document serves as a guide for developing project proposal which will eventually become the proposal and final report.
- You start with the end in mind and adopt an agile approach:
  - Making progress continuously towards your goal.
  - Updating this document continuously along the way.
 
## 1. Title and Author

- Project Title
- Prepared for UMBC Data Science Master Degree Capstone by Dr Chaojie (Jay) Wang
- Author Name 
- Link to the author's GitHub repo of the project
- Link to the author's LinkedIn profile
- Link to your PowerPoint presentation file
- Link to your YouTube video 
    
## 2. Background

Provide the background information about the chosen topic. 

- What is it about? 
- Why does it matter? 
- What are your research questions?

## 3. Data 

Describe the datasets you are using to answer your research questions.

- Data sources
- Data size (MB, GB, etc.)
- Data shape (# of rows and # columns)
- Time period (for example, 2010 to 2020) if your data are time-bound
- **What does each row represent?(a patient, a school, a crime, etc.)**
- Data dictionary
  - Columns name
  - Data type
  - Defition
  - Potential values (for categorical valuables, what are the categories?)
- Which variable/column will be your target/label in your ML model?
- Which variables/columns may be selected as features/predictors for your ML models?

## 4. Exploratory Data Analysis (EDA)

- Perform data exploration using Jupyter Notebook
- You would focus on the target variable and the selected features and drop all other columns.
- produce summary statistics of key variables
- Create visualizations (I recommend using **Plotly Express**)
- Find out if the data require cleansing:
  - Missing values?
  - Duplicate rows? 
- Find out if the data require splitting, merging, pivoting, melting, etc.
- Find out if you need to bring in other data sources to augment your data.
  - For example, population, socioeconomic data from Census may be helpful.
- For textual data, you will pre-process (normalize, remove stopwords, tokenize) them before you can analyze them in predictive analysis/machine learning.
- Make sure the resulting dataset need to be "tidy":
  - each row represent one observation (ideally one unique entity/subject).
  - each columm represents one unique property of that entity. 

## 5. Model Training 

- What models you will be using for predictive analytics?
- How will you train the models?
  - Train vs test split (80/20, 70/30, etc.)
  - Python packages to be used (scikit-learn, NLTK, spaCy, etc.)
  - The development environments (your laptop, Google CoLab, GitHub CodeSpaces, etc.)
- How will you measure and compare the performance of the models?

## 6. Application of the Trained Models

Develop a web app for people to interact with your trained models. Potential tools for web app development:

- **Streamlit** (recommended for its simplicity and ease to learn)
- Dash
- Flask

## 7. Conclusion

- Summarize your work and its potetial application
- Point out the limitations of your work
- Lessons learned 
- Talk about future research direction

## 8. References 

List articles, blogs, and websites that you have referenced or used in your project.
