  # Healthcare Readmission Data Analysis

## Overview:
Many low income families and individuals use Medicare services for their medical needs. Our aging population is experiencing a boom in individuals who are hitting retirement age, this population is also known as the baby boomers (people born between the years of 1946-1964 (investopedia.com)), making more individuals Medicare eligible than ever before. The quality of medical services received and the prevention of wasted medical spending has been a growing concern especially of those who receive Medicare benefits. The federal government has enact legislation to ensure that Medicare recipients receive quality care while preventing wasteful medical spending.  Readmission rates are a good indicator of how effective the services that a healthcare facility provides. By exploring the Center of Medicare of Medicaid and Medicare Services (CMS) readmission data and supporting data can be done to determine how nationally we hold up with maintaining the quality of services for our Medicare recipients and determine the health of our aging population.

## Data Question
Is federal legislation improving quality of care for Medicare recipients in regards to readmissions, complications, and deaths? If so, which states are doing well and which are doing poorly? Are there any additional factors influencing the data.

## The data
For this project data from the CMS website was used. Two datasets were chosen that would support showing how nationally we are doing in terms of mainly quality to CMS standards. The first data set was CMS readmission reduction program data. This dataset provided nationally for all hospitals that service Medicare patients by state. The data from the CMS readmission reduction program was pretty clean there were some hospitals that did not report their data to CMS. The second dataset is CMS complications and death by state which provides information about trending complications and deaths at facilities across all 50 states. This dataset was pretty clean as well but also had some unreported data which resulted in missing values.

## Tools used
I used PowerBI with PowerQuery to perform the data analysis and build my dashboard.

## The Process
I downloaded then retrieve my datasets using the power query functionality that is built within PowerBI. Within power query I cleaned my data and fixed any formatting issues that came with the data. 

From there I started doing exploratory data analysis looking for trends and learning more about the data.
 
 I first looked at which states have the highest readmission rates nationally and the states that have the lowest readmission rates nationally. From there I created an interactive dashboard where a user can look at those states with the lowest and highest readmission rates at a high level and select those states to learn additional information in regards to average number of readmissions, average number of discharges, and the number of facilities reported in the data.
 
![image](https://user-images.githubusercontent.com/52723248/71938994-c9d06080-3176-11ea-944b-64d0c8682e0e.png)

From there I decided to look at top health indicators and demographics by state to see if states with the lowest and highest readmission also fall high on top health indicators in the US. I created an overview dashboard featuring the top 10 statesin the following demographic or health indicator categories: average number of individuals by reported with cancer and chronic dieases, the states with the highest percentage of individuals who are 65+, and states with the highest percentage of individuals with chronic dieaseses.

![image](https://user-images.githubusercontent.com/52723248/71940921-af4db580-317d-11ea-8167-38e6c3a9d4b7.png)

After looking at some of the states indicators and demographic, I pulled in the complications and death dataset, cleaned it in powerquery, and looked at complications and death measures by state. From there I created an interactive dashboard that allowed users to look at top 10 death and complications health measure in regards to the number of facilities within the state who rank best and worse in those measured categories. 

