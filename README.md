# NYC Citibike Analysis

### MD14 - Citibike analysis

### OVERVIEW

Purpose: The purpose of the current analysis is to prepare visualizations that give potential investors a look into the highly-successful NYC Citibike bike-sharing program, so that they can see for themselves that a bike-sharing program in Des Moines is a solid business proposal. Among others, we have prepared visualizations that 1) Show the length of time that bikes are checked out for all riders and genders, 2) Show the number of bike trips for all riders and genders for each hour of each day of the week, and 3) Show the number of bike trips for each type of user and gender for each day of the week.

---

### RESOURCES

 1. Source Files  : 201908-citibike-tripdata.csv, 201908-citibike-revised_tripdata.csv
 2. Software      : Tableau, Python 3.7.6, Jupyter NB, Pandas Library
 3. Link          : https://public.tableau.com/views/Challenge1MD14/NOOFRIDES?:language=en-US&:display_count=n&:origin=viz_share_link


---

### RESULTS

The results of our analysis have been incorporated into a story on Tableau Public

POINT #1 - Comparing visualizations for the 'Top Starting Locations' and 'Top Ending Locations', we can see that the most active starting locations are also among the most active ending locations. This is important, because we need to know whether there might be an excess or shortage of bikes at particularly stations over time.

<img width="982" alt="Screen Shot 2022-06-18 at 1 05 33 AM" src="https://user-images.githubusercontent.com/98849217/174423630-b375c75c-0467-42de-b44f-f9dc57ade82a.png">


POINT #2 - Looking at visualizations for 'Checkout Times for Users' and 'Checkout Times by Gender', we see that most rides are for 20 minutes or less, and that the vast majority of rides are less than one hour. We also see that this pattern is the same regardless of gender.

<img width="965" alt="Screen Shot 2022-06-18 at 1 06 16 AM" src="https://user-images.githubusercontent.com/98849217/174423651-7f381c09-a55b-47c2-8bf2-139265c2bd12.png">

POINT #3 - The heatmap of 'Trips by Weekday per Hour' shows a clear pattern of bicycle useage 1) during the morning weekday commute (7-9 a.m.), 2) during the evening weekday commute (4-7 p.m.) except on Wednesday evenings, and 3) all day long on weekends.

<img width="598" alt="Screen Shot 2022-06-18 at 1 08 07 AM" src="https://user-images.githubusercontent.com/98849217/174423702-022613b0-7237-4311-a094-f328c0cb6ef5.png">

POINT #4 - The 'Trips by Gender (Weekday per Hour)' heatmap shows that the useage pattern is true regardless of gender, although the total numbers for males is considerably higher.

<img width="982" alt="Screen Shot 2022-06-18 at 1 08 35 AM" src="https://user-images.githubusercontent.com/98849217/174423713-a159544a-b3b0-4d81-8e13-e1b8a4ad95c7.png">

POINT #5 - The 'User Trips by Gender by Weekday' heatmap demonstrates the following points: subscribers are mostly male and account for most of the weekday activity, customers' gender are often unknown, and useage on the weekend is more evenly split between subscribers and customers.

<img width="972" alt="Screen Shot 2022-06-18 at 1 09 20 AM" src="https://user-images.githubusercontent.com/98849217/174423727-7c55e169-ceb6-4728-996a-7ab6ce902fde.png">

SUMMARY

The results of this analysis have given insight into the utilization of bicycles in the NYC Citibike bike-sharing program. We've seen the patterns of useage by time and by gender. Utilization rates can now be predicted based on time of day and location. Weekday useage is heavily concentrated around the morning and afternoon commute. Weekend useage is more evenly spread through the day. We would recommend further analysis for a few points. Firstly, while we've seen that the vast majority of trips are 30 min or less, we should perform further analysis to compare weekend trip durations to weekday trip durations. We should also look further into the patterns of useage for the bicycles that see the heaviest use, perhaps preparing maps showing all of the starting/ending routes/locations for the heaviest use bikes. We should also prepare a visualization to determine if there are specific locations that are completely unused.

