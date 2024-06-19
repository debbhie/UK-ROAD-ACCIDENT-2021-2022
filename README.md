# UK-ROAD-ACCIDENT-2021-2022

## TABLE OF CONTENT
- [UNITED KINGDOM ROAD ACCIDENT 2021 AND 2022 OVERVIEW](#united-kingdom-road-accident-2021-and-2022)
- [DATA SOURCE](#data-source)
- [TOOLS](#tools)
- [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)
- [DATA ANALYSIS](#data-analysis)
- [DATA VISUALIZATION](#data-visualization)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)
- [LIMITATIONS IN THE DATASET](#limitations-in-the-dataset)
- [RECOMMENDATIONS FOR LIMITATIONS IN THE DATASET](#recommendations-for-limitations-in-the-dataset)


## UNITED KINGDOM ROAD ACCIDENT 2021 AND 2022 OVERVIEW
The dashboard provides a comprehensive analysis of road accidents in the United Kingdom for the year 2021 and 2022. Key performance indicators (KPIS) such as total casualties, casualties by accident severity, casualties by vehicle type are analyzed to gain insight into road safety and accident prevention measures.

## DATA SOURCE
The primary data set is gotten from google
 -[download here](https://drive.google.com/file/d/1R_uaoZL18nRbqC_MULVne90h3SdRbAyn/view)

## TOOLS
- Microsoft excel - data analysis
- Microsoft excel - dashboard/report

## EXPLORATORY DATA ANALYSIS
### PRIMARY KPIS
* Total casualties
* Percentage of total with respects to accident severity and maximum casualties by type of vehicle

### SECONDARY KPIS
* Total casualties with respect to vehicle type
* Monthly trend showing comparison of casualties for both years (2021 and 2022)
* Maximum casualties by road type
* Distribution of total casualties by road surface
* Relation between casualties by area/location and day/night

## DATA ANALYSIS
### Data Cleaning:
These processes were carried out using power query
* Duplicates was removed
* Spelling errors was corrected
* Dates were changed to united kingdom format
* There were no null values as such nothing in the data set was replaced or removed

![uk road ss2](https://github.com/debbhie/UK-ROAD-ACCIDENT-2021-2022/assets/161854079/12e90667-2de4-4d5a-9d8a-2f04849318ab)


### PRIMARY KPIS
* Total Caualties: The total number of casualties over the two-year period is 417,882. In 2021, the number of casualties was 222,145 and in 2022 it reduced to 195,737

* Percentage of casualties with respect to accident severity:
 * Fatal Casualties: In total for both years, fatal casualties recoreded 7,135 representing 1.7% of the total. From the analysis, in 2021 fatal recorded 4,280 with the percentage of 1.9% and 2022, it had 2,855 and the percentage of 1.5%.

 * Serious Casualties: 59,312 casualties, accounting for 14.2% of the total for both 2021 and 2022. In 2021 alone, 32,267 casualties was recorded with 14.5% of the total casualties while in 2022, 27,045 and the percentage of 13.8% was recorded.

 * Slight Casualties: In both 2021 and 2022, 351,435 casualties were recorded, comprising of 84.1% of the total. 2021 recoreded 185,598 with the percentage of 83.5% while 2022 has 165,837 and the percentage of 84.7%.

### SECONDARY KPIS
* Casualties by vehicle type:
* Car: This has the highest/ maximum casualties by vehicle type with the record of 333,484 and the percentage of 79.8% in both 2021 and 2022. In 2021, car had 177,680 casualties and in 2022, it hasd 155,804 casualties

Csualties with respect to vehicle type 

|vehicle type| both years| 2021|2022|
|------------|-----------|-----|----|
| Cars| 333,484| 177,680| 155,804|
| Vans| 33,472| 17,567| 15,905|
| Bus| 12,798|6,225|6,573|
| Bike| 33,672| 18,093| 15,579|
| Agricultural Van| 1,032| 633|399|
| Others| 3,424| 1,947|1,477|

* Monthly Trends: Analyzing the monthly trend for both years allows for comparison of casualties overtime, identifying the patterns or fluctuations. For the year 2021, the month of april recorded the lowest casualties of 17,335 while the month of november had the highest casualties of 18,439. While in 2022, january had the lowest casualties of 13,163 and november has the highest casualties 0f 18,439.
  The casualties in 2022 is lesser than the casualties in 2021 which is a great improvement. From the chart, the highest casualties in 2022, (18,439) and its a little higher than the casualties in 2021 (17,335).

* Maximum Casualties by Road type: Identifying road types with the highest number ofcasualties helps with priotizing safety measures and infrasture improvemnet. In rural areas, single carriage way recorded the highest casualties by road type of 113.1k followed by dual carriage with 35k and one way street with the lowest casualties by road type of 0.6k.
  In urban areas, the single carriage way had the highest casulties of 196.6k while others had the lowest of 1.3k. In total for both rural and urban areas , the casualties by road type, single carriage way had the highest of 309.7k.

* Casualties by Road Surface: Undestanding the correlation between road surface conditions and casualties aids implementing road maintenance and improvement strategies. In both rural and urban area, dry road surface has the highest with 279,445 followed by wet surface with 115,261 and snow/ice surface has 98,182. In rural area alone, dry surface had 98,182, wet had 50,694 while snow/ice had 12,967.
  In urban area, dry had 181,263, wet had 64,567 and snow/ice had 9,813. Dry surface area need more maintenance and improvement to prevent further road accidents.

* Casualties by location/Area: analyzing casualties distribution by location provides insight into high-risk areas and potential areas for targeted interventions. Urban areas had the highest road casulaties with 255,864 while rural area had 162,018 casualties.

* Casualties by Light Conditions: Examing casulaties under different light conditions highlights the impacts of visibility on road safety and guides measures such as improved lighting and visibility aids. In rural areas, the casualties by light conditions is daylight had 118,801 while dark has 43,217. In urban areas, dark had 69,903 and daylight had 186,161. In total, daylight had 304,962 and dark had 112,920.

  These analysis were derived from the dashboard created and filter functions were used to analyze it and make the dashboard interactive.

  DATA VISUALIZATION
  
![uk road ss](https://github.com/debbhie/UK-ROAD-ACCIDENT-2021-2022/assets/161854079/28bfe5c1-f95f-4233-83a7-e8aaf37632ac)

## INSIGHTS
* OVERALL DECLINE IN TOTAL CASUALTIES: The total number of casualties decreased from 222,145 in 2021 to 195,737 in 2022, indicating a positive trend in road safety efforts or chaanges in driving behavior.

* REDUCTION IN FATAL AND SERIOUS CASUALTIES: There was a decline in both fatal and serious casualties from 2021 to 2022 with fewer fatallities and serious injuries reported in 2022. This suggest potential improvements in emergency response, medical care and road safety measures.

* DECREASE IN SLIGHT CASUALTIES: Slight casualties also decreased from 185,598 in 2021 to 165,837 in 2022. While slight casualties typically involve minor injuries, the reduction still indicates progress in the overall road safety.

* VEHICLE TYPE ANALYSIS: Cars accounted for the highest number of casualties in both years, followed by vans, buses, bikes, agricultural vans and others. Despite the decrease in total casualties, all vehicle types experienced reduction in casualties from 2021 to 2022 except bus that increased slightly from 6,225 in 2021 to 6,573 in 2022.

## RECOMMENDATIONS:
* Continue Road Safety Campaigns: maintain and reinforce road safety campaigns to raise awareness among drivers, pedestrians and cyclists about safe driving practices, the importance of wearing seat blts and helments and also the risks associated with speeding and reckless driving.
  
* Road Surface Maintenance and safety: Improve road surface conditions, especially during adverse weather conditions such as rain, snow/ice. Regular maintenance and timely interventions can reduce the risk of accidents caused by slippery surface and poor road conditions.

* Enhance Emergency Response: strenthing emergency response system to ensure prompt effcetive medical care for accident victims. This includes improving ambulance services , training first responder and equipping hospitals to handle trauma cases effectively.

*  Location Based Safety Initiative: Develop location-specific road safety initiatives targeting urban and rural areas. Address unique challenges and risk factors prevalent in each setting such as traffic congestion in urban areas and limited visibility on rural roads through public education campaigns.

*  Enforce Traffic  Laws: Enforce traffic laws rigorously to deter dangerous driving behaviours such as drunk driving, speeding and distracted driving. Implement stricter penalties for traffic violations to promote compliance with road safety regulations.

*  Data- driven decision making: Contiuous monitor and analyze road accident data to identify trends, hotspots and emerging risks. Use data-deiven insights to inform decision making processes and allocate resources effectively to ares with the highest need for road safety improvements.

*  Enhance Lighting and Visibilty: Improve lighting infrastructure in both urban and rural areas to enhance visibility and reduce accidents, especially during night time driving. Installing street lights, refects road signs and warning signals can help improve safety for road users.

*  Promote Vehicle Safety: Encourage the use of safety features in vehicles such as airbags, anti-lock braking system (ABS) and electronic stability control (ESC) to reduce the severity of injuries in the event of an accident.

*  Monitor Trends: Continuously monitor road accident data and analyze trends to identify emerging risk factord and areas requiring targeted interventions. Use data driven insights to inform policy decisions and allocate resources effectively. Target interventions based on monthly trends by identifying highest number of casualties and implement interventions during these periods. For example, increase law enforcement presence, conduct public awareness campaigns and improve road infrastructure to mitigate risks and reduce accidents.

*  Road Safety Measures for Specific Road Type: Implement road safety measures tailored to different road types. For rural areas, focus on improving the safety measures on single carriage ways addressing hazards on one-way streets. In urban areas, priotize saftey enhancement on single carriage ways and other road types with high casualty rates.

*  Collaborative Efforts: Foster collaboration between government agencies, law enforcement, transportation authorities and community stakeholders to develop and implement strategies. Engage in partnership to leverage resources, expertise and community support for effective road safety initiatives.

  
## LIMITATIONS IN THE DATASET
* SEASONAL VARIATION: The monthly trends may be influenced by seasonal factiors such as weather conditions, holidays or events which could impact travel patterns and accident rates. Failure to account for these variations may lead to skewed interpretation of the data.

* LACK OF CONTEXT: Without additional context or information about external factors such as traffic volume, drivers behaviour, it may be challenging to fully understand the underlying reasons behind the observed trends and patterns.

* LIMITED SCOPE: The analysis focuses primarily on casualties and does not consider other important factors such as the severity of injuries, contributing factors to accidents (for example, distracted driving, speeding) or interventions implemented to improve safety.

## RECOMMENDATIONS FOR LIMITATIONS IN THE DATASET
*SEASONAL ADJESTMENT: Adjust the analysis for seasonal variations by comparing monthly trends to historical averages or accounting for factors such as weather patterns or holidays. This will provide a more accurate assesment of road safety performance through out the year.

*DATA QUALITY ASSURANCE: Conduct thorough data validation and cleaning processes to ensure the accuracy and completness of the dataset. Address any missing or inconsistent data to improve the reliability of the analysis results.

* CONTEXTUAL ANALYSIS: Incorporate additional contectual informations such as weather conditions, road infrastructure, traffic volume to better understand the underlying factors contributing to the observed trends. This will provide a more comprehensive view of the road safety dynamics.

* EXPAND ANALYSIS SCOPE: Expand the analysis to include the other relevant variables such as accident severity, contributing factors and intervention measures. This will allow for a more holistic assesment of road safety performance and facilitate the identification of target interventions to reduce casualties.
  
