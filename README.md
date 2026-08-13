AIRLINE DATA ANALYSIS & POWER BI DASHBOARD

Project Overview

This project is an interactive Airline Data Analysis Dashboard developed using Power BI. It provides insights into flights, passengers, revenue, delays, routes, destinations, aircraft types, passenger feedback, and ticket class patterns through interactive visualizations.

Tools Used

•	Power BI

•	Power Query

•	DAX

Key Features

•	Total Flights KPI

•	Total Passengers KPI

•	Total Revenue KPI

•	Average Delay KPI

•	Flight Status Analysis

•	Monthly Revenue Analysis

•	Flight Count by Airport

•	Average Delay by Route

•	Average Delay by Month

•	Average Delay by Destination

•	Flight Count by Aircraft Type

•	Passenger Feedback Analysis

•	Ticket Class Analysis

•	Feedback Score Distribution

•	Age Group and Ticket Class Analysis

•	Frequent Flyer Analysis

Dashboard Preview

Page 1 – Airline Overview


<img width="940" height="525" alt="image" src="https://github.com/user-attachments/assets/64a37fc5-cd78-4745-8f47-3b9aaa4a971f" />

 

Page 2 – Delay & Aircraft Analysis


<img width="940" height="531" alt="image" src="https://github.com/user-attachments/assets/d61da109-6a63-4d3b-820b-504f080c0baa" />


 
Page 3 – Passenger Feedback & Ticket Insights


 <img width="940" height="524" alt="image" src="https://github.com/user-attachments/assets/443795a1-c6b4-4430-932c-e778a0478837" />


DAX Measures

Average Delay(min) = AVERAGE(Airline_Flights[Delay (min)])

Total Flight = DISTINCTCOUNT(Airline_Flights[Flight ID])

Total Passengers = DISTINCTCOUNT(Airline_Passengers[Passenger ID])

Total Revenue = SUM(Airline_Revenue[Total Revenue])

Feedback Score Count = COUNTROWS(Airline_Passengers)


Skills Demonstrated

•	Power BI

•	Power Query

•	DAX

•	Data Visualization

•	Dashboard Design

•	Interactive Reporting


