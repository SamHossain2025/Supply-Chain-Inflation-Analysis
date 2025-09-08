<p align="center">
  <img src="6 Assets/Banner.png" width="100%">
</p>

# 🌍 Supply Chain and Consumer Inflation Analysis of the World

*This project analyzes global Producer Price Inflation (PPI) using World Bank panel data. We cleaned, optimized, and modeled the data using Fixed and Random Effects to reveal policy-relevant insights.*

* Dataset timeline: 2010 January – 2023 December
* Topics covered: **Macroeconomic Data Analysis**
* Models used: **Linear Regression Panel Data**
* Skills demonstrated: **Data Wrangling, VIF, Correlation Filtering, FE/RE Modeling**
* Expected outcome:

  * **Find out global inflation influencers**
  * **Recommend ways to minimize them**

---

## 🏆 Recognition

**UofT Rotman Datathon 2025 Champion Project**

<p align="center">
  <img src="6 Assets/Recognition1.png" width="50%"> <img src="6 Assets/Recognition2.png" width="45%">
</p>

---

## 👥 Authors

**Sam Hossain, Zaheen Mahaey**

---

## 🔍 Problem Statement

**Goal:**

Identify the economic indicators influencing supply chain-related inflation (PPI) across countries, and determine how regional and income-level differences affect the inflation experience.

**Challenges Addressed:**

* Significant multicollinearity among macroeconomic indicators
* Inconsistent missing data across countries and years
* Need for interpretable models with policy relevance
* Evaluating country and group-level fixed effects vs. random variation
* Providing region- and income-specific policy recommendations

---

## 🔧 Workflow

### ✅ Data Preparation

* Consolidated macroeconomic data from World Bank, UNDP, LPI
* Variable filtering using VIF (threshold = 10)
* Correlation threshold filtering (> 0.9)
* Standardization and feature engineering by region & income group
* Panel structure setup with country-year format

### 🤖 Models Built

| Model   | Type    | Features            | Region/Group          | Technique              |
| ------- | ------- | ------------------- | --------------------- | ---------------------- |
| Model 1 | FE + RE | Full variables      | Country-Year          | Initial baseline model |
| Model 2 | FE + RE | Reduced via VIF     | Country-Year          | Intermediate model     |
| Model 3 | FE + RE | VIF + Corr filtered | Region & Income Group | Final robust model     |

**🌟 Verdict:** Model 3 showed strongest statistical clarity and best policy interpretability.

### 💼 Result Interpretation & Recommendations

* Significant inflation drivers found in trade cost, logistics inefficiency, and energy pricing
* Fixed Effects better captured country-level variation; RE showed income group insights
* Policy levers vary between High Income and Low Income countries

---

## 🎯 Key Findings

* Logistic and infrastructure bottlenecks are top inflation drivers
* RE models revealed patterns across income and region levels
* FE models showed strong individual country differences

<p align="center">
  <img src="6 Assets/Findings1.png" width="80%">
  <img src="6 Assets/Findings2.png" width="80%">
  <img src="6 Assets/Findings3.png" width="80%">
  <img src="6 Assets/Findings4.png" width="80%">
  <img src="6 Assets/Findings5.png" width="80%">
</p>


---

## 💡 Key Recommendations

* Improve logistics performance in developing nations
* Promote energy diversification to stabilize price shocks
* Target income-specific strategies (subsidies, tech transfers, etc.)

<p align="center">
  <img src="6 Assets/Recommendation1.png" width="80%">
  <img src="6 Assets/Recommendation2.png" width="80%">
</p>


---

## 🚀 How to Run This Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/SamHossain2025/Supply-Chain-Inflation-Analysis.git
   cd Supply-Chain-Inflation-Analysis
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

4. **Open and execute notebooks**

   * `Datathon_Model_3_Final.ipynb` → Modeling
   * `Datathon_Model_3_Visualization.ipynb` → Exploratory visuals

---

## 🧬 Data Sources

* 📌 [World Bank Open Data](https://data.worldbank.org/)
* 📌 UNDP Human Development Reports
* 📌 LPI, IEDE Indexes

---

## 🔓 License

This project is licensed under the [MIT License](LICENSE)
