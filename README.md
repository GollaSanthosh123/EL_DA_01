### **Welcome to the first task of my Data Analytics internship at **Elavate Labs** **.                                                                          
                                                                                                                                                              
This repository contains the PDF report of the Data Cleaning conducted as part of Task 01.
### **Objective:**                                                                                                                                                                         
              Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats)           
### **Tools used:**
              Python (Pandas)                                                    
              Jupyter(To write and execute python code)                                  
              Kaggle(to download datasets)                                      
I cleaned The  netflix data using python(pandas) in Jupyter Notebook                          

# **InterView Questions**                                                                    
### 1. What are missing values and how do you handle them?                                    
Ans: These columns having missing values director column and cast column , country , date_added 
column and rating , duration column                                                             
Using fillna() and Dropna() i deal with these Values                                           

### 2. How do you treat duplicate records?
Ans: Use df.duplicated() to identify and df.drop_duplicates() to remove them

### 3. Difference between dropna() and fillna() in Pandas?
Ans: dropna() removes missing values (rows/columns).                                            
fillna() fills them with a specific value (mean or other).   

### 4. What is outlier treatment and why is it important?
Ans: Outlier treatment removes or caps extreme values.
It’s important to avoid skewing the analysis and models.

### 5. Explain the process of standardizing data.                                                   
Ans: set the rows names in title format using   df=df.str.strip().str.title()

### 6. How do you handle inconsistent data formats (e.g., date/time)?
Ans: Use Pandas functions like pd.to_datetime() to convert and standardize formats.

### 7. What are common data cleaning challenges?
Ans: Missing or duplicate values
Inconsistent formats
Wrong data types
Typos in categories (e.g., “Male” vs “male”)

### 8. How can you check data quality?
Use .info(), .isnull().sum(), .describe(), .duplicated()
Also, visually inspect and validate against expected values.
