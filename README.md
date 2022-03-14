# Data Expo 2009 - Airline on-time performance 🛫
## by (Samiha Amroune 😊 )



## [Dataset](https://community.amstat.org/jointscsg-section/dataexpo/dataexpo2009)

The data consists of flight arrival and departure details for all commercial flights within the USA, from October 1987 to April 2008. This is a large dataset: there are nearly 120 million records in total, and takes up 1.6 gigabytes of space compressed and 12 gigabytes when uncompressed. 
So I choose to Analyze data of year **2001**

The data comes originally from [RITA](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp) where it is [described in detail](https://www.transtats.bts.gov/nosessionvar.asp).


## Summary of Findings

> The data used for this study from Year 2001 included only delayed and canceled flights
> The data was analyzed in 3 stages

### 1- Univariate Exploration
#### The results of this stage: 
> The most top 10 Delays or cancelation are: 
>- **By UniqueCarrier :** United Airlines, Inc.**(UA)**, followed by Southwest Airlines Co.**(WN)**, then Delta Air Lines, Inc.**(DL)**, had the most delays
>- **By Origin :** Chicago O'Hare International Airport **(ORD)** ,Dallas/Ft Worth Intl **(DFW)**, Atlanta	Hartsfield-Jackson Int
>- **By Destination :** Chicago O'Hare International Airport **(ORD)**, Dallas/Ft Worth Intl **(DFW)**, Los Angeles **(LAX)**

>- Most days of the week with a flight delay or cancellation are: **Friday, Thursday and Wednesday**

>- Most Month with a flight delay or cancellation is:**September**

>- Highest days of delayed or canceled flights in September: **Days 11, 12, 13, 14**

>- Scheduled Departure Time that have the most delays or cancelation are :**Between 15:00 to 17:00 (3-5 pm)، Maximum delay or cancellation is at 17:00**


>- Most delay or cancellation flight by Air Time:**Airtime on short flights of 50 minutes or less has the greatest cancelled flights**

>- Most 10 TailNum a flight delay or cancellation are:**Plane -N916D has 803 delays and cancellations followed by plane -N914 and plane -N910**

>- Most 10 FlightNum a flight delay or cancellation are:**Flight numbers 197, 481 and 70 are the most delayed flights**

>- The most Distance in miles a flight delay or cancellation:**Flights 337, 370, 109 are the most delayed or canceled**

### Bivariate Exploration
#### The results of this stage: 
>- Relationship between Departure Delay and Arrival Delay is:**Very Strong positive relationship**

>- Relationship between Air Time and Arrival Delay is:**Very week positive**

>- Relationship between Air Time and Distance is:**Very Strong positive relation**

>- Relationship between TaxiIn and Arrival Delay is:**Week positive relation**

### Multivariate Exploration
#### The results of this stage: 
>- From the heatmap there are:
. Very Strong positve relationship between:
    * ArrDelay and DepDelay with correlation coefficient = 0.907
    * DepTime and CRSDepTime with correlation coefficient = 0.882
. Strong positve relationship between:
    * 'CRSArrTime' and 'CRSDepTime' with correlation coefficient = 0.786
    * 'CRSArrTime' and 'DepTime' with correlation coefficient = 0.772
    * 'CRSArrTime' and 'AirTime' with correlation coefficient = 0.605
. Moderate positve relationship between:
    * 'DepTime' and 'ArrTime' with correlation coefficient = 0.461

> - July 1st and August 10th had the highest Average of Departure delays

> - Sunday in july is the day that had the highest Average of Departure delays

> - 12 September the day that have the most cancellation flights

> - Wednesday in September had the most cancellated flghts

>- 17:00 (5PM) to 20:00 (8PM) in June, July , August had the most delay time


## Key Insights for Presentation

> - We noticed that the Airports: **Chicago O'Hare International**, **Airport International Airport**, **Dallas**, **Atlanta**: Highest delay rate <br>
> - September seems to be the only month with the highest number of flight cancellations in **2001** due to attacks on the USA on **11th**<br>
In General:
> - **17:00 (5 pm)** to **20:00 (8 pm)** in **June**, **July**, **August** are the most delayed time <br>
> - **July 1st** and **August 10th** had the highest average departure delays <br>
> The least delayed or canceled day is **Sunday** <br>