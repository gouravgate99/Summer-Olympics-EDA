# 🥇 Summer Olympics Dataset: Comprehensive Exploratory Data Analysis (EDA)

## Project Overview

This project is an in-depth **Exploratory Data Analysis (EDA)** of the modern-day Summer Olympic Games dataset. The analysis follows a structured roadmap of data preparation, cleaning, visualization, and inference generation to uncover meaningful patterns and insights about the athletes, events, and medal history across 120 years of Olympic history.

## 📊 Dataset

The dataset provides a comprehensive record of athlete-event entries from the **1896 Athens Olympics to the 2016 Rio Olympics**.

| Attribute | Description |
| :--- | :--- |
| **ID** | Unique number for each athlete |
| **Name** | Athlete's name |
| **Sex** | M or F |
| **Age** | Athlete's age (Integer) |
| **Height** | Athlete's height (in centimeters) |
| **Weight** | Athlete's weight (in kilograms) |
| **Team** | Team name |
| **Medal** | Gold, Silver, Bronze, or NaN (No Medal) |

* **Size:** 271,116 instances (athlete-events) and 15 attributes.
* **Source:** [120 years of Olympic History: Athletes and Results (Kaggle)](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results).

## 🛠️ Tools and Libraries

The project is implemented in a Jupyter Notebook using Python and key libraries for data manipulation and visualization.

* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `matplotlib.pyplot`, `seaborn`, `plotly.express`

## 📝 Analysis Roadmap

The EDA follows a standard sequence of steps:

1.  **Data Loading:** Importing the primary athlete-events data (`athlete_events.csv`) and the NOC regions data (`noc_regions.csv`).
2.  **Data Cleaning & Preparation:**
    * Inspecting data types and summary statistics.
    * Identifying and fixing missing/incorrect values in columns like `Age`, `Height`, `Weight`, and `Medal`. The analysis noted a significant percentage of missing values in `Notes`, `Medal`, `Weight`, and `Height`.
    * Merging the two datasets for a comprehensive view.
3.  **Exploratory Analysis & Visualization:**
    * Asking and answering various questions related to the dataset using statistical results and mathematical visualizations.
    * Generating charts for distributions (e.g., Age, Height, Weight) and relationships (e.g., Medal counts by country, sport, and year).

## 💡 Key Inferences & Conclusion

The notebook successfully analyzes the dataset and comes up with **solid inferences** using data analysis and visualization techniques.

***

## 💻 How to Run the Notebook

1.  **Install Dependencies:** Ensure you have Python and the required libraries installed. You can install them using pip:
    ```bash
    pip install pandas numpy matplotlib seaborn plotly jupyter
    ```
2.  **Download Data:** Obtain the "120 years of Olympic history: Athletes and Results" dataset (e.g., from Kaggle).
3.  **Run:** Open the Jupyter Notebook in your environment:
    ```bash
    jupyter notebook summer-olympics-dataset-a-comprehensive-eda.ipynb
    ```
4.  **Execute:** Run the cells sequentially to see the data processing and visualizations.
