---
layout: post
title: 2016-01-13 First week at Metis
---

Time flies, especially if you immersed yourself in a high-pace environment and wrap your head around complex problems. That's how the first week at Metis started out. Below you find an account of **lecture content, the weekly project and my personal learnings.** 

---

## Lecture content (selection)

The first week was aimed at building a solid foundation for the curriculum ahead of us. This includes e.g. getting fluent in Git which will allow us to control versions of code. This will prove particularly important once projects get more complex and you work on them in teams.

Furthermore, we were introduced in more depth to pandas, a library of data structures that offers a wide range of ways to manipulate and display data.
When I compare it with Excel, with which I have been working extensively over the past years, pandas does not perform novel tasks but is able to handle much larger data sets.

## Project

The course kicked off with a group project this week, which was a good opportunity to discuss on the scope, approach and execution. The task at hand was to make recommendations on placing street teams on NYC subway stations. The primariy data source was was MTA turnstile data which gives you information on traffic frequency.

In order to arrive at recommendation we had to perform the following steps:

* **importing the data** into a structure that could by handled using the functions and methods at our disposal
* **cleaning the data** by drawing descriptive summary statistics from it and eliminating outliers and nonsensical data
* aggregating the data in a meaningful way to **draw conclusions** from it
–* plotting the data in order to best **support these conclusions** 

Our team applied a 3-step methodolog, as shown below:

1. Filter Subway stations by the median income of their neighborhoods. (>70k)
2. Select the top stations based on their proximity to startups
3. Filter out stations who's traffic won't suffice to fully utilize a 5-member street team  

![methodology](/images/methodology.png)

## Learnings (selection)
* Leaving the more pre-defined toolkit of Excel (among others) and moving to code dramatically expands our ability to handle data
* As soon as a data set has been imported, one should slice,  dice and plot it in order to exclude nonsensical data points
* The output format should be clearly defined before we go about analysing the data in order to conduct it in an efficient and effective manner.