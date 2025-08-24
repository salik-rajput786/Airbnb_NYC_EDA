Airbnb NYC Exploratory Data Analysis (EDA)

Data cleaning, analysis, and visualization of 49K+ Airbnb listings in New York City. 

📌 Introduction

This project explores the Airbnb New York City dataset (2019) with ~49,000 listings across the five boroughs. The goal is to clean the data, handle missing values, remove outliers, and perform exploratory data analysis (EDA) to uncover patterns in pricing, room types, and neighborhood demand.

📊 Dataset

Source: Airbnb NYC 2019 dataset

Size: 48,895 listings

Features include:

Listing details (id, name, host info)

Location (borough, neighborhood, latitude, longitude)

Room type, price, minimum nights

Reviews, availability, and more


🔍 Analysis & Cleaning Steps

Data Cleaning

Handled missing values (e.g., reviews, host name).

Removed unrealistic prices (>$1000) and capped minimum_nights at 30.


Univariate & Bivariate Analysis

Price distribution across listings.

Room type composition by borough.

Neighborhood-level demand trends.


Visualizations

Price histograms & boxplots.

Borough-wise room type comparisons.

Scatter plots for location vs. price.


📈 Key Insights

Most listings are priced under $200 per night; luxury listings above $1000 are rare.

Manhattan dominates as the premium Airbnb market, with the highest prices and demand.

Brooklyn offers affordability with strong demand, making it a traveler-friendly option.

Private rooms are popular in Brooklyn/Queens, while entire apartments dominate Manhattan.

Reviews are concentrated in budget-friendly private rooms, showing high engagement.


🛠 Tech Stack

Python (pandas, numpy)

Matplotlib & Seaborn (visualizations)

Jupyter Notebook


