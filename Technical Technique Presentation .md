# Technical Technique Presentation Proposal

## Introduction
-----------------------------------------------------------------------------
Data Wrangling - A step in the data analysis process that finally allows data scientist to become the cowboy they've always wanted to be. They're required to 'wrangle' up the data with a plethora of techniques. In this technical presentation, I will be going over wrangling data in from the 'Time' formats. Sometimes when beginning a data analysis journey, we can stumble across all types of date & time formatting within datasets. An easy to use function that can turn any date/time column into a desired format with whatever output columns you desire, would be really cool. Unfortunatley I won't be able to do that.. BUT I will be able to show you some techniques for specific Time data wrangling situations.

Data wrangling is crutial in the data analysis process. Importance is so high because data quality ensures accurate, consistent, and error free data. Without following necessary data wrangling protocols to clean the data, this leads to the data being more difficult to work with. Having data that is reliable will lead to gaining reliable information. As the old saying goes 'Garbage in, Garbage out.', implying if you work with garbage, your end product will most likely also be garbage. So wrangle your data, kids!

Objective is to show the viewer some methods in converting date and time columns. There is a lot of different ways to do so, but I will only be covering a specific instance. I will be demonstrating a function that splits data columns into desired column. I will go into more detail in the coming sections.

## Background
-----------------------------------------------------------------------------
Converting Date and time functionality is (in my opinion) actually okay. Date has more functionality than time, from what I have seen (which is not much), but still okay to say the least. It is far from perfect, but it works with functions in Pandas like to_datetime. They are able to make date conversions easily. The biggest challenge for this topic is the endless possibilities that dates can be provided. Anything from YYYY-DD-MM to DD-MM-YY. Also when there is little to no documentation or indication of which number is which, challenges can arise quickly. There is no perfect function (yet) that can fix all date/time conversions. I wish I could come up with that. But I am going to try to come up with something that works for myself an my own data sets.

## Presentation Candidate
-----------------------------------------------------------------------------
My name is Joey Ramsay. I have my bachelor's degree in Business Administration, majoring in Enterprise Systems. My education provided me with an array of knowledge from training in SQL, basics in database deisgn, and enterprise (IT) management strategies. I have worked professionally as an entry level ABAP Programmer for IBM, and as an IT Analyst for IMP Solutions - before deciding to return to NSCC to further my education.

Although my education and experience involved a number of IT topics, nothing has prepared me for data wrangling. I had vaguely heard of it before attending NSCC, but had no idea how important it really was. It is an endless beast that can be tackled a hundred different ways. I am very excited to take a deeper dive into this topic, as I know it will assist me further along in my career. 

## Sample Data Selection
-----------------------------------------------------------------------------
My sample data set I will be using an airline datasets from my previous Business Intelligence presentations/assignments. The columns I am specifically focusing on are the TIMES, not the length of flight, but scheduling times like Departure, Wheels off, arrival, etc. The data is recorded in 24 hours, as all flight data is. Which is fine for some instances, but for my particular situations, I needed to convert the time to the basic 12 hour clocks. Prior to this section of our course, I did that in SQL, with a little manual coding for each column. Now I want to remove that work and streamline it for a pipeline of future data. This gives me a perfect opportunity to apply the skills I have learned throughout more recently in this course.

## Technical Technique Demonstration
-----------------------------------------------------------------------------
The technique is going to be a function that effectively and easily convert the dates to a format that can be changed to a 12 hour clock. For example in column scheduled departure, there is a value 403 which means 4:03am, 1547 means 3:47pm, etc. I am going to make a function that does that conversion automatically. Steps will include defining the function, calling the function, and passing the desired, dirty time columns into the function. Then the results will be able to be pushed back into the parent dataset. Wrangling timestamps is normally a unique situation, and should be handled on an event to event basis. Hopefully this function can help myself down the line of my career.

## Implementation Plan
-----------------------------------------------------------------------------
To implement this type of a project, I need to do one thing - Practice. My function skills are not the best, and this is a perfect opportunity to improve on that. Which is one reason why I am happy to be in team Wrangling. Over the coming weeks I will have to take a deep dive into learning existing methods to parse out times, to see if I can discover any better methods. Advance my current knowledge of date/time functions, to allow me to generate something functional and useful.

## Conclusion
-----------------------------------------------------------------------------
To conclude, I will be focusing on the conversion of time from something that looks like an integar, to a standard timestamp. Cleaning and seperating the data to the desired format will allow me to use this function in the future and allocate time elsewhere. The solution will be able to identify and ammend any erros or invalid times. This fucntion will hopefully make everyones lives involved easier.

## Appendices
-----------------------------------------------------------------------------
- References to technical literature
https://www.coursera.org/articles/data-wrangling
