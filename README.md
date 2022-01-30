# Bikesharing Analysis

## Overview

The purpose of the Bikesharing Analysis was to determine if a bike-share program, similar to the City Bike bikesharing business found in New York City, could be implemented in Des Moines, IA. The inner workings of the City Bike program in NYC was studied and explored by analyzing [August 2019 data](/Resources/new_201908-citibike-tripdata.csv) from the [Citi Bike program in NYC](https://ride.citibikenyc.com/system-data). Tableau and Python were used to manipulate/transform the data and create the following visualizations:
- Checkout Times for Users
- Gender Breakdown
- Checkout Times by Gender
- Trips by Weekday per Hour
- Trips by Gender (Weekday per Hour)
- User Breakdown
- User Trips by Gender by Weekday

The visualizations were created in individual Tableau Sheets, then compiled into a Tableau Story to present to potential investors, which can be found in this [Tableau Workbook](https://public.tableau.com/app/profile/francesca.obordo/viz/NYC_Citibike_Challenge_16433797969610/NYCStoryChallenge).

## Results

### 1. Checkout Times for Users
![Checkout Times for Users](/Resources/Images/Checkout_Times_for_Users.png)

In the Checkout Times for Users visualization, we graphed the length of time that bikes were checked out by users. The visualization showed that a majority of bikes (146, 752 bikes) were checked out for 5 minutes. The minimum checkout time was 1 minute (35,135 bikes), and the maximum checkout time was 23 hours and 54 minutes (3 bikes). We can assume that users that checked out a bike for 1+ hours would park the bike somewhere and return it later when they were finished using it for the day. Since it is unlikely that a user was using a bike for 23+ hours, it can be assumed that the user likely forgot to return the bike, resulting in the long checkout time. Ultimately, it can be concluded that most bikes were checked out on average for 1 to 60 minutes.

### 2. Gender Breakdown
![Gender Breakdown](/Resources/Images/Gender_Breakdown.png)

In the Gender Breakdown visualization, we created a pie chart of the gender breakdown of bike users (male, female, and unknown). The pie chart showed the following breakdown:
- ~65% (1,520,272 out of 2,344,224) of bike users were male 
- ~25% (588,431 out of 2,344,224) of bike users were female
- ~10% (225,521 out of 2,344,224) of bike users were unknown

The pie chart revealed that there are significantly more male Citi Bike users than female.

### 3. Checkout Times by Gender
![Checkout Times by Gender](/Resources/Images/Checkout_Times_by_Gender.png)

In the Checkout Times by Gender visualization, we graphed the length of time that bikes were checkout by each gender. The graph showed that on average, most male users checked bikes out for 5 minutes and most female users checked bikes out for 6 minutes. On average, users of unknown gender checked bikes out for about 15 minutes.

### 4. Trips by Weekday per Hour
![Trips by Weekday per Hour](/Resources/Images/Trips_by_Weekday_per_Hour.png)

In the Trips by Weekday per Hour visualization, we graphed the number of bike trips by weekday for each hour of the day as a heatmap. The heatmap revealed a pattern of the busiest hours of the day for weekdays and weekends for Citi Bike trips. On weekends, the most number of bike trips occurred between 11am and 6pm. It is likely that during this timeframe, users utilized Citi Bike to get around the city on their days off. On weekdays, the most number of bike trips occurred at 8am and between 5pm and 6pm. It is likely that these were the times that users utilized Citi Bike to get to and from work at the beginning and end of their work days.

### 5. Trips by Gender (Weekday per Hour)
![Trips by Gender (Weekday per Hour)](/Resources/Images/Trips_by_Gender.png)

In the Trips by Gender (Weekday per Hour) visualization, we graphed the number of bike trips by gender for each hour of each day of the week as a heatmap. The heatmap revealed a similar pattern as the Trips by Weekday per Hour visualization, however it is visible how many more male users took trips than females. This aligns with the Gender Breakdown visualized, further showing that the Citi Bike program had far more male users than female users. 


### 6. User Breakdown
![User Breakdown](/Resources/Images/User_Breakdown.png)

In the User Breakdown visualization, we created a pie chart of the user breakdown of bike users (customer or subscriber). The pie chart showed the following breakdown:
- ~81% (1,900,359 out of 2,344,224) of bike users were subscribers
- ~19% (443,865 out of 2,344,224) of bike users were customers

The pie chart revealed that there are significantly more subscribers than customers of the Citi Bike program.

### 7. User Trips by Gender by Weekday
![User Trips by Gender by Weekday](/Resources/Images/User_Trips_by_Gender_by_Weekday.png)

In the User Trips by Gender by Weekday visualization, we created a heatmap that shows the number of bike trips broken down by gender for each day of the week by each user type. The heatmap revealed the following:

For female users
- There were more female subscriberes than female customers
- Most female customer trips occurred on Saturday
- Most female subscriber trips occurred on Thursday and Friday

For male users
- There were more male subscribers than male customers
- Most male customer trips occurred on Saturday
- Most male subscriber trips occurred on Thursday and Friday

For unknown users
- There were more unknown customeres than unknown subscribers
- Most unknown customer trips occurred on Saturday
- Most unknown subscriber trips occurred on Thursday and Friday

The commonality between female, male, and unknown genders was that most customer trips occurred on Saturday, while most subscriber trips occurred on Thursday and Friday.

## Summary
Overall, the results revealed the following inights:
- The duration of most bike trips was 5 minutes, regardless of gender
- There were significantly more male user than female users of the Citi Bike program
- On weekends, most bike trips occurred between 11am and 6pm, while on weekdays, most bike trips occurred at 8am and between 5pm and 6pm, regardless of gender
- There were significantly more subscribers than customers of the Citi Bike program, most of which were male
- Most bike trips occurred on Thursday, Friday and Saturday, regardless of user type or gender

Two additional visualizations that could be created for future analysis would be:
1. Top Starting Locations by Gender
2. Top Ending Locations by Gender