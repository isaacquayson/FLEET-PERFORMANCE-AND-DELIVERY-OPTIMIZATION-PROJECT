# FLEET-PERFORMANCE-AND-DELIVERY-OPTIMIZATION-PROJECT

## OVERVIEW
This Excel-based dashboard analyzes delivery operations using key metrics like fuel consumption, costs, delivery times, and breakdowns.  
It provides logistics managers with actionable insights to identify inefficiencies and improve performance.  
The goal is to reduce operational costs, boost delivery efficiency, and enhance service reliability.

---

## GOAL

The goal of this project is to transform raw delivery data into a powerful, actionable Excel dashboard.  
By visualizing key metrics like total deliveries, fuel costs, and average delivery times, it enables deeper operational insights.  
Logistics teams can then optimize routes, reduce costs, improve efficiency, and enhance overall service reliability.

1. How efficient is our delivery operation across vehicle types
   
3. What is the impact of preparation time on the delivery time?
   
4. What are the most frequent causes of breakdowns, and which vehicles are most prone?
   
5. How much are we spending on fuel relative to distance and orders
   
6. How often did we use the vehicles for delivery/the most used vehicle type.
			
7. What is the average vehicle mileage for the vehicle types used for delivery?										
										
8. How many of our oders went through without break down and what percentage is that?										
										
9. How far, on average, does a vehicle travel per delivery?

---

## FEATURES

1. Key Performance Indicators (KPIs): At-a-glance metrics for total deliveries, total fuel cost, total breakdown cost, and average delivery time.

2. Operational Analysis: Detailed insights into delivery performance, including the number of deliveries and average delivery time broken down by vehicle type and time of day.

3. Cost Management: A comprehensive analysis of fuel costs and breakdown costs, allowing users to identify cost drivers and make data-driven decisions to reduce expenses.

4. Vehicle Performance Tracking: The ability to compare vehicle types based on key metrics such as fuel consumption, delivery volume, and breakdown frequency.

5. Interactive Visualizations: Dynamic charts and graphs that display trends in fuel consumption, breakdowns, and costs, making the data easy to understand.

6. Filter and Slicer Functionality: Interactive filters (e.g., by month, vehicle type) that allow users to drill down into specific data subsets and gain customized insights.

---

## TECHNICAL DETAILS

## Technology Stack

This project is built and optimized using **Microsoft Excel**, leveraging its powerful data analysis and visualization features to create an interactive and insightful dashboard.

### Tools & Features Used

- **PivotTables**: Aggregate raw delivery data and summarize key metrics such as total deliveries, costs, and averages.
- **PivotCharts**: Dynamic charts connected to PivotTables for real-time visual representation that updates automatically with filters.
- **Slicers**: Interactive controls that allow users to filter the dashboard by criteria such as Month or Vehicle Type, without manual filtering.
- **Formulas**: Standard Excel functions like `SUMIFS`, `AVERAGEIFS`, and calculated fields within PivotTables are used to derive KPIs and advanced metrics.

---

## Data Structure

The dashboard is powered by a flat dataset imported from `delivery_data.csv`, organized as a single table with the following key columns:

- `Delivery_ID`: Unique identifier for each delivery  
- `Date`: Date of the delivery  
- `Vehicle_Type`: Type of vehicle used  
- `Distance_KM`: Distance covered in kilometers  
- `Delivery_Time_Minutes`: Duration of delivery in minutes  
- `Fuel_Consumed_Liters`: Fuel consumed in liters  
- `Fuel_Cost`: Cost of fuel used  
- `Breakdown`: Indicator of whether a breakdown occurred  
- `Breakdown_Cost`: Associated cost if a breakdown occurred  

---

## Data Model

The project uses a **simple, self-contained data model**. All analysis and visualizations are directly based on the single master data table.  
No external data sources or complex relationships are involved, making the file **easy to manage, portable, and efficient**.

---

## DASHBOARD

![DASHBOARD](https://github.com/isaacquayson/FLEET-PERFORMANCE-AND-DELIVERY-OPTIMIZATION-PROJECT/blob/main/Screenshot%202025-08-07%20210041.png)

## RESULTS AND INSIGHTS

1. Scooters demonstrated the highest delivery efficiency, achieving the shortest average delivery time compared to motorcycles and vans.
   
3.	Motorcycles experienced the highest breakdown frequency, while vans had the lowest, indicating greater reliability for van deliveries.
   
5.	Motorcycles covered the longest cumulative distance, highlighting their extensive usage across the delivery network.
   
7.	There is a clear positive relationship between preparation time and delivery time — the shorter the preparation, the faster the delivery, and vice versa.
   
9.	Breakdown incidents were relatively low, with 70% of deliveries experiencing no breakdowns, reflecting strong overall fleet reliability.
    
11.	Motorcycles were the most utilized vehicle type in delivery operations, followed by scooters and vans.

---

## RECOMMENDATIONS

1. Implement a Preventive Maintenance Schedule for Motorcycles because, Motorcycles have the highest breakdown frequency and cover the longest distances.																			
2. Prioritize Scooters for High-Volume, Time-Sensitive Deliveries. Scooters show highest delivery efficiency (fastest delivery times).																			
3. Monitor and Minimize Preparation Time to Reduce Delivery Delays. There's a positive correlation between preparation time and delivery time.																			
4. Introduce a real-time breakdown alert and response system.																			

---

## CONCLUSION
This project transforms raw delivery data into an interactive Excel dashboard, providing clear KPIs and actionable insights on 
fleet efficiency, costs, and reliability. By revealing patterns in performance and downtime, 
it equips logistics managers to make data-driven decisions that enhance operational efficiency and delivery speed.






