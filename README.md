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

[Kickstarter_Challenge.zip](https://github.com/purvishjd/kickstarter-analysis/blob/main/Kickstarter_Challenge.zip)

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
