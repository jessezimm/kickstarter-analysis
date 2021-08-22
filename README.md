# Louise's Campaign Preparation Analysis

## Overview of Project

Louise is a hopeful playright seeking insights on past crowdfunding initiatives that can help make her future fundraising campaign a success.

### Purpose

The purpose of this project is to analyze past fundraising campaign data and uncover hidden trends. Louise can use the conclusions from this analysis to make informed decisions for her fundraising campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Below, is a line graph with **Launch Dates in Months** on the x-axis and **Counts of Theater Outcomes** on the y-axis. The three lines (outcomes) are **Successful** (blue), **Failed** (red), and **Canceled** (yellow). 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/88340176/130368679-9d28344a-bedf-4a14-a6ac-9fb8f640bb20.png)

### Analysis of Outcomes Based on Goals

Below, is a line graph with **Monetary Goal Ranges** on the x-axis and **Percentage Play Outcomes** on the y-axis. The three lines (outcomes) are **Percentage Successful** (blue), **Percentage Failed** (orange), and **Percentage Canceled** (grey).

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/88340176/130368683-6c1942ea-6977-471c-8d72-155e2b46616a.png)

### Challenges and Difficulties Encountered

When creating the *Theater Outcomes Based on Launch Date* graph, I struggled to determine how to sort the data accurately. I knew sorting the data from Z to A made sense because it chronologically made sense based on the titles of the *Outcomes*. For the *Outcomes Based on Goal* graph, I originally thought that you could select the *Goal* range as part of the *Countifs* function. Eventually, I realized that the *Goal* ranges were text, and I had to manually input the numbers and inequality signs into the formula.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

From January to May, the number of successful campaigns trend upwards, but from May to December, the number of successful campaigns trend downwards. The number of failed campaigns show litle to no dependency on month and tend to hover around 40.

- What can you conclude about the Outcomes based on Goals?

It is difficult to draw a conclusion about *Play Outcomes* based on *Goals* because the line graph shows no consistent trends. However, campaigns below 15000 have more success than failure. Additionally, campaigns above 45000 have more failure than success. Thurs, a lower goal may prove to be successful.

- What are some limitations of this dataset?

The launch dates only go from 2009 to 2017. Thus, we are lacking more recent data. Additionally, although the parent category and subcategory has a variety of fields, these categories may not account for the many types of fundraising campaigns. For instance, a festival campaign could have food trucks, music, and a play, but it will only have one subcategory input. 

- What are some other possible tables and/or graphs that we could create?

We could create a line graph of the **Average Donation by Month** or a stacked column graph of **Count of Outcome by Country**. We could create a table with rows as **Country** and **Pledged and Goal** as columns.
