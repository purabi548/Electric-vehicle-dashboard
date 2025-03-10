Electric Vehicle Analysis Dashboard 

Overview:
This Power BI dashboard provides an in-depth analysis of electric vehicle (EV) trends, adoption rates, and key insights based on the Electric Vehicle Population Dataset. It includes KPIs, charts, and maps to help visualize the market landscape of electric vehicles.

Features
🔹 KPIs:

Total Electric Vehicles,
Average Electric Range,
Total BEV Vehicles & Percentage,
Total PHEV Vehicles & Percentage,

🔹 Visualizations:

📊 Total Vehicles by Model Year (Line Chart),
🌎 Total Vehicles by State (Map Chart),
🚗 Top 10 Vehicle Makes (Stacked Column Chart),
✅ CAFV Eligibility Analysis (Pie Chart),
🔝 Top 10 Vehicle Models (Stacked Bar Chart)

Data Cleaning & Transformation in Power BI:

Renamed Values: BEV → Battery Electric Vehicle, PHEV → Hybrid Electric Vehicle,
Filtered Data: Removed blank vehicle location records,

Created New Columns:
Electric Range Bin (Low: 0-100, Medium: 101-200, High: >200),
Latitude & Longitude Extraction from Location Data

How to Use:
Download the dataset (Electric_Vehicles_dataset.csv).
Open Power BI and load the dataset.
Apply the transformations as described.
Use the pre-built visuals or customize them as needed.

Installation:
To use the Power BI file:

Install Microsoft Power BI (if not already installed).
Clone this repository:
git clone https://github.com/purabi548/electric-vehicle-dashboard.git
Open the .pbix file in Power BI.

Contributing:
Feel free to contribute by adding new visualizations, improving performance, or enhancing the dataset. Fork the repo and submit a pull request!

License:
This project is open-source and available under the MIT License.
