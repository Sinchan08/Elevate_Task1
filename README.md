# 📊 Internship Task 1 - Data Cleaning and Preprocessing

## 📁 Dataset:
**Customer Personality Analysis**  
Source: [marketing_campaign.csv] — taken from Kaggle

## 🎯 Objective:
Clean and preprocess a raw marketing dataset by:
- Handling missing values
- Removing duplicate rows
- Standardizing column names and categorical text values
- Converting date formats
- Fixing inconsistent data types
## 🛠 Tools & Technologies:
- Python
- Pandas
- Google Colab
- 
## 🧹 Cleaning Steps Performed:
- ✅ Checked for missing values using `.isnull().sum()`  
- ✅ Dropped missing data using `dropna()`  
- ✅ Removed duplicate records with `drop_duplicates()`  
- ✅ Standardized column names to lowercase with underscores  
- ✅ Cleaned categorical fields like `Education`, `Marital_Status` using `.str.strip().str.lower()`  
- ✅ Converted `Dt_Customer` to `datetime` format  
- ✅ Created a new `age` column using `2024 - Year_Birth`  
- ✅ Verified and corrected data types using `.dtypes`
- 
## 📦 Files Included:
- `task1.ipynb`  
- `cleaned_marketing_campaign.csv` 

## 📝 Conclusion:
This task gave hands-on experience with real-world data cleaning using Python and Pandas. The dataset was transformed into a clean and structured format, which is now ready for analysis, modeling, or visualization.
