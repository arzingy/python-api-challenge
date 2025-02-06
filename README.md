# Python API Assignment
All the discussions about different linear relationships and maps can also be found in WeatherPy.ipynb and VacationPy.ipynb.
## WeatherPy
### DataFrame with city data
<figure>
  <img
  src="/screenshots/Weather/city_data_df.png">
</figure>

### Scatter plots showcasing the relationship between...
#### Latitude vs. Max Temperature
<figure>
  <img
  src="/screenshots/Weather/scatter_temp.png">
</figure>

#### Latitude vs. Humidity
<figure>
  <img
  src="/screenshots/Weather/scatter_humidity.png">
</figure>

#### Latitude vs. Cloudiness
<figure>
  <img
  src="/screenshots/Weather/scatter_cloudiness.png">
</figure>

#### Latitude vs. Wind Speed
<figure>
  <img
  src="/screenshots/Weather/scatter_wind.png">
</figure>

### Linear regression scatter plot for...
#### Northern Hemisphere: Latitude vs. Max Temperature
<figure>
  <img
  src="/screenshots/Weather/n_temp.png">
</figure>

#### Southern Hemisphere: Latitude vs. Max Temperature
<figure>
  <img
  src="/screenshots/Weather/s_temp.png">
</figure>
</br>We can see a strong negative relationship between latitude and max temperature in Northern Hemisphere and a weak positive relationship in Southern Hemisphere.
</br>That means that the closer we are to the equator, the greater max temperature is.
</br>The R-squared value of 0.676 for Northern Hemisphere indicates this is a reliable trend.
</br>However, the R-squared value of 0.287 for Souther Hemisphere suggests other factors might influence this relationship (ocean currents, land masses, etc.).

#### Northern Hemisphere: Latitude vs. Humidity
<figure>
  <img
  src="/screenshots/Weather/n_humidity.png">
</figure>

#### Southern Hemisphere: Latitude vs. Humidity
<figure>
  <img
  src="/screenshots/Weather/s_humidity.png">
</figure>
</br> Both for Northern and Southern Hemispheres, we can see that there's a weak positive relationship between latitude and humidity.
</br> That means that, generally, when you move north, humidity increases.
</br> However, the low R-squarede value suggests that many other factors affect humidity more than latitude.

#### Northern Hemisphere: Latitude vs. Cloudiness
<figure>
  <img
  src="/screenshots/Weather/n_cloudiness.png">
</figure>

#### Southern Hemisphere: Latitude vs. Cloudiness
<figure>
  <img
  src="/screenshots/Weather/s_cloudiness.png">
</figure>
</br> There's a very weak positive relationship between latitude and cloudiness both in Northern and Southern Hemispheres.
</br> As you move north, cloudiness increases slightly.
</br> The R-squared values of 0.047 and 0.054 indicate that this relationship is not strong, meaning other factors have a larger impact on cloudiness.

#### Northern Hemisphere: Latitude vs. Wind Speed
<figure>
  <img
  src="/screenshots/Weather/n_wind.png">
</figure>

#### Southern Hemisphere: Latitude vs. Wind Speed
<figure>
  <img
  src="/screenshots/Weather/s_wind.png">
</figure>
</br> There’s an extremely weak negative relationship between latitude and wind speed in the Northern Hemisphere.
</br> As you move north, wind speed decreases slightly.
</br> However, the R-squared value of 0.006 indicates that this relationship is almost negligible, meaning latitude hardly explains the variation in wind speed.
</br>
</br> There’s a slightly stronger but still weak negative relationship between latitude and wind speed in the Southern Hemisphere.
</br> We can see that wind speed decreases slightly as we move south.
</br> The R-squared value of 0.038 suggests that other factors significantly influence wind speed beyond just latitude.

## VacationPy
### Map of cities from DataFrame
<figure>
  <img
  src="/screenshots/Vacation/city_map.png">
</figure>


### DataFrame with cities with ideal weather
<figure>
  <img
  src="/screenshots/Vacation/ideal_cities.png">
</figure>


### DataFrame with hotels in the "ideal" cities
<figure>
  <img
  src="/screenshots/Vacation/hotel_df.png">
</figure>


### Map of "ideal" cities. The hotel name and the country is added as additional information in the hover message for each city
<figure>
  <img
  src="/screenshots/Vacation/hotel_map.png">
</figure>
