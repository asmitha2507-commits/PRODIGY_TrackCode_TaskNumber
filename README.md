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
# Task-04: Social Media Sentiment Analysis

## 📌 Project Overview

This project analyzes sentiment patterns in social media data to understand public opinions and attitudes toward different topics, brands, and entities.

The dataset contains social media posts along with the entity/topic they refer to and their corresponding sentiment category.

## 🎯 Objective

The main objectives of this project are:

- Analyze sentiment patterns in social media data.
- Identify the distribution of Positive, Negative, Neutral, and Irrelevant sentiments.
- Find entities with the highest positive sentiment.
- Find entities with the highest negative sentiment.
- Visualize sentiment patterns using charts.
- Generate a word cloud to identify frequently used words.

## 📂 Dataset

The dataset used for this project is the Twitter/Social Media Sentiment Analysis dataset provided for Prodigy InfoTech Task 04.

The dataset contains the following columns:

- **ID** – Unique identifier for each tweet.
- **Entity** – Brand, game, company, or topic mentioned in the tweet.
- **Sentiment** – Sentiment classification of the tweet.
- **Text** – The actual social media post.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- WordCloud
- NumPy

## 🔍 Data Analysis

The following steps were performed:

1. Loaded the dataset using Pandas.
2. Inspected the dataset using `df.info()`.
3. Checked for missing values.
4. Analyzed the number of tweets for each entity.
5. Analyzed sentiment distribution across different entities.
6. Calculated sentiment percentages.
7. Identified the most positive entities.
8. Identified the most negative entities.
9. Created visualizations to compare sentiment patterns.
10. Generated a word cloud of frequently occurring words.
11. Created an overall sentiment distribution chart.

## 📊 Key Findings

The overall sentiment distribution was:

| Sentiment | Percentage |
|-----------|------------|
| Negative | 30.2% |
| Positive | 27.9% |
| Neutral | 24.5% |
| Irrelevant | 17.4% |

The analysis showed that **Negative sentiment** had the highest proportion at approximately **30.2%**, while **Positive sentiment** accounted for approximately **27.9%**.

### Most Positive Entity

**AssassinsCreed** had the highest positive sentiment percentage, at approximately **64.41%**.

### Most Negative Entity

**MaddenNFL** had the highest negative sentiment percentage, at approximately **71.27%**.

## 📈 Visualizations

The project includes:

- Sentiment distribution across the top entities
- Most positive entities
- Most negative entities
- Sentiment percentage comparison
- Overall sentiment distribution pie chart
- Social media word cloud

## 💡 Conclusion

The sentiment analysis provides an overview of public opinion across different brands, games, and topics. The results show that negative sentiment was slightly more common than positive sentiment in the dataset.

The analysis demonstrates how data visualization and sentiment analysis can be used to understand public attitudes and identify entities receiving more positive or negative reactions.

## 👨‍💻 Author

**Prodigy InfoTech – Data Science Internship**

**Task 04: Sentiment Analysis**
