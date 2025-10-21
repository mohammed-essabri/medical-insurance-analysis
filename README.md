# Medical Insurance Cost Analysis

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📊 Project Overview
Comprehensive analysis of 1,338 patient records to identify key drivers of medical insurance costs using Python, pandas, and statistical methods. This project demonstrates data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization techniques.

## 🎯 Business Question
**What factors drive medical insurance costs, and how can insurance companies optimize their risk assessment and wellness programs?**

## 🔍 Key Findings

### 1. 🚭 Smoking - Primary Cost Driver
- **Impact:** 280% cost increase ($23,616 average difference)
- **Significance:** Affects 20.5% of population (274 patients)
- **Average Cost:** 
  - Non-smokers: $8,434
  - Smokers: $32,050

### 2. ⚖️ BMI/Obesity - Secondary Cost Driver
- **Impact:** $5,143 premium over normal BMI
- **Prevalence:** 52.8% of population classified as obese (707 patients)
- **Average Cost:**
  - Normal weight: $10,409
  - Obese: $15,552

### 3. 🏠 Regional Variations
- **Cost Range:** $2,388 difference between regions
- **Highest:** Southeast ($14,735)
- **Lowest:** Southwest ($12,347)

### 4. 🎯 High-Risk Combination
- **145 patients** are both obese AND smokers
- Represent highest priority for intervention programs

## 💼 Business Recommendations

### 1. Smoking Cessation Programs (Priority 1)
- **ROI Potential:** $23,616 per successful participant
- Target high-cost smoking customers first
- Implement tiered incentive structures

### 2. Weight Management Initiatives
- **ROI Potential:** $5,143 per patient achieving normal BMI
- Focus on preventive care for obese customers
- Partner with fitness and nutrition programs

### 3. Regional Cost Investigation
- Analyze Southeast region cost drivers
- Replicate Southwest region cost management best practices
- Investigate provider networks and utilization patterns

### 4. Combined Risk Intervention
- Prioritize 145 customers with both risk factors
- Design targeted wellness programs
- Offer premium discounts for participation

## 🛠️ Technologies Used

- **Language:** Python 3.8+
- **Data Analysis:** pandas, NumPy
- **Visualization:** Matplotlib
- **Environment:** Jupyter Notebook
- **Statistical Methods:** Descriptive statistics, group analysis, correlation analysis

## 📁 Dataset

**Source:** US Health Insurance Dataset (Kaggle)

**Features:**
- `age`: Age of primary beneficiary
- `sex`: Insurance contractor gender
- `bmi`: Body mass index
- `children`: Number of dependents
- `smoker`: Smoking status
- `region`: Residential area in the US
- `charges`: Individual medical costs billed by insurance

**Size:** 1,338 records, 7 features

## 🚀 How to Run This Project

### Prerequisites
```bash
Python 3.8+
Jupyter Notebook
```

### Installation
```bash
# Clone the repository
git clone https://github.com/mohammed-essabri/medical-insurance-analysis.git

# Navigate to project directory
cd medical-insurance-analysis

# Install required packages
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook medical_insurance_analysis.ipynb
```

### Required Packages
```
pandas
numpy
matplotlib
jupyter
```

## 📈 Analysis Process

1. **Data Loading & Inspection**
   - Import dataset and verify data integrity
   - Check for missing values and data types

2. **Exploratory Data Analysis (EDA)**
   - Statistical summary of numerical features
   - Distribution analysis of categorical variables
   - Identify outliers and patterns

3. **Cost Driver Analysis**
   - Smoking impact analysis
   - BMI category comparison
   - Regional cost variations
   - Age and family size effects

4. **Data Visualization**
   - Bar charts for categorical comparisons
   - Statistical summaries with formatted output
   - Clear, business-focused visualizations

5. **Business Insights & Recommendations**
   - Quantified ROI opportunities
   - Prioritized action items
   - Data-driven decision support

## 📊 Sample Visualizations

The project includes professional visualizations showing:
- Average costs by smoking status
- BMI category cost comparisons
- Regional cost variations
- Statistical summaries with business impact

## 🎓 Skills Demonstrated

- **Data Manipulation:** pandas operations, groupby, aggregations
- **Statistical Analysis:** Descriptive statistics, cost driver identification
- **Data Visualization:** Matplotlib, clear business-focused charts
- **Business Analysis:** ROI calculation, actionable recommendations
- **Code Quality:** Clean, well-documented, reproducible analysis
- **Healthcare Analytics:** Understanding of insurance cost factors

## 📫 Contact

**Mohammed Es-Sabri**
- 📧 Email: essabrimohamed07@gmail.com
- 💼 LinkedIn: [linkedin.com/in/mohammed-es-sabri](https://linkedin.com/in/mohammed-es-sabri)
- 🎓 MS Business Analytics (Healthcare Concentration) - SUNY New Paltz

## 📝 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Dataset: Kaggle US Health Insurance Dataset
- Analysis conducted as part of MS Business Analytics portfolio development

---

**⭐ If you found this project helpful, please consider giving it a star!**
