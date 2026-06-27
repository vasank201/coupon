### Readme.md 06/26 v0.1

**Technical Overview**

The analysis of the coupon data is performed against various data points captured in the
dataset. The data has be cleaned, formatted to accomplist a Visual appeal. Bar data,
Cheap restaurant data has be updated for ease of display and visual inference.

1. Y column has been renamed to accept_coupon

2. Bar column has been renamed to barVisits

3. Values of Bar, RestaurantLessThan20, CarryAway, Restaurant20to50, Coffee House has been renamed to the following -
	a. 0
	b. less than 1
	c. 1 to 3
	d. 4 to 8
	e. greater than 8

4. Corresponding Columns attributes have been renamed to the following
	a. CheapRest
	b. Coffee
	c. Takeout
	d. Bar
	e. ExpensiveRest

5. New DataFrame that drops null values for bar and restaurant has been created
	a. bar_data
	b. restaurant_data

6. Seaborn Plot has been extensively use to visualize acceptance data for total observation, bar observation, cheaprestaurant data

7. Violin and Bar plot has been used as ancillary plot for analysis

8. Pandas Query, Macros, Data Manipulation techniques (such as column renames, new data frames from dictionary etc.)

9. Subplot using FacetGrid to compare the acceptance rate for bi-variate and multi-variate data.

10. Used Visualization for data filter for ancillary observation supporting the main observation

11. The cheap restaurant data is used for independent analysis

12. Subplots for Income group analysis and Pandas Query and Grouping was used extensively

** Non-technical Conclusion **


** Part 1 Bar coupon acceptance analysis **

The comparison of acceptance rate of driver who goto bar more than once, gives us similar results. The acceptance proportion is higher when the bar visit of the drivers is more than three.
Inferencing the data along with passanger indicates the likelyhood of acceptance is higher when the driver is alone or driving with a passanger such asfriend(s) are most likely to accept the coupon.
The acceptance rate is higher in warmer weather and the coldest weather is when takeout coupons are offered.

** Part 2 Cheap Restaurant acceptance analysis **

Acceptance rate for drivers is higher who go to the cheap restaurant with or without passangers when the desitnation is not urgent place and income of the driver is less than 50k accept the coupon.
Income higher than 50k has low acceptance rate in comparison.
