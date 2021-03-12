# What's the weather like as we approach the equator? 
A visualization of the weather of 500+ cities across the world of varying distance from the equator.

## Hypothesis:
 Temperature is inversely related to latitude. As latitude increases, the temperature falls, and vice versa.
 
## Questions
1.  Are there observable trends establishing a relationship between latitude and temperature?
2.  Is there a strong correlation between latitude and temperature?
3.  Can the temperature of a loaction be predicted with known latitude?

## Libraries Used
Python
  * Pandas
  * Matplotlib
  * Stats
  * Requests
  * Time

## Data Sources
* Weather data from openweathermap API
* Location (lats and lngs) data obtained from Google Places API

## Visualizations


# Analysis
The negative r-squared value indicates inverse relationship between the variables, whereas a positive r-squared value indicates a direct relationship between variables under consideration.
For r-squared values between 0 to 1, the higher the value, the closer the relationship between the variables and vise-versa. 

Considering the r-squared values for the Norhern and Southern Hemispheres where the variables are maximum temperature and latitude, a -0.88 for the Northern Hemisphere indicates a stonger inverse relationship between latitude and temperature. There is 88% likelyhood that a lower altitude will result in higher temperature. However, a +0.49 value for the southern hemisphere for same variables do not support the observation in the northern hemisphere.

The difference in hemispheres is not significant enough basis to make conclusive theory on weather conditions.
