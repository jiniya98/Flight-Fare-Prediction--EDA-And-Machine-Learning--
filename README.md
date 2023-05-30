# Flight-Fare-Prediction--EDA-And-Machine-Learning--
This is a repository of Final project
### Acknowledgements:
 - The data was for educational purposes only. Note that I don’t claim any copyright for the data.
 - Source: Kaggle

### Abstract:

* Flight fare refers to the price that passengers pay for air travel. The price of airline ticket changes frequently nowadays and there is plenty of difference. Price change keeps happening within few hours for the identical flight.
*  The aim of this analysis is to develop a model that can accurately predict flight fares based on various factors, enabling travelers to make informed decisions when booking flights.

### Content:
* The main idea for flight fare prediction is to gather relevant data about flights and analyze the factors that impact the fares, such as the departure and arrival locations, flight durations,pricing trends and so on. By examining these variables, we can develop a model that can estimate flight fares accurately.

* It's important to note that obtaining a reliable and comprehensive dataset for flight fare prediction is crucial for accurate predictions. Additionally, various machine learning techniques, such as regression models or ensemble methods, can be employed to build a robust flight fare prediction system.

### Problem Statement:
* The basic idea of analyzing flight fare data is to gain insights into the factors influencing the pricing of flights for different routes and airlines. With the continuous growth of the aviation industry and increasing demand for air travel, it has become essential to understand the dynamics of flight fares and provide accurate predictions for travelers.

* In today's fast-paced world, air travel has become a vital mode of transportation. However, with the multitude of airlines, routes, and travel options available, it has become challenging for passengers to determine the most cost-effective flights for their desired destinations. The aim of this analysis is to develop a model that can accurately predict flight fares based on various factors, enabling travelers to make informed decisions when booking flights.

### Study of Existing Systems:
* EDA on Flight Data

  Author:RAHUL KRISHNAN M -In this project, he did the analysis part in different stages.

* Flight Fare Prediction | EDA | Linear Regression

  Author:TUNAHAN ULUSOY -In this project, he did the analysis part and applied machine learning algorithm to predict the price of a airlines.
 
 ### Identification of gaps in existing systems:
 * EDA on Flight Data: Author-RAHUL KRISHNAN M--->Analysis Part should be more in detail.
 * Flight Price Prediction | EDA | Linear Regression: Author-TUNAHAN ULUSOY--->In this project, he applied only one machine learning algorithms to predict the price of a airlines.
 
 ### Proposed Solution:
 * We can apply additional three more Machine learning algorithms Random Forest Regressor, Decision tree Regressor and Extra Tree Regressor and compare the best model by using the accuracy of each model.
 
 ### Main Objective:
 The main agenda of this project is:

* Perform extensive Exploratory Data Analysis(EDA) on the Flight Dataset.

* Build an appropriate Machine Learning Model that will help to predict price based on certain features

### Tools used to implement proposed solution:
 * Python 
 * Pandas
 * Numpy 
 * Matplotlib 
 * Seaborn  
 * Sklearn 
 * Jupyter Notebook
 
 ### Features:
* AIRLINE
* FLIGHT
* SOURCE_CITY
* DEPARTURE_TIME
* STOPS
* DESTINATION_CITY
* CLASS 
* DURATION
* DAYS_LEFT
* PRICE

### Conclusion:
*	Based on the provided accuracy scores, the Random Forest model emerges as the superior choice for predicting flight fares compared to other models. The Random Forest model achieved an impressive training score of 99.76, indicating its ability to accurately predict flight fares when trained on the available data. Furthermore, when tested on new, unseen data, the model obtained a score of 98.56%, highlighting its capability to generalize well and make reliable predictions. The high R2 score of 98.56 further confirms the strong correlation between the predicted and actual flight fares.
*	Our machine learning algorithm will able to predict the restaurant rating.
*	There are 6 unique airlines. Vistara becoming the most popular airline and Spicejet is the least popular
*	Economy Class is the most common class among the airlines
*	flights with a single stop seem to be the preferred choice for travellers.
*	 It can be observed that the Delhi-Mumbai route has the highest frequency of flights compared to other routes. 
*	Vistara has Maximum Price range
*	Flights having one stop has maximum ticket price
*	 There is a significant increase in ticket prices when purchased only 1-2 days before the scheduled departure

### Notes:
For the Detailed Information about the Project, Kindly refer the "Flight-Fare-Prediction--EDA-And-Machine-Learning.pdf" file attached with this Repo.
