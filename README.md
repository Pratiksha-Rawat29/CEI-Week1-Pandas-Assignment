# CEI-Week1-Pandas-Assignment

# CEI Week 1 Pandas Assignment

## Objective
Learn Python basics and perform basic data exploration and cleaning using Pandas.

## Files Included
- CEI_Week1_Pandas_Assignment.ipynb
- sales.csv
- cleaned_sales.csv

## Tasks Performed

### 1. Loaded CSV Dataset
Loaded `sales.csv` into a Pandas DataFrame.

### 2. Explored Data
Used:
- head()
- tail()
- shape
- columns
- dtypes

### 3. Handled Missing Values
- Identified missing values using `isnull().sum()`
- Filled missing values with the mean price

### 4. Basic Operations
- Selected specific columns
- Filtered rows based on conditions

### 5. Removed Duplicates
Used `drop_duplicates()` to remove duplicate records.

### 6. Created Derived Column
Created:

```python
total_amount = price * quantity
```

### 7. Saved Cleaned Dataset
Saved the cleaned dataset as:

```python
cleaned_sales.csv
```

## Summary
The dataset was successfully loaded, explored, cleaned, and transformed using Pandas. Missing values were handled, duplicates were removed, and a new column (`total_amount`) was created. The cleaned dataset was then saved as a new CSV file.

## Author
Pratiksha Rawat
