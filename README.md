This project involves exploratory data analysis (EDA) and feature engineering on a real-world flight price dataset. The goal is to analyze various factors affecting airline ticket prices and prepare the data for accurate price prediction.

 Dataset:
It contains details like airline name, flight code, departure/arrival time, stops, seat class, days left for the journey, and final ticket price.

 Features:
Airline – Name of the airline (6 unique airlines)
Flight – Flight code (categorical)
Source & Destination City – Origin and landing cities (6 unique cities each)
Departure & Arrival Time – Grouped time slots (morning, evening, etc.)
Stops – Number of stops (0, 1, 2+)
Class – Economy or Business
Duration – Total travel time
Days Left – Days between booking date and journey date
Price – Target variable (ticket cost)

Technologies Used:
Python
Pandas, NumPy
Matplotlib, Seaborn for visualizations
Jupyter Notebook

 What I Did:
* Cleaned and understood the structure of the dataset
* Performed detailed EDA to visualize relationships between features and price
* Engineered new features like Days Left, Time of Day from timestamp values
* Prepared the dataset for machine learning by converting categorical variables and handling nulls

 Future Scope
* Train ML models like Linear Regression, Random Forest, 
* Build a web dashboard to input flight details and predict price
