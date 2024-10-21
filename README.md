
<h1 align="center">Bangalore Real Estate Analysis</h1>

<h3 align="center">📊 A Data Science Approach to Analyze Property Trends in Bangalore</h3>

---

## 🏠 Project Overview
This project focuses on analyzing real estate properties in Bangalore using Python. The goal is to provide insights into property prices, areas, and other relevant metrics to assist potential buyers and real estate investors in making informed decisions. The project utilizes data cleaning, preprocessing, and visualization techniques to handle real estate data efficiently.

---

## 🗂 Data Source
The dataset used is sourced from **Real Estate Data V21.csv**, which includes various property details such as:
- Property Title
- Price
- Location
- Total Area
- Price per Square Foot
- Baths
- Balcony availability
- Area

---

## 🎯 Objective
The project aims to:
- Clean and preprocess real estate data specific to Bangalore.
- Provide visual insights into property price distribution across different areas.
- Analyze key factors like BHK, price, and balcony availability to identify trends in the Bangalore real estate market.

---

## 🛠 Data Cleaning & Preprocessing
1. **Handling Missing Values**: Missing values were handled by either filling them with appropriate substitutes or removing rows with incomplete data.
2. **Price Conversion**: Prices listed in different formats (Lakh, Crore) were converted into numeric form for uniformity in price calculations and comparisons.
3. **BHK Creation**: A new column 'BHK' was created by extracting the number of bedrooms from property titles or other attributes.

---

## 📈 Exploratory Data Analysis
Several analyses were performed to derive insights:
1. **Price Distribution**: Visualization of price distribution across various property types, BHK configurations, and areas.
2. **Price vs. BHK Analysis**: Scatter plots were generated to show the relationship between the number of bedrooms (BHK) and the property price (in millions).
3. **Balcony and Non-Balcony Properties**: Separate analyses were performed for properties with and without balconies, comparing their price trends.

---

## 🔍 Results and Insights
- **BHK vs. Price Trends**: Properties with more BHK tend to have higher prices, though there are outliers in premium areas.
- **Balcony Availability**: Properties with balconies generally have higher prices, showing a willingness to pay more for outdoor space.
- **Price Hotspots**: Some areas in Bangalore show significantly higher prices, indicating prime real estate locations.

---

## 🛠 Tools and Libraries Used
- **Pandas** for data manipulation and cleaning
- **Matplotlib** for visualizing trends and relationships
- **NumPy** for numerical operations
- **Regular Expressions (re)** for cleaning and standardizing data

---

## 📊 Conclusion
This project provides a comprehensive analysis of the Bangalore real estate market, highlighting key factors like BHK, price, and area. The results can guide potential property buyers and investors in identifying prime locations and properties that offer the best value for money.

---

## 🚀 Future Enhancements
- Incorporating more granular data, such as property age, builder reputation, and proximity to amenities.
- Building a predictive model to forecast property prices based on historical data for better decision-making.

---

<h3 align="center"> by Monalisa Arya </h3>




