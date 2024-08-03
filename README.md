#Zomato Data Analysis

Project Overview
This project involves an in-depth analysis of restaurant data from Zomato to gain insights into restaurant ratings, voting patterns, locations, and cuisines. The analysis includes data cleaning, feature extraction, and various visualizations to identify trends and patterns in the dataset.

Dataset
The dataset used in this project is sourced from Zomato and contains information about restaurants, including:
- Name
- Online Order Availability
- Table Booking
- Rating
- Votes
- Location
- Restaurant Type
- Cuisines
- Approximate Cost for Two People

Analysis Steps
Data Cleaning
- Removed irrelevant columns such as URL, address, phone number, and menu items.
- Handled missing values in the 'rate' column by dropping entries with missing ratings and converting the rating values to numeric.

Exploratory Data Analysis
- Analyzed the distribution of restaurant ratings.
- Identified restaurants with the highest number of ratings.
- Visualized the distribution of votes and ratings.
- Examined the top cuisines and locations with the highest number of restaurants.

Visualizations
- Top 15 Restaurants by Rating: Bar chart displaying the top-rated restaurants.
- Pie Charts: Representation of online order acceptance and table booking.
- Restaurant Types: Bar chart showing the most common restaurant types.
- Highly Rated vs. Poorly Rated Restaurants: Analysis based on the number of ratings and average rating.
- Location Analysis: Bar chart of the number of restaurants in different locations.
- Top Cuisines: Bar chart showing the most popular cuisines.

Statistical Analysis
- Performed normality tests on the distribution of ratings to determine if the data follows a normal distribution.

Requirements
- Python Libraries: pandas, matplotlib, seaborn, numpy, scipy

Usage
1.   Clone the repository:
     ```bash
     git clone https://github.com/your-username/zomato-restaurant-analysis.git
2.   Navigate to the project directory:
     ```bash
     cd Zomato_Data_Analysis
3.  Install required libraries:
    ```bash
    pip install pandas matplotlib seaborn numpy scipy
4.  Place the zomato.csv dataset file in the project directory.
5.  Run the analysis script:
    ```bash
    python Zomato_Data_Analysis.py

Results
- Top Rated Restaurants: Identified top 15 restaurants based on their ratings.
- Voting Analysis: Restaurants with high voting counts and their average ratings.
- Cuisine Popularity: Top 10 cuisines based on the dataset.
- Location Insights: Locations with the highest number of restaurants.



