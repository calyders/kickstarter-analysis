# Kickstarting with Excel

## Overview of Project

### Purpose
- The purpose of this analysis was to find how other campaigns, namely plays, in the Kickstarter sheet performed and how that relates to both their launch dates and their funding goals. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
    A line chart was created to visualize the relation between launch date and the outcome of exactly 1,369 plays. The possible outcomes were successful, failed, and canceled. According to the chart, the time between the months of April and August have the highest number of successful plays. May in particular has the highest number of all the months. However, likewise, these months also have the most failed plays. While there are consistently less failed plays than successful plays throughout the year, they follow the same trends as well, rising and falling in numbers at the same times throughout the year, more or less. The only time where there is a difference would be in December, where the number of failed plays rises while the number of successful plays falls. This increase in both successful plays and failed plays in the summer months is due to an increase in plays being released at that time, creating more data to calculate. However, the fact that successful plays have a bigger spike than failed plays do in the summer months suggests that this would be the best time to launch a play. This most likely is due to more individuals leaving the house at this time, encouraged by nicer weather.
### Analysis of Outcomes Based on Goals
    In regards to the goals of each of these plays and their outcomes, another line chart was used to show the percentages of successful, failed, and canceled plays based on their goal revenue. This data proved to be a little bit harder to decipher, as the percentages fluxuate quite a bit throughout the chart. Starting at goals less than $1,000, the success rate is 76% while the fail rate is 24%. However, from this point, as the goal gets higher, the success rate drops and fail rate increases. At a goal revenue of $25,000-$30,000, fail rate is at %80 and success at %20. The data then fluxuates again, with success rate reaching 67% again between $35,000 and $45,000, and fail rate being 33%. One last time, the data fluxuates, and ends at $50,000 or more with a success rate of 13% and fail rate of 88%. One factor that should be taken into account though with this data is the number of plays in each of these sets of goals. There is considerably more data for plays with smaller goals, reaching 534 in total for plays with goals between $1,000 and $4,999, while there are only 16 total plays with goals over $50,000.
### Challenges and Difficulties Encountered
    In terms of using Excel, the only problem I ran into was in the first step with creating the Years column. At some point I had changed the format to Short Date for the Years column, which made the numbers it gave me incorrect. It took me sometime to realize I needed to change the format back to General in order for the =Years formula to work correctly and give me the year in each cell of that column.
    The only other difficulty was just trying to read the data provided by the charts and decipher what they meant.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    One, it is better to launch in the spring and summer months, prefereably May, as that is where the highest number of successful plays is shown in the data.
    Two, most plays launch in May and June, which may have scewed the data in the favor of that month and can also mean more competition for someone thinking of releasing a play at this time.
- What can you conclude about the Outcomes based on Goals?
    For better chances at a successful play, it is best to stick to a lower goal, preferably between $1,000 to $5,000 if you want more than a %50 chance.
- What are some limitations of this dataset?
    Like I said above, there is a lot more data for plays with smaller goals than for plays with bigger goals, meaning it is harder to know how successful a play with a higher goal actually is.
    The data for launch dates is also scewed, as there are significantly more plays being launched in the months of May and June, meaning more chances for successful plays but also more chances for failed plays.
- What are some other possible tables and/or graphs that we could create?
    I think that a table or chart comparing pledges, launch dates and outcomes would provide some interesting insight. Does launch date change the amount that is pledged?