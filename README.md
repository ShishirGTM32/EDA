# Marathon Dataset Analysis

## Data Source  
The dataset used in this analysis is sourced from Kaggle:  
🔗 [The Big Dataset of Ultra Marathon Running](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running/discussion/420633)

## Libraries Used  
- **Pandas** – For data manipulation and analysis  
- **Seaborn** – For data visualization  

## Project Overview

This project performs an exploratory data analysis (EDA) on ultra marathon race data, focusing specifically on races held in the **United States in 2018**.

### 1. Data Cleaning
- Addressed missing values
- Removed duplicate entries
- Verified data consistency

### 2. Data Analysis
- Explored participant demographics (age, gender, etc.)
- Analyzed race distances and finish times
- Examined race locations within the U.S.
- Identified trends and patterns in the 2018 race data

### 3. Visualization
- Visualized findings using **Seaborn**
- Created bar plots, histograms, and distribution charts to highlight key insights

### 4. Conclusion
- Summarized major insights and observations
- Provided an overview of ultra marathon participation in the U.S. for 2018


# Titanic DataSet Analysis

## Data Source  
The dataset used in this project is sourced from Kaggle:  
🔗 [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)

## Libraries Used  
- **Pandas** – Data manipulation and cleaning  
- **NumPy** – Numerical operations  
- **Seaborn** – Visualization  
- **Matplotlib** – Visualization

## Project Overview

This project performs exploratory data analysis (EDA) on the famous Titanic dataset to uncover trends and insights into passenger survival. The analysis focuses on identifying patterns related to demographic features, travel class, and other attributes to understand survival likelihoods.

---

### Data Cleaning
- Checked and handled missing values (Age, Embarked, Cabin)
- Converted categorical features into usable formats
- Created new features (e.g., Title from Name, FamilySize from SibSp + Parch)

### Data Analysis
- Investigated survival rates based on:
  - **Gender**
  - **Passenger Class (Pclass)**
  - **Age Group**
  - **Embarked Location**
  - **Fare**
  - **Family Size**
- Analyzed the impact of combined features (e.g., women in 1st class had the highest survival rate)


### Visualization
- Used Seaborn and Matplotlib to generate:
  - Bar charts
  - Heatmaps
  - Distribution plots
  - Violin plots
- Visualized correlation matrix to find feature relationships

### Conclusion
- **Females** had a significantly higher survival rate than males.
- Passengers in **1st class** were more likely to survive.
- Younger passengers and those with smaller families tended to survive more.
- Port of embarkation also played a small role in survival.
