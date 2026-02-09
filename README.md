Exploratory Data Analysis (EDA) – Google Play Store Apps
#Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the Google Play Store dataset to uncover meaningful insights about mobile applications, user behavior, and market trends.
The analysis includes **data cleaning, preprocessing, visualization, and insight generation** using Python.
---
Dataset Information
 **Dataset Name:** Google Play Store Apps
 **Total Records (after cleaning):** ~9,600 apps
 **Features:** App name, category, rating, reviews, installs, size, price, type, content rating, genres, and more.
---

Tools & Technologies Used

* **Python**
* **Pandas** – data manipulation
* **NumPy** – numerical operations
* **Matplotlib & Seaborn** – data visualization
* **Jupyter Notebook / Google Colab**

---

## Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Removed duplicate app records
* Handled missing values
* Converted data types (Reviews, Installs, Price, Size)
* Cleaned string-based numerical columns
* Extracted date features (day, month, year)
* Standardized categorical values

---

## Exploratory Data Analysis

EDA was conducted on both **categorical** and **numerical** variables.

### Categorical Analysis

* App distribution across categories and genres
* Free vs Paid apps comparison
* Content rating analysis
* Category-wise app availability

### Numerical Analysis

* Rating distribution and category-wise average ratings
* Install and review distributions
* Category-wise total installs
* Relationship between ratings, reviews, and installs
* Price and app size analysis

---

## Key Insights

* Majority of apps on the Play Store are **Free (~93%)**
* **GAME** and **FAMILY** categories dominate in terms of app count and installs
* Most apps have ratings **above 4**, indicating positive user feedback
* App installs and reviews are **highly right-skewed**
* Paid apps are concentrated in specific categories like **FAMILY** and **MEDICAL**

---

## Project Structure

```
├── EDA1_GooglePlayStore.ipynb
├── EDA1-GooglePlayStore.pdf
├── README.md
└── dataset/
    └── googleplaystore.csv
```

---

##  How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the notebook:

   ```
   jupyter notebook EDA1_GooglePlayStore.ipynb
   ```

---

## Future Enhancements

* Feature engineering for advanced insights
* Correlation analysis & heatmaps
* Predictive modeling (rating or install prediction)
* Dashboard creation using Power BI / Tableau

---

##  Acknowledgements

Dataset sourced from publicly available Google Play Store data for educational and learning purposes.

---

## Connect With Me

If you have suggestions, feedback, or collaboration ideas, feel free to connect!

---
