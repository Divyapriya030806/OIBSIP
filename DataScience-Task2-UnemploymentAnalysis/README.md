# Unemployment Analysis in India 📊

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on unemployment data in India to understand unemployment trends, regional variations, and the impact of the COVID-19 period.

The project uses Python libraries to clean, analyze, visualize, and interpret unemployment-related data.

This project was completed as part of the **OASIS INFOBYTE Data Science Internship – Task 2**.

## Dataset

The dataset, **Unemployment in India**, was obtained from Kaggle.

It contains unemployment-related information across different regions of India.

**Dataset Details:**

- Total Records: 740
- Total Columns: 7
- Regions Covered: 28
- Time Period: May 2019 – June 2020
- Areas Covered: Rural and Urban

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. **Data Loading:** Imported the dataset using Pandas.
2. **Data Cleaning:** Handled missing values, checked duplicates, and corrected data types.
3. **Data Exploration:** Examined dataset structure and calculated statistical summaries.
4. **Regional Analysis:** Analyzed average unemployment rates across different regions.
5. **Trend Analysis:** Studied monthly unemployment trends and compared selected states.
6. **Correlation Analysis:** Examined relationships between unemployment rate, estimated employment rate, and labour participation rate.
7. **COVID-19 Impact Analysis:** Compared unemployment rates before and during the COVID-19 period.
8. **Area-wise Analysis:** Compared unemployment rates between Rural and Urban areas.

## Key Findings

- Tripura recorded the highest average unemployment rate at **28.35%**, followed by Haryana at **26.28%**.
- A significant increase in unemployment was observed during April and May 2020.
- The average unemployment rate increased from **9.51% before COVID-19** to **17.77% during the COVID period**.
- This represented an increase of approximately **86.91%**.
- Urban areas recorded a higher average unemployment rate of **13.17%**, compared to **10.32%** in Rural areas.
- Correlation analysis revealed a moderate negative relationship between unemployment rate and the derived employment rate.

## Conclusion

This analysis highlights regional variations in unemployment across India and the significant impact of the COVID-19 period on employment trends.

The project demonstrates how Python and its data analysis libraries can be used to explore real-world datasets, identify patterns, and derive meaningful insights through data visualization.

## Project Structure

```text
Unemployment-Analysis/
│
├── data/
│   └── Unemployment in India.csv
│
├── Unemployment_Analysis.ipynb
│
└── README.md
```

---

**Internship:** OASIS INFOBYTE

**Domain:** Data Science

**Task:** Task 2 – Unemployment Analysis in India
