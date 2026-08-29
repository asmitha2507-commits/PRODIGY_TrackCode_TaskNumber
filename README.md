# PRODiGY Task 1 - Population Distribution

## Objective
Create a histogram to visualize the distribution of population across countries.

## Dataset
World Bank population dataset containing total population data for countries and regions.

## Tools Used
- Python
- Pandas
- Matplotlib
- Google Colab

## Visualization
A histogram was created to visualize the distribution of population across countries in 2020.

## Observation
The histogram shows a highly right-skewed distribution. Most countries have relatively smaller populations, while only a few countries have very large populations.
---

# PRODiGY Task 2 - Titanic EDA

## Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand the data and identify factors related to passenger survival.

## Dataset
Titanic passenger dataset containing information about passengers, including:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Embarked

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## EDA Performed
- Loaded and inspected the Titanic dataset.
- Checked the dataset structure and columns.
- Checked for missing values.
- Handled missing values in Age and Embarked.
- Generated descriptive statistics.
- Analyzed survival counts and percentages.
- Analyzed survival by gender.
- Analyzed survival by passenger class.
- Visualized age distribution.
- Visualized age distribution by survival.
- Visualized fare distribution.
- Created a correlation heatmap.
- Saved the cleaned dataset as `titanic_cleaned.csv`.

## Key Findings
- The dataset contains 891 passengers.
- 342 passengers survived and 549 did not survive.
- Female passengers had a higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Most passengers were between young and middle adulthood.
- Fare distribution was highly right-skewed, with most fares being relatively low.

## Files
- `Task_02_Titanic_EDA.ipynb` - Titanic EDA notebook
- `titanic_cleaned.csv` - Cleaned Titanic dataset
