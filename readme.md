# (201905-baywheels-tripdata Dataset Exploration)
## by (Mohamed Gamal)


## Dataset

it's a dataset of trips by wheels in may 2019. the structure of the dataset is 182163 Rows , 14 Columns.
including ('duration_sec', 'start_time', 'end_time', 'start_station_id',
       'start_station_name', 'start_station_latitude',
       'start_station_longitude', 'end_station_id', 'end_station_name',
       'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type',
       'bike_share_for_all_trip') columns.
 the main features of interest in the dataset : duration_sec , start_time , user_type .

 some feature engineering nedded to handle this data into the visualization ..
so i calculated the days of the week and the sessions of the day the users take the trips on from the start_time feature,
and i calculated the durationby hours from duration_sec feature.

## Summary of Findings

duration_minutes column distribution:we can say that the duration is left skewed so we can say people prefer the small trip not the long one. from the describtion of the col ..we can say that the average of trip duration take 12 or 13 minutes .

 user_type feature:
   - from the chart we can say that the most of the users are subscribers not customers
   - from the chart we can say that on average Subscriber users spend more time in trips than Customer users.
   - Subscriber users spend more time in trips on Saturday Than any day .
   - Customer users spend more time in trips on Saturday and Sunday Than any day .
   - through the same day Subscriber people on Average spend more time on trips than Customers.
   - The most session the Subscribers spend time in through the same day is the Late Night session.
   - The most session the Customers spend time in through the same day is the Late Night session

 dayofweek feature:
   - from the chart we can say that people most prefered day to take trip on is Thrusday ,
   and the least prefered day to take trip on is Sunday
   - from the chart we can say that .. in average people spend more time in trips if they take the trip on Saturdayor Sunday.
   - Friday at Late Night is the time the people spend the most time on trips in.
   - Tuesday and Thrusday is the days which people spend the least amount of time through the sessions of these days on trips.
   - Sunday at Night , Monday at Early morning, tuesday at Morning and thrusday at Morning is the time
   when people spend the leat time on trips .

 session feature:
  - from the chart we can say that people prefer to take the trips on Evening Session, then the second prefered Session is the Morning , then the third one is the Afternoon Session,then Early Morning Session ,then Night Session ,and the least prefered session to take trip in is Late Night Session.
  - from the chart we can say that people spend in average more time in trips if it is in the Late Night session.
  - through tha same day Subscriber people on Average spend more time on trips than Customers.
  - The most session the Subscribers spend time in through the same day is the Late Night session.
  - The most session the Customers spend time in through the same day is the Late Night session.
  - Friday at Late Night is the time the people spend the most time on trips in.
  - Tuesday and Thrusday is the days which people spend the least amount of time through the sessions of these days on trips.
  - Sunday at Night , Monday at Early morning, tuesday at Morning and thrusday 
   at Morning is the time when people spend the leat time on trips .


## Key Insights for Presentation

For the presentation, I focus on just the influence of user_type , dayofweek and session
and leave out most of the intermediate derivations. I start by introducing the
duration_minutes variable, followed by the visualizations of the relation ship of each
feature  with the duration feature and the impact of adding third feature from them 
in the relation of one of the others with the duration_minutes










