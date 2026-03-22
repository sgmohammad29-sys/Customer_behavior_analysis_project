1. 📊 Customer Shopping Behavior Analysis
🔍 Overview

This project demonstrates an end-to-end data analytics workflow, transforming raw customer shopping data into actionable business insights. It covers data loading, cleaning, exploratory analysis, SQL-based querying, and interactive dashboard creation.

The goal is to understand customer behavior, purchasing patterns, and key revenue drivers to support data-driven decision-making.

2. 📁 Dataset
   
The dataset contains customer-level shopping data, including:
Demographics (Age, Gender)
Purchase details (Category, Amount)
Ratings and subscription status
Shipping preferences
Data was preprocessed and structured for analysis across Python, SQL, and Power BI.

3. 🛠️ Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn) → Data cleaning & EDA
SQL (PostgreSQL / MySQL / SQL Server) → Data querying & analysis
Power BI → Dashboard & visualization
Gamma → Presentation (PPT generation)

4. ⚙️ Project Workflow
1. Data Loading & Cleaning (Python)
Imported dataset using Pandas
Handled missing values and duplicates
Standardized column names and formats
Created new features (e.g., age groups using binning)
2. Exploratory Data Analysis (EDA)
Analyzed customer distribution by demographics
Identified top-performing product categories
Evaluated purchase trends and ratings
Visualized patterns using charts and plots
3. SQL Analysis
Loaded cleaned data into SQL database
Performed:
Aggregations (SUM, AVG, COUNT)
Grouping by categories, age groups, and gender
Revenue and customer segmentation analysis
4. Power BI Dashboard
Built an interactive dashboard to present insights
Added filters for:
Category
Gender
Subscription status
Shipping type

5. 📊 Dashboard Highlights
   
Total Customers: 3.8K+
Average Purchase Amount: $59.70
Average Rating: 3.75
Key Visuals:
Revenue by category
Sales distribution across categories
Customer segmentation by age group
Subscription vs non-subscription behavior
Purchase trends by demographics

6. 📈 Results & Insights
Senior customers contribute the highest sales
Clothing & Accessories generate the most revenue
Majority of customers are non-subscribers
Purchase behavior varies significantly across age groups
Shipping preferences influence purchasing decisions

🚀 How to Run the Project

1. Python (Data Processing)
# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run notebook/script
python data_cleaning_eda.py

2. SQL (Database Setup)
Import cleaned dataset into:
PostgreSQL / MySQL / SQL Server
Run SQL queries provided in /sql_queries folder

4. Power BI
Open .pbix file
Load dataset or connect to SQL database
Refresh data to view dashboard

6. Presentation
Open Gamma PPT file for final insights and storytelling

📌 Conclusion

This project showcases the ability to:

Work with real-world datasets
Perform end-to-end data analysis
Use multiple tools (Python, SQL, BI tools)
Deliver business insights through dashboards and reports
