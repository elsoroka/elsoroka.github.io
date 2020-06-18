---
title: TimeCrunch
---
# TimeCrunch - Data-Driven Event Scheduling

## The Problem
As an undergraduate, I served as an event planner for UCI's IEEE club. One of my tasks was to choose a time and date for each event.

**This is harder than it looks.**

Suppose you are a recruiter looking to hire EE upperclassmen. You want to reach the maximum number of students - so if you arrive on campus when all the EE upperclassmen have class, your time is wasted. Students are frustrated and tempted to skip class. Bad feelings all around.

## The Solution
**TimeCrunch generates heatmaps of the university schedule,** showing how many students are in class at a specific time.

[See it in action!](http://timecrunch-app.herokuapp.com/) This is our dev site containing Spring 2020 schedules.

TimeCrunch is useful when you know the demographic of students you expect to attend, but don't know individual students' schedules. This occurs for:
* Clubs scheduling events.
* Professors scheduling office hours.
* Recruiters visiting campus


TimeCrunch was built in collaboration with students in UC Irvine Information and Computer Science.

It works using web scrapers to collect publicly available enrollment data, requiring only a course time and date and the number of students enrolled.

We hope to find wider adoption among faculty and students in the upcoming academic year, and eventually to enable the app for more universities.