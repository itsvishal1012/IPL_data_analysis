# 🏏 IPL Deliveries Dataset - Exploratory Data Analysis (EDA)

This repository contains a comprehensive Exploratory Data Analysis (EDA) project on the IPL deliveries dataset. It was created as part of a **summer internship project** focused on analyzing T20 cricket matches at a granular, ball-by-ball level.

---

## 📁 Dataset

- **File**: `deliveries.csv`
- **Source**: Ball-by-ball data from IPL matches
- **Records**: 17,183 deliveries
- **Columns**: 19 (including `match_no`, `date`, `batting_team`, `bowling_team`, `striker`, `runs_of_bat`, `extras`, `wicket_type`, etc.)

---

## 🧠 Objectives

- Clean and preprocess the dataset
- Analyze performance metrics (batting, bowling, dismissals)
- Visualize trends using various plots
- Extract key insights about teams, players, and match phases

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Steps Performed in EDA

### 1. **Data Cleaning**
- Converted `date` column to datetime format
- Removed duplicate records
- Handled missing values in columns like `wicket_type`, `player_dismissed`, and `fielder`

### 2. **Univariate Analysis**
- Histograms & boxplots for numerical data (e.g., `runs_of_bat`, `extras`)
- Bar charts for categorical data like `batting_team`, `wicket_type`

### 3. **Bivariate & Multivariate Analysis**
- Correlation heatmap of numerical variables
- Scatter plots to explore relationships (e.g., `runs_of_bat` vs `extras`)
- Violin plots to assess distribution & outliers
- Stacked bar charts for team-wise runs and extras

### 4. **Advanced Visualizations**
- **Pie charts**: Dismissal types, team contribution to total runs
- **Count plots**: Top 10 bowlers by wickets
- **Line plot**: Average runs per over
- **Box & Violin plots**: Distribution and spread of numerical features

---

## 📈 Key Insights

- Top scorers and bowlers based on total runs and dismissals
- Performance trends during powerplay, middle, and death overs
- Extras like wides and no-balls vary significantly by team
- Caught was the most common mode of dismissal

---

## 📂 Files

| File | Description |
|------|-------------|
| `deliveries.csv` | Original raw dataset |
| `cleaned_deliveries.csv` | Cleaned version of dataset used for analysis |
| `IPL_EDA_Deliveries.ipynb` | Jupyter notebook containing all analysis and visualizations |
| `README.md` | This file |

---

## 🚀 How to Run

1. Clone the repo and run this in your pc.

