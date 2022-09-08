# Defining the most profitable tariff plan for telecom operator

## Task

Megaline's customers are offered two tariff plans: Smart and Ultra. In order to adjust the advertising budget, the commercial department wants to understand which tariff brings in more money.
It is required to conduct a preliminary analysis of tariffs on a small sample of customers. There is data of 500 users: who they are, where they come from, what tariff they use, how many calls and messages each sent in 2018. It is necessary to analyze the behavior of customers and conclude which tariff is better.

**Data description:**

***Users table (user information):***

- user_id — unique user ID
- first_name — user name
- last_name — last name of the user
- age — user's age (years)
- reg_date — tariff activation date (day, month, year)
- churn_date — date of termination of use of the tariff (if the value is omitted, the tariff was still valid at the time of data upload)
- city — the user's city of residence
- tarif — name of the tariff plan

***Calls table (information about calls):***

- id — unique call number
- call_date — date of the call
- duration — the duration of the call in minutes
- user_id — ID of the user who made the call

***Messages table (information about messages):***

- id — unique message number
- message_date — date of the message
- user_id — ID of the user who sent the message

***Internet table (information about internet sessions):***

- id — unique session number
- mb_used — the amount of Internet traffic spent per session (in megabytes)
- session_date — date of the internet session
- user_id — user ID

***Tariffs table (information about tariffs):***

- tariff_name — name of the tariff
- rub_monthly_fee — monthly subscription fee in rubles
- minutes_included — the number of minutes of conversation per month included in the subscription fee
- messages_included — the number of messages per month included in the subscription fee
- mb_per_month_included — the amount of Internet traffic included in the subscription fee (in megabytes)
- rub_per_minute — the cost of a minute of conversation over the tariff package (for example, if the tariff has 100 minutes of conversation per month, then with
- 101 minutes will be charged)
- rub_per_message — the cost of sending a message over the tariff package
- rub_per_gb — the cost of an additional gigabyte of Internet traffic over the tariff package (1 gigabyte = 1024 megabytes)

***Description of tariffs***

***Smart tariff***

Monthly fee: 550 rubles
Included 500 minutes of conversation, 50 messages and 15 GB of Internet traffic
The cost of services in excess of the tariff package: 1. Minute of conversation: 3 rubles (Megaline always rounds up the values of minutes and megabytes. If the user spoke for only 1 second, the whole minute is counted in the tariff); 2. message: 3 rubles; 3. 1 GB of Internet traffic: 200 rubles.

***The "Ultra" tariff***

Monthly fee: 1950 rubles
3000 minutes of conversation, 1000 messages and 30 GB of Internet traffic are included
The cost of services in excess of the tariff package: 1. minute of conversation: 1 ruble; 2. Message: 1 ruble; 3. 1 GB of Internet traffic: 150 rubles.

## Libraries

- pandas
- matplotlib.pyplot
- numpy
- seaborn
- scipy

## Project description

A preliminary analysis of the use of tariffs on a sample of customers was carried out, the behavior of customers when using the operator's services was analyzed and optimal sets of services for users were recommended. The data has been preprocessed and analyzed. Hypotheses about the difference in revenue of subscribers of different tariffs and the difference in revenue of subscribers from Moscow and other regions have been tested.

## Keywords

Data processing, histogram, boxplot, statistical test, Student's t-test.
