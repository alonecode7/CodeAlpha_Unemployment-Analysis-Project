# Unemployment Analysis with Python

## Project Overview

This project analyzes unemployment trends in India using Python-based data analysis and visualization techniques. 

The analysis focuses on:
- unemployment trends over time
- Covid-19 impact on employment
- state-wise unemployment comparison
- urban vs rural unemployment analysis
- monthly unemployment trends
- correlation analysis between employment-related factors

The project uses data cleaning, exploratory data analysis (EDA), and visualization techniques to derive meaningful economic insights from unemployment datasets.

---

# Objectives

- Analyze unemployment rate data representing unemployed population percentage.
- Perform data cleaning and preprocessing using Python.
- Explore and visualize unemployment trends.
- Investigate the impact of Covid-19 on unemployment rates.
- Identify monthly unemployment patterns.
- Present insights useful for economic and social policy analysis.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Dataset Information

Two unemployment datasets were used in this project:

1. `Unemployment in India.csv`
2. `Unemployment_Rate_upto_11_2020.csv`

Taken from [kaggle](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india)

The datasets contain:
- unemployment rate (%)
- employed population
- labour participation rate
- state-wise unemployment data
- urban/rural classification
- Covid-period unemployment statistics

---

# Project Workflow

## 1. Data Loading
- Imported datasets using Pandas.

## 2. Data Cleaning
- Removed missing values.
- Removed duplicate rows.
- Converted date columns into datetime format.
- Standardized column names.

## 3. Exploratory Data Analysis (EDA)
Performed:
- overall unemployment trend analysis
- state-wise unemployment analysis
- urban vs rural comparison
- monthly unemployment trend analysis
- Covid-19 impact analysis
- correlation heatmap analysis

---

# Key Insights

- Unemployment remained relatively stable before Covid-19.
- A major spike in unemployment occurred during April–May 2020.
- Urban areas were more affected than rural areas.
- Significant variation in unemployment rates exists across states.
- Covid-19 caused severe disruption in employment conditions.
- Gradual recovery was observed after lockdown restrictions eased.

---

# Visualizations Included

- Line plots
- Bar charts
- Comparative analysis graphs
- Heatmap correlation analysis

---

# Conclusion

The analysis demonstrates the significant impact of Covid-19 on unemployment in India. 

The project highlights how data analysis and visualization can help understand economic trends and support policy-making decisions.

---

# How to Run the Project

## 1. Clone Repository

```bash
git clone https://github.com/alonecode7/CodeAlpha_Unemployment-Analysis-Project.git
```

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

## 3. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:
```text
Unemployment_Analysis.ipynb
```

---

# Project Structure

```text
Unemployment-Analysis-Project/
│
├── data/
│   ├── Unemployment in India.csv
│   └── Unemployment_Rate_upto_11_2020.csv
│
├── Unemployment_Analysis.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Future Improvements

- Interactive dashboards using Plotly or Streamlit
- Time-series forecasting
- State-wise geospatial visualization
- Machine learning-based unemployment prediction

---

# Author

Shivam Gupta
Data Analyst | Python Developer | Artificial Intelligence and Machine Learning Enthusiast

- Email: [sg.shivamgupta083@gmail.com](mailto:sg.shivamgupta083@gmail.com)
- [GitHub](https://github.com/alonecode7)
- [LinkedIn](https://linkedin.com/in/shivam-gupta02)
