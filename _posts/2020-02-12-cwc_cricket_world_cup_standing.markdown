---
layout: post
title:      "CWC (Cricket World Cup) Standing"
date:       2020-02-12 22:34:53 -0500
permalink:  cwc_cricket_world_cup_standing
---


My first CLI project i created at Flatiron School, i build CLI gem project, that gets the data from web. Data my app is dealing with does not updates with in days or months, it updates after few years on web because Cricket World Cup places after few years. Last time it was placed in England 2019 and next world cup will be placed in India 2023, so expecting to see updates on my applcation data after few years. 

I thought about it, thats a long time, so i decided to add feature in my application where user can delete team from standing and add their own, user can modify the standing list, add as many as teams does the user wants, delete any team, change team standing and soon user will be able to save new modified team to .txt file.

Before, i started working on this project, i decided to work on application that allows the user to add data of students, Name, Age, Major (ex: engineering or business), Undergrad or Graduated, if the user is Undergrad (expected year of graduation and what will school will that student will be graduating from) and if the user is Graduated (what was the year or graduation and from what school). After entering the data, user comes back to main-menu to either look at the list of students or add new student or exit. On selection of list of students, students name will appear in list and user will get an option to either go back to main menu or select student to see data of selected student.

Simply, adding data from web and/or adding data from user inputs and viewing it sounds bit boring. I decided build something, where users would like to know the results of CWC. If the user does not like standing of each team, user have an option to modify the data and save it in .txt file. 

As of 2020, CWC 2019 standing should look like this.

![]()
<img src="(https://drive.google.com/file/d/1I0juIewaNt3_mT3L2aNcx72BafQl4w2X/view?usp=sharing">


To view final details (Total Matches playes, wins, losses, draw and final score), select it by entering the position number.

![](https://drive.google.com/open?id=1PSUPnDupG4-BkcKxxqtGK2YDVrejVFdA)


After modifying the data of CWC Standing, this is how it should look like. Position 4 is changed from New Zealand to Spain and added new team Brazil.

![](https://drive.google.com/file/d/1G4tpRE1pRdwEOuXLy7xn45friKTdy2nR/view?usp=sharing)

In order to install this gem. Add this gem into application's Gemfile:

```
gem 'students_database'
```

Then, excute it

```
$ bundle install
```

Or, install it yourself as:

```
$ gem install students_database
```
