# An Analysis of Kickstarter Campaigns
Module 1 - Working with Kickstarter Campaign Data to Perform Analysis and Discover Trends

## **Overview of Project**

### **Purpose of Project:**

Louise wants to start a crowdfunding campaign for her new play "Fever". She has an estimated budget of over 10k. 

We are using the Kickstarter Crowd Funding dataset to visualize past  theater and play campaign outcomes to determine the best launch date and goal funding amount for Louise to launch a successful campaign for her new play "Fever".

## **Analysis and Challenges**

### **Process of *Analysis of Theater Outcomes Based on Launch Date*:**

We started by adding a "Year" column in the Kickstarter dataset so that we can add a filter for year when reviewing best launch months. Next, we created a pivot table reviewing the count of outcomes per month. We also added a filter on parent category and year to reiew specific outcomes per year and category. We created a line chart to visualize the outcomes. Reference [Theater_Outcomes_vs_Launch](https://github.com/corispade/Module-1-Kickstarter-Campaign-Data/blob/main/Resources/Theater_Outcomes_vs_Launch.png).

When reviewing the data, the greatest number of campaigns were run during the summer months of May, June and July, so we saw the highest amount of successful and failed theater campaings during these months. 

I added a column for percentage successful, percentage failed and percentage canceled for better analysis of launch date. There is a higher probability that the theater campaings will be the most successful in the months of May and June. 

### **Process of *Analysis of Play Outcomes Based on Goals*:**

We created a chart on a separate tab to analyze the play outcomes based on the dollar goal amount. We categorized goal amount into ranges to determine outcome vs goal amount by range. We then calculated percentage of success, failure and cancelation based on the dollar goal amount. We created a line chart to visualize the outcomes. Reference [Play_Outcomes_vs_Goals](https://github.com/corispade/Module-1-Kickstarter-Campaign-Data/blob/main/Resources/Play_Outcomes_vs_Goals.png).

When reviewing the data, the percentage of successful and failed play campaigns varied by goal funding amount. No plays campaigns were canceled. The most successful play campaigns had a goal funding amount less than $15000. The least successful and most failed campaigns had goal funding amounts $40000 to $50000.

### **Challenges Encountered During Analysis:**

I came across challenges with formatting. I created a table from the existing data before I finished adding all the necessary data columns. The data colums that I attempted to add at the end of the table did not get included in the pivot table data set. I had to scrap the table and create a new table with the added data points. 

## **Results**

### **Two Conclusions Drawn About the *Theater Outcomes Based on Launch Date*:**

- There is a higher chance of success and lower chance of failure if Louise launches her play "Fever" in the month of May than any other month. 

- There is a higher chance of failure and lower chance of success if Louise launches her play "Fever" in the month of December. 


### **Conclusions Drawn About the *Play Outcomes Based on Goals*:**

- Louise's estimated budget for "Fever" is over $10000. Based on the data, the most successful campaings had a goal funding amount less than $15000. There is a greater rate of success, the lower the cost of the goal funding amount. 

- For Louise to have the most success, I would suggest she does not exceed a $10000 budget. 

### **Limitations of this Dataset:**

We did not take into account the location or year for "Theater Outcomes Based on Launch Date" or "Play Outcomes Based on Goals". The results may vary by year depending on the economy and what is happening in the world. Maybe there is a pandemic and people are unable to attend the theater. The results may also vary by location depending on the most or least popluar countries for plays to be successful. It would be even more helpful to filter down to city.


### **Other Possible Tables and Graphs Potentially Created:**

1. We can get more specific and include data for what types of plays are the most successful (example: comedy, action, romance, horror, etc.). I would create another row of data on the Kickstarter Data set table to determine a second subcategory of "Play Category". We can use a bar chart to visualize the data. This way Louise can see what location, launch date and funding amount is the most acceptable for her play category.

2. We can create a pivot table to view play or theater outcomes by country. We can use a stacked bar chart to analyze the data. Based on this information, theaters and plays both had the most success in US and GB. With a higher probability of success in GB. Reference [Theater_Outcomes_by_Location](https://github.com/corispade/Module-1-Kickstarter-Campaign-Data/blob/main/Resources/Theater_Outcomes_by_Location.png).

3. We can filter by year to determine the best month to launch the play campaign. Filtering the data by years 2015-2017 only, the success rates drop drastically from the months of June to December, when comparing to all years combined. Reference [Theater_Outcomes_vs_Launch_2015-2017](https://github.com/corispade/Module-1-Kickstarter-Campaign-Data/blob/main/Resources/Theater_Outcomes_vs_Launch_2015-2017.png). To have the most accurate analysis, I would suggest to use the most updated data and line chart visual for years 2015-2017 to determine the most successful months for the launch of Louise's "Fever". 
