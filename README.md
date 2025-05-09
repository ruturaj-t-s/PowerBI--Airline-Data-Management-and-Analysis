# PowerBI--Airline-Data-Management-and-Analysis
Using PowerBI, analyze and visualize airline data to gain operational  insights, improve passenger management, and track booking trends effectively.

## 📌 Overview

This project focuses on analyzing airline operations using **Power BI**, offering deep insights into flight schedules, passenger behavior, and ticketing trends. With the airline industry being dynamic and data-intensive, this analysis helps in streamlining operations and enhancing customer experience.

## 🎯 Objective

To visualize and analyze airline data for better operational insights, efficient passenger management, and an understanding of booking behaviors using interactive dashboards and data models.

## 📊 Datasets Used

- **Flight Information**: FlightID, FlightNumber, Airline, Destination, Status  
- **Passenger Information**: PassengerID, FlightID, SeatNumber  
- **Ticket Information**: TicketID, FlightID, BookingStatus  

## 🛠️ Key Steps Performed

### 1. Data Cleaning & Transformation
- Removed duplicates and handled missing values  
- Used Power Query to format data types and categorize fields  
- Applied filters to detect and correct anomalies  

### 2. Data Modeling
- Created relationships using `FlightID` as the primary key  
- Defined one-to-many relationships between Flight, Passenger, and Ticket tables  
- Ensured correct cardinality and single-direction filtering  

### 3. Enhanced Insights
- Added a `Classification` column to label flights as **Best** or **To Be Improved**  
- Used "Column from Examples" to extract and transform fields  
- Verified integrity by cross-checking with original data  

### 4. DAX Calculations
- Performed various DAX calculations and created measures for better understanding and analysis of data.

### 📊 Visualizations & Interactive Features

- **Visuals**:
  - 📊 Bar chart: Passenger count by airline
  - 🥧 Pie chart: Ticket booking statuses
  - 🌳 Decomposition Tree: Flights by airline and destination
  - 🗺️ Map visualization: Flight destinations

- **Interactive Elements**:
  - 🔘 Slicers with a Reset button
  - 🔖 Bookmark buttons for quick view navigation (e.g., Best Flights, Crowded Flights)
  - 🕵️‍♂️ Drill-through reports for airline-specific performance details

---

### 🖥️ Final Dashboard & Deployment

- ✅ Published to Power BI Service in a new workspace
- 🔐 Configured **Row-Level Security (RLS)** for Airline A
- 🔄 Set up daily data refresh at **5 PM**
- ⚠️ Note: Map visual may not render for all users due to account-level restrictions

---

### 🔍 Key Insights

- **Flight Status Overview**:
  - 82 flights were **On Time**
  - 60 flights were **Cancelled**
  - 58 flights were **Delayed**

- **Ticket Trends**:
  - 19 bookings **Cancelled**
  - 17 bookings **Confirmed**
  - 14 bookings **Pending**

- **Passenger Load** (Average per flight):
  - Cancelled: **1.28**
  - Delayed: **1.17**
  - On-Time: **1.2**

- **Cancellations**:
  - Highest: **Airline A** and **Airline D**
  - Top destination with cancellations: **Los Angeles**

- **Delays**:
  - Most by **Airline D**
  - Worst-affected destinations: **Houston**, **Los Angeles**, **Phoenix**

---

### ✅ Key Takeaways

- **Airline A** and **Airline D** need operational improvements
- **Los Angeles** and **Houston** should be reviewed due to high disruption
- **Airline B** showed the **most reliability** among all carriers

---

### 📽️ Demo Video

▶️ [Watch Project Walkthrough](https://drive.google.com/file/d/1SL4uVQmg8ZF6jqmPlbt8LdOug5yBUXSB/view?usp=sharing)

