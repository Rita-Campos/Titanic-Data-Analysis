 🚢 Titanic Data Analysis Project

 📊 Project Overview

This project performs an end-to-end data analysis of the Titanic dataset, focusing on data cleaning, exploration, visualization, and reporting.

The goal is to uncover patterns that influenced passenger survival using Python-based data analysis tools.

---

 🎯 Objectives

* Load and explore raw dataset
* Clean and prepare data for analysis
* Analyze survival patterns across key variables
* Create clear visualizations to communicate insights
* Export results into a structured report

---

 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* OpenPyXL (for Excel reporting)
* Jupyter Notebook

---

 📂 Dataset

* Source: Titanic Dataset (CSV format)
* Key features:

  * Passenger class (Pclass)
  * Sex
  * Age
  * Fare
  * Survival (target variable)

---

 🧹 Data Cleaning Process

The dataset required preprocessing before analysis:

* Filled missing **Age** values using the median
* Removed **Cabin** column due to high missing data (~77%)
* Dropped rows with missing **Embarked** values
* Saved a clean dataset for reuse

---

 📊 Exploratory Data Analysis

 🔹 Survival by Gender

* Strong correlation between gender and survival
* Female passengers had significantly higher survival rates

 🔹 Survival by Class

* First-class passengers had higher survival probability
* Third-class passengers had the lowest survival rates

 🔹 Age Distribution

* Survival varied across age groups
* Younger passengers showed different survival trends

 🔹 Fare Analysis

* Higher fares were generally associated with higher survival rates

---

 📊 Visualizations

**Survival Rate by Sex**

![survival-by-sex](my_project/outputs/survival_by_sex.png)

**Survival by Class and Sex**

![survival-by-class-and-sex](outputs/survival_class_sex.png)

**Age Distribution**

![age-distribution](outputs/age_distribution.png)

**Fare Distribution**

![fare-distribution](outputs/fare_distribution.png)

**Fare by Class**

![fare-by-class](outputs/fare_by_class.png)

**Age vs Fare Scatter Plot**

![scatter-survival](outputs/scatter_survival.png)

---

 📊 Reporting

* Generated a structured Excel report using **OpenPyXL**
* Included:

  * Summary statistics
  * Formatted tables
  * Visual elements embedded into the report

---
Project Structure

```
titanic-data-analysis/
├── data/
│   └── Titanic-Dataset.csv
├── notebooks/
│   └── My_Data_Analysis_Project.ipynb
├── outputs/
│   ├── titanic_clean.csv
│   ├── titanic_report_v2.xlsx
│   ├── survival_by_sex.png
│   ├── survival_class_sex.png
│   ├── fare_distribution.png
│   └── scatter_survival.png
└── README.md
```


---

 🚀 How to Run the Project

```bash
pip install pandas numpy matplotlib seaborn openpyxl
jupyter notebook
```

Then open:

```
My_Data_Analysis_Project.ipynb
```

Run all cells from top to bottom.

---

 📌 Key Insights

* Gender is one of the strongest predictors of survival
* Socioeconomic status (class) significantly impacted outcomes
* Fare correlates with survival probability
* Data cleaning is essential before any meaningful analysis

---

 🧠 What I Learned

* How to clean and prepare real-world datasets
* How to create meaningful visualizations
* How to structure a complete data analysis workflow
* How to present results clearly for non-technical audiences

---

 📬 Contact

* Location: Lisbon
* LinkedIn: ([add your link here](https://www.linkedin.com/in/rita-campos-431633112/))


