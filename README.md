<p align="center">
  <img src="6 Assets/Banner.png" width="100%">
</p>

# 📦 Supply Chain and Consumer Inflation Analysis of the World

*A global analysis of PPI (Producer Price Inflation) using World Bank panel data, with variable optimization via VIF and correlation filtering, and model selection via Fixed and Random Effects modeling.*

- Topics covered: **Macroeconomic Data Analysis**
- Models used: **Linear Regression Panel Data**
- Expected outcome:
    - **Find out global inflation influencers** 
    - **Recommend ways to minimize them**

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

## 🎯 Overview

This project investigates the key drivers of **Producer Price Inflation** across countries using a structured panel dataset sourced from the **World Bank**, **UNDP**, and other development indicators. We applied panel data regression techniques (FE/RE) and selected variables using statistical filters like VIF and correlation thresholds.

---

## 🧠 Key Features

- ✅ **Panel data regression** with country-year granularity
- ✅ **Multicollinearity reduction** using VIF & correlation matrix
- ✅ **Modeling with Fixed Effects and Random Effects**
- ✅ **Hausman Test** to determine the preferred model
- ✅ **Interactive visualizations** for data insight

---

## 🧪 Model Insights

* Multicollinearity handled via VIF (threshold = 10) and correlation > 0.9
* Fixed and Random Effects models built on cleaned features
* Hausman Test used to choose FE vs RE
* Model 3 demonstrated the most **robust results** and interpretability

---

## 🧾 Dashboard

* 🎯 **Presentation:** `presentation/Datathon-2025-Sam_Zaheen_PPT.pptx`
* 📄 **Report:** `presentation/Datathon-2025-Sam_Zaheen_Report.pdf`

Glimpse of our extensive research and findings dashboards:

<p align="center">
  <img src="presentation/assets/dashboard1.jpg" alt="Dashboard 1" width="80%">
  <img src="presentation/assets/dashboard2.jpg" alt="Dashboard 2" width="80%">
  <img src="presentation/assets/dashboard3.jpg" alt="Dashboard 3" width="80%">
  <img src="presentation/assets/dashboard4.jpg" alt="Dashboard 4" width="80%">
  <img src="presentation/assets/dashboard5.jpg" alt="Dashboard 5" width="80%">
  <img src="presentation/assets/dashboard6.jpg" alt="Dashboard 6" width="80%">
  <img src="presentation/assets/dashboard7.jpg" alt="Dashboard 7" width="80%">
  <img src="presentation/assets/dashboard8.jpg" alt="Dashboard 8" width="80%">
</p>

---

## 🚀 How to Run This Project

1. **Clone the repository**

   ```bash
   git clone https://github.com/YOUR_USERNAME/Supply-Chain-Inflation-World-Bank-Data-Analysis.git
   cd Supply-Chain-Inflation-World-Bank-Data-Analysis
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

## 📊 Data Sources

* 📌 [World Bank Open Data](https://data.worldbank.org/)
* 📌 UNDP Human Development Reports
* 📌 LPI, IEDE Indexes

---

## 🔓 License

This project is licensed under the [MIT License](LICENSE)

---






<p align="center">
  <img src="6 Assets/Banner.png" width="100%">
</p>

# 📦 Supply Chain and Consumer Inflation Analysis of the World

*This project analyzes global Producer Price Inflation (PPI) using World Bank panel data. We cleaned, optimized, and modeled the data using Fixed and Random Effects to reveal policy-relevant insights.*

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

## ⚙️ Workflow

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

## 🧪 Key Findings

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

## 🧪 Key Recommendations

* Improve logistics performance in developing nations
* Promote energy diversification to stabilize price shocks
* Target income-specific strategies (subsidies, tech transfers, etc.)

<p align="center">
  <img src="6 Assets/Recommendation1.png" width="80%">
  <img src="6 Assets/Recommendation2.png" width="80%">
  <img src="6 Assets/Recommendation3.png" width="80%">
  <img src="6 Assets/Recommendation4.png" width="80%">
  <img src="6 Assets/Recommendation5.png" width="80%">
</p>



---

## 📊 Output Dashboard

<p align="center">
  <img src="6 Assets/Dashboard1.png" width="80%">
  <img src="6 Assets/Dashboard2.png" width="80%">
  <img src="6 Assets/Dashboard3.png" width="80%">
  <img src="6 Assets/Dashboard4.png" width="80%">
  <img src="6 Assets/Dashboard5.png" width="80%">
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

## 📊 Data Sources

* 📌 [World Bank Open Data](https://data.worldbank.org/)
* 📌 UNDP Human Development Reports
* 📌 LPI, IEDE Indexes

---

## 🔓 License

This project is licensed under the [MIT License](LICENSE)
