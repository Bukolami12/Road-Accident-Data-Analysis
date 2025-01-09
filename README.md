
# Road Accident Data Analysis

## Project Overview
The project aims to analyze road accident data to identify trends, geographic patterns, and insights into accident severity, frequency, and contributing factors. This analysis can help inform policies or interventions to improve road safety.

## Data Collected
### Accident Details

These fields provide information about individual accidents:

•	Accident_Index: A unique identifier for each accident.

•	Accident Date: The date when the accident occurred.

•	Day_of_Week: The day of the week (e.g., Monday, Tuesday).

•	Time: The time of the accident.

•	Accident_Severity: The severity level of the accident (e.g., Slight, Serious, Fatal).

•	Number_of_Casualties: Total casualties resulting from the accident.

•	Number_of_Vehicles: Number of vehicles involved.

### Location Details
These fields provide information about where the accidents occurred:

•	Latitude and Longitude: GPS coordinates of the accident location.

•	Local_Authority_(District): The district where the accident occurred.

•	Urban_or_Rural_Area: Specifies whether the accident occurred in an urban or rural area.

 ### Road Conditions
These fields describe the environment during the accident:

•	Junction_Control: Details about traffic control at junctions (e.g., Give Way, Stop Sign).

•	Junction_Detail: Type of junction (e.g., Roundabout, T-junction).

•	Road_Type: Classification of the road (e.g., Single carriageway, Dual carriageway).

•	Speed_limit: Speed limit on the road.

•	Road_Surface_Conditions: Describes road surface at the time (e.g., Dry, Wet, Snow).

•	Light_Conditions: Lighting conditions during the accident (e.g., Daylight, Darkness).

•	Weather_Conditions: Weather at the time of the accident (e.g., Rain, Fog).
## Project Objective 
The objective of this project is to analyze road accident data to uncover critical patterns, trends, and insights that can inform policies and interventions to improve road safety. By leveraging data analysis and visualization techniques, this project aims to achieve the following:

•	Identify temporal patterns in road accidents (monthly, yearly).

•	Examine trends in accident severity and casualty rates.

•	Compare accident rates in urban vs. rural areas.

•	Analyze the impact of road, weather, and light conditions on accidents.

•	Correlate accident severity with environmental factors.

## Key Metrics 
To measure and analyze the trends and patterns in road accidents, the following key metrics will be used:

•	Total Number of Accidents: The overall count of accidents in the dataset.

•	Monthly/Yearly Accident Trends: Number of accidents occurring per month or year.

•	Percentage of accidents categorized as Slight, Serious, or Fatal.

•	Casualties by Severity: Casualties associated with each severity level.

•	Urban vs. Rural Analysis: Comparison of accidents in urban vs. rural settings.

•	Lighting Conditions: Analysis of accidents occurring during daylight, nighttime, or poor lighting.

• Number and types of vehicles involved in accidents.

## Tool Used
- Microsoft Excel [Download Here](https://wwww.microsoft.com)
  
• Used for initial data exploration, cleaning, and preparation.

• Created visualizations like pie charts, line graphs, and donut charts for summarizing key insights.

• Performed calculations to derive metrics like trends, accident severity breakdowns, and geographic summaries.

## Visual Analysis and Inference

# 1. Monthly/Yearly Accident Trend 

## Filtered Chart of 2021 and 2022 Casualties
![monthly trend analysis](https://github.com/user-attachments/assets/bbc7b960-b461-42c8-a11b-4d2d584b32d8)

## Inference 

### Yearly Trends:
• In 2021, the total number of casualties was 222,146, while in 2022, it reduced to 195,737, indicating a 12% decrease in road casualties.

• The decrease in casualties may be attributed to improved road safety measures, stricter enforcement of traffic rules,or other external factors such as reduced travel or improved infrastructure.

### Monthly Patterns:
• Casualties in both years show seasonal fluctuations, with July, August, and November consistently having higher numbers of casualties.

• Casualties are notably lower in January and December of 2022 compared to 2021, which may be due to factors like weather conditions, travel restrictions, or increased public safety 
  campaigns during the festive seasons.
  
### 2022 Improvements:
The overall downward trend in casualties in 2022 reflects potential improvements in safety measures.

### Recommendations
 #### Focus on Peak Months:
 • Since casualties are higher in July, August, and November, targeted road safety campaigns, increased enforcement, and public awareness initiatives should be implemented during these 
   months.

 #### Investigate and Improve Seasonal Safety:
• Analyze the underlying causes for higher casualties in these months. Possible factors may include increased travel (e.g., holidays) or poor weather conditions.

• Deploy additional traffic monitoring tools and increase public transport options during peak months to reduce road accidents.

 #### Maintain Awareness Campaigns:
• The reduction in casualties in January and December 2022 suggests that campaigns during these months were effective. These efforts should be replicated or enhanced for consistency.

• Data-Driven Policies: Utilize advanced analytics to pinpoint specific areas, times, or conditions (e.g., weather, road types) that correlate with increased accidents to allocate resources effectively.

### Conclusion
The analysis highlights a positive reduction in road accident casualties from 2021 to 2022, reflecting progress in road safety. However, the persistently high casualties during certain months indicate the need for more focused strategies during peak accident periods. By leveraging data-driven approaches, maintaining public awareness, and improving infrastructure, further reductions in casualties can be achieved in the future.

# 2 . Accident Severity
   ## Filtered Chart Of Percentage Of Accident Severity
   ![Accident Severity](https://github.com/user-attachments/assets/6b056354-8785-4c08-a16e-fff243e22aef)

## Inference

  ### Fatal Severity
  •	 Total Fatal Cases: 7,135 (1.7% of total cases).
  
  •	Observation: Fatal accidents represent a small percentage of total accidents, indicating that while fatalities are rare, they are 
    critical for targeted safety interventions.

  •	Inference: Efforts should focus on understanding the conditions leading to fatalities (e.g., high-speed zones, lack of protective 
    barriers).
  
  ### Serious Severity
•	Total Serious Cases: 59,312 (14.2% of total cases).

•	Observation: Serious accidents make up a significant portion of cases, indicating a notable risk of severe injuries during accidents.

•	Inference: These cases may require deeper analysis of factors like:

-	Road conditions: Poor maintenance or lighting.
  
-	Vehicle involvement: Heavy vehicles like buses or trucks.
  
- Driver behavior: Speeding or distracted driving.

  ### Slight Severity
•	Total Slight Cases: 351,436 (84.1% of total cases).

•	Observation: Most accidents result in slight injuries, likely involving minor collisions or accidents at lower speeds.

•	Inference: This suggests that while accidents are frequent, the majority are less severe. Emphasis on driver training and minor road improvements (e.g., better signage, traffic calming measures) could reduce these incidents.

Overall Inference
•	The vast majority of accidents (98.3%) do not result in fatalities, with slight injuries being the most common outcome.

•	Fatal and serious accidents together account for around 15.9% of cases, highlighting areas where critical attention is needed to save lives and prevent serious injuries.

### Recommendations
1. 	#### Focus on Fatalities and Serious Injuries:
	• Investigate blackspots or high-risk areas with recurring fatal/serious accidents.

 •	Implement policies for stricter speed enforcement and seatbelt/helmet usage.
 
2. #### Reduce Slight Injuries:
 •	Focus on accident-prone intersections with minor collisions.
 
 •	Install low-cost solutions like rumble strips and improved signage.

### Conclusion 
The analysis of accident severity reveals distinct trends in casualty outcome in which Fatal accidents constitute only 1.7% of all incidents, suggesting that while fatalities are a small percentage, they remain a critical area for targeted safety measures while serious accidents account for 14.2% of cases, highlighting the need for improved response mechanisms, such as quicker emergency services and better medical facilities in accident-prone areas.While majority of cases, 84.1%, are slight accidents, indicating that while the impact is less severe, they still pose risks and may result in indirect economic and social consequences.
This breakdown underscores the importance of tailored interventions. Preventative measures must focus on reducing all types of accidents, with particular attention to minimizing fatalities and serious injuries through improved road safety policies, driver training programs, and infrastructure upgrades.

3. # Casualties By Vehicle Type 

 ## Filtered Chart Of Vehicle Type and Number Of Casualties 
 ![casualties ](https://github.com/user-attachments/assets/0c5aeb2e-17cb-44b9-a712-17a82ee0f467)

 ## Inference 
 #### Cars:
  	•	Casualties = 333,485 (79.8% of total casualties).
   •	Observation: Cars contribute the largest share of casualties, highlighting their prevalence in road accidents.
   •		Inference: The high number could be attributed to the large number of cars on the road, driver behavior, and possibly lack of 
      adherence to traffic rules.
 ####  Bikes:
   •	Casualties = 33,672 (8.1% of total casualties).
   • Observation: Bikes account for a significant portion, despite fewer bikes compared to cars.
   •	Inference: Vulnerability due to less protection for riders and increased risk of severe injury.
#### Vans:
  •		Casualties = 33,472 (8.0% of total casualties).
  
  • 	Observation: Vans have a similar casualty count as bikes, indicating their involvement in frequent accidents.
  
  •	 Inference: May be linked to delivery or commercial operations, often involving long hours or urban congestion.
#### 	Bus:
  •	Casualties = 12,798 (3.1% of total casualties).
  
  •		Observation: A lower number of casualties compared to other vehicles, possibly due to professional drivers and regulated operations.
  
  •	Inference: Buses are involved in fewer incidents but may pose risks in densely populated areas.
#### 	Agricultural Vehicles:
  •		Casualties = 1,032 (0.2% of total casualties).
  
  •		Observation: Minimal involvement in accidents, likely due to lower usage on public roads.
  
  •Inference: Their involvement may be limited to rural or farming areas.
#### Others:
•	Casualties = 3,424 (0.8% of total casualties).

• Observation: Represents less common vehicle types or unspecified incidents.

### Recommendations
- ##### 	For Cars:
 •	Enforce Speed Limits: Implement strict speed control measures in urban and high-risk areas.

 •	Promote Driver Education: Raise awareness about safe driving practices, especially among car drivers.

 •	Technology Integration: Encourage the adoption of advanced driver-assistance systems (ADAS).

- #### 	For Bikes:
 •	Safety Gear Enforcement: Mandate helmets and protective gear for all riders.
 
 •	Dedicated Lanes: Develop more bike lanes to separate them from larger vehicles.
 
 •	Awareness Campaigns: Educate riders and other road users about sharing roads safely.
- #### 	For Vans and Commercial Vehicles:
 •	Regulate Driving Hours: Reduce fatigue by enforcing rest periods for commercial drivers.
 
 •	Training Programs: Introduce regular driver training for van operators.
- #### 	For Buses:
•	Urban Area Regulation: Implement speed and route restrictions in densely populated zones.

•	Maintenance Checks: Regularly inspect buses for safety and mechanical fitness.















