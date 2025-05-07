
# 🚗 Uber Rides Data Analysis

This project is a comprehensive analysis of Uber ride data, aimed at uncovering patterns in trip usage, distance, timing, and purposes of travel. The data is visualized using **Power BI**, and data preprocessing is performed using **Power Query Editor**.

## 📊 Dashboard Overview

The interactive dashboard provides key insights through various visualizations:

### **1. KPIs (Key Performance Indicators)**
- **Total Time:** `21.05K` units (could represent minutes/hours depending on dataset)
- **Total Trips:** `1108`
- **Total Distance:** `14.11K` units
- **Average Speed:** `38.60`

### **2. Sum of Distance by Purpose (Pie Chart)**
- Highlights how distance traveled is distributed across different travel purposes.
- Major contributor: **Business (38.29%)**
- Other categories include Personal, Meeting, Errands, and Airport, among others.

### **3. Duration vs Distance (Scatter Plot)**
- Shows correlation between trip duration and distance.
- Helps identify outliers or long-duration, short-distance trips and vice versa.

### **4. Total Distance by Time of Day (Bar Chart)**
- Most distance covered during **Afternoon**, followed by **Evening** and **Morning**.
- Least distance recorded during **Night** hours.

### **5. Trip Logs (Table)**
- Lists start and stop locations of rides.
- Useful for route optimization and popular destinations.

### **6. Sum of Distance by Month (Line Chart)**
- Identifies travel volume trends over months.
- Peaks observed in **March, July, October, and December**.

### **7. Number of Trips by Month (Line Chart)**
- Helps track ride frequency monthly.
- December shows the highest number of trips.

### **8. Filters/Controls**
- **Day Filter:** To analyze specific days (e.g., Friday, Monday).
- **Month Filter:** For monthly trend drilling.
- **Day Time Filter:** For segmenting data by time of day.

## 🛠 Tools & Technologies Used

- **Power BI Desktop**
  - For interactive dashboard design and visualization.
  - Used custom visuals and slicers for intuitive filtering.

- **Power Query Editor**
  - For data cleaning, transformation, and shaping.
  - Operations include: Removing duplicates, formatting date/time, filtering nulls, and deriving new columns.

## 📁 Project Structure

```
uber_Rides_Data_Analysis/
│
├── README.md                # Project documentation
├── Image.png                # Dashboard screenshot
└── Uber_Rides_Report.pbix   # Power BI report file (assumed location)
```

## 📈 Key Insights

- **Business rides** contribute the most to overall distance.
- **Afternoon** is the most active time for travel.
- **December** sees a peak in both number of trips and total distance.
- Duration vs Distance plot shows data quality and trip efficiency.

## 📌 How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Use slicers on the left panel to filter by day, month, and time.
3. Hover over graphs for tooltips with more information.
4. Use the pie chart and scatter plot to drill down into trip purposes and efficiency.

## 🚀 Future Enhancements

- Integrate weather data for correlation with ride trends.
- Add cost analysis and fare breakdown.
- Predictive modeling for forecasting ride demand.
