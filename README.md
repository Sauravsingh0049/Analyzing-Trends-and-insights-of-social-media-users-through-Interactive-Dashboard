# Analyzing Trends and insights of social media users through Interactive Dashboard on Microsoft PowerBi


## Objectives
We want to gain the insights and trends of social media users from the United States, the United Kingdom, and Australia. 

## Dataset Used
A historical dataset with 1001 rows and 14 columns containing data of social media users from three countries of different age groups. Data is extracted from the Kaggle website and it is stored in a single table.

![image](https://github.com/Sauravsingh0049/Data-Analysis-with-MySQL/assets/155745836/0f766b2c-a2b5-48bd-9c71-d6de94a34dd8)


## Steps of Creating an Interactive Dashboard on Microsoft PowerBI

1. Data Cleaning - I have created a different column by the name of age group in which users having ages more than 0 but less than 18 are in the group "0-18", users having ages more than 18 but less than 35 are in the group "18-35", more than 35 but less than 60 in the group "35-60" and the user having age more than 60 are in the group "60+" by using excel function "=IF(B2<=18, "0-18", IF(B2<=35, "18-35", IF(B2<=60, "35-60", "60+")))"

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/60dfc95a-419a-4cf7-930c-8c122df7a62e)

2. Replacing Sub_Urban to Sub Urban for more clarity by using the "Find and Replace" function.

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/b476188b-1008-42b2-a20e-857bad15dab0)

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/9958c28e-a40e-4445-aa84-2c6d670ed66b)

Now The data is cleaned and we can import data on the MicroSoft PowerBI.
- For importing Data from the Excel to the Microsoft PowerBI,
  Open Microsoft PowerBI > New File > Get Data > Excel Workbook > select Excel file < select worksheet.
![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/439270b3-944c-430a-a142-153e9c4f0290)

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/221d7e12-bad9-49ad-9821-e1c0be60fcbd)

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/f51c474b-7e0e-4363-8ac2-bcd3c7434053)

  Now we are ready to create an interactive Dashboard with the data.

## Steps of creating an Interactive Dashboard from the dataset

- Creating a Card Visual for reprenting average time used on social media by the users.

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/36768803-d04c-4260-9d66-e5a356d7aad9)


- Creating a clustered column chart to represent the contribution of different age groups.
  
![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/c54b9f4f-efee-42a3-aed1-2e3e767d598d)


- Creating a Donut chart to represent the contribution of people on different platforms.
  

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/c3771c71-23ae-422c-a9b9-2cbd007e6fc5)

- Creating a card visual for representing the average salary of the users.

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/b26d57e3-7072-49a7-9e17-a6367f55e0b3)



- Creating a map visual for representing the no of users in different locations.

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/9f076e4c-b120-4198-8d1d-21aab58e0871)



- Creating a table for representing the total no. of users with their interest.
  
![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/4aa80d32-95d7-4805-8212-64ed3858d07a)


- Creating a pie chart to represent the contribution of people by their profession.

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/5dfa9189-5229-4809-a0eb-de47b6cbc427)


- creating a slicer visual based on gender and demographic location.

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/e09a4843-503f-491a-805a-ac52e0b4283c)

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/29456f0a-2e43-49cd-9832-0ad374775e23)


## Overview
![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/ba37b8c9-3ef2-4888-9350-132d98ec51e9)

![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/6490058e-5916-4f6d-be40-6c9a8f19751a)



## Tools Used
![image](https://github.com/Sauravsingh0049/SocialSphere-Insights-PowerBI-Dashboard-Project/assets/155745836/2b8c283b-c8fb-4e1e-9c81-bd7153059229)


Microsoft Power BI is an interactive data visualization software product developed by Microsoft with a primary focus on business intelligence.[2] It is part of the Microsoft Power Platform. Power BI is a collection of software services, apps, and connectors that work together to turn various sources of data into static and interactive data visualizations. Data may be input by reading directly from a database, webpage, PDF, or structured files such as spreadsheets, CSV, XML, JSON, XLSX, and SharePoint.

## Result
- Suburban people invested more time on social media followed by rural and then urban people.
- Females are using social media than males.
- Most people use Instagram, followed by YouTube and then Facebook.
- people in the age group 35-60 are the highest-time consumers on social media.



