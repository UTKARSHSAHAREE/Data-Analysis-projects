# Data-Analysis-projects
This is my Starting Individual project for learning purpose
# 📊 Data Analysis Portfolio

Welcome to my collection of data analysis projects! This repository showcases various exploratory data analyses demonstrating statistical concepts, data visualization techniques, and real-world problem-solving using Python.

---

## 📁 Projects Overview

### 1. [Drug Impact on Memory Recall](./kaggle(Druggers_Island).ipynb)
**Analysis of anti-anxiety medications vs. placebo on memory performance**

**Key Insights:**
- **Drug A (Peach)** : Most variable effect with wide score spread (improvements up to +50 points)
- **Drug T (Teal)** : Most consistent but minimal effect (tight clustering around 0-5 points)
- **Placebo (Yellow)** : Expected sugar pill effect with scores near baseline
- **Sampling Demonstration**: Small sample (n=50) vs. population (n=1138) comparison reveals how limited data can mask true patterns
- **Demographic Factors**: Age categories (Young, Adult, Senior) show different drug responses; Adults most positively impacted

**Skills**: Statistical analysis, data visualization, sampling theory, demographic analysis

---

### 2. [Statistical Distributions & Car Crash Analysis](./Car_crash_Analysis(Distribution).ipynb)
**Comprehensive guide to probability distributions with real crash data application**

**Statistical Distributions Covered:**
- Uniform, Normal, Exponential, Logistic, Poisson, Gamma, Beta, Chi-square

**Key Techniques:**
- **Outlier Detection**: IQR-based tagging system with visualization
- **Binning Strategy**: Converting continuous variables into categorical buckets
- **Log Transformation**: Converting skewed distributions to normal
- **KDE Plots**: Understanding probability density across groups

**Crash Data Findings:**
- Insurance losses follow semi-normal distribution with moderate variance
- Speeding and total crashes show complex relationship
- Right-side outliers in alcohol-related crashes identified

**Skills**: Distribution theory, outlier detection, data transformation, feature engineering

---

### 3. [Palmer Penguins: Species & Sexual Dimorphism](./penguins_Dataset.ipynb)
**In-depth analysis of penguin morphology across species and islands**

**Key Findings:**
- **Sexual Dimorphism**: Males significantly larger than females across all measurements
- **90% Confidence Intervals**:
  - Bill Length: Males (43.2-49.3mm) vs. Females (38.7-45.9mm)
  - Body Mass: Males (4138-4996g) vs. Females (3394-4226g)
- **Island Distribution**: 
  - Gentoo exclusively on Biscoe (35.7% of total)
  - Chinstrap only on Dream (20.4%)
  - Adelie across all three islands
- **Correlations**: Flipper length vs. Body mass (0.87), Bill length vs. Flipper length (0.66)

**Statistical Concepts**: Confidence intervals, sampling distributions, stratified sampling, correlation analysis

---

## 🛠️ Core Skills Demonstrated

### Data Manipulation
- Pandas for data cleaning, transformation, and aggregation
- Grouping and pivoting for stratified analysis
- Handling missing values

### Statistical Analysis
- Hypothesis testing concepts through confidence intervals
- Correlation analysis
- Outlier detection (IQR method)
- Distribution fitting and transformation

### Visualization
- Matplotlib and Seaborn for publication-quality plots
- Histograms, KDE plots, box plots, scatter plots
- Color-coded visualizations for group comparisons
- Pie charts for categorical distributions

### Key Statistical Concepts
- Sampling distributions
- Confidence intervals (90%, 95%)
- Central Limit Theorem demonstration
- Stratified vs. random sampling
- Binning and categorization
- Log transformations

---

## 🎯 Learning Outcomes

These projects demonstrate:
1. **Real-world application** of statistical concepts
2. **Critical thinking** about data quality and sampling
3. **Effective visualization** for insight communication
4. **Biological/medical interpretation** of quantitative results
5. **Practical Python implementation** of analysis workflows

---

## 🚀 Getting Started

Each notebook is self-contained with:
- Clear markdown explanations
- Step-by-step code execution
- Visual outputs embedded
- Key takeaways summarized

**Requirements:**
```python
pandas
numpy
matplotlib
seaborn
```

---

## 📫 Connect

Feel free to explore the analyses, reproduce the results, or adapt the techniques for your own projects!

---

*"The goal is to turn data into information, and information into insight."*
