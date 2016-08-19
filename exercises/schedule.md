---
layout: exercises
title: Schedule Exercise
---

# Schedule

## Introduction

In this exercise you will practice using generators, data structures, and the Python [datetime module](https://docs.python.org/3/library/datetime.html).

## Problem Description

You need to build a class schedule for a class that meets each week on particular weekdays.

## Solution Description

Write a Python script in a file called `make_blank_schedule.py` that takes three command line arguments:

1. The first day of classes, expressed in ISO date format.
2. The last day of classes, expressed in ISO date format.
3. The weekdays to include in the schedule, where the days of the week use the one-letter codes MTWRFSU.

and prints the dates of class days.

Example:

```
$ python3 make_blank_schedule.py 2016-08-22 2016-12-06 TR
2016-08-23
2016-08-25
2016-08-30
2016-09-01
2016-09-06
2016-09-08
2016-09-13
2016-09-15
2016-09-20
2016-09-22
2016-09-27
2016-09-29
2016-10-04
2016-10-06
2016-10-11
2016-10-13
2016-10-18
2016-10-20
2016-10-25
2016-10-27
2016-11-01
2016-11-03
2016-11-08
2016-11-10
2016-11-15
2016-11-17
2016-11-22
2016-11-24
2016-11-29
2016-12-01
2016-12-06
```
