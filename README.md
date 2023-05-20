# Data-Architecture

In this project, I used US Flight Delays dataset, which contains information about flight schedules and delays across multiple airlines and airports in the United States. I  performed an exploratory analysis of the dataset to gain insights into flight delays, identify patterns, and provide valuable information for airline companies and passengers.

___________________________________________________________________________________________________________________________________________________________________
![Flights (1)](https://github.com/Thamer0101/Data-Architecture/assets/127024138/9fba138c-82a0-46e2-b05f-49ffdc9542bd)


# 1- Loading dataset:
### I loaded the dataset in oracle database tables by using SQL Developer IDE to storing the data

![oracle](https://github.com/Thamer0101/Data-Architecture/assets/127024138/23e6d680-68db-46d7-8bcb-7793fb17a021)
___________________________________________________________________________________________________________________________________________________________________
### sql query to checking the dataset loaded into the database successfully.


![sql](https://github.com/Thamer0101/Data-Architecture/assets/127024138/0f78475e-3166-47a5-a7df-3020c7754b5c)

___________________________________________________________________________________________________________________________________________________________________

##  2- Connecting to the oracle database using Spark through jupyter IDE and importing the dataset:


![Spark UI3](https://github.com/Thamer0101/Data-Architecture/assets/127024138/973e4fb8-a4ee-495b-aab1-8407fa9ef3dd)

## 3- To see analytics, statistics and visualizations ,open "Exporatpry Analysis".ipynb file.
________________________________________________________________________________________________________________________________________

### Tools and technologies used in this project:
 This project makes use of various Big Data processing technologies including:
  - Oracle database, because oracle database has availability of having multiple databases, analytics tools, and machine learning environments.
  - Apache Spark, because of its ability to process massive amounts of data as well as the use of its unified analytics engine and convenient APIs
  - Pandas, due to its convenient dataframe manipulation functions
  - Matplotlib, to plot data and gain further insights

________________________________________________________________________________________________________________________________________
## 4- Insights and Recommendations:
After seeing the data analytics and visualizations, I will make recommendations to the airlines and passengers as follows:

### Recommendations for Airlines:
- Depending on the data analysis, Chicago O'Hare and Hartsfield-Jackson Atlanta airports are the most late arrival and departure airports, so I would recommend       airlines to increase the effort in managing arrivals and departures at airports in general and these two airports in particular.
- I found a relationship between the flight time and the arrival delay. The longer the flight time, the less the arrival delay, I would recommend airlines to         focusing on short flights and manage them more to decrease arrival time.
-

### Recommendations for Passengers:
- There is a high rate of flight delays in June and July of the year, I would recommend passengers to avoid booking flights in these two months.
- "Delta Air Lines", "Hawaiian Airlines" and "Virgin America" has best rate of departure delays, if you want to save your time, then book your tickets from them.
-

Airport "Chicago O'Hare" and "Hartsfild-Jackson Atlanta" are the most delayed airports in arrival and departure, 


















