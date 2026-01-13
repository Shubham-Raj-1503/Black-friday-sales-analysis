# Black Friday Sales Analysis 🛒

A comprehensive exploratory data analysis (EDA) project analyzing Black Friday sales data to uncover customer purchasing patterns and behaviors.

## 📊 Project Overview

This project analyzes Black Friday sales data to understand:
- Customer demographics and their purchasing behavior
- Gender-based spending patterns
- Age group preferences and spending habits
- Marital status impact on purchases
- City-wise sales distribution
- Occupation and product category insights

## 📁 Dataset

The analysis uses `BlackFriday.csv` which contains transactional data with the following features:

| Column | Description |
|--------|-------------|
| User_ID | Unique customer identifier |
| Product_ID | Unique product identifier |
| Gender | Customer gender (M/F) |
| Age | Age group of customer |
| Occupation | Occupation code (0-20) |
| City_Category | City type (A, B, C) |
| Stay_In_Current_City_Years | Years in current city |
| Marital_Status | Marital status (0/1) |
| Product_Category_1 | Primary product category |
| Product_Category_2 | Secondary product category |
| Product_Category_3 | Tertiary product category |
| Purchase | Purchase amount |

## 📓 Notebooks

| Notebook | Description |
|----------|-------------|
| `Black Friday - Walkthrough.ipynb` | Initial data exploration and cleaning |
| `Black Friday - Analysing Columns.ipynb` | Overview of all columns and unique values |
| `Black Friday - Analysing Gender.ipynb` | Gender-based purchase analysis |
| `Black Friday - Analysing Age & Marital Status.ipynb` | Age and marital status impact on purchases |
| `Black Friday - Combining Age & Marital Status.ipynb` | Combined analysis of age, gender, and marital status |
| `Black Friday - MultiColumn Analysis.ipynb` | Cross-column analysis with visualizations |
| `Black Friday - Occupation and Products Analysis.ipynb` | Occupation and product category insights |

## 🔍 Key Analyses

### Gender Analysis
- Gender distribution among customers
- Purchase amount comparison by gender
- Average spending patterns

### Age Analysis
- Purchase distribution across age groups
- Products purchased by different age segments
- Total and average spending by age

### City & Location Analysis
- Sales distribution across city categories
- Customer residency duration impact on purchases

### Occupation & Product Analysis
- Top-selling product categories
- Occupation-wise purchase patterns
- Product preferences by demographics

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **Seaborn** - Statistical data visualization
- **Matplotlib** - Plotting and visualization

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Shubham-Raj-1503/Black-friday-sales-analysis.git
   ```

2. Install required packages:
   ```bash
   pip install pandas seaborn matplotlib
   ```

3. Open the notebooks in Jupyter or VS Code and run the cells sequentially.

## 📈 Sample Visualizations

The notebooks include various visualizations:
- Bar charts for purchase distribution
- Pie charts for ratio analysis
- Count plots for categorical comparisons
- Grouped bar charts for multi-variable analysis

## 📝 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

---

*Happy Analyzing!* 📊
