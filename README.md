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
- temp coef:0.5684
- humidity coef:-0.1643
- windspeed coef:-0.1943
- year coef:0.2296
- light snow coef:-0.2425
- winter coef:0.1251

## Final Model Equalation

** count (cnt) = 0.1907 + workingday \* 0.0526+ temp \* 0.5684 - humidity \* 0.1643 - windspeed \* 0.1943 + year_2019 \* 0.2296 - month_Jan \* 0.0401 - month_Jul \* 0.0429 + month_Sep \* 0.0909 + weekday_monday \* 0.0629 + season_summer \* 0.0765 + season_winter \* 0.1251 - weathersit_light_snow_rain \* 0.2425 - weathersit_misty \* -0.0538 **

## Verdict

- Temparature Effect:
  - Summer season or warmer months have more count of bike thus offers should give at that time
- Weather Conditions
  - Promotions and offers should be given when the weather is clear. There is a decline in adverse weather condition.
- Windspeed & humidity effect
  - In High windspeed or high humid seasons, there is a decline thus startegical chgange and infra level upgradation can be done this time
- Year
  - Year 2019 (post pandemic) is showing good result thus focus on year end busniess with offers and promotions.
