# luxury_housing_sales_analysis
Building a complete real estate analytics solution using Python for advanced data cleaning, load the refined dataset into a SQL database, and use Power BI to directly connect to SQL and build a dashboard.

Step 1: Python — Data Cleaning & Feature Engineering
●	Load the raw .csv file
●	Clean inconsistent formats (e.g., Ticket_Price_Cr)
●	Handle nulls in Amenity_Score, Booking_Status, etc.
●	Normalize text fields (Builder, Micro_Market)
●	Derive columns like Price_per_Sqft, Quarter_Number, Booking_Flag
●	Output: Cleaned CSV or DataFrame ready for DB insertion

Step 2: SQL — Load Clean Data into RDBMS
●	Create appropriate SQL table schema
●	Use Python (via SQLAlchemy or pymysql) to insert data into MySQL/PostgreSQL
●	Run initial SQL validation queries:
  ○	SELECT COUNT(*)
  ○	GROUP BY booking status
  ○	AVG ticket price per builder

Step 3: Power BI — Visualize via Direct SQL Connection
●	Connect Power BI to SQL DB
●	Build relationships, DAX calculations
●	Create interactive dashboards:
  ○	Filter by Builder, Quarter, Market
  ○	Map visuals, booking conversion KPIs
  ○	Text box insights from Buyer Comments

  Results: 
●	Clean, loaded SQL table with normalized data
●	Interactive Power BI dashboard connected to SQL live
●	Analytical insights useful to real estate firms
●	Hands-on with 3 critical tools in the data analytics workflow




