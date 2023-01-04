# Flight Price Prediction

We will be analyzing the flight fare prediction using Machine Learning dataset using essential exploratory data analysis techniques then will draw some predictions about the price of the flight based on some features such as what type of airline it is, what is the arrival time, what is the departure time, what is the duration of the flight, source, destination and more.

### About the dataset
Airline: So this column will have all the types of airlines like Indigo, Jet Airways, Air India, and many more.
Date_of_Journey: This column will let us know about the date on which the passenger’s journey will start.
Source: This column holds the name of the place from where the passenger’s journey will start.
Destination: This column holds the name of the place to where passengers wanted to travel.
Route: Here we can know about that what is the route through which passengers have opted to travel from his/her source to their destination.
Arrival_Time: Arrival time is when the passenger will reach his/her destination.
Duration: Duration is the whole period that a flight will take to complete its journey from source to destination.
Total_Stops: This will let us know in how many places flights will stop there for the flight in the whole journey.
Additional_Info: In this column, we will get information about food, kind of food, and other amenities.
Price: Price of the flight for a complete journey including all the expenses before onboarding.

We have perform EDA, Data Analysis, Data Visualization, Machine Learning


![airline_vs_price](https://user-images.githubusercontent.com/67755812/210572264-d95de817-af4d-4f99-89fe-51f76e721ba4.png)

###### With the help of the cat plot we are trying to plot the boxplot between the price of the flight and airline and we can conclude that Jet Airways has the most outliers in terms of price.

![source_vs_price](https://user-images.githubusercontent.com/67755812/210572403-ff088b08-8af2-4fbb-bddd-59cfd34adc32.png)

###### With the help of cat plot only we are plotting a box plot between the price of the flight and the source place i.e. the place from where passengers will travel to the destination and we can see that Banglore as the source location has the most outliers while Chennai has the least.


![destination_vs_price](https://user-images.githubusercontent.com/67755812/210572590-d106e2fc-e47b-4854-b34e-c1136695727e.png)

###### With the help of a cat plot between the price of the flight and the destination to which the passenger is travelling and figured out that New Delhi has the most outliers and Kolkata has the least.


### In feature Engineering


![feature](https://user-images.githubusercontent.com/67755812/210572936-ad86251c-3d9a-4bdc-8f30-9d52b48b6a4b.png)


###### Total_stops is the feature with the highest feature importance in deciding the Price as we have also seen above. After that Journey Day also plays a big role in deciding the Price. Prices are generally higher on weekends.

### Machine Learning
###### RandomForestRegressor was used as it was giving a best R2score as 80% than DesicionTreeRegressorr
