# Indian Bail Judgments Analysis

## 📊 Project Overview

This project analyzes **1,200 Indian bail judgment records** to identify patterns in bail outcomes, courts, crime types, regions, bail types, accused characteristics, prior cases, landmark cases, and other judgment-related attributes.

The project combines **Python, Excel, and Power BI** to demonstrate an end-to-end data analytics workflow:

**Raw Data → Python Analysis & Validation → Excel Pivot Analysis → Power BI Dashboard → Business/Analytical Insights**

---

## 🎯 Objectives

The main objectives of this project are:

* Analyze the distribution of bail outcomes.
* Compare **Granted vs Rejected** bail cases.
* Analyze different types of bail.
* Identify case distribution across courts and regions.
* Analyze crime types associated with bail judgments.
* Examine accused gender and prior-case information.
* Analyze landmark and bail-cancellation cases.
* Explore the use of parity arguments and bias flags.
* Build an interactive Power BI dashboard for visualization.
* Practice an end-to-end Data Analyst workflow.

---

## 🛠️ Tools & Technologies

| Tool           | Purpose                                                           |
| -------------- | ----------------------------------------------------------------- |
| **Python**     | Data loading, validation, transformation and exploratory analysis |
| **Pandas**     | Data manipulation and analysis                                    |
| **NumPy**      | Numerical operations                                              |
| **Matplotlib** | Data visualization                                                |
| **Seaborn**    | Visualization support                                             |
| **Excel**      | Pivot tables and summary analysis                                 |
| **Power BI**   | Interactive dashboard and visualization                           |
| **GitHub**     | Project version control and portfolio                             |

---

## 📁 Dataset

The dataset contains **1,200 records and 21 columns**.

### Main Columns

| Column                        | Description                                             |
| ----------------------------- | ------------------------------------------------------- |
| `case_id`                     | Unique case identifier                                  |
| `case_title`                  | Name/title of the case                                  |
| `court`                       | Court associated with the judgment                      |
| `date`                        | Judgment date                                           |
| `judge`                       | Judge information                                       |
| `bail_type`                   | Type of bail                                            |
| `bail_cancellation_case`      | Indicates whether the case concerns bail cancellation   |
| `landmark_case`               | Indicates whether the case is marked as a landmark case |
| `accused_name`                | Name of accused                                         |
| `accused_gender`              | Gender information                                      |
| `prior_cases`                 | Information about previous cases                        |
| `bail_outcome`                | Granted or Rejected                                     |
| `bail_outcome_label_detailed` | Detailed description of the bail outcome                |
| `crime_type`                  | Type/category of crime                                  |
| `facts`                       | Case facts                                              |
| `legal_issues`                | Legal issues involved                                   |
| `judgment_reason`             | Reasoning behind the judgment                           |
| `summary`                     | Case summary                                            |
| `bias_flag`                   | Bias-related flag                                       |
| `parity_argument_used`        | Indicates use of parity argument                        |
| `region`                      | State/region associated with the case                   |

---

# 🔍 Python Analysis

The Python notebook performs exploratory analysis and data validation using Pandas, NumPy, Matplotlib and Seaborn.

### Key steps performed

1. Imported the dataset using Pandas.
2. Inspected the dataset using `head()` and `info()`.
3. Converted the `date` column to datetime format.
4. Checked missing values.
5. Checked duplicate records.
6. Checked unique case IDs.
7. Analyzed court distribution.
8. Analyzed bail types.
9. Analyzed bail cancellation cases.
10. Analyzed landmark cases.
11. Analyzed accused gender.
12. Analyzed prior cases.
13. Analyzed bail outcomes.
14. Analyzed crime types.
15. Analyzed bias flags.
16. Analyzed parity arguments.
17. Analyzed regional distribution.
18. Calculated unique values for each column.
19. Calculated bail outcome percentages.
20. Created a bail outcome visualization.
21. Exported the analyzed dataset as a CSV file.

---

# 📈 Key Findings

Based on the Python analysis:

* **Total cases:** 1,200
* **Granted:** 736 cases (**61.33%**)
* **Rejected:** 464 cases (**38.67%**)
* **Regular bail:** 906 cases
* **Anticipatory bail:** 268 cases
* **Interim bail:** 19 cases
* **Bail cancellation cases:** 116
* **Landmark cases:** 147
* **Male accused:** 1,071
* **Female accused:** 123
* **Prior cases – Yes:** 401
* **Prior cases – No:** 216
* **Prior cases – Unknown:** 583
* **Bias flag = True:** 13
* **Parity argument used:** 341 cases

### Regional distribution

The largest regional case counts in the dataset include:

* Uttar Pradesh — 130
* Bihar — 121
* Karnataka — 120
* Delhi — 119
* Maharashtra — 115
* Punjab — 100
* Madhya Pradesh — 99
* Jharkhand — 70

### Crime categories

The analysis includes crime categories such as:

* Narcotics
* Theft or Robbery
* Dowry Harassment
* Fraud or Cheating
* Sexual Offense
* Cyber Crime
* Extortion
* Kidnapping
* and other categories.

---

# 📊 Excel Analysis

Excel was used to create Pivot Table-based summaries.

The Excel workbook contains:

* Cleaned dataset
* Pivot analysis
* Regional summaries
* Bail type summaries
* Prior-case summaries
* Gender analysis
* Other categorical analysis

The workbook contains Pivot Tables and charts for exploring the dataset from different dimensions.

---

# 📊 Power BI Dashboard

The Power BI report provides an interactive dashboard for analyzing Indian bail judgments.

### Dashboard components include:

* KPI cards
* Bail outcome analysis
* Crime type analysis
* Court analysis
* Regional map
* Landmark case analysis
* Bail-related metrics
* Interactive filtering

The dashboard uses the cleaned dataset:

`indian_bail_judgements_cleaned`

### Power BI file

`Indian-Bail-Judgments analysis.pbix`

---

# 🔄 Project Workflow

```text
Indian Bail Judgments Dataset
            ↓
       Python / Pandas
            ↓
 Data Validation & EDA
            ↓
      Cleaned CSV
            ↓
          Excel
      Pivot Analysis
            ↓
        Power BI
 Interactive Dashboard
            ↓
      Final Insights
```

---



# 💡 Skills Demonstrated

### Python

* Pandas
* NumPy
* Data inspection
* Data type conversion
* Missing-value validation
* Duplicate validation
* Exploratory Data Analysis
* Descriptive statistics
* Percentage analysis
* Data visualization

### Excel

* Data analysis
* Pivot Tables
* Aggregation
* Categorization
* Summary reporting
* Charts

### Power BI

* Data modeling
* DAX measures
* KPI cards
* Bar charts
* Donut charts
* Maps
* Interactive dashboard design
* Data visualization


## ⭐ Project Summary

This project demonstrates an end-to-end **Data Analyst workflow** by combining Python-based exploratory analysis, Excel Pivot Table analysis, and Power BI dashboard development to analyze patterns in Indian bail judgments.
