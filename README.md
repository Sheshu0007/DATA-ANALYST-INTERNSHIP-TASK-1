# DATA ANALYST INTERNSHIP TASK 1

## Description
This repository contains the completed work for the Data Analyst Internship Task 1. The task involved **data cleaning, standardization, and basic analysis** using Python and pandas in a Jupyter Notebook.
1. **Data Import**
   - Imported datasets using `pandas.read_csv()` 
   - Checked initial structure using `.head()`, `.info()`, and `.describe()`.

2. **Data Cleaning**
   - **Dropped null values** from important columns using `.dropna()`.
   - **Dropped duplicate rows** using `.drop_duplicates()`.
   - **Standardized column headers**: Converted all column names to lowercase using:
     ```python
     df.columns = df.columns.str.lower()
     ```
   - **Checked data types** of all columns using:
     ```python
     df.dtypes
     ```

3. **Data Transformation**
   - Converted **date columns** to datetime type using:
     ```python
     df['date_column'] = pd.to_datetime(df['date_column'])
     ```
   - Reformatted dates for display using `.dt.strftime('%d-%m-%Y')`.
   - Converted text columns to proper case or lowercase as needed.
   - Verified dataset after cleaning.
  

5. **Data Export**
   - Saved cleaned/processed data using:
     ```python
 
     ```
