# Vehicle dataset

This dataset contains information about used cars.
This data can be used for a lot of purposes such as price prediction to exemplify the use of linear regression in Machine Learning. It contains information about 98 car brands. In this post, we will perform exploratory data analysis on the Cars Dataset. The data can be found here.
The columns in the given dataset are as follows:


## Data

Data contains 8 columns.


**Name**: This column represents contains names of cars.

**Year**: This column represents years of cars

**Selling_price**: This column represents Car's selling price

**Km_driven**: It refers to how much distance (in kilometres) the car had travelled.

**Fuel_Type**: A motor fuel (Diesel,Petrol,CNG) is a fuel that is used to provide power to the motor in motor vehicles. 

**Seller_type**: Defines whether the seller is a dealer or an individual.

**Transmission** This column represents whether the car is manual or automatic.

**Owner**: This column represents the person who bought the car or the person who has been gifted the vehicle.


Data Correlation is a way to understand the relationship between multiple features dataset. Using Correlation, we see that there is no highly correlation:

![correlation](https://user-images.githubusercontent.com/62169942/163659257-1253b55e-030d-4033-9661-932ed16ec6c3.png)

l have used several regression algorithms to compare models. 

![accuracy](https://user-images.githubusercontent.com/62169942/163667289-3a881cff-43fa-4c32-bea8-115940eaacef.png)

At the end Gradient Boosting, Random Forest and XGBoost selected best models in our modelling. Then check by hyperparametrs view mean absolute error, mean squared error, root mean squared error and r2 score.
