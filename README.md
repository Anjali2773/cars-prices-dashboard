🔍 Project Overview
This Power BI dashboard analyzes a comprehensive dataset of car prices to derive meaningful business insights for automobile resellers, dealers, and analysts. It visually represents key metrics including car distribution by seller, year, transmission type, fuel, and price trends over time.

🗃️ Data Source
Dataset Name: car_prices dataset.xlsx

Primary Columns Used:

sellingprice

seller

year

transmission

model, mmr, odometer, state, trim, vin, saleyear, oldest year, etc.

📊 Key Visuals and What They Show
KPI Cards (Top Panel)

Total Cars: Total number of car entries in the dataset.

Average Selling Price: Mean selling price across listings.

Total Revenue: Sum of all selling prices (formatted in billions).

Average Year: Mean of all car manufacture years.

Pie Chart – Total Cars by Seller

Displays distribution of cars across different seller organizations.

Field used: seller

Column Chart – Total Cars by Year

Shows the number of car listings per manufacturing year.

Fields: Axis = year, Values = Count of cars

Line Chart – Price Trend by Year

Visualizes how car prices have evolved over time.

Axis: year, Value: Average sellingprice

Bar Chart – Total Cars by Transmission

Compares the count of manual vs automatic cars.

Field: transmission

Bar Chart – Average Selling Price by Transmission

Compares average selling prices between transmission types.

Axis: transmission, Values: Avg sellingprice

Pie Chart – Seller Type Revenue Share

Represents the revenue contribution of each seller based on selling price.

Fields: seller, sellingprice

🧩 Slicers Used (Interactive Filters)
Transmission Type – Filter by manual or automatic.

Year – Slider to filter by manufacturing year.

Selling Price – Slider to set a price range.

Additional filters visible in the filter pane can be customized as needed.

📌 Key Insights
Identify top sellers by volume and revenue.

Observe market trends based on manufacturing year.

Understand how transmission types affect car prices.

Monitor price depreciation and value retention over time.
