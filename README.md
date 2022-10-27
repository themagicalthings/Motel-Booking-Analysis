# Booking-Analysis
# Data Information:
  Airbnb, Inc. is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. 
	Based in San Francisco, California, the platform is accessible via website and mobile app. 
	The Dataset have ~50k rows of various Airbnb hosts with 16 columns of various attributes like host name, boroughs, neighbors, price etc.
	Performing EDA on this dataset can help the company to know about the various host listings in different boroughs of NYC and their price and availability with rating and reviews.
	Attributes:
	1.neighbourhood_group: Consists data which tells us about locations in New-York state.
	2. neighbourhood: This attributes tells us about neighborhood areas from the major cities of New-York state.
	3. room_type: Consists data which tells us about all the available room type among various cities of New-York state.
	4. price: Contains prices for each Airbnb among various city locations.
	5. minimum_nights: Tells us the number of minimum nights people were stayed in that Airbnb.
	6. availability_365: Tells us about the number of days when listing is available for booking.
	7. number_of_reviews: Contains data which shows the number of reviews given by their customer to that particular Airbnb.
	8. latitude/longitude: Shows the geographical location of each host spread over the state of New- York.
	9. host_id/host_name: Contains list of names and ids of hosts, by whom the house was rented from.
 10. id/name: Contains list of names and ids of customers, to whom the house was rented. 
 11. review_per_month: Contains number of reviews given to specific room in each Month. 
 12. calculated_host_listings_count: It contains the amount of listing per host.
 # Data Processing:
 there are total 16 columns and 48895 rows.
 4 columns have missing values :
# Conclusion:
Expensive listings has fewer reviews and less expensive listings has more reviews.
• By analyzing host_id it shows that there are more than 37,000 hosts available across NYC.
• Majority of bookings were done for Entire home/apt (25393), followed by private room (22306).
• Manhattan was the busiest neighbourhood group with 21643 entries, followed by Brooklyn with 20089 entries.
• Staten Island has the highest average availability of 199 days were Manhattan has the least average availability of 112 days.
• Manhattan has the highest average minimum nights of 8 days.
• Average price of neighbourhood group –
• Bronx was the cheapest with average price of $87, Manhattan was the most expensive with average price of $196.
• Average price of all neighbourhood group is $152.
• 23909 listings choose the Airbnb whose price were less than $100, only 8378 listings booked Airbnb for more than $200.
