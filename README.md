# Business-Intelligence-Dashboard-on-Ed-Tech-Data-2011-2013
Tableau Link : https://public.tableau.com/app/profile/amit.kumar.ray/viz/BusinessIntelligenceDashboardonEd-TechData2011-2013/Dashboard1
The data have total of 9447 rows and 20 columns initially. Some of the columns are repeated with string format. We can delete those columns.
We can drop discount_price__currency and price_detail__currency as all discount and price have same currency i.e. INR.
We tood the difference between Publish_Date_Time and Created_date_time and drop the data whose difference is less than 0
We changed date time to only date and created one extra column for Year.
We create a bin for Ratings and see that Number of subcribers per rating bin. We create a bin for Ratings and see that Number of Reviews per rating bin.
