# 📊 COVID-19 Exploratory Data Analysis (EDA)

This project analyzes the global COVID-19 pandemic using real-world data from [Worldometer](https://www.worldometers.info/coronavirus/) and performs visual exploratory data analysis (EDA) using Python libraries like **Pandas**, **Seaborn**, and **Matplotlib**.

---

## 📁 Dataset

### 1. `worldometer_data.csv`
Contains COVID-19 statistics per country, including:
- Total Cases, Deaths, Recoveries, Tests
- Population
- Per million metrics (Cases/1M, Deaths/1M)
- Continent & WHO Region

### 2. `country_wise_latest.csv`
Includes:
- Latest cases, deaths, and recoveries per country
- WHO region, population, and testing data

---

## 🧪 Technologies Used

- **Python** 3.x
- **Pandas** – data handling and cleaning
- **Matplotlib** – static plots
- **Seaborn** – advanced visualizations

---

## 📈 Visual Analysis Performed

- ✅ Top 10 countries by total cases, deaths, and tests
- ✅ Histogram of cases per million (with KDE)
- ✅ Correlation heatmap between case metrics
- ✅ Scatter plots:
  - Active cases vs Population
  - Total tests vs Total cases
  - Death rate vs Recovery rate
- ✅ WHO region-wise analysis

---

## 📊 Sample Visuals

> *(You can add images of your plots here)*

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/covid19-eda.git
cd covid19-eda

