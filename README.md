# Airline-Pricing-Analysis
Airline Pricing Analysis using Python and Excel
📌 Project Overview
Airline ticket prices fluctuate based on multiple factors such as airline type, number of stops, travel duration, and seasonality.
This project performs an end-to-end analysis of airline pricing data using Python and Microsoft Excel to identify pricing patterns, key cost drivers, and actionable business insights.
The objective of this project is to demonstrate core Data Analyst skills including data cleaning, exploratory data analysis (EDA), visualization, and business insight generation using industry-relevant tools.
📂 Project Structure
Airline-Pricing-Analysis/
│
├── data/
│   └── flight_price.csv
│
├── python_analysis/
│   └── airline_pricing_analysis.ipynb
│
├── excel_analysis/
│   └── airline_pricing_analysis.xlsx
│
├── visuals/
│   └── charts.png
│
├── README.md
└── requirements.txt
📊 Dataset Description
The dataset contains real-world airline ticket booking information with the following attributes:
•	Airline – Name of the airline
•	Source – Departure city
•	Destination – Arrival city
•	Date of Journey – Travel date
•	Departure Time – Flight departure time
•	Arrival Time – Flight arrival time
•	Duration – Total travel duration
•	Total Stops – Number of stops
•	Price – Ticket price (target variable)
This dataset closely reflects real airline pricing systems, making it suitable for analytical and business use cases.
🛠️ Tools & Technologies
🔹 Programming & Analysis
•	Python (Pandas, NumPy)
•	Jupyter Notebook
🔹 Visualization
•	Matplotlib
•	Seaborn
•	Microsoft Excel (Pivot Tables, Charts)
🧹 Data Cleaning & Feature Engineering (Python)
The following preprocessing steps were performed using Python:
•	Converted journey date into datetime format
•	Extracted journey day and journey month
•	Converted flight duration (e.g., 2h 50m) into total minutes
•	Converted total stops from categorical to numeric values
•	Removed duplicate records and handled missing values
•	Dropped irrelevant columns for clarity and efficiency
These steps ensured that the dataset was clean, consistent, and analysis-ready.
📈 Exploratory Data Analysis (Python)
The Python-based EDA focused on answering key business questions:
•	Which airlines have the highest average ticket prices?
•	How does the number of stops impact ticket price?
•	Do flight prices vary by month (seasonality)?
•	What is the relationship between flight duration and ticket cost?
Professional visualizations were used to clearly communicate trends and patterns.





📊 Excel Extension (Business-Focused Analysis)
To complement Python analysis, an Excel-based analytical layer was added to demonstrate spreadsheet and reporting skills commonly required in Data Analyst roles.
🔹 Excel Tasks Performed
•	Imported cleaned airline data into Excel
•	Created Pivot Tables for:
o	Airline-wise average ticket price
o	Route-wise price comparison
o	Total stops vs average price
o	Monthly pricing trends
•	Built interactive charts:
o	Bar chart: Airline vs Average Price
o	Line chart: Monthly Price Trend
o	Column chart: Stops vs Price
•	Applied filters and slicers for:
o	Airline
o	Source & Destination
o	Month
🔹 Excel Insights
•	Premium airlines show consistently higher average fares
•	Non-stop flights command higher prices than connecting flights
•	Prices peak during summer and holiday travel months
•	Flights with more stops are cheaper but have longer duration
📌 Why Excel matters:
Excel dashboards are widely used by business stakeholders, and this extension shows the ability to translate Python insights into business-friendly reports.
🧠 Key Business Insights
•	Premium airlines follow higher pricing strategies
•	Non-stop flights are significantly more expensive
•	Strong seasonality exists in airline pricing
•	Longer-duration flights tend to be cheaper
•	Total stops and journey month are the strongest price drivers


📌 Conclusion
This project demonstrates the complete data analytics lifecycle, from raw data cleaning to business insight generation using Python and Excel. It highlights strong analytical thinking, technical skills, and the ability to communicate insights effectively—making it ideal for fresher and entry-level Data Analyst roles.
