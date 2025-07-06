# 📊 Data Analysis with Pandas, NumPy, and Machine Learning

Welcome to this comprehensive repository built while following [freeCodeCamp’s 17-hour YouTube course](https://www.youtube.com/watch?v=r-uOLxNrNk8) on data analysis using **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, and **Scikit-learn**.  

As an **advanced beginner**, this project showcases hands-on practice across core data analysis topics—organized into clear sections and projects with datasets and Jupyter notebooks.

Whether you're a **fellow learner**, a **recruiter**, or an **open-source contributor**, this repository demonstrates a structured and practical approach to learning data analysis.

---

## 📚 Table of Contents

1. [Introduction to Pandas](#1-introduction-to-pandas)
2. [Project 1: Web Scraping with Pandas](#2-project-1-web-scraping-with-pandas)
3. [Data Filtering](#3-data-filtering)
4. [Data Extraction](#4-data-extraction)
5. [Pivot Tables](#5-pivot-tables)
6. [Project 2: Data Visualization](#6-project-2-data-visualization)
7. [GroupBy and Aggregation](#7-groupby-and-aggregation)
8. [Merging and Concatenating](#8-merging-and-concatenating)
9. [Regular Expressions](#9-regular-expressions)
10. [Project 3: Data Cleaning](#10-project-3-data-cleaning)
11. [Machine Learning](#11-machine-learning)
12. [Project 4: Text Classification](#12-project-4-text-classification)

---

## ⚙️ Tools and Libraries Used

- **Pandas** – for data manipulation and analysis  
- **NumPy** – for numerical computing  
- **Matplotlib** & **Seaborn** – for data visualization  
- **Statsmodels** & **Scikit-learn** – for machine learning  
- **Jupyter Notebook** – for interactive development  
- **CSV/Excel files** – used as real-world datasets

---

## 1. Introduction to Pandas

> 📘 Learn the basics of creating, modifying, and exploring Pandas DataFrames.

**Folder:** [`01.Introduction to panda`](./01.Introduction%20to%20panda)  
**Key Files:**
- `1.Creating a Dataframe.ipynb`
- `3.Basic Attributes, Methods and FUnctions.ipynb`
- `6.Add New column to a dataframe.ipynb`
- `10.Sort a Dataframe with sort_values().ipynb`

**Dataset:** [`StudentsPerformance.csv`](./01.Introduction%20to%20panda/StudentsPerformance.csv)

---

## 2. Project 1: Web Scraping with Pandas

> 🔍 Extract football league data and convert it into structured CSVs for analysis.

**Folder:** [`02.Project 1 - Web Scraping with Pandas`](./02.Project%201%20-%20Web%20Scraping%20with%20Pandas)  
**Key Files:**
- `code-1.ipynb`
- `code-2.ipynb`
- `code-3.ipynb`

**Datasets:**
- `English_League_1.csv`, `German_Bundesliga.csv`, `Spanish_La_Liga.csv`, etc.

---

## 3. Data Filtering

> 🎯 Use conditions, `np.where()`, `np.select()`, `isin()`, and methods to handle duplicates and unique values.

**Folder:** [`03.Data Filtering`](./03.Data%20Filtering)  
**Key Files:**
- `01.Filtering a dataframe based on 1 condition.ipynb`
- `04.Creating a Conditional Column from More Than 2 Choices np.select().ipynb`
- `06.Find Duplicate Rows with the .duplicated() Method.ipynb`

**Dataset:** [`laptop_price.csv`](./03.Data%20Filtering/laptop_price.csv)

---

## 4. Data Extraction

> 📎 Learn selection, indexing, value assignment, and using `.loc`, `.iloc`, `.query()`, and `.apply()`.

**Folder:** [`04.Data Extraction`](./04.Data%20Extraction)  
**Key Files:**
- `2.Selecting elements by index label with .loc().ipynb`
- `6.Create Random Sample with the sample() Method.ipynb`
- `9.Lambda function + apply() method.ipynb`

**Dataset:** [`players_20.csv`](./04.Data%20Extraction/players_20.csv)

---

## 5. Pivot Tables

> 📊 Summarize and reshape datasets using `pivot()` and `pivot_table()`.

**Folder:** [`05.Pivot Table`](./05.Pivot%20Table)  
**Key Files:**
- `1.pivot() and pivot_table().ipynb`

**Datasets:** [`gdp.csv`](./05.Pivot%20Table/gdp.csv), [`supermarket_sales.xlsx`](./05.Pivot%20Table/supermarket_sales.xlsx)

---

## 6. Project 2: Data Visualization

> 📈 Create line plots, bar charts, and export visualizations using Pandas and Matplotlib.

**Folder:** [`06.Project 2 - Data Visualization`](./06.Project%202%20-%20Data%20Visualization)  
**Key Files:**
- `2.Data Visualization with Pandas.ipynb`
- `Interactive Visualization with Pandas.ipynb`

**Visual Output:**  
- ![Sample Plot](./06.Project%202%20-%20Data%20Visualization/my_test.png)  
**Datasets:** [`population_total.csv`](./06.Project%202%20-%20Data%20Visualization/population_total.csv)

---

## 7. GroupBy and Aggregation

> 📂 Use `groupby()` to aggregate and summarize large datasets.

**Folder:** [`07.GroupBy and Aggregate Function`](./07.GroupBy%20and%20Aggregate%20Function)  
**Notebook:** `GroupBy and Aggregate Functions.ipynb`  
**Datasets:** `Car_sales.csv`, `vgsales.csv`

---

## 8. Merging and Concatenating

> 🔗 Combine multiple DataFrames using joins and concatenation methods.

**Folder:** [`08.Merging and Concatenating DataFrames`](./08.Merging%20and%20Concatenating%20DataFrames)  
**Key Files:**
- `Concatenate.ipynb`
- `Joins.ipynb`

**Datasets:**  
- `IMDb movies.csv`, `IMDb ratings.csv`  
- `Others/`: `books.csv`, `ratings.csv`, `tags.csv`

---

## 9. Regular Expressions

> 🔤 Use `re.search()` and `re.findall()` to clean and extract patterns from text.

**Folder:** [`09.Regular Expressions`](./09.Regular%20Expressions)  
**Key Files:**
- `1.search() and findall().ipynb`
- `2.Exercise.ipynb`

---

## 10. Project 3: Data Cleaning

> 🧹 Clean messy Netflix title data by handling nulls, formatting, and text cleanup.

**Folder:** [`10.Project 3 - Data Cleaning`](./10.Project%203%20-%20Data%20Cleaning)  
**Notebook:** `Project 3 Data Cleaning with Pandas.ipynb`  
**Dataset:** [`netflix_titles.csv`](./10.Project%203%20-%20Data%20Cleaning/netflix_titles.csv)

---

## 11. Machine Learning

> 🤖 Build linear regression models using both `statsmodels` and `scikit-learn`.

**Folder:** [`11.Machine Learning`](./11.Machine%20Learning)  
**Key Files:**
- `2.Linear Regression with Statsmodels (Simple).ipynb`
- `4.Linear Regression with sklearn.ipynb`

**Dataset:** [`Boston House Prices.csv`](./11.Machine%20Learning/Boston%20House%20Prices.csv)  
**Visual Output:**  
- ![Linear Regression](./11.Machine%20Learning/linear_regression.png)

---

## 12. Project 4: Text Classification

> 📝 Perform binary sentiment classification on IMDB reviews using logistic regression.

**Folder:** [`12.Project 4 - Text Classification`](./12.Project%204%20-%20Text%20Classification)  
**Notebook:** `Project 4 - Binary Text Classification.ipynb`  
**Dataset:** [`IMDB Dataset.csv`](./12.Project%204%20-%20Text%20Classification/IMDB%20Dataset.csv)

---

## 📌 How to Use This Repository

1. **Clone the repository**
   ```bash
   git clone https://github.com/Nikhil-vaishnav-17/Data-Analysis-FreeCodeCamp.git
   cd Data-Analysis-FreeCodeCamp

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
3. **Launch Jupyter Notebooks**
   ```bash
   jupyter notebook

---

## 🙌 Acknowledgements

Thanks to freeCodeCamp for their outstanding course content and structured curriculum. This repository mirrors the hands-on side of that learning journey.

---

## 📬 Contact
If you’d like to connect, collaborate, or give feedback—feel free to open an issue or connect via GitHub!
