# Analysing Smart City Bike Sharing Data

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Data Source](#-data-source)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [How to Use](#-how-to-use)

## 📊 Project Overview and Objective
This project involves cleaning, transforming, and analysing raw data and creating an interactive Power BI dashboard to derive meaningful business insights.

The main objective is to demonstrate data pre-processing techniques using an interactive Power BI dashboard visualization to make informed decisions.

## 🗂️ Data Source
Webscraping

## 🛠️ Tools & Technologies
- **Visualization:** Power BI
- **Documentation:** MS Word

## 🧹 Data Cleaning & Preparation
●	Data Cleaning & Transformation: Handled missing values, standardized formats, and created calculated fields.

●	Filtering & Sorting: Organized data to focus on relevant records.

●	Split address column to separate address from number.

## 🔍 Data Modelling and DAX (Power BI)
●	Data Model: Established relationships between tables and defined cardinality. 

<img width="701" height="419" alt="image" src="https://github.com/user-attachments/assets/04636d87-1d66-4559-b0d1-8c17b2d82726" />

●	DAX Measures: Implemented DAX formulas for key metrics, such as Average Bike availability rate (%), Occupancy (%), Average Stand availability rate (%), and Open Stand rate (%).

<img width="440" height="434" alt="image" src="https://github.com/user-attachments/assets/f3767279-814b-4b0b-93b9-f1f4b151b8b7" />

## 🔍 Analysis and Visualizations (Power BI)

<img width="1015" height="574" alt="image" src="https://github.com/user-attachments/assets/15a5944f-5cc3-44d8-ae72-c295ebe7b196" />

## 💡 Key Insights

The percentages of average bike availability in each city in shown in the bar chart below. The ideal availability is between 40 to 60 percent considering a good balance between bike and stand availability. Out of 25, 9 cities perform well in terms of bike availability, 7 have medium performance, and the others are under performing. The number of bikes has to be increased in those underperforming cities. 

<img width="1061" height="607" alt="image" src="https://github.com/user-attachments/assets/0f3be70a-f8a0-44ef-928b-de08a07ede6a" />

 
The availability of stands is categorized into High (more than 70%), Medium (30-70%), and Low (below 30%). This pie charts indicates that most of the cities have high availability and more than 30% cities have medium availability. However, a significant number of cities have low availability where focus is required on increasing the stands.

 <img width="940" height="592" alt="image" src="https://github.com/user-attachments/assets/d909228d-8f52-4488-937d-45bec7d570a0" />


Ideally for a smooth operation, the balance between occupancy rate and stand availability rate is crucial. Individually these two categories should remain between 40-60% to maintain a good balance. Any number outside this range affects the balance significantly. The chart below shows this balance across cities.

<img width="940" height="508" alt="image" src="https://github.com/user-attachments/assets/199f45a1-95f9-4a5a-9717-3ba71a8bb3fd" />

 
The percentages of average bike availability in each city in shown in the map below. The ideal availability is between 40 to 60 percent considering a good balance between bike and stand availability. Out of 25, 9 cities perform well in terms of bike availability, 7 have medium performance, and the others are under performing. The number of bikes has to be increased in those underperforming cities. 

  <img width="863" height="537" alt="image" src="https://github.com/user-attachments/assets/1bd83721-ea35-4848-b26b-f6db975b96f5" />


The trends of average Stand availability and average Bike availability from 2022 to 2025 are shown below. The stand availably predominantly lies in the higher range whereas the bike availability lies in the lower range. This indicates the requirement to increase the number of bikes is more than that of the stands. 
 
<img width="931" height="544" alt="image" src="https://github.com/user-attachments/assets/69a29c83-33cb-4d7c-b885-a3a24a044540" />


## 🚀 Recommendations

To achieve maximum operating efficiency, both the occupancy rate and the stand availability rate has to be balanced. To maintain these rates within the optimum range of 40-60% the number of stands is required to be increased in few cities and the number of bikes is required to be increased in few other cities as per the charts indicate. 

