# Bike Ride Analysis in NYC
In this work, we analyze a data set of Citi Bike in New York City to what are the important information we can extract if we are going to start a bike sharing business in another city. 

### Data
The citi bike data is available in the following [citibike](https://s3.amazonaws.com/tripdata/index.html) website. The data set we use here is "201908-citibike-tripdata.csv.zip" represents the rides in the month of August in 2019. The data set has following columns:
- Trip Duration (seconds)
- Start Time and Date
- Stop Time and Date
- Start Station Name
- End Station Name
- Station ID
- Station Lat/Long
- Bike ID
- User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
- Gender (Zero=unknown; 1=male; 2=female)
- Year of Birth

## Results
According to the data set, there were 2,344,224 rides in August, 2019. As shown below, 443,865 of them are short-term riders and the others, 1,900,359 are annual subscribers.

  <img width="192" alt="Screenshot 2023-08-23 at 12 09 42 PM" src="https://github.com/ranilb/bikesharing/assets/112113327/813ffd29-507a-4a72-9d9e-dfc9681a3c40">

Another important information we can find out is that the number of rides in each hour entire 24 hours. The foll graph is shown bellow: 
  
  <img width="648" alt="Screenshot 2023-08-23 at 12 21 26 PM" src="https://github.com/ranilb/bikesharing/assets/112113327/411aa15b-9c4c-47af-8cda-e074adf25cf1">


  As we can observed, the peak hours are from 5:00 PM to 7:00 PM.

  In addition to the above information, the symbol maps for Top starting point and the Top ending points were created. The top starting point map is shown below. Dark blue represents the most popular stations and light blue represents less popular stations. 

  
  <img width="420" alt="Screenshot 2023-08-23 at 2 24 04 PM" src="https://github.com/ranilb/bikesharing/assets/112113327/791f6fb4-b8e5-4cf3-8209-6d32d4d6f0ea">

Also, the top ending point map is shown below. Red represents the most popular stations and the gold represents less popular areas.

  <img width="447" alt="Screenshot 2023-08-23 at 2 23 17 PM" src="https://github.com/ranilb/bikesharing/assets/112113327/a5257dc2-2c38-4dcb-a546-ba2b564f8b3b">

#### Gender Breakdown
When we consider the total number of rides, 1,530,272 are males, 588,431 are females and the 225,521 are unkown. Therefore, we can observe that the male riders are about three times more than the female riders. The following pie-chart shows the results.

  <img width="196" alt="Screenshot 2023-08-24 at 10 23 36 AM" src="https://github.com/ranilb/bikesharing/assets/112113327/dc4dc429-29ba-4389-995d-a98e92238199">  <img width="118" alt="Screenshot 2023-08-24 at 10 52 06 AM" src="https://github.com/ranilb/bikesharing/assets/112113327/41be3c81-3b3f-4b6c-9c56-b3f86d99a752">

#### Average Trip Duration
Next the averate duration of rides was computed for each person's birth year. The results are shown below. It can be observe that the duration of young riders are longer than the others. That means, in general, the later the birth year, the longer the ride duration. 

  <img width="713" alt="Screenshot 2023-08-24 at 1 13 37 PM" src="https://github.com/ranilb/bikesharing/assets/112113327/9c73cb11-b706-48ca-b219-aa19604492f7">


#### Which bikes needs repairs
The bikes used most frequently will probably be the ones that require the most maintenance. Therefore, we are going to determine which bikes have the highest sum of "Number of Rides." The following figure shows the mumber of rides for each bike ID.

  <img width="739" alt="Screenshot 2023-08-24 at 2 05 52 PM" src="https://github.com/ranilb/bikesharing/assets/112113327/39296dc2-217d-4cf9-92e5-4a21900de52e">
