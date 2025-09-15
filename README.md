# Exploratory Data Analysis (EDA) on Insurance Dataset

This project explores the **Medical Insurance Cost dataset** from Kaggle.  
It contains 1338 records of individuals with features like age, sex, BMI, smoker status, number of children, and region, along with their medical insurance charges.

## 📂 Files
- `dataset/insurance.csv` → The dataset.  
- `eda_notebook.ipynb` → Jupyter Notebook with code + plots.  
- `eda_script.py` → Python script to generate plots.  
- `plots/` → Contains saved visualizations (PNG).  
- `insights.txt` → Summary insights from analysis.  

## 📊 Visualizations
Screenshots of important plots (generated in `plots/`):
- Histogram of **Age**
- Boxplot of numeric features
- KDE (density) plots of age, BMI, and children
- Bar chart of mean charges by smoker
- Scatter matrix of numeric features

## 🔑 Insights
- **Smoker status is the strongest predictor** of charges: smokers (~32k) vs non-smokers (~8.4k).  
- **Age** is moderately correlated with charges (corr ≈ 0.30).  
- **BMI** is weakly correlated (corr ≈ 0.20); more than 52% are obese (BMI ≥ 30).  
- **Children** has minimal effect (corr ≈ 0.07).  
- **Sex and region** show only small differences in mean charges.  
- Distribution of charges is **right-skewed** with outliers.

## 🚀 How to Run
Clone/download the repo and run either:
```bash
# run script
python eda_script.py
