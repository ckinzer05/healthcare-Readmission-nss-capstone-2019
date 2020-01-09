  # Healthcare Medicare Quality Data Analysis

## Overview:
Many low income families and individuals use Medicare services for their medical needs. Our aging population is experiencing a boom in individuals who are hitting retirement age, this population is also known as the baby boomers (people born between the years of 1946-1964 (investopedia.com)), making more individuals Medicare eligible than ever before. The quality of medical services received and the prevention of wasted medical spending has been a growing concern especially of those who receive Medicare benefits. The federal government has enact legislation to ensure that Medicare recipients receive quality care while preventing wasteful medical spending.  Readmission rates are a good indicator of how effective the services that a healthcare facility provides. By exploring the Center of Medicare of Medicaid and Medicare Services (CMS) readmission data and supporting data can be done to determine how nationally we hold up with maintaining the quality of services for our Medicare recipients and determine the health of our aging population.

## Data Question
Is federal legislation improving quality of care for Medicare recipients in regards to readmissions, complications, and deaths? If so, which states are doing well and which are doing poorly? Are there any additional factors influencing the data.

## The data
For this project data from the CMS website and the Big Cities Health Coalitions. The datasets chosen would support showing how nationally we are doing in terms of mainly quality to CMS standards. All datasets were pretty clean and only had formatting issue that needed to be fixed in powerquery.

CMS Hospital Readmission and Reduction Program (HRRP): Provided Medicare data from 2014-2017 in regards to HRR. https://data.medicare.gov/Hospital-Compare/Hospital-Readmissions-Reduction-Program/9n3s-kdb3

CMS Complications and Death-State: Provided state-level data from 2016-2018 for the hip/knee complication measure, the CMS Patient Safety Indicators, and 30-day death rates. https://data.medicare.gov/Hospital-Compare/Complications-and-Deaths-State/bs2r-24vh

Big Cities Health Coalition: Provided 18,000 data points from 2010-2018 across more than 50 health, socio-economic, and demographic indicators across 11 categories in the United States for health in 30 of the largest most urban cities. https://bchi.bigcitieshealth.org/indicators/1829/searches/35654


## Tools used
I used PowerBI with PowerQuery to clean, perform the data analysis, and build my dashboard.

## The Process
I downloaded then retrieve my datasets using the power query functionality that is built within PowerBI. Within power query I cleaned my data and fixed any formatting issues that came with the data. 

From there I started doing exploratory data analysis looking for trends and learning more about the data.
 
 I first looked at which states have the highest readmission rates nationally and the states that have the lowest readmission rates nationally. From there I created an interactive dashboard where a user can look at those states with the lowest and highest readmission rates at a high level and select those states to learn additional information in regards to average number of readmissions, average number of discharges, and the number of facilities reported in the data.
 
![image](https://user-images.githubusercontent.com/52723248/71938994-c9d06080-3176-11ea-944b-64d0c8682e0e.png)

From there I decided to look at top health indicators and demographics by state to see if states with the lowest and highest readmission also fall high on top health indicators in the US. I created an overview dashboard featuring the top 10 statesin the following demographic or health indicator categories: average number of individuals by reported with cancer and chronic dieases, the states with the highest percentage of individuals who are 65+, and states with the highest percentage of individuals with chronic dieaseses.

![image](https://user-images.githubusercontent.com/52723248/71940921-af4db580-317d-11ea-8167-38e6c3a9d4b7.png)

After looking at some of the states indicators and demographic, I pulled in the complications and death dataset, cleaned it in powerquery, and looked at complications and death measures by state. From there I created an interactive dashboard that allowed users to look at top 10 death and complications health measure in regards to the number of facilities within the state who rank best and worse in those measured categories. 

![image](https://user-images.githubusercontent.com/52723248/71941665-3734bf00-3180-11ea-98da-08d28a9a61a9.png)

Lastly after looking at complications and deaths measures of facilities by state, I wanted to see if the average number of readmissions by state impacted the number of facilities by state who rank worse or better in complications and deaths. I created a bar and line graph to show the if there was any relationship. 

![image](https://user-images.githubusercontent.com/52723248/71942311-63e9d600-3182-11ea-9b98-513ced9692bc.png)

## Conclusion

The Hospital readmission reduction program does not seem to making an impact on excessive readmissions nationally. Penalities seem to be helping with reducing Medicare costs but is not helping with Medicare patients get quality care. Large metropolitian areas with higher geriatric populations are struggling with readmission rates. Lastly readmission rates do not seem to be largely impacted by complication and death rates;however, the complications and death data that I used was limited and with additional information a more informed decision can be made. 

## Next Steps

In future analysis, I would like to dig deeper within Florida and Texas data. They hit high consistenly across many metrics in my analysis. It would also be interested to pull in medicare payment and penalty data to highlight offenders.

## Dashboard Link

PowerBI Dashboard: https://app.powerbi.com/view?r=eyJrIjoiODY1NGJkMzktZTJmYy00MmJjLThhOWUtMzUwODM2MzJmNmZiIiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9

