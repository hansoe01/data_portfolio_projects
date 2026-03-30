## 🏠 Airbnb Listings Data Analysis
**Evaluating the Impact of 2015 Regulations in Paris on Airbnb Market Trends**

### 📌 Project Overview and Objective

This project analyzes Airbnb listings in Paris to understand how the 2015 rental regulations impacted market dynamics, including host activity and pricing trends.

The analysis was conducted using Python with a focus on data preparation, visualization, and business insights generation.

### 🎯 Implementation Steps

**✅ Step 1: Explore and profile the data to correnct any quality issues.**
  
**✅ Step 2: Prepare and reformat the Data for Visualization.**
  
**✅ Step 3: Visualize the data and identify the key insights and recommendations.**


### 🛠️ Tools & Technologies
- Python
- Pandas – Data cleaning and transformation
- Seaborn – Statistical visualization
- Matplotlib – Charting and plotting
  
### 🔍 Data Analysis Workflow

**1️⃣ Data Cleaning & Preparation**

- Import/open the listings.csv file
- Cast any data column as datatime format
- Filter the data down to rows where the city is Paris and keep only the columns 'host_since' , 'neighbourhood', 'city', 'accommodataes' and 'price' in table
- QA the Paris listings data: chekc for the missing values, and calculate the minimun, maximun and average for each numeric field

<img width="1433" height="735" alt="Screenshot 2026-03-30 at 07 48 40" src="https://github.com/user-attachments/assets/05a1e6f0-9341-443f-8f2b-bacbcac20689" />

  

**2️⃣ Exploratory Data Analysis (EDA)**

- Create a table named paris_listings_neighbout that groups Paris listings by ' neighbouthood' and calculated the mean price for each neighbouthood sorted from lowest to highest average price
- Then, create a table named paris_listings_accommodations. This table is filterted down to the most expensive neighbourhood in Paris, grouped by the 'accommodations" column, and contain the mean price for each value of 'accommodates' sorted from loswest to highest average price
- Finally, create a table called paris_listings_over_time, which is grouped by the year of the 'host-since' column. Calculate a count of rows, representing total number of new hosts, and the averate price of each year

<img width="1433" height="735" alt="Screenshot 2026-03-30 at 07 49 41" src="https://github.com/user-attachments/assets/2bc0fe51-f94c-47c4-b998-0ee541d72cdd" />



**3️⃣ Data Visualization**

- Create a horizontal bar chart of the average price by neighbouthood in Paris and add a title and axis labels
<img width="1433" height="735" alt="Screenshot 2026-03-30 at 07 50 49" src="https://github.com/user-attachments/assets/eed0e68a-2335-43b8-8f80-0961306f511e" />


- Create a horizontl bar chart of the average price by 'accommodates' in Paris most expensive neighbourhood and add a title and axis labels

<img width="1433" height="735" alt="Screenshot 2026-03-30 at 07 51 09" src="https://github.com/user-attachments/assets/c7abbfa0-de6b-4f21-ba36-dc84c185bd8a" />

  
- Create two line charts: one of the count of new hosts over time, and one for average price.

<img width="1433" height="735" alt="Screenshot 2026-03-30 at 07 51 38" src="https://github.com/user-attachments/assets/1c56bbd9-61d6-4d5e-ae7a-3a8a6254ca04" />

  
### 📊 Key Findings

📉 2015 regulations led to fewer new Airbnb hosts entering the market<br>
💰 Average listing prices increased after regulation changes<br>
🏙️ Central Paris areas continue to dominate listing availability


### 💡 Business Insights & Recommendations

⚖️ Regulations appear effective in reducing new host growth <br>
📊 Policymakers should balance tourism benefits vs housing availability <br>
💵 Rising prices suggest reduced supply or increased demand pressure

#### Return to : [Projects Main](https://github.com/hansoe01/data_portfolio_projects)
