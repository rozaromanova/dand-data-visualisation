# Data Visualisation - FordBikes usage in 2018

Ford GoBike is a bicycle sharing system in the San Francisco Bay Area. Beginning operation in August 2013 as Bay Area Bike Share across San Francisco, East Bay and San Jose. In 2017 the system officially launched as Ford GoBike in a partnership with Ford Motor Company.

Now the service is operated by Lyft.

### The data for the analysis

The data set contains approx 185,000 rides taken in 2018. It contains trip data(start/end time), as well as customer data(age, gender). The original dataset can be found [here](https://www.fordgobike.com/system-data)

Before the analysis was conducted, the data set was cleaned and additional colums that would make the analysis easier were introduced:
- start time month
- start time weekday
- start time hour
- duration min
- member age

### Findings

In the exploration phase I found out that the behaviour difference between 2 user groups - Subscribers and Customer is signigicantly differ.

#### Subscribers 

The majority of the system users are Subscribers. Subscribers behavior suggest that they are primarly daily commuters.
1. Bike usage on weekdays, with significant drop on weekends
2. Usage time 8-10am and 4-6pm
3. Short trips

#### Customers 

Customers are tourists or casual riders

1. Bike usage on weekends, or weekday evenings
2. Usage time 10am-6pm on the weekends, and 4-6pm weekdays
3. Longer trips

#### General observations

There is an interesting finding regarding the gender differences. In general male/female/other behaviours look pretty much the same, except of females in the Customer group. The female Customers tend to use the bikesharing more in the winter months between January and March in comparison to males, also taking longer trips.


