# **Airplane Crashes and Fatalities Analysis**

## **Project Overview**
This repository contains an analysis of airplane crashes and fatalities data to uncover patterns and insights related to aviation safety. The dataset includes information on flight incidents from 1948 onward, detailing the date, location, aircraft type, operator, route, number of people aboard, fatalities, and more. The goal of this project is to provide valuable insights into aviation safety trends and potential risk factors.

## **Objectives**
- Analyze airplane crash trends over time
- Identify aircraft types with the highest number of crashes
- Determine the most affected airlines and flight routes
- Visualize patterns related to seasonal and regional crash occurrences
- Provide an interactive Power BI dashboard summarizing key insights

## **Data Sources and Tools Used**
- **Dataset**: Airplane Crashes and Fatalities Dataset (obtained from Data Society)
- **Tools Used**:
  - **Microsoft Excel**: Data cleaning and initial exploration
  - **Power BI Desktop**: Data visualization and dashboard creation

## **Exploratory Data Analysis (EDA)**
### **Data Description**
The dataset contains the following key columns:
- `Date` – The date of the airplane crash
- `Time` – Time of the incident
- `Location` – Geographical location of the crash
- `Operator` – Airline or entity operating the aircraft
- `Flight #` – Flight number
- `Route` – Flight path of the aircraft
- `Type` – Model/type of aircraft involved
- `Registration` – Aircraft registration number
- `Aboard` – Number of passengers and crew aboard
- `Fatalities` – Total number of deaths
- `Ground` – Number of fatalities on the ground
- `Summary` – Brief description of the incident

### **Methodology**
1. **Data Cleaning & Preparation**
   - Handled missing values and inconsistencies in Excel
   - Converted date and time formats to ensure uniformity
   - Standardized aircraft operator names for consistency

2. **Data Analysis in Excel**
   - Used Pivot Tables to summarize crash data by year, operator, and aircraft type
   - Analyzed survival rates and ground fatalities
   - Identified peak crash months and regional hotspots

3. **Visualization & Insights in Power BI**
   - Built an interactive dashboard summarizing key findings
   - Created trend analysis on yearly airplane crashes
   - Mapped locations of frequent crashes globally
   - Identified top 10 aircraft types with the most crashes

## **Key Insights & Interpretation**
### **1. Crash Trends Over Time**
- The highest number of airplane crashes occurred between the 1960s and 1980s.
- There has been a general decline in crash incidents post-2000, likely due to advancements in aviation safety.

### **2. Aircraft Types with the Most Crashes**
- The **Douglas DC-3, de Havilland Canada DHC-6, and Antonov AN-26** had the highest recorded crashes.

### **3. Most Affected Airlines & Routes**
- **Aeroflot, Pan American World Airways, and Air France** are among the airlines with the most crashes.
- The busiest flight routes tend to have higher incidents, requiring deeper analysis into safety compliance.

### **4. Monthly Crash Occurrences**
- Crashes tend to peak in **January and December**, possibly due to extreme weather conditions.

## **Data Visuals**
The Power BI dashboard includes:
- Yearly crash trends
- Top 10 aircraft types involved in crashes
- Most affected airlines and operators
- Monthly distribution of crashes
- Geographic heatmap of airplane crash locations

## **Dashboard**
  ![image](https://github.com/user-attachments/assets/a90f6709-aa5f-4940-a156-c87e8d53248f)

## **Data Story**
This dashboard was created to analyze aviation safety by examining Boeing 707 airplane crashes and fatalities since 1948. The goal is to identify patterns in crash occurrences, operators, and aircraft types to improve safety measures.

Key Findings:
- Aeroflot and Military - U.S. Air Force, are the top operators with the highest number of crashes
- The Douglas DC-3 aircraft type is involved in the most crashes
- Flight routes over the Atlantic and Pacific Oceans are the most dangerous

Supporting Evidence:
- Top 10 Operators: Aeroflot (0.36M crashes) and Military - U.S. Air Force are the top operators
- Top 10 Aircraft Types: Douglas DC-3 (0.25M crashes) leads the list
- Flight Routes: Atlantic and Pacific Ocean routes have the highest crash frequencies

Conclusion:
To improve aviation safety, focus on stricter maintenance protocols for older aircraft like the Douglas DC-3, enhance emergency response systems for transoceanic flights and conduct safety audits for operators with high crash frequencies


