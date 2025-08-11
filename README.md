# OIBSIP_Data_Analytics_Project3_Level1
#  NYC Airbnb Data Cleaning Project

##  Project Overview
This project focuses on **cleaning and preprocessing** the `AB_NYC_2019.csv` dataset to ensure it is ready for analysis or machine learning tasks.  
The dataset contains details about Airbnb listings in New York City, including price, location, and host information.  
Data cleaning steps were performed to handle missing values, remove duplicates, standardize formats, and detect/remove outliers.

---

##  Aim
To improve the quality of the NYC Airbnb dataset by ensuring:
- No missing or inconsistent values in important fields
- Removal of duplicate records
- Standardized text formatting
- Detection and removal of extreme outliers

---

##  Dataset
**Source:** https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data
**File Used:** `AB_NYC_2019.csv`  
**Rows:** 48,895  
**Columns:** 16  

---

##  Technologies Used
- **Python 3.x**
- **Pandas** - Data manipulation
- **NumPy** - Numerical operations
- **Matplotlib** & **Seaborn** - Data visualization

---

##  Steps Performed
1. **Import Required Libraries**
2. **Load the Dataset**
3. **Inspect the Dataset**
4. **Visualize Missing Values**
5. **Handle Missing Data**
6. **Remove Duplicate Rows**
7. **Standardize Data Formatting**
8. **Outlier Detection (Price)**
9. **Handle Outliers using IQR**
10. **Visualize Data After Cleaning**
11. **Save the Cleaned Dataset**
12. **Summarize Improvements**

---

##  Key Improvements
| Step | Before Cleaning | After Cleaning |
|------|----------------|----------------|
| Missing Values | Present in multiple columns | Handled & filled |
| Duplicate Rows | Yes | Removed |
| Price Outliers | Extreme values present | Removed using IQR |
| Text Formatting | Mixed case | Standardized to lowercase |

---

## Visualizations
- Missing Values Heatmap
- Price Distribution Before Cleaning
- Price Distribution After Outlier Removal

---


