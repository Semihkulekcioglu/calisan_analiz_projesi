# 📊 Employee Performance & Salary Analysis Project

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7+-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-purple.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

**[🇬🇧 English](#) • [🇹🇷 Türkçe](README.tr.md)**

</div>

---

## 📖 About The Project

This is a comprehensive **data analysis project** I developed to enhance my data science and statistical analysis skills. Using a synthetic dataset of 500 employees, I aimed to derive meaningful insights by analyzing employee performance, salary, experience, and other features.

I built this project to reinforce the concepts I learned from a **Machine Learning and Data Science** course on Udemy and apply them to real-world problems.

## ✨ Features

- 📊 **Synthetic dataset** creation with 500 employees
- 🔍 **Statistical analysis**: Mean, median, standard deviation, correlation
- 🧹 **Data cleaning**: Missing value handling and feature engineering
- 📈 **15+ visualizations**: Histogram, scatter, box plot, violin plot, heatmap, pair plot
- 🎯 **Department-based** comparisons and performance analysis
- 🔎 **Outlier detection**: Using IQR method
- 📉 **Correlation matrix**: Relationship analysis between variables
- 💼 **Business insights** and recommendations

## 🛠️ Technologies Used

```
Python 3.8+
├── Pandas 2.0+          # Data manipulation and analysis
├── NumPy 1.24+          # Mathematical operations
├── Matplotlib 3.7+      # Data visualization
├── Seaborn 0.12+        # Advanced visualization
└── SciPy 1.10+          # Statistical computations
```

## 📚 Topics Learned and Applied

### 1. Statistical Analysis
- ✅ Measures of central tendency (mean, median, mode)
- ✅ Measures of dispersion (std, variance, range)
- ✅ Correlation and covariance analysis
- ✅ Skewness and kurtosis
- ✅ Percentiles and quartiles

### 2. Data Manipulation (Pandas)
- ✅ DataFrame creation and management
- ✅ Missing value detection and imputation
- ✅ GroupBy operations and aggregation
- ✅ Pivot table creation
- ✅ Data filtering and selection
- ✅ CSV read/write operations

### 3. Mathematical Operations (NumPy)
- ✅ Array operations and vectorization
- ✅ Statistical functions
- ✅ Data normalization and standardization
- ✅ Random number generation

### 4. Data Visualization (Matplotlib & Seaborn)
- ✅ Histograms and distribution plots
- ✅ Scatter plots
- ✅ Bar charts
- ✅ Box plots and outlier detection
- ✅ Violin plots
- ✅ Heatmaps
- ✅ Pair plots (multi-variable relationships)
- ✅ Multi-subplot panels

## 🚀 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Semihkulekcioglu/calisan-analiz-projesi.git
cd calisan-analiz-projesi
```

### 2. Install Required Packages
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 4. Open and Run the Notebook
Open `Calisan_Analiz_Projesi.ipynb` and run the cells sequentially!

## 📊 Project Structure

```
calisan-analiz-projesi/
│
├── 📓 Calisan_Analiz_Projesi.ipynb    # Main analysis notebook (48 cells)
├── 📋 requirements.txt                 # Required Python packages
├── 📄 README.md                        # Main documentation (language selection)
├── 📄 README.tr.md                     # Turkish documentation
├── 📄 README.en.md                     # English documentation
│
└── 📁 Output Files (generated after running notebook)
    ├── calisan_analiz_data.csv        # Analyzed dataset (500 records)
    ├── departman_ozet.csv              # Department summary report
    └── grafik_ciktilar/                # Saved visualizations (PNG, PDF, SVG)
```

## 🎯 Analysis Steps

### Section 1: Data Preparation
1. Importing libraries
2. Creating synthetic dataset with 500 employees
3. Exploring the dataset and general information

### Section 2: Data Cleaning and Preprocessing
4. Detecting and handling missing values
5. Feature engineering (creating new variables)
6. Categorical variable transformations

### Section 3: Statistical Analysis
7. Calculating measures of central tendency
8. Department-based comparisons
9. Creating correlation matrix

### Section 4: Visualizations
10. Basic charts with Matplotlib (histogram, scatter, bar)
11. Advanced charts with Seaborn (box, violin, heatmap)
12. Creating multi-panel visualizations

### Section 5: Outlier Analysis
13. Detecting outliers using IQR method
14. Visualizing outliers

### Section 6: Advanced Pandas Operations
15. Pivot table analysis
16. Detailed aggregation with GroupBy
17. Complex filtering examples

### Section 7: Mathematical Transformations with NumPy
18. Normalization and standardization
19. Statistical calculations

### Section 8: Conclusions and Recommendations
20. Interpreting findings
21. Business intelligence recommendations

## 📈 Sample Visualizations

Types of charts created in this project:

| Chart Type | Purpose | Library |
|------------|---------|---------|
| 📊 Histogram | Distribution analysis | Matplotlib |
| 📍 Scatter Plot | Two-variable relationship | Matplotlib |
| 📊 Bar Chart | Category comparison | Matplotlib |
| 📦 Box Plot | Outlier detection | Seaborn |
| 🎻 Violin Plot | Detailed distribution | Seaborn |
| 🔥 Heatmap | Correlation matrix | Seaborn |
| 🎨 Pair Plot | Multi-variable relationships | Seaborn |
| 🥧 Pie Chart | Proportion display | Matplotlib |

## 💡 Key Findings

### 1. Salary Analysis
- ✅ Average salary: **~65,000 TL**
- ✅ Salary distribution is **right-skewed** (most employees below average)
- ✅ High standard deviation → **Salary inequality exists**

### 2. Department Comparisons
- ✅ **IT department** has the highest average salary
- ✅ Performance differences between departments are **statistically significant**
- ✅ Some departments have **high outlier rates**

### 3. Correlation Findings
- ✅ **Strong positive correlation** between experience and salary (r > 0.8)
- ✅ Performance score is **moderately correlated** with salary
- ✅ Training hours **positively affect** performance

### 4. Outlier Analysis
- ⚠️ **5-7%** of the dataset consists of outliers
- ⚠️ High-salary positions are typically **senior/expert level**
- ⚠️ Some low-performing employees receive **high salaries** (requires investigation)

## 🎓 Learning Source

This project was developed to reinforce the following topics I learned from the **Udemy - Machine Learning and Data Science Course**:

- 📊 **Chapter 4 - Statistics Fundamentals**: Central tendency, dispersion measures
- 🐼 **Chapter 4 - Pandas**: DataFrame, GroupBy, Pivot Tables
- 🔢 **Chapter 4 - NumPy**: Array operations, mathematical functions
- 📈 **Chapter 4 - Matplotlib**: Basic visualizations
- 🎨 **Chapter 4 - Seaborn**: Advanced charts, heatmap, pair plot
- 📦 **Chapter 4 - Box Plot**: Outlier detection, IQR method

## 🔧 Requirements

### Minimum Requirements
- Python 3.8 or higher
- pip (Python package manager)
- Jupyter Notebook or JupyterLab

### Python Libraries
```
pandas>=2.0.0
numpy>=1.24.0
matplotlib>=3.7.0
seaborn>=0.12.0
scipy>=1.10.0
jupyter>=1.0.0
```

## 📝 Usage Examples

### Basic Usage
```python
# Open Jupyter Notebook and run cells sequentially
jupyter notebook Calisan_Analiz_Projesi.ipynb
```

### Saving Charts
```python
# To automatically save charts
import matplotlib.pyplot as plt

plt.savefig('grafik_ciktilar/chart_name.png', dpi=300, bbox_inches='tight')
```

### Reading the Dataset
```python
import pandas as pd

# Reading the dataset created from analysis
df = pd.read_csv('calisan_analiz_data.csv')
print(df.head())
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create a feature branch (`git checkout -b feature/NewFeature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

In short: You are free to use, modify, and distribute this project!

## 📧 Contact

**Semih Külekçioğlu**

- 🐙 **GitHub**: [@Semihkulekcioglu](https://github.com/Semihkulekcioglu)
- 💼 **LinkedIn**: [Your Profile](https://www.linkedin.com/in/yourprofile/)
- 📧 **Email**: your.email@example.com
- 🌐 **Portfolio**: [website.com](https://your-website.com)

## 🌟 If You Like This Project

If you found this project useful:
- ⭐ Give it a **star**
- 🔄 **Fork** it
- 📢 **Share** it

This motivates me to develop more projects! 🚀

## 🙏 Acknowledgments

- **Udemy** - For quality educational content
- **Pandas Team** - For an amazing data analysis library
- **Matplotlib & Seaborn** - For beautiful visualizations
- **GitHub** - For the open-source community

## 📚 My Other Projects

If you'd like to check out my other data science projects:
- [Project 1](https://github.com/Semihkulekcioglu/proje1)
- [Project 2](https://github.com/Semihkulekcioglu/proje2)
- [Portfolio](https://github.com/Semihkulekcioglu)

---

<div align="center">

**Made with Python and ❤️**

![Python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)
![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?logo=Jupyter)

**[⬆ Back to Top](#-employee-performance--salary-analysis-project)**

**[🇹🇷 Türkçe'ye Geç](README.tr.md)**

</div>

