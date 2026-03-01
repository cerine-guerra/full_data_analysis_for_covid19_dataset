# COVID-19 Data Cleaning and Exploratory Analysis

## Project Description
This project involves cleaning, preparing, and analyzing multiple COVID-19 datasets to understand global, regional, and country-level trends in confirmed cases, deaths, recoveries, and testing. The analysis is performed using Python (Pandas and Matplotlib) in Google Colab, and the project demonstrates **data cleaning, preparation, exploratory analysis, and meaningful visualizations**. 

The main goal is to provide a **comprehensive overview of the COVID-19 pandemic** and highlight patterns that can help in understanding its progression.

---

## Datasets
The project uses **6 CSV files**, each containing different levels of COVID-19 data:

1. **full_grouped.csv** – Day-to-day country-level cases including County/State/Province data.  
2. **covid_19_clean_complete.csv** – Day-to-day country-level cases without County/State/Province data.  
3. **country_wise_latest.csv** – Latest country-level statistics.  
4. **day_wise.csv** – Daily global cases (no country-level breakdown).  
5. **usa_county_wise.csv** – Daily county-level cases in the USA.  
6. **worldometer_data.csv** – Latest global COVID-19 data from Worldometer.

---

## Project Tasks

The project follows a structured approach:

### **1. Understanding the Data**
- General overview of each dataset.
- Number of rows and columns.
- Description of all columns and their data types (numerical or categorical).

### **2. Data Cleaning**
- Checked for missing values.
- Handled missing data appropriately (drop or fill with justification).
- Removed duplicate rows.

### **3. Data Preparation**
- Converted columns to appropriate data types.
- Created meaningful features where applicable.

### **4. Exploratory Analysis**
- Computed basic statistics for each dataset.
- Grouped data to analyze differences between categories (e.g., WHO Regions, countries, states).
- Summarized trends in confirmed, deaths, and recovered cases.

### **5. Visualizations**
Created **5 meaningful visualizations** across all datasets using Matplotlib. Each visualization includes:
- Clear title
- Proper axis labels
- Brief explanation of what the plot shows

**Examples of visualizations:**
1. Global daily progression of confirmed, deaths, and recovered cases (line plot).  
2. Top 10 countries by total confirmed cases (bar chart).  
3. Case fatality rate by WHO Region (pie chart).  
4. Active cases per continent (horizontal bar chart).  
5. Distribution of total deaths vs. total recovered globally (scatter plot).  

### **6. Insights and Conclusions**
- COVID-19 impact is **uneven across countries and regions**.  
- High-population areas and countries with extensive testing report the most cases.  
- Mortality rates vary significantly between WHO regions.  
- Global trends show **waves of infection**, with recoveries steadily increasing.  
- Combining multiple datasets provides a **holistic view of the pandemic**, highlighting hotspots, fatality trends, and testing disparities.

---

## How to Run This Notebook
1. Clone the repository:  
```bash
git clone https://github.com/cerine-guerra/full_data_analysis_for_covid19_dataset.git
