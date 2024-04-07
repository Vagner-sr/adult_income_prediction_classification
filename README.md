**Project README**

**Project Summary:**

The project aims to analyze a dataset containing demographic information to predict whether an individual earns more than $50K annually. The dataset includes features such as age, education, occupation, marital status, and others.

**Main Insights:**

**Demographic Trends:**

- Individuals between 20 and 50 years old are most represented in the dataset.
- The dataset is predominantly composed of men (67%) compared to women (33%).
- Marital status and race seem to have an impact on income distribution, with certain categories showing a higher proportion of incomes over $50K.

**Education and Occupation:**

- Individuals with higher levels of education tend to have higher incomes.
- Certain occupations like Exec-managerial and Prof-specialty have a higher proportion of incomes over $50K.

**Machine Learning Results:**

- The XGBoost classifier yielded the highest accuracy among all models, achieving an accuracy score of 87.65%.
- An ensemble of multiple models slightly improved the accuracy to 86.88%.
- Other models such as Gradient Boosting Classifier, Random Forest, Logistic Regression, and Naive Bayes also provided competitive accuracy scores ranging from 83% to 87%.

**Project Structure:**

**Data Cleaning and Preprocessing:**

- Renaming columns, handling missing values, and encoding categorical variables.
- Feature engineering to modify the 'education' feature.
- Dropping unnecessary columns and filtering rows based on specific conditions.

**Exploratory Data Analysis (EDA):**

- Analyzing the distribution of numerical and categorical variables.
- Investigating demographic trends in relation to income using visualizations.

**Feature Selection and Transformation:**

- Encoding categorical variables and scaling numerical features.
- Reducing the number of features based on correlation analysis.

**Machine Learning Modeling:**

- Training various classifiers including RandomForest, XGBoost, Logistic Regression, Naive Bayes, and Gradient Boosting Classifier.
- Evaluating model performance using accuracy scores.

**Conclusion:**

The project provides valuable insights into demographic trends and their impact on income distribution. By leveraging machine learning models, it successfully predicts whether an individual earns more than $50K annually based on demographic features. The XGBoost classifier emerged as the best-performing model, achieving an accuracy score of 87.65%.
