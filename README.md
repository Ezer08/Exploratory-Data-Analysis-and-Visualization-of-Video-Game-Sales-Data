🎮 Video Game Sales Analysis
📝 Project Overview
This project analyzes video game sales data to uncover trends and insights, including the top platforms, genres, and publishers that dominate the market. The analysis provides a comprehensive view of sales distribution across different regions and identifies the key drivers of global success.

📊 Dataset
The dataset includes information about video game sales, categorized by:

Rank
Name
Platform
Year
Genre
Publisher
Sales: North America (NA), Europe (EU), Japan (JP), Other regions, and Global sales.

🚀 Steps in Analysis
1. Data Preprocessing
Checked dataset information using df.info(), df.shape, and df.dtypes.
Checked and handled missing values:
Used df.isnull().sum() to identify missing values.
Dropped rows with missing values using df.dropna(inplace=True).

2. Exploratory Data Analysis (EDA)
I performed comprehensive visualizations and analyses to explore key insights, such as:

🔍 Key Visualizations
Distribution of Games by Platform: Number of games released per platform.
Distribution of Games by Year (5-Year Intervals): Visualized the release trend over time.
Distribution of Games by Genre: Compared the popularity of different genres.
Top Publishers Analysis: Identified the top 9 publishers contributing to global sales.
Regional Sales Distribution: Examined sales in North America, Europe, Japan, and other regions.
Top-Selling Games:
Top 10 globally.
Regional breakdown: NA, EU, JP, and others.
Platform Ranking: Platforms with the highest global sales.
Sales Contribution by Region: Assessed the role of each region in global sales.
Genre Performance: Identified the most successful genres globally and regionally.
Global Sales Trends by Year: Trends of sales over time, highlighting peaks and declines.


🔑 Key Insights
Some of the main insights obtained:

Top Platforms: Platforms like DS and PES 2 dominated global sales.
Most Successful Genre: Action and Sports  were the most successful genres.
Sales Trends: Sales peaked around the mid-2000s, driven by popular platforms like Wii and games like Wii Sports.
Regional Impact:
North America contributed the largest portion to global sales.
Top Publishers: Nintendo emerged as the dominant publisher both globally and regionally.

🛠️ Technologies and Libraries Used
The following Python libraries were used for analysis and visualizations:

pandas: Data manipulation and cleaning
matplotlib: Basic data visualization
seaborn: Advanced and styled visualizations
plotly & plotly.express: Interactive charts and plots

Platform

🛠️ Future Improvements
Add interactive visualizations using Streamlit or Dash.
Incorporate machine learning models to predict future game sales trends.
Analyze other datasets to compare trends across entertainment industries.
🙌 Contributors
Ezer Meftahi

