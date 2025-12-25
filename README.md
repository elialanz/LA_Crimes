**Link →** Link Will Be Inserted Here


## 📊 Los Angeles Crime Analysis (2020)

### 1. Project Overview

This project analyses reported crime incidents in Los Angeles during **2020** to explore how crime patterns vary across **time, geographic locations, and crime types.**
Using official LAPD crime data, the analysis focuses on identifying temporal trends, spatial concentrations, and dominant crime characteristics within a single year, providing a detailed snapshot of crime dynamics during 2020.

The project follows a structured data analytics workflow, including data profiling, cleaning, feature engineering, exploratory analysis, and visualisation.

### 2. Objectives

- Understand **when** crimes most frequently occur during 2020
- Identify **where** crime is concentrated across Los Angeles areas
- Analyse **what types of crime** are most prevalent and how they differ by time and location
- Combine time, location, and crime characteristics to uncover meaningful patterns

### 3. Data Source

- **Dataset:** Crime Data from 2020 to Present
- **Source:** Kaggle (originally from LAPD Open Data)
- **Scope Used:** Records from the year **2020 only**
- **Observations:** ~986,000 crime reports
- **Unit of Analysis:** Individual reported crime incidents

### 4. Tools & Technologies

- **Python** (pandas, numpy): data cleaning, transformation, and analysis
- **Jupyter Notebook**: exploratory analysis and documentation
- **Tableau**: data visualisation and spatial analysis
- **GitHub**: version control and project documentation

### 5. Methodology

**Data Profiling & Understanding**
Inspected data structure, data types, and dataset size
Identified missing values, non-uniform fields, and data limitations

**Data Cleaning & Preparation**
Renamed columns for clarity and consistency
Parsed and standardised date and time fields
Handled missing values by limiting analysis scope rather than imputing unreliable data

**Feature Engineering**
Derived temporal variables (month, day of week, hour, time of day)
Prepared geographic variables for spatial analysis
Grouped crime attributes to support higher level analysis

**Exploratory Data Analysis**
Analysed crime frequency across time intervals
Compared crime volumes across Los Angeles areas
Examined distributions of crime types, premises, and weapon involvement

**Visualisation & Interpretation**
Built charts and maps to highlight key patterns
Interpreted results with attention to data limitations and context

### 6. Key Insights (Summary)

- Crime frequency varies significantly by **time of day and month** within 2020
- Certain Los Angeles areas consistently report higher concentrations of crime
- Property related crimes dominate reported incidents
- Crime patterns differ when time, location, and crime type are analysed together
(Detailed insights are presented in the analysis notebooks and dashboards.)

### 7. Limitations

- The analysis is limited to **reported crimes** and may not reflect unreported incidents
- Only **one year (2020)** of data is analysed, so findings describe intra year patterns rather than long term trends
- Some victim and weapon related fields contain substantial missing data and were used cautiously

### 8. Future Improvements

- Extend the analysis to multiple years for trend comparison
- Integrate socioeconomic or demographic data for deeper contextual insights
- Incorporate external spatial boundaries (e.g. census or LAPD polygons) for enhanced mapping
