# EDA Project 
# Catholic Student Achievement Dataset

---

This repository contains the `catholic.csv` dataset, which records student-level standardized reading and math scores, demographic data, and family background characteristics. The data enables analysis of educational achievement among students, with particular emphasis on differences related to Catholic vs. non-Catholic school attendance and various demographic and socioeconomic factors.

---

## 📂 Dataset

| Column         | Type      | Description |
|----------------|-----------|-------------|
| read12         | Numeric   | Reading scores (grade 12) |
| math12         | Numeric   | Math scores (grade 12) |
| motheduc       | Numeric   | Mother’s education (years) |
| fatheduc       | Numeric   | Father’s education (years) |
| lfaminc        | Numeric   | Log family income |
| female         | Binary    | 0 = Male, 1 = Female |
| asian          | Binary    | 1 if Asian, else 0 |
| hispan         | Binary    | 1 if Hispanic, else 0 |
| black          | Binary    | 1 if Black, else 0 |
| cathhs         | Binary    | 1 if attended Catholic HS |
| parcath        | Binary    | 1 if parents are Catholic |
| hsgrad_category|Categorical| HS Graduation status/category |

---

## 📌 Features
The script includes:

### 1. **Data Preparation**
- Loads the dataset (`catholic.csv`)
- Handles categorical encoding
- Missing values visualization
- Scaling for multivariate techniques

### 2. **Statistical Analysis**
- Descriptive statistics for numeric columns:
- Range (min–max) calculations
- Outlier identification via boxplots

### 3. **Univariate Analysis**
- Histograms & KDE plots
- Boxplots & violin plots
- Bar plots and pie charts for categorical variables

### 4. **Bivariate Analysis**
- Scatterplots with regression lines
- Boxplots (numeric vs categorical variables)
- Correlation heatmaps
- Violin plots grouped by category

### 5. **Multivariate Analysis**
- Pairplots (scaled variables) with hue
- PairGrid scatter/density combinations
- 3D scatter plots
- Correlation heatmaps

---
