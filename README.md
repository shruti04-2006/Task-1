# Task-1: Cleaning and Preprocessing of Customer Data

## 📥 Dataset Source  
Downloaded from Kaggle: [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

## 🛠 Tools Used
- Python
- Jupyter Notebook
- pandas, seaborn, numpy

## 📂 What’s in this Repository
- `Customers_Dataset.ipynb` → Jupyter notebook with all cleaning steps
- `Customer_Data.csv` → Final cleaned dataset
- `README.md` → Project description (this file)

## 🧹 Data Cleaning Summary
The following data cleaning and preprocessing tasks were performed:
- Handled missing values in the `Income` column
- Dropped the `Marital_Status` column after creating a cleaned `Marital_Category` column
- Checked and removed duplicates
- Formatted `Dt_Customer` to datetime
- Verified data types for all columns
- Used boxplot to identify income outliers
- Exported cleaned dataset to `cleaned_customers.csv`

## 📌 How to Run
1. Clone or download the repository
2. Open `Customers_Dataset.ipynb` in Jupyter Notebook
3. Run all cells to reproduce cleaning
4. Use `Customer_Data.csv` for further analysis

---

🧑‍💻 _Made by Shruti Shivankar_
