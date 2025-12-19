# Hospital Patient Data EDA System 🏥

A Python-based Exploratory Data Analysis project that cleans hospital patient records and visualizes department-wise workload and treatment patterns.

## 📋 Project Overview

**Course:** Minor 1 Project  
**Difficulty:** Medium  
**Student:** Aadarsh Mishra (ERP: 6605983, Serial No: 07)

This project analyzes hospital patient data to provide insights into:
- Department-wise patient distribution
- Average treatment costs across departments
- Length of stay patterns
- Resource allocation insights

## 🎯 Problem Statement

Build an EDA system for hospital patient records with the following requirements:
- Clean raw patient data (handle duplicates, invalid entries)
- Map medical conditions to hospital departments (feature engineering)
- Create visualizations for department workload analysis
- Generate statistical summaries

## 🗂️ Dataset

- **Source:** Kaggle
- **File:** `hospital_data_analysis.csv`
- **Features:** Patient info, Medical Condition, Treatment Cost, Length of Stay

## 🛠️ Tech Stack

- **Python 3.14.0**
- **Pandas** - Data manipulation and cleaning
- **NumPy** - Numerical operations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical graphics

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/aadarshm24/Hospital_Patient_Data_EDA_System.git

# Navigate to project directory
cd hospital-eda-project

# Install required packages
pip install pandas numpy matplotlib seaborn
```

## 📊 Features

### 1. Data Cleaning
- Removes duplicate patient records
- Filters out invalid entries (negative costs/stays)
- Handles missing values

### 2. Feature Engineering
- Created custom mapping for 15+ medical conditions to departments:
  - Cardiology (Heart Disease, Heart Attack, Hypertension)
  - Orthopedics (Fractures, Osteoarthritis)
  - Oncology (Cancer types)

### 3. Visualizations
- **Pie Chart:** Department-wise patient load distribution
- **Box Plot:** Length of stay distribution by department
- **Bar Chart:** Average treatment costs by department

## 💻 Usage
 execute cells in Jupyter Notebook:
```bash
jupyter notebook hospital_analysis.ipynb
```

## 📈 Key Insights

- Cardiology and Orthopedics handle the most patients
- Oncology has the highest average treatment costs
- Emergency department has shortest patient stays
- Maternity and Oncology show longer hospitalization periods


## 📁 Project Structure

```
hospital-eda-project/
│
├── hospital_data_analysis.csv           # Dataset
├── Hospital_Patient_Data_EDA.ipynb      # Main Python script
├── README.md                            # This file
└── requirements.txt                     # Dependencies
```

## 🎓 What I Learned

- Real-world data is messy and needs thorough cleaning
- Feature engineering can solve missing data problems
- Domain knowledge (healthcare) is important for data science
- Choosing the right visualization type matters
- Pandas groupby and mapping functions are powerful

---

⭐ If you found this project helpful, consider giving it a star!

*Made with ☕ and lots of Googling*