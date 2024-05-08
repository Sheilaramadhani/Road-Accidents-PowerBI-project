

# Road Accidents Dashboard

### [Dashboard Link](https://github.com/Sheilaramadhani/Road-Accidents-PowerBI-project/blob/one/RA%20DASHBOARD.pdf)

## Problem Statement

This dashboard helps the stakeholders gain insights from the following KPIs. Clients want to create a Road Accident Dashboard for years 2021 and 2022 so that they cai have insight on the below requirements:

* Primary KPI - Total Casualties and Total Accident values for the Current Year and YoY growth
* Primary KPIs - Total Casualties by Accident Severity for Current Year and YoY growth
* Secondary KPIs - Total Casualties with respect to vehicle type for Current Year
* Monthly trend showing the comparison of casualties for the Current Year and the Previous Year
* Casualties by Road Type for the Current year
* Current Year Casualties by Area/ Location & by Day/ Night
* Total Casualties and Total Accidents by Location

### Stakeholders:
* Ministry of Transport
* Road Transport Department
* Police Force
* Emergency Services Department
* Road Safety Corps
* Transport Operators
* Traffic Management Agencies
* Public
* Media

### Data Source: Kaggle.


### Steps followed 

- Step 1: Connecting raw data/ flat file with power bi
- Step 2: Data Cleaning in Power Query- Data cleaning process was performed in each column to check if there was any duplicates and spelling errors. In the accident severity column there was a spelling error which was Fetal instead of Fatal, and this was edited in the power Query editor by replacing values.
- Step 3: Data Processing - Using DAX formulas inorder to transform data to meet the stakeholders' needs.
- Step 4: Time Intelligence Function/ Calendar Date Table in Power BI - Time Intelligence functions have to be used to create the Date, Year, and month table since the stakeholders wanted to know the year to date casualties, perecntage of increase and percentage of decrease of casualties.
Function for the calendar:
![cale](https://github.com/Sheilaramadhani/Road-Accidents-PowerBI-project/assets/104450673/f538ca0b-4365-4f0e-9908-69465c26d302)

Function for Date:
![cale](https://github.com/Sheilaramadhani/Road-Accidents-PowerBI-project/assets/104450673/7ba079d4-2022-4196-aefa-71e3e468c87a)


- Step 5: Data Modelling (Relationship between multiple tables)
There are two tables which are the calendar table which has distinct dates and the raw data table which has repeated dates hence the relationship is one to many as shown below:
![cale](https://github.com/Sheilaramadhani/Road-Accidents-PowerBI-project/assets/104450673/57bac7dd-48a5-43c7-a5b4-1109ce9defb7)


- Step 6 : YTD and YoY Growth Calculations using DAX
Measures were created to calculate YTD and YoY Growth calculations.
For  Total Current year casualties and year-on-year casualties for the Previous year:
![cale](https://github.com/Sheilaramadhani/Road-Accidents-PowerBI-project/assets/104450673/ab391285-8ba6-4a08-b587-f2ff11db8820)

![acc](https://github.com/Sheilaramadhani/Road-Accidents-PowerBI-project/assets/104450673/ecf4d1ca-a6a9-4350-8c34-ffc570ef4755)

![fat](https://github.com/Sheilaramadhani/Road-Accidents-PowerBI-project/assets/104450673/8c3e826c-facf-4aef-bb8b-40df523b1e59)

![ser](https://github.com/Sheilaramadhani/Road-Accidents-PowerBI-project/assets/104450673/33891de1-d1bb-418a-81ca-c2d7835c0a55)

![slight](https://github.com/Sheilaramadhani/Road-Accidents-PowerBI-project/assets/104450673/094a8e9e-c185-43db-83a8-57cf12225c8d)

- Step 7: Creating different charts and generating insights


![dashboard](https://github.com/Sheilaramadhani/Road-Accidents-PowerBI-project/assets/104450673/8fe99656-f708-49f2-8273-5e87af6846ac)
           
    

Key Insights:

	1.	Road Type Analysis:
* Single carriageway-less roads exhibit the highest frequency of accidents, followed by dual carriageways, roundabouts, one-way streets, and slip roads.
* This suggests that road infrastructure and design play a significant role in accident occurrence, with single-carriageways presenting a higher risk due to potentially narrower lanes and fewer safety features.

	2.	Urban-Rural Disparities:
* Urban areas experience a higher incidence of accidents compared to rural areas.
* This disparity could be attributed to higher traffic volumes, increased pedestrian activity, and more complex road networks in urban settings.

	3.	Light Conditions Impact:
* Accidents are more prevalent during daylight hours compared to nighttime.
* The lower accident rates during the night may be attributed to reduced traffic volume and potentially heightened awareness of road hazards in low-light conditions.

	4.	Temporal Analysis:
* Comparing casualties between the current year (2022) and the previous year (2021), fluctuations in accident rates are observed across different months.
* For example, February 2021 recorded low casualties, while January 2022 exhibited a similar trend. Conversely, November 2021 and 2022 saw a spike in accident rates.
* These fluctuations may be influenced by various factors such as weather conditions, holidays, and changes in traffic patterns.

Recommendations:
Based on the insights gleaned from this analysis, several recommendations can be proposed to mitigate road traffic casualties:

	1.	Implement targeted safety measures on single carriageway-less roads to address their higher accident rates, such as improved signage, enhanced lighting, and traffic calming measures.
	2.	Increase enforcement and awareness campaigns in urban areas to promote safer driving behaviors and pedestrian awareness.
	3.	Enhance road maintenance and visibility during daylight hours to mitigate accident risks.
	4.	Conduct further research to understand the underlying causes of fluctuations in accident rates across different months and implement targeted interventions accordingly.

Conclusion:
In conclusion, this analysis provides valuable insights into the factors influencing road traffic casualties. By understanding the patterns and trends identified, stakeholders can develop more effective strategies and interventions to improve road safety and reduce accident rates.

 

  
     
