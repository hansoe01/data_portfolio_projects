## 🏠 Airbnb Listings Data Analysis
**Evaluating the Impact of 2015 Regulations in Paris on Airbnb Market Trends**

### 📌 Project Overview

This project analyzes Airbnb listings in Paris to understand how the 2015 short-term rental regulations impacted market dynamics, including host activity and pricing trends.

The analysis was conducted using Python with a focus on data preparation, visualization, and business insights generation.

### 🎯 Project Objectives

**✅ Objective 1: Explore and profile the data to correnct any quality issues.**
  
**✅ Objective 2: Prepare and reformat the Data for Visualization.**
  
**✅ Objective 3: Visualize the data and identify the key insights and recommendations.**


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
  
**2️⃣ Exploratory Data Analysis (EDA)**
Distribution of listings across neighborhoods
Price comparison by room type
Host activity analysis (single vs multi-listing hosts)

**3️⃣ Data Visualization**
Trend analysis of listings over time
Price distribution using boxplots
Availability distribution using histograms
Host listing patterns

### 📊 Key Findings
📉 2015 regulations led to fewer new Airbnb hosts entering the market
💰 Average listing prices increased after regulation changes
🏙️ Central Paris areas continue to dominate listing availability
👥 A portion of hosts manage multiple listings, indicating commercial usage
📅 High availability listings suggest full-time rental operations

### 💡 Business Insights & Recommendations
⚖️ Regulations appear effective in reducing new host growth
💼 Continued monitoring is needed for multi-property (commercial) hosts
📊 Policymakers should balance tourism benefits vs housing availability
💵 Rising prices suggest reduced supply or increased demand pressure

#### Return to : [Projects Main](https://github.com/hansoe01/data_portfolio_projects)
