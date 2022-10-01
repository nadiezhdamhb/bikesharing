# Bikesharing

### 1. Overview of the analysis
The purpose of this analysis is to determine if a bike sharing program would be successful in Des Moines, Iowa and must be able to understand the components. It's important to create a clear argument to convince investors that a bike-sharing program in Des Moines is a solid business proposal. A bike trip analysis will be shown to the key stakeholders. From the CitiBike Data, the "tripduration" column will need to be changed from an integer to a datetime datatype. Then, using the converted datatype, visualizations will be created to show the following: 

- Show the length of time that bikes are checked out for all riders and genders;
- Show the number of bike trips for all riders and genders for each hour of each day of the week;
- Show the number of bike trips for each type of user and gender for each day of the week.

[Click Here to view the Dashboard!](https://public.tableau.com/app/profile/nadiezhda.hernandez/viz/NYCCitibikeAnalysis_16646272585350/NYCCITIBikeStory#1)

### 2. Results
##### a. The overall information for CitiBike data
- The number of total trips is 2,344,224;
- Male or male-indetified customers have more rides;
- August peak hours are from 5pm-7pm

![image](https://github.com/nadiezhdamhb/bikesharing/blob/main/NYC%20CitiBike%20Dashboard.png)

##### b. Starting locations
Popular start location is Manhattan. The size of the circles and darkness of the BLUE indicate the relative number of trips started at those locations. It is apparent that the bulk of the bike trips are originating in the densely populated areas, which always have heavier traffic all the day.

![image](https://user-images.githubusercontent.com/103073631/179435812-2073c17e-017e-496e-ae6b-eb96009f0e8c.png)

##### c. Start time hours
The time periods of high bikesharing usage are from 5pm to 7pm and sometime between 8am-9am.

![image](https://user-images.githubusercontent.com/103073631/179447929-4b2dcbab-0778-489b-bcef-b9624fb9fe64.png)

##### d. Checkout Times by Gender
Most trips are under a half-hour and male or male-indetified customers take more rides than females or unknown users.

![image](https://user-images.githubusercontent.com/103073631/179448297-40e58758-84bd-4c3c-aefe-c7595f45b509.png)

![image](https://user-images.githubusercontent.com/103073631/179448024-08420728-4463-486e-b13d-dd05ffa7f8cc.png)

##### e. Trips by Weekday for Each Hour
The below heatmap shows patterns during the day. We can see the heavy bike traffic or usage during weekday commute hours from 7am-9am and 5pm-7pm, and weekend usage is spread out from the middle of the day. There is relatively low bike usage during early commute hours such as 4am-6am and late night such as 9pm-11pm. For further analysis we may need more data to check for patterns on low usage happening on Wednesdays since we only use the August 2019 data to analyze the trips by weekday for each hour.

![image](https://user-images.githubusercontent.com/103073631/179448890-e75cea5a-bf79-4e72-805f-a8102214c10f.png)

##### f. Trips by Gender (Weekday per Hour) & the User Trips by Gender by Weekday

Below two heatmaps show the customers are mainly male or male-indetified users. We could use more data and further study to analyze the factors for male customers to prefer bikesharing as opposed to female customers. One important piece of information could be crime rate comparison between various areas in the city and user trips by gender. 

![image](https://user-images.githubusercontent.com/103073631/179448996-5bdb8666-4e89-4ab9-99cc-5301a4affba6.png)

![image](https://user-images.githubusercontent.com/103073631/179449008-99fb501b-b9c1-44e1-8e77-656f1d403bd2.png)


### 3. Summary
In conclusion, the bikesharing program could be a solid business proposal. We can see Citibikes are popular and busy in NYC, based on the time of usage we see that bikesharing reaches its peak during periods of heavy traffic hours such as morning time when people go to work and in the evening when they are off work.

For the gender part of the analysis, male or male-indetified customers take more rides than others. Crime rate studies would be necessary to identify potential causes for females to not ride as much as males. Also it would be a good idea to improve the bike-parking places to make them safe and set alerts in the pick up areas to help customers feel safe and improve the business profitability.
For future analysis:
1. Analysis on potential reasons for the big difference in user trips between genders including crime rates, lack of adequate and safe infrastructure on different locations to see if there is a correlation with trips by gender.
2. Another important analysis would be to study weather data to see the relationship between the number of rides and weather.
