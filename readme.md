# Ford GoBike System Data Exploration

## Dataset

The data consists of information regarding 2506983 bike rentals (data downloaded for the year 2019), including the rentals duration, stations, user type and membership details. The dataset used for exploration is from the Ford GoBike System Data(now lyft) for the year 2019 and it is found [here](https://s3.amazonaws.com/baywheels-data/index.html) and the dataset information can be found [here](https://www.lyft.com/bikes/bay-wheels/system-data)

Note: The data files used can be found [here](https://s3.amazonaws.com/baywheels-data/index.html), which has to be downloaded and unzipped. Later should be stored in a Folder named "Data".

Files to download (For year 2019) - 201901-fordgobike-tripdata.csv, 201902-fordgobike-tripdata.csv, 201903-fordgobike-tripdata.csv, 201904-fordgobike-tripdata.csv, 201905-fordgobike-tripdata.csv, 201906-fordgobike-tripdata.csv, 201907-fordgobike-tripdata.csv, 201908-fordgobike-tripdata.csv, 201909-fordgobike-tripdata.csv, 201910-fordgobike-tripdata.csv, 201911-fordgobike-tripdata.csv, 201912-fordgobike-tripdata.csv

## Summary of Findings

In the exploration process, I wanted to explore the time of maximum bike rentals. Initially I checked for the average time of bike rentals using univariate plots then further investigated the time duration of bike rental for different user types(Customer and Subscriber) using Bivariate plots. The maximum duration of Customer was higher than the subscriber, but the number of subscribers were higher.

In order to find time for maximum bike rentals, we had to traverse further but for different user types. I have used both univariate and bivariate plots to explore the dataset and find time of maximum bike rentals for both user types.The plots obtained clearly showed that the subscribers were usually locals using the bike rentals for daily commute. Similarly, the customers were visitors or tourists using the bike rental for leisure or travel. Additionally, the bike rentals provided membership to locals and all of them were from subscriber data and none from the customer data.

Finally, I investigated further using multivariate plots to find the time of maximum rentals for both subscribers and customers. For the dataset used for exploration, the bike rentals for customers were high in the month of September, October and December. It was usually high on Weekends and in the Evenings. Similarly, for subscribers, the bike rentals were high in the evenings of weekdays all through the year.

## Key Insights for Presentation

For the presentation, the key area of focus will be the maximum bike rentals for both the user types. We will first look at the maximum bike rentals for each month, week and then by time of day. Then we will look at the same parameters but for different user types i.e., Subscriber and Customer.

Finally we will use heat maps to find the maximum bike rentals for both users, First by day of week and the time of the bike rental. Secondly, by month and time of bike rental. This will provide a view on the maximum bike rentals trend for the year 2019 by user types. 

