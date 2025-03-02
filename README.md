Github link:- https://github.com/Rambilas2003/Data-Engineering-


Installation
1. Prerequisites
Ensure you have Python installed (Python 3.7 or later recommended).

2. Install Dependencies
Run the following command to install the required package:

pip install pandas
3. Download the Dataset
Download the Travel Dataset from Kaggle.
Save the dataset file as travel_dataset.csv in the project directory.
Using in a Python Program
To use the ranking function within a Python script, follow these steps:

from travel_recommender import rank_weekend_places

city = "Delhi" 
->It should be your preffered city 
top_places = rank_weekend_places(city)
print(top_places)
This will return the top 5 recommended travel destinations for the specified city.
