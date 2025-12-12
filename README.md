# <img width="210" height="29" alt="image" src="https://github.com/user-attachments/assets/1c95f29d-c786-45f7-a293-5ebb92baaac7" />

The sales team struggled to identify which markets were driving the most profit and which products were seasonal. They needed a solution to answer three key questions at a glance:
1. profitability: Which countries and products generate the highest margins?
2. Volume: How are units sold trending month-over-month?
3. Strategy: Where should marketing efforts be focused based on historical performance
# <img width="261" height="29" alt="image" src="https://github.com/user-attachments/assets/e336fab5-005e-45e9-aaf7-763ce0c01e00" />

This dashboard consolidates data from over 700+ transaction records (Data.csv) to visualize the following metrics:

<img width="300" height="73" alt="image" src="https://github.com/user-attachments/assets/6689e785-9e06-4874-b7f5-d5e73b222f02" />

• Metric: Profit by Month

• Visualization: Trend lines showing the rise and fall of net profit.

• Insight: Identified peak sales periods (Q4) allowing for better inventory forecasting.

<img width="189" height="25" alt="image" src="https://github.com/user-attachments/assets/e5e229a6-bf95-4905-b696-e92c8d9b0d49" />

• Metric: Units Sold Each Month

• Visualization: Bar charts comparing monthly volume.

• Insight: Correlated specific marketing campaigns with spikes in unit sales.

<img width="334" height="25" alt="image" src="https://github.com/user-attachments/assets/703e82c4-d262-4ec5-8fdc-9d31e696c2a1" />

• Metric: Profit by Country & Cookie Type

• Visualization: Heatmaps/Stacked Charts.

• Insight:

       • Identified that while "Chocolate Chip" is the volume leader, premium cookies drive higher profit margins in specific European markets.
       
       • Comparative analysis of performance across 5 different countries.

<img width="228" height="29" alt="image" src="https://github.com/user-attachments/assets/4bd0cd6d-0939-4d12-8685-6a76b02cc828" />
<br><br>
  <img width="200" height="21" alt="image" src="https://github.com/user-attachments/assets/7ad1849d-a742-49a2-a2ac-59404f57d303" />

 Imported raw sales logs (Data.csv and New Data.csv).

 Standardized date formats and currency fields.

 Checked for duplicates and null values to ensure data integrity.

<img width="166" height="21" alt="image" src="https://github.com/user-attachments/assets/db58b742-d627-4178-a78e-5f12e0e1d750" />

 Created relationships between raw data tables and lookup tables.

Structured data to support scalable Pivot Tables (Profit by month.csv, Units sold each month.csv).

<img width="229" height="21" alt="image" src="https://github.com/user-attachments/assets/e8c06e34-0a6b-4ac6-b15a-8ad546fcf72c" />

 Utilized Pivot Charts for dynamic visualization.
 
 Implemented Slicers to allow users to filter the entire dashboard by Country, Product, or Date range instantly.
 
 Designed with a user-centric layout for intuitive navigation

<img width="174" height="29" alt="image" src="https://github.com/user-attachments/assets/0f5bd3b6-8a71-43b5-a4a8-8d6020473015" />

• Data.csv: The historical raw sales data used for training the model.

• New Data.csv: Incremental data sets used to test the dashboard's dynamic updating capabilities.

• Profit by country and cookie.csv: Aggregated data focusing on geospatial profitability.

• Excel Interactive Dashboard.xlsx: The final interactive tool.

<img width="297" height="29" alt="image" src="https://github.com/user-attachments/assets/1a1abf06-f616-4ab1-a1de-05fcd9222631" />

1. Download the Excel Interactive Dashboard.xlsx file.

2. Open the file in Microsoft Excel (2016 or later recommended).

3. Use the Slicers on the left panel to filter by Country (e.g., "United States") or Product (e.g., "Fortune Cookie").

4. Watch the charts automatically update to reflect the specific segment selected.

















