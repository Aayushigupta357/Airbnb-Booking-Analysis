# 🏡 Airbnb Booking Analysis

# 📘 Project Overview
This project is a comprehensive exploratory data analysis (EDA) of Airbnb listings, designed to uncover insights into pricing, availability, neighborhood trends, and host activity. By using real-world Airbnb data, we aim to understand booking behaviors and provide actionable recommendations to hosts, travelers, and platform operators.

# 🎯 Objective
Explore and visualize Airbnb listings across a major city (e.g., NYC).
Understand the distribution of prices, room types, and availability.
Analyze spatial and temporal booking trends.
Derive business insights to optimize listing performance.
Recommend strategies based on data-driven analysis.

# 🛠️ Tools & Libraries Used
Python 3.x
Pandas for data manipulation
Matplotlib & Seaborn for visualizations
Plotly Express for interactive maps
NumPy for numerical operations
Google Colab for analysis execution

# 📂 Dataset
The dataset used in this project was obtained from a public Airbnb dataset that includes listings in New York City, with features such as:

Listing ID, host ID
Neighbourhood group and neighbourhood
Latitude & longitude
Room type
Price
Minimum nights
Number of reviews
Availability and review scores

# 📊 Analysis Report

1. Data Cleaning
Filled missing values in reviews_per_month with 0.
Removed unnecessary columns like name and host_name for analysis.
Dropped rows with any remaining missing values.
Removed duplicate records to ensure consistency.

3. Room Type Analysis
Entire home/apt is the most commonly booked room type, followed by private rooms.
Shared rooms are least used, indicating guest preference for privacy.
Recommendation: Hosts should consider offering entire apartments for better booking chances.

3. Price Distribution
The majority of listings are priced under $200.
A small fraction of luxury listings skew the average upward.
Outliers (extremely high prices) exist and were trimmed for visual clarity.
Recommendation: Hosts should aim to competitively price within the $100–$150 range unless they offer premium amenities.

4. Availability Analysis
Listings are available anywhere from 0 to 365 days per year.
Highly available listings tend to have more reviews, implying greater popularity and trust.
Recommendation: Consistently available listings can boost trust and increase booking frequency.

5. Neighborhood Insights
Manhattan and Brooklyn dominate in terms of number of listings and higher prices.
Queens and Bronx offer more budget-friendly listings with moderate availability.
Neighborhoods close to tourist attractions generally have higher pricing.
Recommendation:
Hosts in non-central areas can stand out by improving listing quality.
Airbnb should promote underused neighborhoods for a more even demand spread.

6. Geospatial Distribution
Mapped listings show clusters in central Manhattan, Williamsburg, and other tourist-heavy zones.
Listings in less popular areas (far from city centers) offer potential for growth.
Tool: Interactive map using Plotly to visualize listing concentration and price heat zones.

7. Correlation Insights
Price is moderately correlated with availability and number of reviews.
Number of reviews is positively correlated with listings that are available year-round.
Note: Categorical columns like room type and neighbourhood were excluded from correlation but could be used in future ML models via encoding.

# 📌 Key Takeaways
Insight	Implication
Majority listings are Entire apartments	Guest preference for privacy
Price < $200 is most common	Budget-focused market
Manhattan has highest prices	Popular, high-demand zone
High availability → More reviews	Availability boosts visibility and bookings

# 📦 Recommendations
For Hosts
Keep calendars open year-round to improve visibility.
Set prices competitively below the $150 mark.
Consider investing in entire apartments rather than private/shared rooms.

For Travelers
Book early to avoid seasonal spikes.
Explore cheaper neighborhoods like Queens and Bronx.

For Airbnb (Platform)
Feature underrated neighborhoods to balance demand.
Offer smart pricing suggestions based on seasonal data.

# 📈 Future Scope
Predict listing prices using machine learning (Linear Regression, XGBoost).
Forecast occupancy rates based on seasonality and location.
Add NLP analysis for listing descriptions and review sentiment.

# 📁 Folder Structure
Airbnb-Booking-Analysis/
│
├── Airbnb.csv                   # Raw dataset
├── cleaned_airbnb_data.csv      # Cleaned version
├── Airbnb_Jupyter_notebook.ipynb
├── README.md                    # Project summary and analysis

# 🤝 Contributing
Feel free to fork this project and contribute. For suggestions or improvements, please open an issue or submit a pull request.

**📬 Contact**
Author: Aayushi Gupta

LinkedIn: [https://www.linkedin.com/in/aayushi-gupta-8757371a9/]

GitHub: [https://github.com/Aayushigupta357]

