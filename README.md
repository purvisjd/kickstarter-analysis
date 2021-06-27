# Kickstarting with Excel

## Overview of Project
The purpose of this project is to assist up and coming playwright, Louise, with establishing a successful Kickstarter program for play by comparing it
to similar Kickstarter campaigns.  Raw data has been obtained of a sample of Kickstarter campaigns comprising multiple categories and project types.
This information has been organized, sorted, and analyzed to identify potential factors that can influence a given program's success.  Trends were 
identified to assist Louise with identifying similar programs and "mirroring" those that have shown to be successful.

## Analysis and Challenges
Raw data was obtained and then focused to reflect four primary factors in order to be more applicable to Louise's identified goals:  Kickstarter programs 
that were focused on theater, specifically plays, the identified goals and pledges of those programs, the timeframe given to the campaign, and the ultimate
outcome (success vs failure) of those campaigns.  Utilizing these categories of information, it was possible to identify specific inlfuential factors for 
campaign succcess.

The data obtained from Kickstarter was loaded into an Excel spreadsheet (Kickstarter tab).  The information on this tab was sorted and further clarfied
by separating the categories into both parent and subcategory, as well as converting the Unix timestamp into a readable format.  

[Kickstarter_Challenge.zip](https://github.com/purvisjd/kickstarter-analysis/blob/main/Kickstarter_Challenge.zip)

### Analysis of Outcomes Based on Launch Date
To isolate the information that would be most pertinent to Louise's project, 2 additional tabs were created to make isolating the desired data easier. On 
the Theater Outcomes by Launch Date tab, a pivot table was created that would demonstrate the number of successful, failed, and canceled theater Kickstarter 
campaigns based on the month in which they were launched.  A filter is also included to allow further evaluation based on the specific year rather than
the entire range provided in the raw data set.  A line chart was also created to provide a visual representation of the success, failure, and cancellation
rates based on the launch date.

[Theater_Outcomes_vs_Launch.png](https://github.com/purvisjd/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
In addition to the analysis based on launch date, an additional table was created on the Outcomes Based on Goals tab in which the data was further focused
on Plays specifically as a subcategory.  Goals were broken into defined ranges and the information was categorized based on the number of successful,
failed, and cancelled within each range.  This data was then further calculated to show percentages as to the success, failure, and cancellation rates.
To provide further visual representation of this breakdown of information, another line chart was created to demonstrate the percentage of 
successful, failed, and cancelled based on the goal set for the campaign.

[Outcomes_Vs_Goals.png](https://github.com/purvisjd/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Only minor challenges were encountered with regards to analyzing this specific dataset.  Certain columns of information had to be re-formatted into 
something that would be more easily readable (Unix datestamp specifically).  Additional calculations needed to be added to the dataset in order to 
appropriately demonstrate the requested data.  If this information is not calculated properly, it could significantly skew results and ultimate analysis.

## Results
Two specific conclusions can be drawn from this data as it currently stands.  When viewing the Outcomes Based on Launch Date, there appears to be a 
trend of a higher potential for success for those campaigns that are launched during the second quarter.  This correlation would indicate an increased
likelihood for future campaigns that are launched during that timeframe.  Also noted was that the rate of cancellation does not appear to be significantly 
impacted by the launch date with the exception of the months of April and July.  Further analysis would be required in order to identify specific reasoning
for this observed result.

The Outcomes Based on Goals evaluation provides additional useful information regarding the potential for success.  Significantly higher success rates 
were observed with 2 specific categories of goal ranges; those that were less than $5000 and those between $25,000 and $35,000 appear to have significantly
higher success rates with Kickstarter campaigns.

It must be noted that there are limitations to this dataset.  It is reasonable to conclude that this data does not represent all Kickstarter campaigns 
that have ever been created and we are, therefore, looking at a sample dataset.  Whenever you are looking at a sample, you have to take into consideration
the inherent limitations that this represents and the possibility of not having data that may have a significant impact on outcome and analsysis. 
Further, in order to be able to draw more accurate comparisons to the requested data, further analysis would need to be done on Plays as a specific subset
as the type of theater can have a significant impact on outcomes.  An additional pivot table showing a comparison of plays versus musicals would have 
been able to provide significant assistance with determining what type of theater has the highest demonstrated potential for Kickstarter success
with a bar graph providing a visual representation of that comparison.  An additional line graph could also be created to demonstrate trends
over years of time to see if certain subcategories have been more successful in the past and which ones may be trending more successful now.  Also, 
since this is an analysis of a category typically considered a "luxury", it would be prudent to also include an analysis of socio-economic factors of the 
given timeframes that may have had a significant impact on outcome.


