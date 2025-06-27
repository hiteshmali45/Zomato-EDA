# Zomato-EDA
Here's a README file based on the contents of your uploaded Jupyter Notebook (`zomato_eda_(Hitesh) (1).ipynb`). This assumes the notebook performs Exploratory Data Analysis (EDA) on the Zomato dataset. You can further customize this as needed:

---

# Zomato Dataset Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Zomato Restaurant Dataset** to derive meaningful insights into the food and restaurant landscape. The goal is to understand patterns, trends, and hidden details that can help food businesses or platforms like Zomato make informed decisions.

## 📂 Dataset

* **Source**: Zomato (Kaggle or similar platforms)
* **Contents**: Restaurant information including name, location, rating, cuisine types, cost, and other metadata.

## 📊 Key Objectives

* Clean and preprocess the dataset
* Handle missing and duplicate data
* Explore and visualize key attributes like:

  * Restaurant locations
  * Rating distributions
  * Most popular cuisines
  * Online delivery availability
  * Cost for two people
  * Votes and their correlation with ratings
* Identify business insights through data patterns

## 🔧 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly (if interactive visualizations are used)

## 🧹 Data Cleaning Steps

* Removed irrelevant columns
* Renamed columns for consistency
* Dropped duplicates and missing values
* Standardized categorical values (like country names, city names, etc.)
* Converted appropriate columns to numerical types

## 📈 Visualizations & Insights

Some of the questions explored:

* Which countries have the most restaurant data?
* What are the most popular cuisines?
* Which cities have the highest number of restaurants?
* What is the average rating and what factors affect it?
* How does cost vary with cuisines and locations?
* Do restaurants offering online delivery get better ratings?

## 🧠 Key Insights

* The majority of restaurants are located in India.
* North Indian cuisine is among the most common.
* Higher-rated restaurants often receive more votes.
* Online delivery is more common in urban areas.
* Premium cities show a trend of higher cost-for-two.

## 📁 File Structure

```
zomato_eda_(Hitesh).ipynb    # Jupyter Notebook with EDA
README.md                    # Project overview and summary
```

## ✅ How to Run

1. Clone this repository.
2. Make sure you have Python 3.x installed with the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
3. Run the notebook using Jupyter:

   ```bash
   jupyter notebook zomato_eda_(Hitesh).ipynb
   ```
