# Monetization model for a mobile game

## Task

It is required to develop a monetization model for a gaming application.
When monetizing mobile games with advertising, there is a problem: the user can get into an outflow if you start showing him ads before the game seems interesting to him. At the same time, the later the advertising starts, the less advertising revenue the application developers will receive.
You need to choose the optimal time to launch an ad.
The main dataset contains event data. Users are building their own space program and trying to colonize the galaxy. It is assumed that the display of advertising will take place on the screen with the choice of the type of object to be built.
The dataset contains data on the game of users at the first level.

Completing the first level requires the player to fulfill one of two conditions:

- Victory over the first enemy
- Implementation of the project - development of the orbital assembly of satellites

The dataset contains data from the first users of the application — a cohort of users who started using the application in the period from May 4 to May 10 inclusive.

**Data description:**

**Main dataset game_actions.csv:**

* event_datetime — time of the event;

* event — one of three events:
1. building — the object is built,
2. finished_stage_1 — the first level is completed,
3. project — the project is completed;

* building_type — one of three building types:
1. assembly_shop — assembly shop,
2. spaceport — spaceport,
3. research_center — research center;

* user_id — user ID;
* project_type — type of the implemented project;

***Information about advertising activities***

**ad_cost.csv dataset:**

* day - the day on which the ad was clicked
* source - traffic source
* cost - cost of clicks

**user_source.csv dataset:**

* user_id - user ID
* source - the source from which the user who installed the application came

## Libraries

- pandas
- plotly.express
- datetime
- matplotlib
- seaborn
- numpy
- scipy
- warnings

## Project description

Hypotheses were tested about the difference in the average time of passing the level between users with different strategies and users who came on different days of the week. Considering performed calculations, the monetization model was proposed.

## Keywords

Statistical test, data visualization, EDA, histogram, boxplot.
