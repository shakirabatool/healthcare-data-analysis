# Healthcare Patient Analysis & Insights


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/shakirabatool/healthcare-data-analysis/blob/main/LICENSE)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shakirabatool/healthcare-data-analysis/blob/main/notebooks/healthcare_analysis.ipynb)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)



## 📌 Project Overview

This project analyzes a healthcare patient dataset to identify patterns and insights related to patient demographics, medical conditions, hospital admissions, billing, length of stay, and other healthcare-related factors.

The project follows a complete data analysis workflow, starting from data cleaning and exploratory data analysis (EDA) to visualization, key findings, and recommendations.

The main goal is to transform raw healthcare data into meaningful insights that can support data-driven understanding of patient and hospital patterns.


## 🎯 Project Objectives 

The main objectives of this project are to:

* Understand the structure and characteristics of the healthcare dataset.
* Clean and prepare the data for analysis.
* Explore patient demographics and medical conditions.
* Analyze admission types and hospital stay patterns.
* Examine billing patterns across different medical conditions.
* Create meaningful data visualizations.
* Identify important findings from the analysis.
* Provide data-driven recommendations based on the results.



## 📊 Dataset

The dataset contains **55,500 patient records initially** with information related to:

* Patient Name
* Age
* Gender
* Blood Type
* Medical Condition
* Date of Admission
* Doctor
* Hospital
* Insurance Provider
* Billing Amount
* Room Number
* Admission Type
* Discharge Date
* Medication
* Test Results

After data cleaning and duplicate removal, the final dataset contained **54,860 records and 15 columns**.



## 🛠️ Tools & Technologies

The following tools and libraries were used:

* **Python**
* **Jupyter Notebook**
* **Pandas** – data manipulation and analysis
* **NumPy** – numerical operations
* **Matplotlib** – data visualization
* **Seaborn** – statistical visualization
* **Git & GitHub** – project version control and portfolio management



## 🧹 Data Cleaning

Several data-cleaning steps were performed before analysis:

* Checked the structure and data types of the dataset.
* Identified and removed duplicate records.
* Standardized inconsistent patient name formats.
* Checked for missing values.
* Reviewed numerical values for inconsistencies.
* Removed invalid negative billing amounts.
* Converted admission and discharge dates into appropriate datetime formats.
* Created a **Length of Stay** column using admission and discharge dates.
* Created **Length of Stay Categories** to group hospital stays.
* Created a **Billing per Day** column to examine billing relative to length of stay.

After cleaning, duplicate records were removed and the dataset was prepared for further analysis.



## 🔎 Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the distribution and patterns within the dataset.

The analysis focused on:

* Patient age distribution
* Gender distribution
* Medical condition frequency
* Admission type
* Billing amounts
* Length of hospital stay
* Billing per day
* Relationships between selected healthcare variables

Descriptive statistics and visualizations were used to identify patterns and differences within the dataset.



## 📈 Data Visualizations

Several visualizations were created using **Matplotlib and Seaborn** to communicate the findings clearly.

### Medical Conditions

The most frequently recorded medical conditions were:

| Medical Condition | Number of Patients |
| ----------------- | -----------------: |
| Arthritis         |              9,207 |
| Diabetes          |              9,197 |
| Hypertension      |              9,131 |
| Obesity           |              9,127 |
| Cancer            |              9,121 |
| Asthma            |              9,077 |

The distribution is relatively balanced, with no single medical condition dominating the dataset.

### Age Distribution

The dataset includes patients between **13 and 89 years old**, with an average age of approximately **51.5 years**.

### Admission Type

The analysis also examined patient admissions across:

* Emergency
* Urgent
* Elective

This helped identify differences in patient admission patterns and hospital stay duration.

### Billing Analysis

Billing amounts were compared across medical conditions to identify differences in average healthcare costs.

### Length of Stay

Length of stay was calculated from the admission and discharge dates to analyze how long patients remained in the hospital.



## 💡 Key Findings

The analysis produced several important findings:

* The cleaned dataset contained **54,860 patient records**.
* The average patient age was approximately **51.5 years**.
* Arthritis was the most frequently recorded medical condition with **9,207 cases**.
* Asthma had the lowest frequency among the six listed conditions, with **9,077 cases**.
* The distribution of medical conditions was relatively balanced.
* Average length of stay was very similar across admission types.
* Emergency admissions had an average stay of approximately **15.6 days**, compared with **15.5 days for Elective** and **15.4 days for Urgent** admissions.
* Obesity had the highest average billing amount among the analyzed conditions at approximately **25,859**.
* Cancer had the lowest average billing amount among the analyzed conditions at approximately **25,206**.



## 📌 Recommendations

Based on the analysis, the following recommendations were identified:

1. **Prioritize chronic condition management**
   Healthcare providers can give particular attention to frequently occurring conditions such as Arthritis, Diabetes, and Hypertension through appropriate monitoring and preventive-care strategies.

2. **Maintain balanced healthcare resource planning**
   Since the medical conditions were relatively evenly distributed, healthcare resources should be planned across multiple conditions rather than focusing primarily on one condition.

3. **Consider the needs of older patients**
   With an average patient age of approximately 51.5 years, healthcare organizations should consider services and monitoring strategies appropriate for middle-aged and older patient populations.

4. **Monitor billing patterns**
   Differences in average billing across medical conditions can be monitored to better understand healthcare resource utilization and potential cost variations.

5. **Monitor hospital stay duration**
   Since average length of stay was similar across admission types, healthcare organizations can examine additional factors that may influence hospital stay duration rather than relying on admission type alone.


## 📁 Project Structure
```text
Healthcare-Patient-Analysis/
│
├── data/
│   └── healthcare.csv
│
├── images/
│   ├── Age_Distribution.png
│   ├── avg_billing_amount.png
│   ├── avg_length_of_stays.png
│   └── ...
│
├── notebooks/
│   └── healthcare_analysis.ipynb
│
├── LICENSE
├── README.md
├── requirements.txt
└── .gitignore
```



## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/shakirabatool/healthcare-data-analysis
```

### 2. Navigate to the Project Folder

```bash
cd Healthcare-Patient-Analysis
```

### 3. Create or Activate the Python Environment

Install the required libraries using:

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook located inside the `notebooks` folder and run the cells sequentially.

---

## 📚 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Data Visualization
* Statistical Analysis
* Feature Creation
* Healthcare Data Analysis
* Python for Data Analysis
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Data Interpretation
* Data-Driven Recommendations

---

## 👩‍💻 Author

**Shakira Batool**

Data Scientist | Data Analytics | Python | SQL | Power BI

This project is part of my data science portfolio and demonstrates my ability to clean, analyze, visualize, and interpret real-world healthcare data to generate meaningful insights and data-driven recommendations.
