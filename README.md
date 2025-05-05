# PRODIGY_DS_05

# Prodigy InfoTech Data Science Internship  
## Task 05: US Accidents (March 2023) Dataset Analysis

### 📌 Objective:
To analyze and build a machine learning model using the US Accidents dataset from Kaggle. The aim is to explore accident patterns, identify key features influencing accident severity, and develop a predictive model.

### 📁 Dataset:
- **Source**: [US Accidents (March 2023) - Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **File Used**: `US_Accidents_March23.csv`

### 🔍 Key Steps Performed:

1. **Data Preprocessing**
   - Loaded the dataset and checked shape, info, and missing values.
   - Dropped irrelevant or high-missing-value columns (`Number`, `Wind_Chill(F)`, `Precipitation(in)`, etc.).
   - Handled missing values using `.dropna()` for critical columns.
   - Converted time columns (`Start_Time`, `End_Time`) to datetime and extracted `Hour`, `Weekday`, and `Month`.

2. **Exploratory Data Analysis (EDA)**
   - Distribution of severity levels.
   - Accidents by state, hour, weekday, and month.
   - Weather and visibility analysis.
   - Top 10 states with highest accident counts (bar chart).
   - Correlation heatmap between numerical features.

3. **Feature Engineering**
   - Created new features from date/time columns.
   - Encoded categorical variables using `LabelEncoder`.
   - Selected important columns for modeling (`Severity`, `Temperature(F)`, `Humidity(%)`, etc.).

4. **Modeling**
   - Built a **Random Forest Classifier** to predict accident severity.
   - Performed train-test split with 80:20 ratio.
   - Evaluated using:
     - Accuracy
     - Confusion Matrix
     - Classification Report

5. **Feature Importance**
   - Identified top features influencing severity (e.g., `Visibility`, `Humidity`, `Temperature`, etc.).

6. **Visualization**
   - Bar charts, count plots, histograms, and heatmaps using `matplotlib` and `seaborn`.

### 📈 Results:
- Random Forest achieved a reasonable accuracy in predicting accident severity.
- Features like **visibility**, **humidity**, and **weather condition** had significant impact.

### 🛠️ Libraries Used:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `datetime`

### 📌 Learnings:
- Handling real-world messy data with missing values and redundant features.
- Feature engineering using datetime.
- Model building and evaluation for multiclass classification.
- Visualization for better understanding of data distribution and patterns.

### 🏁 Internship Task Completion:
This was the **final task (Task 05)** of the **Data Science Internship** under **Prodigy InfoTech**, successfully completed by analyzing a real-world dataset with comprehensive steps from EDA to machine learning modeling.

---

✅ **Task Completed By**: *[Ankita Raje]*  
🎓 **Internship Role**: Data Science Intern  
🏢 **Organization**: Prodigy InfoTech  
📅 **Task**: 05 – US Accidents Data Analysis
