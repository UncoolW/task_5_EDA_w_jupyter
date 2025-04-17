#  Titanic EDA task

This project explores the **Titanic dataset** from Kaggle using exploratory data analysis (EDA) techniques to uncover patterns and relationships that influenced passenger survival.

##  Dataset

The dataset includes information about passengers such as age, gender, class, fare, and survival outcome.

Source: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

---

##  Objectives

- Understand the structure and distribution of the data.
- Perform univariate and bivariate analysis.
- Identify key features that influenced survival.
- Build visual insights for future modeling steps.

---

##  Key Analyses

###  Univariate Analysis
- Explored distributions of features like `Age`, `Sex`, `Pclass`, `Fare`, etc.
- Noticed skewed fare distribution and missing values in `Age`.

###  Bivariate Analysis
- **Sex vs Survival**: Majority of survivors were female.
- **Pclass vs Survival**: Higher class → higher survival rate.
- **Embarked vs Survival**: Cherbourg port passengers had higher chances.
- **Fare & Age vs Survival**: Survivors tended to have paid slightly higher fares.

###  Correlation Analysis
- Used a heatmap to examine numeric feature relationships.
- `Fare` showed moderate positive correlation with survival.
- `Pclass` had a moderate negative correlation.

---

##  Summary of Insights

- Being **female**, in **1st class**, and paying a **higher fare** increased survival chances.
- **Family presence** (via SibSp + Parch) helped survival when grouped contextually.
- These patterns form the basis for future feature engineering and modeling.

---

##  Files Included

- `titanic_eda.ipynb`: Main notebook with all visualizations and insights.
- `titanic_eda_colab_pdfreport.pdf`: Exported version of notebook for easy viewing.
- `data/train.csv`: Original dataset used for analysis.

---

##  Next Steps (provisional)

- Create new features like `FamilySize`, `IsAlone`.
- Encode categorical variables and prepare for modeling.
- Train classification models to predict survival.

---

##  Author

**Vanshika Verma**  
Data Analyst | Python Developer