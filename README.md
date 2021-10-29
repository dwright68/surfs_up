# surfs_up

## Project Overview
The purpose of this project is to utilize weather data in a SQLite database to determine if a new surfshop in Oahu would be viable. We will do this using Python and SQLAlchemy. 

## June Weather Data

Using data point from 1700 days in the month of June, we were able to see that the month sees little variance in overall temperature. With the maximum temp being 85 and the lowest being 64. See below for further details on temperature variance in the month of June. 

![June_temps](https://user-images.githubusercontent.com/88564212/139491734-c2241359-2439-4b39-aa69-d2dc185b4b24.png)


## December Weather Data

On the opposite end of the temperature spectrum we have December. While it is sliightly cooler compared to a peak summer month like June, it is still a very comfortable temperature overall. This month should see similar traffic as a summer month, possibly even more as people flee the cold in their homes.


![Dec_temps](https://user-images.githubusercontent.com/88564212/139492852-8004d052-5972-4cbd-a3d5-4896ea835916.png)


## Overall findings
Using the information gained from looking at just the temperature data from these two months we can infer that 
- The standard deviation of temperatures for Dec is 3.25 while the deviation for June is 3.74. 
- The summer months will be a peak time of traffic for the surf shop.
- The winter months will have a very similar weather pattern as the the summer, so business should not slow significantly. 

## Additional Queries

Below I refactored the code to also include precipitation data for the two months. This data can also help us collect more info on weather variance in the two different season. 

### June
![June Precip](https://user-images.githubusercontent.com/88564212/139496741-7eea3479-4c4a-4495-935b-94ded24843de.png)

### December

![Dec precip](https://user-images.githubusercontent.com/88564212/139496803-6286f595-82af-4dd7-b4b8-413a2e04aa1a.png)

