# Analysis of video games market

## Task

The online store "Streamchik" sells computer games all over the world. Historical data on game sales, user and expert ratings, genres and platforms (for example, Xbox or PlayStation) are available from open sources. It is necessary to identify patterns that determine the success of the game. This will allow you to bet on a potentially popular product and plan advertising campaigns.
Data is available for the project until 2016, the company is planned for 2017.


**Data description:**

- Name — the name of the game
- Platform — platform
- Year_of_Release — year of release
- Genre — genre of the game
- NA_sales — sales in North America (millions of copies sold)
- EU_sales — sales in Europe (millions of copies sold)
- JP_sales — sales in Japan (millions of copies sold)
- Other_sales — sales in other countries (millions of copies sold)
- Critic_Score — critics' score (maximum 100)
- User_Score — user rating (maximum 10)
- Rating — rating from the ESRB organization (English Entertainment Software Rating Board). This association determines the rating of computer games and assigns them a suitable age category.
- Data for 2016 may be incomplete.

## Libraries

- pandas
- matplotlib.pyplot
- numpy
- seaborn
- math
- scipy
- warnings

## Project description

The parameters determining the success of the game in different regions of the world are revealed.
Based on this, a report has been prepared for a computer game store for planning advertising campaigns. Data preprocessing and analysis were carried out. The current period for analysis is selected. Portraits of users of each region have been compiled.
Hypotheses have been tested: the average user ratings of the Xbox One and PC platforms are the same; the average user ratings of the Action and Sports genres are different. The Student's criterion for independent samples was used in the analysis.

## Keywords

Data processing, histogram, lineplot, statistical test, Student's t-test.
