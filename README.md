# RainAUS-Prediction

Rain is indispensable event in human life, especially in agriculture, or transportation. It affects greatly on various employment, such as farmers, who want to know exactly when it will rain to have the strategy for their farming activities. Or fishermans to plan for their fishing trips.

Therefore, in this project, we are going to build the predictive model that using the givien information, such as rain fall rate, or the temparature of a date, to forecast when the rain will happen. This job is extremely important since it would cause an adverse effect on people lives.

We will use data Rain in Australia from Kaggle for this project.


This dataset contains about 10 years of daily weather observations from many locations across Australia. It includes information of 145460 days with 22 atmospheric features and one output feature.

All features are described below:
* **Date**: Date data taken.
* **Location**: City in Australia.
* **MinTemp**: Minimum temparature of that collected date.
* **MaxTemp**: Maxium temparature of that collected date.
* **Rainfall**: Amount of rainfall that day in mm.
* **Evaporation**: Amount of evaporation in mm for 24 hours.
* **Sunshine**: The number of hours the day is bright with sunlight.
* **WindGustDir**: Direction of highest wind speed during the 24 hours prior to 12 at night that day.
* **WindGustSpeed**: The highest wind speed in km/h during the 24 hours before 12 at night that day.
* **WindDir9am**: Wind direction at 9 am.
* **WindDir3pm**: Wind direction at 3 pm.

* **WindSpeed9am**: Wind speed at 9am in km/hour calculated from the average wind speed 10 minutes before 9 am.

* **WindSpeed3pm**: Wind speed at 3pm in km/hour calculated from the average wind speed 10 minutes before 3 pm.

* **Humidity9am**: Humidity at 9am in percentage.
* **Humidity3pm**: Humidity at 3pm in percentage.
* **Pressure9am**: Barometric pressure at 9am in hpa.
* **Pressure3pm**: Barometric pressure at 3pm in hpa.

* **Cloud9am**: Percentage of sky covered by clouds at 9am. counted in octas, units ⅛, counting how many units ⅛ of the sky is covered with clouds. If 0, the sky is clear, if 8, the sky is completely covered with clouds.
* **Cloud3pm**: Percentage of sky covered by clouds at 3 pm.

* **Temp9am**: Temparature at 9am in Celcius.
* **Temp3pm**: Temparature at 3pm in Celcius.

* **RainToday**: did it rain today: if the rainfall in the 24 hours before 9am exceeded 1mm, then this value is 1, otherwise it is 0.

* **RainTomorrow**: The output if it Rain or Not.

After process of cleaning dataset and feature engineering, I will apply three common models, which are Logistic Regression, Decision Tree and Random Forest. 

**The result is amazing when it reaches to 100% of accuracy for both model of Logistic Regression and Random Forest**.
