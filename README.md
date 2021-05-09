# bikesharing

# Overview of our Analysis

The purpose of our project is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis. For this analysis, I used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, I created a set of visualizations to:
Show the length of time that bikes are checked out for all riders and genders, show the number of bike trips for all riders and genders for each hour of each day of the week, and show the number of bike trips for each type of user and gender for each day of the week in the month of August. Finally, I added these new visualizations created in this module for my final presentation and analysis to pitch to investors.

The link below takes you to the Tableau Data Visualization dashboard:
[link to dashboard]("https://public.tableau.com/profile/kushali.shah#!/vizhome/NYCCitiBike_16199973622460/NYCCitiBikeStory?publish=yes")

# Results:

- ![august_peakhours](https://github.com/kushalishah/bikesharing/blob/main/august_peakhours.png)

I created seven different types of visualizations using the total number of trips, type of users, adn the trip duration. We found that the month of August had the highest number of rentals. The bike trips totaled to 2,344,224. The graph above shows us the peak hours.

- ![check_out_time](https://github.com/kushalishah/bikesharing/blob/main/checkout_time_users.png)

The graph above shows us that 146,752 bikes were rented within the first 10 minutes of the trip duration.

- ![checkout_time_gender](https://github.com/kushalishah/bikesharing/blob/main/checkout_time_gender.png)

The graph shows us that males rented 108,087 bikes, females rented 34,151 bikes and the rest who were labeled as unknown rented 7,298 bikes.

- ![trips_weekday_hour](https://github.com/kushalishah/bikesharing/blob/main/trips_weekday_hour.png)

The heatmap above shows us that morning and evenings during the weekdays had the most rentals. The weekend would be as expected.

- ![trips_gender](https://github.com/kushalishah/bikesharing/blob/main/trips_gender.png)

The heatmap above shows us that there is a similar distribution in overall rentals, however, the male gender had darker coloration indicating more rentals.

-![user_trips_gender](https://github.com/kushalishah/bikesharing/blob/main/user_trips_gender.png)

The heatmap above shows us that in general, subscribers rode more bikes. Again, males rented the most bikes.

-![top_ending_locations](https://github.com/kushalishah/bikesharing/blob/main/top_ending_locations.png)

This additional dataset was interesting as we can see that most bikers ended their rides near the water.

# Summary

The CitiBike Analysis tells that Thursday is the most popular day for bike rides, especially in the evenings. The data shows us that males rented 108,087 bikes, females rented 34,151 bikes and the rest who were labeled as unknown rented 7,298 bikes. Also, there are more Subscribers than regular non-subscribers. The top ending locations were along the waterfront. 

A visualization I'd like to see is whether these rentals are utilized by locals or tourists. This way CitiBike can market towards the right group of people. Another visualization that would be helpful is looking at the data for other months to plan for maintenance.
