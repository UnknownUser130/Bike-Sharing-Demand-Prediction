<h1>Bike-Sharing Demand Prediction</h1>
This project aims to develop a predictive model to forecast the bike rental count based on various features such as date, weather conditions, and time of the day. By analyzing historical data, we can create a model that accurately predicts the number of bikes that will be rented at different times.

<h1>Dataset Description</h1>
<h2>Day Dataset</h2>
The “day” dataset contains daily aggregated bike rental information, while the “hour” dataset provides hourly details. Here are the key columns in the “day” dataset:

instant: A unique identifier for each record
dteday: Date of the record
season: Season of the year (1 = spring, 2 = summer, 3 = fall, 4 = winter)
yr: Year (0 = 2011, 1 = 2012)
mnth: Month (1 to 12)
holiday: Binary flag indicating if it is a holiday (1 = yes, 0 = no)
weekday: Day of the week (0 to 6, where 0 = Sunday)
workingday: Binary flag indicating if it is a working day (1 = yes, 0 = no)
weathersit: Weather situation (1 = clear, 2 = mist/cloudy, 3 = light rain/snow, 4 = heavy rain/snow)
temp: Normalized temperature in Celsius
atemp: Normalized feeling temperature in Celsius
hum: Normalized humidity
windspeed: Normalized wind speed
casual: Count of casual bike rentals
registered: Count of registered bike rentals
cnt: Total count of bike rentals (casual + registered)
