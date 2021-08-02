# bikesharing

## The purpose of the analysis:
Is to convince investors that a bike-sharing program in Des Moines will be a successfull business to invest in. To solidify the proposal, we will analyze New York bike sharing program to give the investors a clear idea on how it can help Des Moines; having this analysis will help one of the key stakeholders be able to see it.

For this analysis, we will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, we will create a set of visualizations to:
- Show the length of time that bikes are checked out for all riders and genders.
- Show the number of bike trips for all riders and genders for each hour of each day of the week.
- Show the number of bike trips for each type of user and gender for each day of the week.

## Results:

#### There were over 2.3 million rides for the month of August in New York:
<img width="180" alt="NYC Number of Rides" src="https://user-images.githubusercontent.com/83566868/127803131-6308671b-2aad-4fd8-912a-4194d4eac959.png">

#### 81% (1.9 million) of the users were subscriber and 65% (443K) of the users were customers in New York:
<img width="450" alt="NYC Subscribers" src="https://user-images.githubusercontent.com/83566868/127803233-eb2c4798-cd63-4523-83c4-f9154ea43617.png"> <img width="472" alt="NYC Customers" src="https://user-images.githubusercontent.com/83566868/127803246-6bc74ae1-693b-4038-a50e-b883b26fca58.png">

#### Average duration of a bike rider, by age:
<img width="472" alt="NYC Customers" src="https://user-images.githubusercontent.com/83566868/127803419-9251c66d-f08a-45fb-9a40-2aced1d934b4.png">
The birth year relating to the data is telling us that younger tend to use the the service for longer rides.

#### Top sharing location happens to be in Manhattan:
<img width="816" alt="NYC TopSharingLocations" src="https://user-images.githubusercontent.com/83566868/127803649-3f832767-1a91-4c32-b8cc-81b6e16b7883.png">

#### Top ending locations also happens to be in Manhattan:
<img width="806" alt="NYC TopEndingLocations" src="https://user-images.githubusercontent.com/83566868/127803741-15412be5-13c3-42cd-965e-159c4bb228cb.png">

#### August Peak Hours:
<img width="797" alt="NYC AugustPeakHours" src="https://user-images.githubusercontent.com/83566868/127803795-c4aed3f6-5771-4f30-9536-1c40fd7d990a.png">
- Highest activity seems to be in the hours between 5:00pm to 7:00pm, which means it will require most units to be available.
- Lowest activity are in the hours between 2:00am to 5:00am, which means this will be the time window for any bike maintenance.

#### Bike Utilization:
<img width="644" alt="NYC BikeUtilization" src="https://user-images.githubusercontent.com/83566868/127804207-750c8369-aff8-4017-abb6-e91b1c9440a8.png">
This allowed us to view the total usage time per bike, which will give us insight into which bikes may need repairs.

## Summary:
This data showed us the activity of the bike sharing service for users in New York, August happens to be the month with the highest activity, therefore we felt this month was going to be the best month to show our analysis to our investors. Majority of the rides were in Manhattan, which allowed us to understand a deeper understanding as to why, and it simply was an alternative to public transportation. 

Future analysis can help us if we:
- comparing ride sharing differences in weekday and weekends
- comparing ride sharing differences between months

#### Weekday:
<img width="553" alt="Weekday" src="https://user-images.githubusercontent.com/83566868/127804904-c496b229-a683-48c6-af0f-f7d721a5e12e.png">

#### Different Month Examples:
<img width="258" alt="DifferentMonths" src="https://user-images.githubusercontent.com/83566868/127805171-f4dc567a-a8ee-4201-903d-499f59f98bfe.png">


Tableau link:
[link to dashboard](https://public.tableau.com/app/profile/molly6200/viz/bikesharing_16278802592450/NumberofRecords?publish=yes)
