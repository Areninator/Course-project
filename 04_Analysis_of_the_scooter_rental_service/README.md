# Project Description

You are an analyst for the popular scooter rental service GoFast. You were given data about some users from several cities, as well as about their trips. Analyze the data and test some hypotheses that can help the business grow.

To travel around the city, users of the GoFast service use a mobile application. The service can be used:

without subscription:
- there is no subscription fee
- price of one minute of travel - 8 rubles
- cost of start (start of trip) - 50 rubles

with Ultra subscription:
- subscription fee - 199 rubles per month
- cost of one minute of travel - 6 rubles
- start-up cost is free

## Data Description
Master data contains information about users, their trips and subscriptions.

### Users — users_go.csv

* user_id - unique user identifier
* name - username
* age - age
* city - city
* subscription_type - subscription type (free, ultra)

### Rides - rides_go.csv

* user_id - unique user identifier
* distance - the distance the user has traveled in the current session (in meters)
* duration - session duration (in minutes) - the time from the moment the user pressed the “Start trip” button until the moment he pressed the “End trip” button
* date - travel date

### Subscriptions — subscriptions_go.csv

* subscription_type - subscription type
* minute_price -  price of one minute of travel for this subscription
* start_ride_price - price of starting the trip
* subscription_fee - monthly payment price