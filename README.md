# Diabetes Analysis

## Table of Content

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Feature Engineering](#data-cleaningfeature-engineering)
- [Data Analysis](#data-analysis)
- [Exploratory Data Analysis](#exploratory-data-analysis)

### Project Overview
This Data Analysis aims to provide actionable insights of a Diabetes Dataset by analyzing various aspect of the given data; identify problems and make data-driven decisions/recommendation

<img width="827" alt="Diabetes Analysis" src="https://github.com/user-attachments/assets/442ddbbe-991b-436e-8e96-3386be68fc01">

### Data Source
Diabetes Data : the primary dataset used for this analysis is the "diabetes.csv" file, containing the data needed for the analysis given by SkyHUB Nigeria

### Tools
- Microsoft Excel- Data Cleaning, Data Analysis, Data Visualization & Report Creating 
	- [Download Here](https://microsoft.com)

### Data Cleaning/Feature Engineering

I performed the following tasks
- Created a custom field “BloodPressureCategory” from an already existing field “BloodPressure” using the IFS function to group the BloodPressure into “Low”, “Normal” & “High”


### Data Analysis
- The diabetes “Outcome” field contained “0” representing No Diabetes & “1” representing Diabetes. I changed the numerical values to it’s alphabetical meaning on my Pivot Table by “Right Click > Field Setting > Number Setting > Custom > [>0] “Diabetes”;”No Diabetes””
* I grouped the “Age” field into intervals of 10 to get the given Age Range & I also grouped the “DiabetesPedigreeFunction” field into intervals of 0.5 to extract the given the Range


### Exploratory Data Analysis

Exploring the diabetes data to answer key questions, such as:
- Average Glucose Level By Age Groups
- Average BMI By Diabetes Outcome
- Pregnancy Distribution Across Diabetes Outcome
- Average Insulin Level By Blood Pressure Group
- Correlating Diabetes Pedigree Function By Glucose Levels
