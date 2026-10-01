# 🌍 World Happiness Report Analysis

## 📌 Project Overview

This project analyzes the **World Happiness Report 2015 dataset** to identify the major factors associated with happiness levels across different countries.

The analysis focuses on factors such as **GDP per capita, family support, life expectancy, freedom, generosity, and perceptions of corruption**.

---

## 🎯 Aim

The aim of this project is to analyze the World Happiness Report dataset and identify the major factors influencing happiness levels across countries.

---

## 📊 Dataset

**Dataset:** World Happiness Report 2015

The dataset contains information about countries and several factors contributing to happiness, including:

- GDP per Capita
- Family Support
- Life Expectancy
- Freedom
- Generosity
- Perceptions of Corruption
- Happiness Score
- Happiness Rank

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab** – Notebook environment

---

## 🔍 Methodology

The project followed these steps:

1. Loaded the dataset into a Pandas DataFrame.
2. Explored the dataset structure, column names, and summary statistics.
3. Checked for missing values and duplicate records.
4. Created a new categorical column called **`Happiness level`** based on happiness score ranges.
5. Performed statistical analysis.
6. Performed correlation analysis to study relationships between variables.
7. Created different visualizations to identify patterns in the data.

---

## 📈 Data Analysis

The analysis includes:

- Identifying the country with the highest happiness score.
- Calculating the average happiness score for each happiness category.
- Analyzing the top happiest countries.
- Filtering countries with above-average happiness scores.
- Studying the relationship between GDP, life expectancy, and happiness.

---

## 📊 Visualizations

The following visualizations were created as part of the analysis:

### 1. Distribution of Happiness Score
A box plot was used to understand the distribution of happiness scores across countries.

### 2. Correlation Heatmap
A correlation heatmap was used to examine relationships between numerical variables.

### 3. Average Happiness Score by Happiness Level
A bar chart was used to compare the average happiness score across different happiness categories.

### 4. Happiness Score Trend Across Countries
A line plot was used to visualize the relationship between happiness score and happiness rank.

### 5. Life Expectancy vs Happiness Score
A scatter plot was used to study the relationship between life expectancy and happiness score.

### 6. Distribution of Countries by Happiness Level
A pie chart was used to visualize the distribution of countries across happiness categories.

### 7. Pair Plot
A pair plot was used to explore relationships between multiple numerical variables.

---

## 🔎 Key Observations

- Countries with higher GDP per capita generally show higher happiness scores.
- Life expectancy has a positive relationship with happiness levels.
- Most countries fall into the average happiness category.
- Economic stability and social support appear to be major contributors to overall happiness.

---

## 💡 Conclusion

The analysis of the World Happiness Report dataset shows that **economic conditions, health, and social support** are strongly associated with happiness levels across countries.

Countries with better living standards and stronger support systems tend to report higher happiness scores.

This project demonstrates how **data analysis and visualization techniques** can be used to identify important patterns and relationships in real-world datasets.

---

## 📁 Project Structure

```text
World-Happiness-Report/
│
├── World_Happiness_Report.ipynb
├── World_Happiness_Report.csv
├── World_Happiness_Report.pdf
└── README.md
