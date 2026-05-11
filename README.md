# Titanic Dataset Cleaning Analysis
## Project Overview
This repository contains a fully cleaned version of the Titanic dataset, ready for machine learning analysis. The dataset explores passenger survival during the 1912 Titanic disaster, with engineered features for better insights. Priyanshu Sahu from Meerut, Uttar Pradesh, performed the complete data cleaning and feature engineering.

# Dataset Features
- The cleaned CSV includes these key columns:

- Survived: Survival status (0 = No, 1 = Yes).

- Pclass: Ticket class (1, 2, or 3).

- Sex: Gender (male/female).

- Age: Passenger age.

- Fare: Ticket fare paid.

- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

- Title: Extracted title (e.g., Mr, Mrs, Miss, Master).

- AgeGroup: Binned age (Child, Teen, Adult, MiddleAge, Senior).

- FamilySize: Total family members (SibSp + Parch + 1).

- FarePerPerson: Fare divided by family size.

- IsAlone: 1 if traveling solo, 0 otherwise.

- No missing values remain after cleaning.

# Cleaning Process
- Handled missing values in Age, Fare, and Embarked.

- Extracted titles from names using regex.

- Created AgeGroup bins: Child (<12), Teen (12-18), Adult (19-50), MiddleAge (51-65), Senior (>65).

- Computed FamilySize and IsAlone flags.

- Derived FarePerPerson for equitable fare comparison.

- Ensured numeric consistency and removed duplicates.

# Key Insights
- Females had higher survival rates than males.

- First-class passengers (Pclass=1) survived more often than third-class.

- Children (via Title=Master or AgeGroup=Child) showed elevated survival.

- Solo travelers (IsAlone=1) had lower odds.

- Higher FarePerPerson correlated with better survival chances.

# Files
File Name	Description
Cleaned-Titanic-Dataset.csv	Processed dataset (891 rows, 11 columns). 
# Usage
Load in Python:

python
import pandas as pd
df = pd.read_csv('Cleaned-Titanic-Dataset.csv')
Ideal for logistic regression, random forests, or survival prediction models.

