# tableau-challenge

### Background
Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the Citi Bike Data webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program.

### Challenge
The challenge is to build a set of data reports to provide the answers to some of the below questions and complete the following tasks.
* Aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.
* Design 2-5 visualizations for each discovered phenomena (4-10 total). You may work with a timespan of your choosing. Optionally, you may merge multiple datasets from different periods.
    * 1 City Official Tableau Map
    * 2 Tableau Dashboards
    * 1 Tableau Story Board
* A text or markdown file with your analysis on the phenomenons you uncovered from the data.

### Considerations
Remember, the people reading your analysis will NOT be data analysts. Your audience will be city officials, public administrators, and heads of New York City departments. Your data and analysis needs to be presented in a way that is focused, concise, easy-to-understand, and visually compelling. Your visualizations should be colorful enough to be included in press releases, and your analysis should be thoughtful enough for dictating programmatic changes.

### Data
* [Citi Bike Data Link](https://www.citibikenyc.com/system-data)
* Tableau Workbook file labelled: "*CitiBike-Insights 2019 vs 2020.twbx*"
    * Note: Need Tableau Desktop app to open

## Analysis Write-Up
_____________

### Summary
This project seek to share insights taken from a 6-month span in 2019 and 2020 through visualizations and data surrounding the Citi Bike's of New York. The hope is to answer the following series of questions:
* Who is using the bikes? (User Insights)
* When are the bikes being used?
* How much are the bikes being used? (wear & tear)

### Data Considerations
Due to the *Big Data* encountered in this analysis 6-month periods from each year was extracted for analysis. This analysis took place at the start of November 2020. This is why the months are offset.
* 2019 - month range (July - December)
* 2020 - month range (May - October)

### Visualizations

#### CitiBike Locations & Popularity 2019 (Jul - Dec)
This Map is highlighting the most popular CitiBike locations in New York as taken from the six-month 2019 dataset. As the size of the ciricle increases this represents the (sum) trips taken. 
#### Phenomenon Insights
* Most popular station displayed is *Perishing Square North* at 84K total trips. This would be interesting to look at the surrounding envirnment to see if conclusions can be drawn why the popularity. By visually looking at the image below some noteworthy buildings are in close proximity.
![Perishing Square North](/resources/images/Perishing-Square-North.png)
* The 2nd most popular station displayed is *E 17 ST & Broadway* at 72K total trips.
![E 17 ST & Broadway](/resources/images/E-17-St-Broadway.png)

#### Total Bike Trips Throughout the Day
This visualization takes the 6-month data sets and shows the total bike trips taken during each hour of the day.
#### Phenomenon Insights
The 2019 visualizations shows what someone would expect when looking at bike usage. There are spikes in usage during commuter hours (morning & evening).
![total-bike-trips-2019](/resources/images/total-bike-trips-2019.png)
As we expect 2020 data looks a bit different with a drop during the start of the day, but still heavy use in the evening.
![total-bike-trips-2020](/resources/images/total-bike-trips-2020.png)

#### Total 
#### Phenomenon Insights