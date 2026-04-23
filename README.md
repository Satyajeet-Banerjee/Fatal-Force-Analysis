# 🕊️ US Police Fatal Shootings Data Analysis (2015–2017)

## 📌 Project Overview
This project analyzes fatal police shootings in the United States from 2015 to 2017 using publicly available datasets compiled by *The Washington Post*. The goal is to explore patterns related to race, age, gender, mental health, armed status, and socio-economic factors such as poverty and education.

---

## 📊 Datasets Used

This project combines multiple datasets:

### 1. Fatal Police Shootings Dataset
- Source: The Washington Post
- Contains details like:
  - Age, race, gender
  - Armed status
  - Mental illness indicators
  - Location and date

### 2. US Census Socio-Economic Data
- Median household income (2015)
- Poverty rate
- High school graduation rate
- Racial demographics by city

---

## 🧹 Data Cleaning & Preprocessing
- Handled missing values in income, race, age, and armed status
- Standardized city and state names
- Converted categorical values into numeric format
- Created new feature: `weapon_category`
- Mapped race codes into readable categories

---

## 📈 Key Analyses Performed

### 1. Socio-Economic Analysis
- Poverty rate by state
- High school graduation rate by state
- Relationship between poverty and education

### 2. Race & Demographics
- Racial composition across US states
- Race distribution in police shootings
- Comparison of population vs shooting rates in cities

### 3. Police Shooting Insights
- Age distribution of victims
- Gender distribution
- Armed vs unarmed cases
- Type of weapons involved
- Mental illness percentage among victims

### 4. Geographic Analysis
- Top cities with highest police killings
- State-wise distribution of fatalities
- Choropleth map of killings across the US

### 5. Time Series Analysis
- Yearly trend of police shootings (2015–2017)

---

## 📊 Key Insights

- A significant majority of victims were armed (especially with firearms)
- A noticeable percentage of cases involved individuals with mental illness
- Younger individuals (<25 years) account for a smaller but important portion of cases
- Certain states show higher poverty rates and higher incidents of police shootings
- Racial disparities are visible when comparing population vs victim distribution
- Police killings slightly declined after 2015 peak

---

## 📌 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

---

## 📷 Visualizations Included
- Bar charts
- Line plots
- KDE plots
- Pie charts (donut style)
- Regression plots
- Choropleth map (USA)

---

## 🚀 How to Run This Project

```bash
1. Clone the repository:

```
git clone https://github.com/Satyajeet-Banerjee/Fatal-Force-Analysis.git
```

2. Open the notebook:

```
jupyter notebook
```

3. Run all cells
