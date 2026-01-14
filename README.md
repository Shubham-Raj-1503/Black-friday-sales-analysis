<div align="center">

# 🛍️ BLACK FRIDAY SALES ANALYSIS

### *Decoding the Shopping Frenzy — One Data Point at a Time*

[![Python](https://img.shields.io/badge/Python-3.8+-FFD43B?style=for-the-badge&logo=python&logoColor=blue)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" alt="line" width="100%">

```
🏷️ 537,577 Transactions  •  5,891 Customers  •  3,623 Products  •  1 Epic Analysis
```

</div>

---

## 🎯 What's This About?

> **"The best time to buy is Black Friday. The best time to analyze is NOW."**

Ever wondered what makes Black Friday tick? This project dives deep into the chaos of the biggest shopping day of the year, revealing hidden patterns in customer behavior, demographics, and purchasing decisions.

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│   👤 WHO buys?        →  Demographics deep-dive                 │
│   🛒 WHAT do they buy? →  Product category analysis             │
│   💰 HOW MUCH?         →  Spending patterns revealed            │
│   🏙️ WHERE from?       →  City-wise behavior mapping            │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

</div>

---

## 📊 The Story in Numbers

<div align="center">

| 🔢 Metric | 📈 Value |
|:---------:|:--------:|
| Total Transactions | **537K+** |
| Unique Customers | **5,891** |
| Products Analyzed | **3,623** |
| Age Groups | **7** |
| City Categories | **3** |
| Occupations | **21** |

</div>

---

## 🗂️ Dataset Blueprint

<div align="center">

```
📦 BlackFriday.csv
│
├── 👤 CUSTOMER DATA
│   ├── User_ID ─────────── Unique shopper fingerprint
│   ├── Gender ──────────── M / F
│   ├── Age ─────────────── Age brackets (0-17 to 55+)
│   ├── Occupation ──────── Career codes (0-20)
│   └── Marital_Status ──── Single(0) / Married(1)
│
├── 🏙️ LOCATION DATA
│   ├── City_Category ───── City tier (A/B/C)
│   └── Stay_In_City_Years ─ Residency duration
│
└── 🛒 PURCHASE DATA
    ├── Product_ID ──────── Unique product code
    ├── Product_Category ── 1, 2, 3 (hierarchical)
    └── Purchase ────────── 💵 Amount spent
```

</div>

---

## 📓 Analysis Journey

Navigate through our modular notebook collection:

<div align="center">

| # | 📒 Notebook | 🎯 Focus | 🔍 You'll Discover |
|:-:|:------------|:---------|:-------------------|
| 1️⃣ | **Walkthrough** | 🚀 Getting Started | Data loading, cleaning, null handling |
| 2️⃣ | **Analysing Columns** | 🔬 Data Discovery | Unique values, data types, overview |
| 3️⃣ | **Analysing Gender** | 👫 Gender Insights | Who spends more? M vs F showdown |
| 4️⃣ | **Age & Marital Status** | 🎂💍 Life Stage | Age groups & relationship impact |
| 5️⃣ | **Combining Demographics** | 🔗 Deep Merge | Gender + Marital combo analysis |
| 6️⃣ | **MultiColumn Analysis** | 📊 Cross-Patterns | City × Age × Gender correlations |
| 7️⃣ | **Occupation & Products** | 💼📦 Career Buys | What professions buy what |

</div>

---

## 🔮 Key Discoveries

<div align="center">

### 👫 Battle of the Sexes

```
╔═══════════════════════════════════════════════╗
║                                               ║
║   👨 MALE SHOPPERS        👩 FEMALE SHOPPERS  ║
║   ═══════════════        ══════════════════   ║
║                                               ║
║   🔥 75% of buyers       💎 25% of buyers     ║
║   💰 Higher spending     🎯 Focused purchases ║
║                                               ║
╚═══════════════════════════════════════════════╝
```

### 🎂 Age Tells a Story

```
     26-35 yrs   ████████████████████  🏆 TOP SPENDERS
     36-45 yrs   ████████████████  
     18-25 yrs   ██████████████ 
     46-50 yrs   ████████
     51-55 yrs   ██████
     55+   yrs   █████
     0-17  yrs   ███
```

### 🏙️ City Chronicles

| City Type | Transactions | Spending Pattern |
|:---------:|:------------:|:-----------------|
| 🌆 **B** | Highest | Urban millennials rule |
| 🏙️ **C** | Medium | Steady & consistent |
| 🌃 **A** | Lower | Premium but selective |

</div>

---

## 🎨 Visualization Showcase

Our notebooks feature rich, insightful visualizations:

<div align="center">

| 📊 Chart Type | 🎯 Used For |
|:--------------|:------------|
| 📊 Bar Charts | Purchase distributions, comparisons |
| 🥧 Pie Charts | Ratio analysis, proportions |
| 📈 Count Plots | Categorical frequency analysis |
| 📉 Grouped Bars | Multi-variable comparisons |
| 🔥 Heatmaps | Correlation discovery |

</div>

---

## 🚀 Quick Start

### Prerequisites

```bash
pip install pandas seaborn matplotlib
```

### Launch the Analysis

```bash
# Clone the repo
git clone https://github.com/Shubham-Raj-1503/Black-friday-sales-analysis.git

# Navigate to project
cd Black-friday-sales-analysis

# Fire up Jupyter
jupyter notebook
```

### Recommended Order

```
1️⃣ Walkthrough → 2️⃣ Columns → 3️⃣ Gender → 4️⃣ Age → 5️⃣ Combined → 6️⃣ Multi → 7️⃣ Products
```

---

## 📁 Project Structure

```
Black-friday-sales-analysis/
│
├── 📊 BlackFriday.csv                                    # Raw dataset
│
├── 📓 Black Friday - Walkthrough.ipynb                   # Start here!
├── 📓 Black Friday - Analysing Columns.ipynb             # Data overview
├── 📓 Black Friday - Analysing Gender.ipynb              # Gender analysis
├── 📓 Black Friday - Analysing Age & Marital Status.ipynb
├── 📓 Black Friday - Combining Age & Marital Status.ipynb
├── 📓 Black Friday - MultiColumn Analysis.ipynb
├── 📓 Black Friday - Occupation and Products Analysis.ipynb
│
└── 📖 README.md                                          # You are here!
```

---

## 🛠️ Tech Stack

<div align="center">

| Tool | Purpose |
|:----:|:--------|
| 🐍 **Python** | Core programming language |
| 🐼 **Pandas** | Data manipulation wizard |
| 🎨 **Seaborn** | Beautiful statistical plots |
| 📊 **Matplotlib** | Foundational visualizations |
| 📓 **Jupyter** | Interactive analysis environment |

</div>

---

## 💡 What's Next?

<div align="center">

| 🔮 Enhancement | 📝 Description |
|:---------------|:---------------|
| 🤖 ML Models | Predict purchase amounts |
| 📱 Dashboard | Interactive Streamlit/Dash app |
| 🔗 API | RESTful access to insights |
| 📈 Time Series | Seasonal trend analysis |
| 🎯 Clustering | Customer segmentation |

</div>

---

## 🤝 Contributing

Love data? Have ideas? Jump in!

```
1. 🍴 Fork it
2. 🌿 Branch it (git checkout -b feature/CoolAnalysis)
3. 💾 Commit it (git commit -m 'Add CoolAnalysis')
4. 📤 Push it (git push origin feature/CoolAnalysis)
5. 🎉 PR it!
```

---

## 📜 License

Open source for **educational purposes**. Learn, explore, share!

---

<div align="center">

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" alt="line" width="100%">

### ⭐ Star this repo if it helped you understand Black Friday shopping!

**Built with 🛒 and lots of ☕**

*May your analysis be as deep as Black Friday discounts!*

**[⬆ Back to Top](#️-black-friday-sales-analysis)**

</div>
