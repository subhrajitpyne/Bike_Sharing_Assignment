# Bike-sharing-assignment

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

# General Information

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

### The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Technologies Used

- numpy 2.0.0
- pandas 2.2.2
- matplotlib 3.9.0
- seaborn 0.13.2
- statsmodels 0.14.2
- sklearn 1.5.0
- scipy 1.14.0

## Conclusion

Significant variables to predict the demand for shared bikes

- ### Top features for the model
  - temp coef:0.57
  - humidity coef:-0.1682
  - windspeed coef:-0.194
  - year coef:0.23
  - light snow coef:-0.2411
  - winter coef:0.13

## Final Model Equalation

- ** count (cnt) = 0.1936+temp _ 0.5668 + humidity _ -0.1682 + windspeed _ -0.1936 + year_2019 _ 0.2299 + month*Jan * -0.0406 + month*Jul * -0.0423 + month*May * 0.0127+ month*Sep * 0.0916 + weekday*monday * 0.0631 + season*summer * 0.0723 + season*winter * 0.1251 + weathersit*light_snow_rain * -0.2411 + weathersit_misty-0.0536 **
