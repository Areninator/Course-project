# Project Description
At your disposal is data from the Yandex Real Estate service - an archive of advertisements for the sale of apartments in St. Petersburg and neighboring settlements for several years.

You need to learn how to determine the market value of real estate. To do this, conduct exploratory data analysis and establish parameters that affect the price of objects. This will allow you to build an automated system: it will track anomalies and fraudulent activity.

For each apartment for sale, two types of data are available. The first ones are entered by the user, the second ones are obtained automatically based on cartographic data. For example, the distance to the center, airport and other objects - this data is automatically obtained from geoservices. The number of parks and reservoirs is also filled without user intervention.

## Data Description
* airports_nearest — distance to the nearest airport in meters (m)
* balcony — number of balconies
* ceiling_height — ceiling height (m)
* cityCenters_nearest — distance to the city center (m)
* days_exposition - how many days the ad was posted (from publication to removal)
* first_day_exposition — publication date
* floor - floor
* floors_total - total floors in the house
* is_apartment - apartments (boolean type)
* kitchen_area - kitchen area in square meters (m²)
* last_price — price at the time of removal from publication
* living_area - living area in square meters (m²)
* locality_name — name of the locality
* open_plan - open plan (boolean type)
* parks_around3000 — number of parks within a 3 km radius
* parks_nearest — distance to the nearest park (m)
* ponds_around3000 — number of ponds within a 3 km radius
* ponds_nearest — distance to the nearest body of water (m)
* rooms — number of rooms
* studio - studio apartment (boolean type)
* total_area — total area of the apartment in square meters (m²)
* total_images — number of photos of the apartment in the ad