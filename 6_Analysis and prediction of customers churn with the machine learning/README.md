# Analysis and prediction of customers churn with machine learning

## Task

A gym chain develops a strategy for interacting with customers. It is considered that the client has fallen into the outflow if he has never visited the gym in the last month. To combat the problem of churn, the fitness center has converted customer questionnaires into electronic form.
It is required to develop a model to predict the outflow of customers, segment them and make recommendations based on the results of the study.

**Data description:**

**Customer data for the previous month before checking the fact of outflow:**
- gender — gender;
- Near_Location — living or working in the area where the fitness center is located;
- Partner — an employee of the club's partner company (cooperation with companies whose employees can receive discounts on a subscription - in this case, the fitness center stores information about the client's employer);
- Promo_friends — the fact of the initial recording within the framework of the "bring a friend" campaign (used a promo code from a friend when paying for the first subscription);
- Phone — availability of a contact phone;
- Age — age;
- Lifetime — the time since the first visit to the fitness center (in months).

**Information based on the log of visits, purchases and information about the current status of the customer's subscription:**
- Contract_period — the duration of the current valid subscription (month, 6 months, year);
- Month_to_end_contract — the period until the end of the current valid subscription (in months);
- Group_visits — the fact of attending group classes;
- Avg_class_frequency_total — the average frequency of visits per week for the entire time since the beginning of the subscription;
- Avg_class_frequency_current_month — average frequency of visits per week for the previous month;
- Avg_additional_charges_total — total revenue from other fitness center services: cafes, sporting goods, beauty and massage parlors.
- Churn — the fact of outflow in the current month.

## Libraries

- pandas
- warnings
- seaborn
- sklearn.preprocessing
- sklearn.model_selection
- sklearn.linear_model
- sklearn.ensemble
- matplotlib
- itertools
- sklearn.cluster
- scipy.cluster.hierarchy

## Project description

Machine learning is used in this project. The probability of outflow is predicted (at the level of the next month) for each client; typical portraits of users are formed: the brightest groups are highlighted, their main properties are characterized; the main signs that most strongly influence outflow are analyzed.

## Keywords

KMeans, Machine Learning, RandomForestClassifier, LogisticRegression, dendrogram.
