# FINAL PROJECT: MONETIZATION STRATEGY ANALYSIS AND REVENUE PREDICTION FOR SPACE BROTHERS MOBILE GAME
# Data
- events_us.csv: Contains data on user events within the game, including event datetime, event type, building type, user ID, and project type. The events include activities such as building facilities, completing the first stage, and implementing projects.
> - event_datetime - date and time of event
> - event — event type
> - building_type — type of facility to be constructed
> - user_id - unique id of users
> - project_type — type of project implemented

- ad_cost_us.csv: Contains data on advertising costs, including the day the user clicked on the ad for the first time, the traffic source, and the click cost.
> - day — the day the user clicked on the ad for the first time
> - source — traffic source
> - cost — click cost

- user_source_us.csv: Contains data on user sources, including the user ID and the source from which the user downloaded the app.
> - user_id — user identifier
> - source — the source from which the user who downloaded the app came
> - event_date - date of event occured

# Goal
> - Conduct an exploratory data analysis (EDA) to understand user behavior and event distribution.
> - Develop a monetization model that predicts revenue from advertisements based on user events.
> - Analyze potential revenue from different user groups (those who complete the stage and those who do not).
> - Formulate and test statistical hypotheses regarding user behavior and monetization.
> - Provide detailed conclusions and recommendations for optimizing the game's monetization strategy.

# Libraries
> - *pandas ,matplotlib ,numpy, seaborn, nltk, scipy, plotly.express, plotly.graph_objects, proportions_ztest, scikit-learn (sklearn)*
