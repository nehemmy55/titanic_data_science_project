# Titanic Data Science Project

## 📋 Project Overview

This project is part of a **5-Day Data Science with Python Bootcamp** and provides a comprehensive analysis of the Titanic dataset. The project demonstrates fundamental data science workflows including data loading, cleaning, exploration, analysis, and visualization.

## 🎯 Objectives

- Load and explore the Titanic dataset
- Perform data cleaning and preprocessing
- Analyze survival patterns and passenger demographics
- Create meaningful visualizations to gain insights
- Extract key statistics and trends from the data

## 📊 Dataset

**File**: `titanic_dataset.csv`

The dataset contains information about Titanic passengers including:
- `survived`: Whether the passenger survived (0 = No, 1 = Yes)
- `pclass`: Passenger class (1st, 2nd, or 3rd)
- `sex`: Passenger gender (male/female)
- `age`: Passenger age
- `sibsp`: Number of siblings/spouses aboard
- `parch`: Number of parents/children aboard
- `fare`: Ticket fare
- And other relevant features

## 🔧 Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

## 📁 Project Structure

```
titanic_data_science_project/
├── README.md                          # Project documentation
├── Titanic_Data__Science_Project.ipynb # Main analysis notebook
├── titanic_dataset.csv               # Raw dataset
└── cleaned dataset.csv               # Processed dataset (generated)
```

## 📝 Notebook Contents

### 1. **Data Loading**
   - Imports necessary libraries (NumPy, Pandas, Seaborn, Matplotlib)
   - Loads the Titanic dataset from CSV

### 2. **Data Cleaning**
   - Displays first and last rows of the dataset
   - Identifies dataset dimensions and column names
   - Handles missing values (fills age column with mean value)
   - Removes remaining null values
   - Generates cleaned dataset output

### 3. **Data Analysis**
   - Filters passengers by age (>30 years)
   - Filters passengers by gender
   - Calculates survival rate by gender
   - Sorts passengers by age
   - Creates derived features (family_size = parch + sibsp)
   - Computes maximum fare

### 4. **Data Visualization**
   - **Survival Rate Bar Chart**: Shows percentage of survivors (65% survived)
   - **Survival by Gender**: Compares survival rates between males and females
   - **Additional visualizations** for deeper insights into passenger demographics

## 🚀 How to Use

1. **Open the notebook**:
   ```bash
   jupyter notebook Titanic_Data__Science_Project.ipynb
   ```

2. **Run cells sequentially**:
   - Execute cells from top to bottom to perform data loading, cleaning, analysis, and visualization
   - Each cell builds upon previous results

3. **Generate cleaned dataset**:
   - The notebook automatically creates `cleaned dataset.csv` with processed data

## 📈 Key Findings

- **Survival Rate**: Approximately 65% of Titanic passengers survived
- **Gender Impact**: Significant difference in survival rates between males and females
- **Demographic Patterns**: Age and passenger class influence survival outcomes

## 🔍 Analysis Techniques Used

- **Data Aggregation**: `groupby()` operations for group-level statistics
- **Data Filtering**: Boolean indexing for data subsetting
- **Data Transformation**: Feature engineering (family_size calculation)
- **Statistical Summary**: Descriptive statistics and value counts
- **Data Visualization**: Bar plots, and categorical analysis plots

## 📥 Input/Output

- **Input**: `titanic_dataset.csv`
- **Output**: `cleaned dataset.csv` (after running the notebook)

## 💡 Learning Outcomes

Upon completing this project, you will understand:
- Essential pandas operations for data manipulation
- Data cleaning best practices
- Exploratory data analysis (EDA) techniques
- Data visualization with matplotlib and seaborn
- How to extract meaningful insights from historical datasets

## 🤝 Contributing

This is an educational project. Feel free to extend it with:
- Advanced statistical analysis
- Predictive modeling (classification)
- Additional visualizations
- Hypothesis testing

## 📚 References

- [Pandas Documentation](https://pandas.pydata.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Titanic Dataset Information](https://www.kaggle.com/c/titanic)

## ✅ Status

- ✓ Data Loading
- ✓ Data Cleaning
- ✓ Exploratory Analysis
- ✓ Data Visualization
- ⏳ Predictive Modeling (Optional Extension)

---

**Created**: April 2026  
**Course**: Data Science with Python - 5-Day Bootcamp  
**Level**: Beginner-Intermediate
