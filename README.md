# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends
## Overview of Project
### Purpose 
A woman named Louise wants to start a crowd-funding campaign to fund a play called Fever in the U.S. She has an estimated budget of about twelve thousand dollars. She wants to know what is the best way to apporach this project so my job is to analyze several thousand crowdfunding projects in order to help her determine factors that could lead to a successful campaign. 
## Analysis and Challenges 
Looking through the data I kept serval factors in mind, one was the budget and the other was location and time. The aim was to sort through the data to find projects that had simialr goals. Looking through the goal column indicated how much money each projected needed, the pledged column told me the amount that was actually obtained, the outcomes column told me if the campaign was a success or not, and finally looking down the country column told me the location. 
### Analysis of Outcomes based on Launch Date
Since Louise was intrested in a campaign fro theater, I filtered the data to only show theater campaigns. ![theater_outcomes_vs_launch](https://user-images.githubusercontent.com/100797549/159208146-b33e5852-4f56-4023-81f8-5a2da0c473fa.png)
Based on the line chart it was easy to determine that the months of May and June had greater success rates meanwhile July, August and October all had around the same number of failed campaigns. 
### Analysis of Outcomes based on Goals 
For a more defines visual, data was sorted to collect the outcomes and goals for plays since that is Lousie's primary reason to start a campaign. Looking at the line graph one can determine that the highest percentage of success was when the goal amount for a play was less than $1,000. Anything upwards of $40,000 was set to fail. ![outcomes_based_on_goal](https://user-images.githubusercontent.com/100797549/159209783-0e888864-300a-4be9-b83a-2d22fab8cae5.png)
### Challenges and Difficulties Encountered 
A problem I had encountered when sorting data was when I preformed calculations to find the average donation, Excel did not recognize the formuals output format. In order to debug this error and clean the data to present to Louise, I had to alter the formula. Since I was looking to find the average from the pledges and backers, not every cell had a campaign backer therefore it was counted as zero, and since numbers are not divisible by zero, I was prompted with an error in Excel. Luckly this error was eradicated. 
## Results 
The first conclusion that can be drawn about the Theater Outcomes by Launch Date is that the length of the fundraising campaigns is correlated to success, and the second conclusion that can be made is that Louise should launch her campaign aorund the end of May or beginning of June since those had the highest success rates. 
One conclusion that can be made from the Outcomes based on Goals is that Louise is aksing for too much funding in order to kickstart her campaign, she needs to lower her asking number. 
The limitation of this data set fails to answer the question as to why there are failed projects, if the failed projects were also getting a median pledge of about $3,000 but the median is much lower there may be another factor we cannot determine based on the data. 
My recommendation would be to include a bar chart that includes the most successful categories and how much funding those may require. As well as a graph that shows on average how many backers commited to a project and when, perhaps after tax refunds people are more generous. 
