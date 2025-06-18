# Developer Survey Data Analysis

This project analyzes a global developer survey to uncover trends in tools, learning preferences, coding experience, AI tool usage, and salary prediction.

##  Project Overview

We performed exploratory data analysis (EDA), data cleaning, and built a machine learning model to predict developer salaries based on:

- Country
- Education Level
- Years of Experience
- Employment Type

This project was part of a data storytelling and communication task, and results were also summarized in a blog post.

## Dataset

The data used in this project comes from the [Stack Overflow Developer Survey](https://insights.stackoverflow.com/survey).  
It includes responses from thousands of developers worldwide on their tools, experience, education, and salary.


##  Key Analyses

- **Top Desired Developer Tools** (e.g., Docker, React, AWS)
- **Learning Sources**: Comparison between professionals and learners
- **Experience by Education Level**: More education tends to correlate with more coding years
- **AI Tool Adoption**: Higher usage by professionals
- **Salary Prediction** using Linear Regression

##  Machine Learning Model

A Linear Regression model was built to predict yearly salaries.  
After feature engineering and regularization (Ridge), the final performance was:

- **R² Score**: ~0.33  
- **Mean Squared Error**: around 1.23e9

### Example Prediction

> A full-time developer from the United States, with a Master's degree and 5 years of experience, is predicted to earn approximately **$28,552 per year**.

*Note: Due to data variability and missing variables (e.g., job role, company size), prediction accuracy is limited.*

## Blog Post

For a full breakdown of the insights and visualizations:  

🔗 [What Developers Want: Tools, Learning Paths, and AI Adoption – A Data Science Project](https://medium.com/@maam66282/what-developers-want-tools-learning-paths-and-ai-adoption-a-data-science-project-5f8924b4fd86)

##  Files

- `developer_survey_analysis.ipynb`: Main notebook with all steps
- `README.md`: This file

##  Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- Jupyter Notebook
- Medium (for blog publishing)

##  Contact

Feel free to open an issue or connect if you have feedback or questions!

