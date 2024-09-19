# DescriptiveAnalytics-AWS
Project Description: Project Description: Descriptive Analysis of Rental Issues in Vancouver

Project Title: Understanding Rental Issues in Vancouver's Grandview-Woodland and Downtown Neighborhoods

Objective:

This project aims to perform a descriptive analysis of rental issues in Vancouver's Grandview-Woodland and Downtown neighborhoods. The primary goal is to determine the percentage of rental units with outstanding issues in each neighborhood, enabling a comparison of property management effectiveness. The findings will help identify potential problem areas and provide actionable insights to improve rental conditions.

Dataset:

The analysis will utilize a dataset containing detailed information on rental properties in Vancouver, focusing on the following key features:
•	BUSINESSOPERATOR: The operators or companies managing the rental properties.
•	StreetNumber and Street: The specific addresses of the rental properties.
•	TOTALOUTSTANDING: The total number of outstanding issues reported for each property.
•	TotalUnits: The number of rental units within each property.
•	Geo Local Area: The neighborhood classification (Downtown, Grandview-Woodland).

Methodology:

1.	Data Collection and Preparation:
o	The dataset will be securely stored in Amazon S3 buckets, with data organized by neighborhood (Downtown and Grandview-Woodland).
o	AWS Glue DataBrew will be used to clean the dataset, addressing any inconsistencies, missing values, or duplicates to ensure data quality.
![image](https://github.com/user-attachments/assets/ce21810e-03d5-4f1d-ab45-367628c0883c)

3.	Descriptive Statistics:
o	Amazon Athena will be employed to query the dataset stored in S3 and calculate key metrics, including the percentage of rental units with outstanding issues in each neighborhood and the total number of issues and rental units.
![image](https://github.com/user-attachments/assets/bcfb0522-58bc-447a-ad37-aa536455c8cd)

5.	Data Visualization:
o	AWS QuickSight will be utilized to create visualizations that illustrate the findings:
	Bar charts to compare the percentage of rental units with outstanding issues between neighborhoods.
	Heatmaps to show the concentration of issues within each neighborhood.
	Line graphs to track trends in outstanding issues over time.
![image](https://github.com/user-attachments/assets/4f856378-79fa-41e7-80a6-d6110c04f826)

7.	Insights and Findings:
o	The analysis will uncover which neighborhood has a higher percentage of rental units with outstanding issues and identify specific areas or streets with more significant problems.
8.	Recommendations:
o	Based on the insights, recommendations will be provided to improve property management practices in neighborhoods with higher percentages of outstanding issues.
o	AWS CloudWatch Dashboards will be set up for real-time monitoring of rental issues, enabling proactive management.

Tools and Technologies:
![image](https://github.com/user-attachments/assets/8fc04335-1ba0-4c5f-b446-e88691b7dc22)


•	Amazon S3 for secure data storage.
•	AWS Glue DataBrew for data cleaning and preparation.
•	Amazon Athena for data querying and analysis.
•	AWS QuickSight for data visualization and dashboard creation.
•	AWS CloudWatch for ongoing monitoring and alerting.

Deliverables:

•	A comprehensive report detailing the analysis methods, findings, and recommendations.
•	Visualizations and dashboards in AWS QuickSight are used to present the key insights clearly.
•	A CloudWatch Dashboard for continuous monitoring of rental issues, helping property managers address problems as they arise.

Summary:

This descriptive analysis will provide valuable insights into rental issues in Vancouver's Downtown and Grandview-Woodland neighbourhoods. By identifying areas with higher percentages of outstanding issues, the project will inform strategies to enhance property management and improve rental conditions for tenants.


