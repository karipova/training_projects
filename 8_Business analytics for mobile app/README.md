# Business analytics for mobile app

## Task

It is necessary to analyze the results of attracting users to the mobile application for the period from 2019-05-01 to 2019-10-27.

Initial data:
- server log with data about new users' visits to the application;
- data on purchases for the specified period;
- data on advertising expenses incurred.

It is required to identify the reasons for ineffective user engagement and form recommendations for the marketing department.


**Data description:**

*visits_info_short.csv:*

- User Id — unique user ID,
- Region — user's country,
- Device — user's device type,
- Channel — ID of the transition source,
- Session Start — date and time of the session start,
- Session End — date and time of the end of the session.

*orders_info_short.csv:*

- User Id — unique user ID,
- Event Dt — date and time of purchase,
- Revenue — the amount of the order.

*costs_info_short.csv:*

- dt — дата проведения рекламной кампании,
- Channel — идентификатор рекламного источника,
- costs — расходы на эту кампанию.

## Libraries

- pandas
- datetime
- seaborn
- matplotlib
- numpy

## Project description

The data from ProcrastinatePRO+ was analyzed.
Various metrics were calculated, cohort analysis was used: LTV, CAC, Retention rate, DAU, WAU, MAU, etc. Previously written metric calculation functions were used. Correct conclusions have been drawn based on the data obtained.

## Keywords

Data processing, statistical test, LTV, CAC, cohort analysis.
