# DATSH.AI

# Welcome to your 

# DATSH.AI

## ⚠️ Warning: Private Repository Notice
This repository contains a work-in-progress project and is currently private. While the code is not publicly accessible, this README provides an overview of the project, including the technologies used and a link to the hosted application. The reason for hiding the code is that the project is still under development, and its details are subject to change. Once finalized, the code may be made public. Thank you for understanding.

## Project Information

**URL**: [DATSH.AI ](https://datshdattashodhini.vercel.app/)




# DATSH.AI: Data Shodhini - Transform Your Data with Intelligent Cleaning and Processing  

DATSH.AI is an intelligent platform for cleaning and preprocessing messy data. With just a few clicks, you can upload your CSV or Excel file, select the cleaning operations you want, and download the cleaned dataset ready for analysis.  

## Key Features  

- **Upload Your Data:**  
  Drag and drop your CSV or Excel file, or browse to upload.  

- **Cleaning Options:**  
  - Remove duplicate rows.  
  - Remove empty rows.  
  - Standardize header case.  
  - Trim unnecessary whitespace.  

- **Handle Missing Values:**  
  - Replace missing values with "NA."  
  - Detect and handle outliers.  

- **Preview Data:**  
  - View both the original and cleaned data side-by-side.  

- **Detailed Statistics:**  
  - Total rows and columns.  
  - Percentage of missing values.  
  - Duplicate row statistics.  
  - Changes made during cleaning.  

## Example Output  

### File Statistics:  
- **Total Rows:** 12  
- **Total Columns:** 11  
- **Missing Values:** 6 (4.55%)  
- **Duplicate Rows:** 1 (8.33%)  
- **Rows Removed After Cleaning:** 2 (16.67%)  

### Sample Data Preview:  

#### Original Data  
| ID  | Name         | DOB          | Email             | Gender | Salary  | Join Date       | Department   | Phone          | Extra Col | Region |  
| --- | ------------ | ------------ | ----------------- | ------ | ------- | --------------- | ------------ | -------------- | --------- | ------ |  
| 101 | John Doe     | 33007.229282 | johndoe@gmail.com | Male   | 50000   | 42156.229282    | Sales        | 123-456-7890   | Lorem     | North  |  
| 102 | jane_doe     | 14/06/1992   | janedoe@gmail.com | female | 55000   | 43296.229282    | Marketing    | 9876543210     | Ipsum     | East   |  

#### Cleaned Data  
| ID  | Name       | DOB         | Email             | Gender  | Salary | Join Date       | Department   | Phone          | Extra Col | Region |  
| --- | ---------- | ----------- | ----------------- | ------- | ------ | --------------- | ------------ | -------------- | --------- | ------ |  
| 101 | John Doe   | 1990-06-15  | johndoe@gmail.com | Male    | 50000  | 2015-06-10      | Sales        | 123-456-7890   | Lorem     | North  |  

## How It Works  

1. **Upload:** Provide your CSV or Excel file.  
2. **Select Cleaning Options:** Choose the operations that suit your needs.  
3. **Download:** Get the cleaned dataset instantly.  

DATSH.AI simplifies data cleaning, saving you time and effort while ensuring your data is accurate and consistent.

## Technologies Used
This project is built using:

- **Vite**
- **TypeScript**
- **React**
- **shadcn-ui**
- **Tailwind CSS**
