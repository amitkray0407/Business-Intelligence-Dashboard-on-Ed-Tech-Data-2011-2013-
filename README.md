# Business-Intelligence-Dashboard-on-Ed-Tech-Data-2011-2013
Tableau Link : https://public.tableau.com/app/profile/amit.kumar.ray/viz/BusinessIntelligenceDashboardonEd-TechData2011-2013/Dashboard1
The data has a total of 9447 rows and 20 columns initially. Some of the columns are repeated in string format. We can delete those columns.
We can drop discount_price__currency and price_detail__currency as all discount and price have same currency i.e. INR.
We took the difference between Publish_Date_Time and Created_date_time and dropped the data whose difference was less than 0.
We changed the date time to only date and created one extra column for Year.
We created a bin for Ratings and see that Number of Subscribers as per rating bin. We created a bin for Reviews to see the Number of Reviews per rating bin.
