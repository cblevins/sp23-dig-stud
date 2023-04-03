---
title: Introduction to Mapping in Tableau Public
---

## Introduction

- The goal of today is to learn some of the basics of mapping in Tableau Public. You're going to be using the same dataset you used for the Tableau Public II tutorial: [1871 Postmaster Salaries]({{site.baseurl}}/modules/1871-postmaster-salaries.csv). This is a dataset that Prof. Blevins collected while researching the history of the US postal system in the American West during the late 1800s. This particular dataset contains information of every post office in the western United States in 1871 along with how much compensation its postmaster received from the federal government that year for operating the post office.
- Note: You do not need to submit today's tutorial as an assignment.
- Open Tableau Public and connect to the data source you used for Tableau Public II that you downloaded to your `tableau-public` folder. Note: if you need to download it again or can't find it: download the file [`1871 Postmaster Salaries.csv`]({{site.baseurl}}/modules/1871-postmaster-salaries.csv) and save the file inside your `tableau-public` folder on your computer.

## Making Maps

### Sheet 1

*Let's start with the optional Bonus question from Tableau Public II. Review with your classmates immediately next to you how you would create the following:*

Question: where were post offices located in each state?
{: .notice--primary}

- [Create a dot map](https://www.youtube.com/watch?v=WKAHZox2sKg) of every post office in the dataset.
	- Hint: Use the `Longitude` and `Latitude` fields - *not* the ones that say (generated)
- Use the Marks card to size the dots according to the postmaster salary at that post office - the larger the salary, the larger the dot.
- Use the Color button on the Marks card to adjust:
	- Color: Green
	- Opacity: 70% 
	- Border: Black

### Sheet 2

Goal: Make a map that fills in western **states** colored to the **average postmaster compensation** (darker = higher average compensation)
{: .notice--primary}

- Drag or double-click the `State` field onto the sheet
- Under the Marks tab, change the drop-down menu from `Automatic` to `Map`
- Drag the `PM Salary` field onto the Color button on the Marks tab
- Click the drop-down menu over `SUM(PM Salary)`. Change from `Measure (Sum)` to `Measure (Average)`.  It should now say `AVG(PM Salary)` in the Marks tab with a little color icon next to it.
- Modify the above steps so that you *also* include a `Label` on each state that has the average PM salary written.
- Click on the empty Color button in the marks 	- Change the `Opacity` to 60% so you can see the underlying map a bit better
	- Click on the `Edit Colors` button
	- Under `Palette` select the `Purple` gradient

### Sheet 3

Goal: Make a map that fills in western **counties** according to **how many post offices** were in each county (darker = more post offices)
{: .notice--primary}

- Try and repeat the steps you followed for Sheet 2, but switch the fields you're using. 
- Instead of `State` and `PM Salary`, you're going to be using: `County` and *`1871-postmaster-salaries.csv (Count)`*.
- Note: after creating your map, you should see "missing" gaps in the map without any data. Brainstorm with the person next to you: what do you think is happening here? 
	- *Hint: click the `5 unknown` note that has appeared in the bottom right corner of the map.*

### Sheet 4

Goal: Create a map that illustrates the **“classification" little lie** described in Deluca and Nelson, “Lying With Maps” (p. 136).
{: .notice--primary}

- Duplicate either Sheet 2 or Sheet 3
- Click on the empty Color button in the marks and click on the `Edit Colors` button
	- Click `Advanced` button and modify the start and/or or end points. Click `Apply`. What did it change about the map?
	- Change the `Stepped Color` option from 5 steps to 3 steps. Click `Apply`. What did this change about the map?

