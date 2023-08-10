# Education Ministry Project
## Introduction
The Ministry of Education plays a pivotal role in shaping the future of a country by inculcating an educated and skilled citizenry. Its efforts gear to the development of a well-rounded, knowledgeable population capable of contributing to the social, economic, and cultural growth and progress of the nation.
They generate data on various aspects of the education system, such as enrollment rates, dropout rates, academic performance, and a lot more. 
This project was done using a Power BI desktop for the Analysis, Modelling and Visualization.
## About the dataset
This dataset was provided at a named Senior Secondary School community volunteering project that I participated in. The file comprises of two dataset- Student dataset; having 7784 rows and 6 columns,  and Course dataset with 67891 rows and 7 columns.
The dataset can be found [here]
## Project Description
In this Module's Scenario, I have been tasked by senior leadership of exams and records department of the school to create a suite of reports that are dependent on data store by HR in an excel document. The Goal of this project is to track students who dropped out of High school and are now Re-enrolled into the program. 

## Skills Demonstrated
The following Power BI was incoporated:
- Microsoft Power BI 
- Data Modelling
- DAX
- Building Dashboard

## Problem Statement
1. Monthly Student Enrollments by State
2. Monthly graduates - by state
3. Monthly credits earned - by state
4. Any other insights in the data you think might be useful.
## Data Extraction 
The dataset (in csv) was extracted and loaded into the Power BI desktop. This was further transformed to view the anomalies and view missing values in the dataset 

![](https://github.com/AzeezOdekunle/Education-Ministry-Project/blob/main/Solution/Data%20Extraction.jpg)

## Data Cleaning
The transformed dateset was cleaned by removing the null (empty) values so that data integrity was ensured to give a robust analysis. This can be seen below at the deactivation date and deactivation reason gave 100% valid compared to 65% of dirty data.
The null values was unchecked by clicking and hover the cursor on the filter funnel of the ‘Deactivation Date’ column.


Dirty student Data                 | Null values                             | Cleaned student Data
:---------------------------------:|:---------------------------------------:|:--------------------------------:
![](dirty_student_data.png)        |![](student_data_null.png)                                    |![](cleaned_student_data.png)


## Data Modelling
The created relatioship established within the data for quick measures and calculations. The cardinality generated is many to one, having single as cross filter direction. 

![](model_view.png)


## Data Analysis Expression (DAX) and Measures.
Based on some certain calculations which were not implicitly calculated by Power BI. I calculated some measures using DAX to give summary of KPI’s and visualize them for data driven decisions. Some of the measures that were explicitly calculated were:
Grades A, B and C categories, total course entries, course program type, total credit earned e.t.c

![](https://github.com/AzeezOdekunle/Education-Ministry-Project/blob/main/DAX/DAX_A-.png)
![](https://github.com/AzeezOdekunle/Education-Ministry-Project/blob/main/DAX/dax_b%2B.png)
![](https://github.com/AzeezOdekunle/Education-Ministry-Project/blob/main/DAX/dax_c.png)
![](https://github.com/AzeezOdekunle/Education-Ministry-Project/blob/main/DAX/total_credit_earned.png)
![](https://github.com/AzeezOdekunle/Education-Ministry-Project/blob/main/DAX/total_program.png)
![](https://github.com/AzeezOdekunle/Education-Ministry-Project/blob/main/DAX/total_student.png)


![](https://github.com/AzeezOdekunle/Education-Ministry-Project/blob/main/Solution/Model%20and%20Measures%20Field.PNG.jpg)


## Dashboard
The visuals of the analysis is shown below which provided answers to the problem statement:


![](https://github.com/AzeezOdekunle/Education-Ministry-Project/blob/main/Measures.PNG)



![](https://github.com/AzeezOdekunle/Education-Ministry-Project/blob/main/DashBoard.PNG)



