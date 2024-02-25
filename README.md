# Analyzing Trends and insights of social media users through Interactive Dashboard on Microsoft PowerBi


## Objectives
We want to gain the insights and trends of social media users from the United States, the United Kingdom, and Australia. 

## Dataset Used
A historical dataset with 1001 rows and 14 columns containing data of social media users from three countries of different age groups. Data is extracted from the Kaggle website and it is stored in a single table.

![image](https://github.com/Sauravsingh0049/Data-Analysis-with-MySQL/assets/155745836/0f766b2c-a2b5-48bd-9c71-d6de94a34dd8)


## Steps of Creating an Interactive Dashboard on Microsoft PowerBI

1. Data Cleaning - I have created a different column by the name of age group in which users having ages more than 0 but less than 18 are in the group "0-18", users having ages more than 18 but less than 35 are in the group "18-35", more than 35 but less than 60 in the group "35-60" and the user having age more than 60 are in the group "60+" by using excel function "=IF(B2<=18, "0-18", IF(B2<=35, "18-35", IF(B2<=60, "35-60", "60+")))"

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/ae6f0140-c61c-4636-8605-6c518d4b9f4b)

2. Replacing Sub_Urban to Sub Urban for more clarity by using the "Find and Replace" function.

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/b8f04898-9b3d-4cda-9ef2-e628dce2a3d7)

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/f186d226-ee9c-4663-9420-1b7a556d8830)

Now The data is cleaned and we can import data on the MicroSoft PowerBI.
- For importing Data from the Excel to the Microsoft PowerBI,
  Open Microsoft PowerBI > New File > Get Data > Excel Workbook > select Excel file < select worksheet.
  ![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/0805f1d9-893a-4ce2-8e4d-df26adda9de8)

  ![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/f6bd424c-221c-44a8-8fe7-ca21866ed248)

  ![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/31ed4110-be5d-4f38-9f5a-40df1432eb7c)

  Now we are ready to create interactive Dashboard with the data.

## Steps of creating an Interactive Dashboard from the dataset

- Creating a Card Visual for reprenting average time used on social media by the users.

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/99bff980-718f-477d-9c5a-6655f7aae117)


- Creating a clustered column chart to represent the contribution of different age groups.
  
![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/c77ea102-cb13-4d8f-a8ab-07320ecbe20e)


- Creating a Donut chart to represent the contribution of people on different platforms.
  

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/657d32f4-287d-49d3-8f99-84a150d70b09)

- Creating a card visual for representing the average salary of the users.

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/d235a9bb-c1c1-4aa6-b082-08104a6ec968)



- Creating a map visual for representing the no of users in different locations.

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/bcf9c657-233f-46de-ba38-5c3a3a17b080)



- Creating a table for representing the total no. of users with their interest.
  
![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/4aa80d32-95d7-4805-8212-64ed3858d07a)


- Creating a pie chart to represent the contribution of people by their profession.

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/0023f618-2caf-4730-8b9e-34ceb8afc6b1)


- creating a slicer visual based on gender and demographic location.

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/34f6017a-55bb-4d00-83b7-39d14c58bd98)

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/ba2a4d2f-e068-4e70-81de-96ed6b9919a8)


## Overview
![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/a7e0b414-3c5c-4c8b-b9fc-4e9ce22f2a1a)

![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/5d8f3557-b57e-4cde-8388-1cd5d05c5a86)



## Tools Used
![image](https://github.com/Sauravsingh0049/Analyzing-Trends-and-insights-of-social-media-users/assets/155745836/0930ebb4-1abf-403b-ba6c-903b69492a58)


Microsoft Power BI is an interactive data visualization software product developed by Microsoft with a primary focus on business intelligence.[2] It is part of the Microsoft Power Platform. Power BI is a collection of software services, apps, and connectors that work together to turn various sources of data into static and interactive data visualizations. Data may be input by reading directly from a database, webpage, PDF, or structured files such as spreadsheets, CSV, XML, JSON, XLSX, and SharePoint.

## Result
- Suburban people invested more time on social media followed by rural and then urban people.
- Females are using social media than males.
- Most people use Instagram, followed by YouTube and then Facebook.
- people in the age group 35-60 are the highest-time consumers on social media.



