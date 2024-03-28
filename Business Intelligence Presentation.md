# Business Intelligence Presentation Proposal

## Introduction
---------------------------------------------------------------------
- Overview of the business intelligence topic
> Business Intelligence topics are: ETL/SQL Data model, Data Visualization/Dashboards, and Predictive Analytics.

For my final BI presentation, I will be focusing on the following topics from our allowed list: ETL/SQL Data model, Data Visualization/Dashboards, and Predictive Analytics. I'll use these topics to create somewhat of a 'pipeline' for my data. This hypothetical pipleine will be displaying skills I have learned throught the entirety of the whole course. Beginning with the ETL/SQL modelling, transforming the data in MSSQL to have a clean, de-normalized reporting schema. Then using the schema to construct a useful dashboard to visually look at trends of car prices. Finishing with a small predictive analytical analysis of the data set, which can help predict the price of a car if someone is looking to receive a quote on their car.

- Significance of data-driven decision-making
The significance is with creating a tool as the one I described above, I can predict the future value of cars. If I was in the market for a new car, I could use this to help me determine the best deal. This type of model is extremely interesting to me, even though this will not be the most complex predictive model, it is an amazing starting point to allow myself to dive much deeper into the topic over my (hopefully) long career. 

- Goals of the presentation
The goal of the presentation is to not only demonstrate the skills I have learned in this course, but also how to apply those skills to an array of datasets/situations. It is also a great tool for me to tidy up and focus on some skills that I need some help with. For example I have felt a little behind in the predictive analystical topics we have covered, so I need to improve my understanding of that. And from your teachings, there is no better way to improve at something than to practice repeatedly. 


## Presentation Candidate
---------------------------------------------------------------------
My name is Joey Ramsay. I have my bachelor's degree in Business Administration, majoring in Enterprise Systems. My education provided me with an array of knowledge from training in SQL, basics in database deisgn, and enterprise (IT) management strategies. I have worked professionally as an entry level ABAP Programmer for IBM, and as an IT Analyst for IMP Solutions - before deciding to return to NSCC to further my education.

I do not have as much experience with BI tools as I would like - which is the main reason why I'm in this program. During my time in University, Tableu was at the height of its popularity, and we used that for a few courses. I remember loving Tableau and it's functionalities, the software helped me discover a passion for Business Intelligence. The visualization of data and helping portray the data's story is extremely rewarding for myself. I knew when I moved on from UNiversity Business Intelligence was a field I wanted to work in.

Working at IBM, the minimal BI experience I gained was from the Business/Data warehousing of SAP work I did. I didn't gain much technical skills from that, due to my short tenure, but my understanding of data warehousing and how important it is really stuck with me. Sadly, I did not gain much of any BI experience while at IMP. The role was more IT support and I was focused on helping end users. But on the flip side, I learned so much in regards to IT management, networking, and troubleshooting, that I know has helped me through this course on the daily.


## Data Selection
---------------------------------------------------------------------

My data is focused on used Car sales throughout the USA. I will be honest, before I decided on this type of dataset, I was debating on using a sports gambling dataset with March Madness odds. But I didn't know the schools policies on gambling, and didn't want to step on any toes. Furthermore, After some research, I found that the precitions I was looking to make were a little to advanced for my skill level at this time. I don't want to bite off more than I can chew for this project, so I decided on a my new dataset - car sales.

There is an endless amount of sources for this type of data. I spent a considerable amount of time trying to pick the right one. I listed all of the potential sources (urls) below. I had some troubles finding a data set that had a timeline from before the COVID-19 pandemic to after. So for now I am gathering 2 datasets, the first from 2015 and the second from 

## Business Intelligence Techniques Demonstration
---------------------------------------------------------------------
The selected BI techniques I will be focusing on will be as follows: 
- Data Visualization/Dashboards
- ETL/SQL Data model
- Predictive Analytics
- Python Data modelling (maybe)

Application & Insights:
- Data Visualization
    > IF Airlines: Through this course I have always used the same data set. I consider this deliverable the 'Final Boss' in my visualization adventure while at NSCC. I Will have an improved map displaying the flights, directions and (relative) flight path. The map will be on top of a well constructed dashboard focusing on trends in the data with basic bar charts, line/scatter plots etc.
    
    > IF Cars: Try to have a nice Bar chart that displays the car or the car manufacturers logo on the bar chart.
    *** Could drop visualization portion for cars. ***

Insights: 
    Airline - Clearly see the trends and patterns in flights per airline. Visaully see the high traffic flight areas.

    Car Sales - View all the difference in sale prices, state registration and sellers across all cars models and makes.

  

- ETL/SQL
    > For BOTH possible data sets, they come in relativeley flat files. To report on the data it will need to be cleaned and formatted. Taking the data from its raw CSV to a completed, normalized (or denormalized for reporting) database schema. 
    > Airlines: multiple tables to create, have CSV for some dimensions.
    > Car Sales: Will need to create hierarchy of cars make, model and trim. Also had some data incorrectly input, need to fix.

Insights:
    BOTH - Data needs to be formatted, for number of columns of date and time. Possibly be able to identify duplicate records during the process.


- Predictive Analytics
    > Have not yet decided the model or method. But ideas so far:
    > Airlines: Predictive model that shows airline most likely to have delay (maybe greater than a min limit)
    > Car Sales: Model to predict the price of cars for future upload. If someone inputs a car the website can give reccommended price. Based on attributes like year, mmr (historical?), odometer, 

Insights:
    Airline - Predict the delay times for airlines for certain flights??
    ***** Something I need to ask Pat for help with. Not sure where to go with this. ******

- Python Data modelling (maybe)
    > Thought maybe this was the same thing as the ETL/SQL as in it has the same objective; to have cleaned efficient data model/set.
    > Would probably involve a lot of EDA or something along those lines.

Insights:
    BOTH - Similar to the ETL/SQL except here able to perform and visualize an extremely useful EDA. Displaying trends in the data easily and concisely.


## Implementation Plan
---------------------------------------------------------------------
- Schedule for the development of the presentation
    > My plan is already in motion. As I have been trying to get the data structured to my liking as this proposal is being worked on.
    > Complete data cleaning by this weekend sometime (MINIMUM). And then next week beging diving into creating the best airline dashboard ever. 

- Necessary resources (BI tools, datasets, etc.)
    > Will be using power BI to create the report.
    > Cleaning data with combination of python and Power Query.
    > Structure tables with MSSQL
    > Data sets are both from Kaggle
- Rehearsals and feedback sessions

## Conclusion
---------------------------------------------------------------------
- Recap of the expected contributions of the presentation
- Encouragement for audience engagement

## Appendices
---------------------------------------------------------------------
- Bibliography of business intelligence literature
- Resources for additional learning and exploration
