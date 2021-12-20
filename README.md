# Kickstarting with Excel

## Overview of Project
My client, Louise, is an up-and-coming playwright who is using the crowdfunding platform, Kickstarter, to fund her latest project.
Her campaign is off to a successful start, but she is interested in seeing how similar projects have fared in relation to their launch dates and funding goals.
This project will need to utilize Kickstarter data to identify projects that are similar to Louise's campaign.
Additionally, this project will need to analyze how launch date and funding goals are related to a campaign's ultimate success or failure.
I will provide a Pivot Table, Data Table, and Two Line Charts to help Louise visualize this information. 

### Purpose
To visualize how launch dates and funding goals affect the ultimate success or failure of Kickstarter campaigns that are comparable to Louise's campaign. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The following Pivot Table has been created to analyze how a campaign's success is affected by its launch date. This table specifically analyzes campaigns in the Theater parent category: 

![Theater Outcomes by Launch Date - Challenge](https://user-images.githubusercontent.com/93888037/146707595-7025b82e-4dfc-42bc-b1a2-ebb209a69589.png)

Campaigns are most successful in May and June. However, this is also when the most theater campaigns are launched. 
The number of failed campaigns is fairly consistent throughout the year. The rate of failure is particularly high in October, where about 43% of projects fail, or in December, where about 47% of projects fail.

This is the line chart created from the Pivot Table. It shows that the most successful campaigns are launched in May and June, while the least number of successful campaigns are launched in December.
January has the highest amount of canceled projects, which is consistent with the idea that fundraising is the most difficult in December. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/93888037/146707638-a3b1f618-6c18-448d-87ad-8066937c3bb9.png)

### Analysis of Outcomes Based on Goals
The line chart below visualizes the percentage of failed, successful, and canceled campaigns for plays based on their goal amount. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/93888037/146707651-b1439df2-9334-4a8f-aab5-8b9711c3795e.png)

When the Kickstarter results were filtered by subcategory, no play campaigns were listed as canceled. Our focus can shift to play campaigns that were succesful or failed. 
76% of play campaigns with a goal of under $1000 were successful. However, the percentage of successful campaigns does not decrease significantly when the range is adjusted to $1000-$4999. This indicates that there is very little difference in outcome between a project under $1000 and a project between $1000-$4999.
Additionally, the rate of success does not change much between these three goal amounts: $5000-$9999, $10,000-$14,999, and $15,000-$19,999. Each of these goal amount ranges has a rate of success between 50%-55%.
While projects from $20,000-$24,999 are about 45% successful, there is a large decrease in the rate of success when the goal amount is increased to $25,000-$34,999.
There were only 2 total successful projects with goal amounts over $45,000. 
The rates of failure are particularly high in these goal amount ranges: $25,000-$29,999; $30,000-$34,999; and Greater than $50,000.
The goal amount of $45,000-$49,999 only included one project, and that project failed.

### Challenges and Difficulties Encountered
One challenge related to this data set is the various parent categories and subcategories available. For example, my Pivot Table and initial line chart (by launch date) is filtered by the parent category of Theater. However, the second line chart and data table (by Goal Amount) is filtered by the subcategory "play."
When analyzing and visualizing data for Louise, it would be important to clarify how the results might vary based on the subcategory. Particularly because the theater(spaces) subcategory has very different data than theater(plays). If I were to attack this challenge again, I might add a subcategory filter to the Pivot Table and line chart that visualizes project success based on launch date. 

When calculating the data, it was difficult to input the COUNTIFS formulas for each goal amount range. Ensuring that each comma, quotation mark, dollar sign, and inequality symbol was correct was time-consuming, but ultimately vital to the overall project. However, I was able to complete the task and after a few rows, the formula became easier and easier to perfect.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Projects launched in May or June have the best chance of being successful.
2. Projects launched in November or December carry the most risk and have the highest chance of failure.

- What can you conclude about the Outcomes based on Goals?
1. Projects with goals equal to or less than $4,999 have the highest rate of success.
2. There is very little difference in the rate of success for projects in these goal amount ranges: $5,000-$9,999; $10,000-$14,999; and $15,000-$19,999. 
3. Projects with these goal amount ranges carry the highest risk for failure: $25,000-$29,999; $30,000-$34,999, Greater than $50,000. 

- What are some limitations of this dataset?
1. Some goal amount ranges have extremely limited data. For example, there was only one play campaign launched with a goal amount of $45,000-$49,999.
2. Because this dataset includes international campaigns, we may see very different results if we filtered by country. Even once filtered by country, we can't filter by city. More specific locations could have very different campaign outcomes. For example, I would predict that a play campaign in Greenville, North Carolina might be less successful than a play campaign in a larger city like Raleigh, North Carolina. However, I would predict that a play campaign in Manhattan or Los Angeles might see a lower rate of success because of the number of actors, directors, and playwrights that might be looking for funding in that area.
3. This dataset does not reflect marketing for the campaign. The method of sharing the campaign would have a significant impact on whether or not a campaign was successful or not.

- What are some other possible tables and/or graphs that we could create?
1. I would be interested in creating a Pivot Table that lists the number of successful play projects by goal amount and then filters for country. I would be interested to see how goal amounts affect overall outcome in various countries.
2. I think it would be worthwhile to visualize how the length of the campaign is related to the outcome of the project. How long do projects generally take to be successful?
3. For Louise's purpose in particular, she would need a visualization of the number of play campaigns that were successful by launch date. Filtering only by the parent category, theater, is not specific enough for her project. Funding a theater space in particular seems like it would be a very different campaign than funding one production.

