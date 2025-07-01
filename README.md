# 🗽 EDA: New York City Airbnb Listings

Welcome to another entry in my data science portfolio — an **Exploratory Data Analysis (EDA)** of the [NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) dataset from Kaggle.

The goal of this project was to explore trends, pricing behavior, and neighborhood patterns in NYC’s Airbnb listings, and to develop insights into **what drives listing popularity and price** in different boroughs. This was also inspired by my desire to get into the space of Airbnb investing, so learning how to handle data like this will help me greatly later on when I need to conduct market research.

I am going to answer the following questions sorted into difficulty:

### Beginner:

    1.	Which neighborhood group has the most Airbnb listings?
	2.	What is the average price of an Airbnb listing in each borough?
	3.	What is the distribution of room types across NYC?
	4.	Which 5 neighborhoods have the highest average price?
	5.	How many listings are available for at least 300 days a year?

### Intermediate:

    1.	Is there a correlation between number of reviews and price?
	2.	What is the average price of listings based on room type and neighborhood group?
	3.	Which hosts have the most listings, and how much do they charge on average?
	4.	How does availability vary by borough across different room types?
	5.	What are the most reviewed listings in Manhattan and their price ranges?

### Hard:

	1.	Can we identify clusters of high-priced listings using latitude and longitude (e.g., via KMeans)?
	2.	What is the price elasticity across room types and minimum night stays (does price predict duration)?
	3.	Is there a statistically significant price difference between boroughs (e.g., ANOVA)?
	4.	Can we build a model to predict listing price using features like room type, location, and availability?
	5.	How do availability and number of reviews impact price — controlling for neighborhood and room type (multivariate regression)?

    * (I am going to save the harder questions for a later end-to-end where I create my own Airbnb analytics software for personal market research)

---

## 🔍 Key Insights From This Project

• **Manhattan** and **Brooklyn** dominate the Airbnb scene, with the highest number of listings and the highest prices.  
• The most expensive neighborhoods include **Fort Wadsworth**, **Woodrow**, and parts of **Tribeca**.  
• **Entire homes/apartments** are most common and most expensive, but **private rooms** offer more affordability.  
• There is a **listing type effect** on the booking rate of listings, with shared rooms and private rooms having a much higher booking rate compared to entire homes/apts.  
• There is **no correlation** between **price** and **number of reviews** for a listing.  

This project demonstrates my skills in data wrangling (pandas), visualization (seaborn and matplotlib), and analysis, and my ability to tell a compelling story with real-world data.

---

## 📊 Skills Demonstrated

- 🧹 **Data Cleaning** with `pandas`, `numpy`, `data wrangler`
- 📈 **Data Visualization** with `matplotlib`, `seaborn`, and `Tableau Public`
- 📊 **Descriptive Statistics** and trend analysis
- 🗺 **Geospatial Visualization** of neighborhood-level data

---

## 📍 Tableau Dashboard

![Tableau Visual](./analysis%20pics/Screenshot%202025-06-30%20at%208.34.31 PM.png)


## Results from Matplotlib and Seaborn

Here are my results from the easier questions that I sought to answer:

![Beginner Results](./analysis%20pics/nyc_airbnb_beginner_analysis.png)

Here are the intermediate results from the questions above:

![Intermediate Results](./analysis%20pics/nyc_airbnb_intermediate_analysis.png)


---

## 🛠 Tools & Environment

- **Python** (pandas, numpy, matplotlib, seaborn)  
- **Jupyter Notebook**  
- **Tableau Public** for visual storytelling  
- Dataset: [NYC Airbnb Open Data on Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)

---

## 🚀 Next Steps

- Predict Airbnb prices using regression models  
- Cluster listings based on amenities and pricing  
- Add NLP-based review sentiment analysis

---

## 📫 Contact Me

If you have any questions or feedback, feel free to reach out:

- 📧 Email: [andrewjhlava@gmail.com](mailto:andrewjhlava@gmail.com)  
- 🌐 Website: [andrewhlavacek.github.io](https://andrewhlavacek.github.io/)

---

Thank you for checking out my work!