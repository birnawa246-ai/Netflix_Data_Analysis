# 🎬 Netflix Movie Data Analysis

## 📌 Project Overview

This project is a **Movie Data Analysis** project built using Python. It performs Exploratory Data Analysis (EDA) on a movie dataset to understand movie popularity, ratings, votes, release dates, and genres.

The project uses **Pandas, NumPy, Matplotlib, and Seaborn** for data cleaning, analysis, and visualization.

---

## 🎯 Objectives

* Analyze the movie dataset
* Understand the structure of the data
* Check duplicate and missing values
* Clean and preprocess the dataset
* Analyze movie genres
* Categorize movies based on vote averages
* Find the most popular movies
* Find movies with the lowest popularity
* Create visualizations to understand the data
* Extract useful insights from the dataset

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📂 Project Files

```text
Netflix-Movie-Data-Analysis/
│
├── netfilx.ipynb
├── mymoviedb.csv
└── README.md
```

---

## 📊 Dataset

The dataset contains information about movies such as:

* Release Date
* Movie Title
* Overview
* Popularity
* Vote Count
* Vote Average
* Original Language
* Genre
* Poster URL

The dataset contains approximately **9,827 movie records**.

---

## 🔄 Data Analysis Process

### 1. Data Loading

The dataset is loaded using Pandas.

```python
import pandas as pd

df = pd.read_csv("mymoviedb.csv", lineterminator="\n")
```

### 2. Data Inspection

The following functions are used to understand the dataset:

```python
df.head()
df.info()
df.describe()
```

### 3. Data Cleaning

The project performs several data-cleaning operations:

* Checking duplicate records
* Checking missing values
* Converting release-date information
* Removing unnecessary columns
* Handling missing data

Unnecessary columns removed include:

```text
Overview
Original_Language
Poster_Url
```

---

## ⭐ Vote Average Categorization

The `Vote_Average` column is divided into four categories:

* `not_popular`
* `below_avg`
* `average`
* `popular`

These categories help in understanding the popularity level of movies based on their vote averages.

---

## 🎭 Genre Analysis

The project processes the `Genre` column to analyze the distribution of different movie genres.

The analysis helps identify the most common genres and understand their presence in the dataset.

---

## 📈 Data Visualization

Matplotlib and Seaborn are used to create visualizations and understand patterns in the dataset.

The project analyzes:

* Vote Average Distribution
* Movie Genres
* Popularity
* Vote Count
* Movie Ratings

---

## 🔎 Key Questions

The project answers questions such as:

1. What is the most frequent genre?
2. Which genres are most common?
3. Which movie has the highest popularity?
4. What genre does the most popular movie belong to?
5. Which movie has the lowest popularity?
6. What genre does the least popular movie belong to?

---

## 📌 Key Findings

Based on the analysis:

* **Drama** is the most frequent genre.
* Movies are categorized into four vote-average groups.
* **Spider-Man: No Way Home** appears as one of the highest-popularity movies in the analyzed dataset.
* Its genres include **Action, Adventure, and Science Fiction**.
* The lowest popularity value observed is approximately **13.354**.

---

## 💡 Skills Demonstrated

This project demonstrates practical knowledge of:

* Python
* Pandas
* NumPy
* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Data Visualization
* Missing Value Handling
* Duplicate Detection
* Categorical Data
* Genre Analysis
* Data Interpretation

---

## 👨‍💻 Author

**Subham Maurya**

Computer Science Student

Interested in:

* Data Analytics
* Data Science

---

## ⭐ Project

If you find this project useful, consider giving the repository a ⭐ Star.


