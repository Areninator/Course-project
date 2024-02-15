# Project Description
Mobile operator Megaline found out that many customers use archived tariffs. They want to build a system that can analyze customer behavior and offer users a new tariff: “Smart” or “Ultra”.


You have data on the behavior of customers who have already switched to these tariffs. We need to build a model for the classification task that will select the appropriate tariff. There is no need for data preprocessing - you have already done it.


Build a model with the highest possible accuracy value. To pass the project successfully, you need to bring the percentage of correct answers to at least 0.75. Check the accuracy on a test sample yourself.

## Data Description
Each object in the dataset is information about the behavior of one user for a month. Known:
* calls — number of calls,
* minutes — total duration of calls in minutes,
* messages — number of SMS messages,
* mb_used — consumed Internet traffic in MB,
* is_ultra — what tariff you used during the month (“Ultra” - 1, “Smart” - 0).