The process of creating a dashboard in Power BI consist of following steps:

1.Requirement Gathering
2.Data Collection
3.Data Transformation & Modelling
4.Data Visualization Blueprint
5.Dashboard Layout & Design
6.Adding Interactivity & Navigation

Now lets see all of these steps in detail and develop a Power BI dashboard from scratch.

#1 Requirement Gathering

Identify Stakeholders – 

Determine primary stakeholder and establish a point of contact who might be the domain experts or leaders who will eventually use the dashboard

Understand Business Objectives – 

Through meetings and calls  with stakeholders you should get an outline of Goals from the entire endeavor. Asking open ended questions will help you gain more insights to understand the data and how this dashboard will help achieve a specific business goal.

High Level Data Study –

A high level overview of data is required before you initiate discussions around scope, metrics and other granular topics. So here we will try to understand the data in terms of:

1.Data Sources
2.Column Description
3.Data Type
4.Volume and frequency
5.Data Quality – Missing Values or Anomalies
Define Scope –
This is the perfect stage to discuss Key Metrics, KPIs & Deployment Timelines. Document the calculations, time frames & scope which will help in setting the expectations and avoiding any future disagreements. Also as a best practice remember to keep a 20% buffer while finalizing deadlines because it’s always better to over deliver after a standard commitment than to underdeliver after an extraordinary delivery pitch.

What is the problem statement :
Overall Objective

1.Track current status of patient waiting list
2.Analyze historical monthly trend of waiting list in Inpatient & Outpatient categories
3.Detailed specialty level & age profile analysis

Data Scope
2018 – 2021

Metrics
1.Average & Median Waiting List
2.Current Total Wait List

View
1.Summary Page
2.Detailed Page for Granular Analysis

#2 Data Collection
This is the stage where you decide the source of your data. This step is very important because this will also define how you are going to refresh the dashboard after deploying the solution.

#3 Data Transformation
Data transformation is a process of changing the structure of your data or applying additional steps which will clean or process your data for final usage. We do these transformations in the Power Query Editor which is inbuilt into Power BI.


#4 Visualization Blueprint
I have already created a blueprint, however in live scenarios you will sit down with your team and create a wireframe of the required dashboard. You will then get this approved from the end stakeholder before starting your development activities.


#5 Dashboard Layout & Design
Summary Page

Now place the charts based on our blueprint i.e doughnut, clustered column chart & top five Multi Row card. And remember to use the new measure which is Avg/Med Wait List in the values section.

Finally in the line chart at the bottom use Total column directly along with the Archive_Date. Remember to add a visual filter for Case_Type. So one chart will show Day Case & Inpatients and the other chart will show Outpatients. Add slicers for Archive_Date, Case_Type and Specialty.

Detailed View

Add a new page here add a matrix view using the Archive_Date, Specialty_Name, Age_Profile, Time_Bands, Case_Type and Total.


Tooltip Page

Create a new page which will be used as a tooltip. Add a chart to show Specialty and Total waitlist. Also add a card to show the Total sum of Wait List. 

#6 Adding Interactivity
Now add interactivity in your dashboard like navigation buttons, chart alt display text and hovering info.

