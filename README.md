# NYC-Airbnb-Price-Prediction
# Background:
Since 2008, guests and hosts have used Airbnb to expand the possibilities of travel and present a more unique and personalized way of experiencing the world. By analyzing various columns in the Airbnb dataset, we can explore the relationship between data and train models to predict prices.

# Analysis Object:
The dataset used in this analysis is the 2019 Airbnb housing information data. The dataset contains approximately 49,000 observations, 16 columns, and is a mixture of categorical and numerical values. It includes id, name, host_id, host_name, neighbourhood_group, neighbourhood, latitude, longitude, room_type, price, minimum_nights, number_of_reviews, last_review, reviews_per_month, calculated_host_listings_count, availability_365. The following figure shows information about the dataset:

![image](https://user-images.githubusercontent.com/60024169/236051578-172ba836-3009-445e-b7da-981f21344284.png)

# EDA:
Through EDA, the map of New York City Airbnb housing can be drawn by longitude and latitude and location. The map of the location of different types of houses can be drawn by longitude and latitude and house type. The number of different types of houses in each area, the relationship between house prices and changes in longitude and latitude, etc., can also be obtained.

![image](https://user-images.githubusercontent.com/60024169/236051643-a945c373-7515-4541-b3dd-e94866ef8a45.png)

![image](https://user-images.githubusercontent.com/60024169/236051659-57f80bf9-cdda-473c-a6bf-bd1fe39adc6e.png)

# Prediction:
I mainly want to use the indicators of neighbourhood_group, room_type, minimum_nights, number_of_reviews, reviews_per_month, calculated_host_listings_count, availability_365 to predict the price of the house. Before prediction, delete unnecessary columns and encode object data types for neighbourhood_group and room_type.
Method 1: Use linear regression for price prediction.
Method 2: Use decision trees and random forests for prediction.
Method 3: Use support vector machines for prediction.
