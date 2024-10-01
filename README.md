# Car Price Prediction Dashboard

### Problem Statement
In today’s fast-paced automotive market, **accurate car price predictions** are essential for businesses to make smart decisions about inventory, pricing, and marketing strategies. However, predicting car prices is tricky—it involves many factors like brand, model, features, mileage, and even market trends.

### Project Objective
The goal of this project is simple: to build a powerful **car price prediction model** that estimates a car's price based on its attributes. This model helps industry stakeholders to:
- **Optimize Inventory Management**: Stock the right car models in the right quantities by forecasting demand and pricing trends.
- **Enhance Pricing Strategies**: Set competitive prices by understanding what drives price variations.
- **Boost Marketing Efforts**: Target customers with personalized offers based on their preferences and budgets.

### Data Acquisition and Cleaning
The dataset was sourced from **Kaggle** and went through thorough cleaning to ensure high-quality data. Here's how it was processed:
1. **Loading**: Imported the dataset into Power BI with `Csv.Document`.
2. **Promoting Headers**: Set the first row as headers for clearer column names.
3. **Cleaning Unused Columns**: Removed irrelevant columns for a cleaner dataset.
4. **Fixing Car Names**: Standardized and corrected car name typos.
5. **Consistent Capitalization**: Capitalized the first letter in the "Car Name" and "Car Type" columns.
6. **Extracting Brand Names**: Split the "Car Name" column to extract and standardize car brands.
7. **Logical Column Order**: Reordered columns for easier analysis.
8. **Renaming Columns**: Gave columns more descriptive names for clarity.
9. **Standardizing Fuel Types**: Changed "gas" and "diesel" to "Petrol" and "Diesel."
10. **Derived Features**: Created "AVG KMPL" to calculate the average fuel efficiency.
11. **Data Type Conversion**: Ensured all columns had the appropriate data types.

### Data Transformation and Feature Engineering
With clean data, the next steps involved transforming it for modeling:
- **Encoding Categorical Variables**: Converted variables like "Car Type," "Fuel Type," and "Brand" into numeric formats using one-hot encoding.
- **Handling Outliers**: Managed outliers to prevent them from skewing the results.
- **Feature Scaling**: Applied scaling techniques (e.g., normalization) to ensure all features contributed fairly to the model.

### Dashboard Development
I built an **interactive Power BI dashboard** to visualize the dataset and the model's performance. Here’s what it includes:
- **Descriptive Stats**: Summaries like average price, car count, and price distribution.
- **Correlation Analysis**: Visualizations of how different car attributes influence prices.
- **Interactive Filters**: Users can explore the data by filtering attributes like brand, car type, and price range.

![image](https://github.com/user-attachments/assets/ba98eae6-f7bd-4048-a648-ac1a91086068)


### Key Insights
Through the dashboard, some key insights emerged:
- **Brand & Car Type Matter**: Certain brands and car types consistently sell at higher prices, showing strong customer preferences.
- **Engine Size & Fuel Type Impact Price**: Larger engines and premium fuel types lead to higher prices, connecting performance with cost.
- **Mileage & Condition**: Cars with lower mileage and better condition have higher resale values.
- **Model Accuracy**: The prediction model performed well, making it a useful tool for price estimation.

### Conclusion
This car price prediction dashboard is a powerful tool for anyone in the automotive industry, from dealerships to manufacturers. By combining **data analytics** with **machine learning**, it provides valuable insights to help with pricing, inventory, and marketing decisions. As the market evolves, this dashboard can be easily expanded with new data to stay ahead of the curve.
