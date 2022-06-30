# Kickstarting with Excel

## Overview of Project

### Analyze a set of data from a crowdfunder, Kickstarter, using descriptive statistics to show a trend on graphs (line, bar).

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

- Used the data from the "Kickstarter" Worksheet and made a Pivot Table in a new tab.
- The Pivot Table was filtered by Parent category, the columns represented the outcomes, the rows were the date created by months and the values in the table of the count of outcomes.

![Pivot Table](https://1drv.ms/u/s!AkcEaWONZ7eSkXzqzRe1LyrIIxZh?e=IuuuoD)

### Analysis of Outcomes Based on Goals

- I made a table representing the number of successful, failed, and canceled projects from a range of goal values. This was done using the =COUNTIFS function.
- After totally the number of projects. Simple math was used to determine a percentage of successful, failed, and canceled projects and their goal.
- Using the percentage information, a line graph was created to depict the success rate of projects in relation to the goal amount.

![Percentage Line Graph](C:\Users\MBugy\OneDrive\Desktop\Data Boot Camp\Module 1\Lesson 1-4\resources\Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

- When creating the "Outcomes Based on Goals" line graph, I had trouble selecting the correct graph. I initially chose the "stacked" line graph which only showed one line (as seen below). To fix this, I tried playing with the data to see if that was the issue. But I realized that I had to play with several of the line graph options to see which one properly reflects my data. I had to select the graph with overlapping lines, so both the percentage successful and unsuccessful lines showed.
- I had a hard time efficiently creating the =COUNTIFS() functions in the "Outcomes Based on Goals". I tried quickly copying the formulas into the rest of the cells. But i didn't make the rows absolute values. So, I went back to the first formula and made it an absolute reference, then had to input the ranges for goal amounts by row. AFter the first column was done, I could then auto fill the rest. I still had to change the outcome from 'successful' to 'failed', etc.

![Wrong Graph](https://1drv.ms/u/s!AkcEaWONZ7eSkXzqzRe1LyrIIxZh?e=njEw70)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	1. failed projects were approximately between 35-50 throughout the year
	2. Projects were successful in the summer months, particularly in May

- What can you conclude about the Outcomes based on Goals?

	1. Projects with goals of > $45,000 had a low to no success rate
	2. Least successful projects are from $25,000 - 30,000

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
