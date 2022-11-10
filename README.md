# Speed-Dating-Analyses
This analysis consists of exploratory data analysis and machine learning implementation on a unique speed dating dataset. 

Datset:
- Data was gathered from participants in experimental speed dating events from 2002-2004. During the events, the attendees would have a four minute "first date" with every other participant of the opposite sex. At the end of their four minutes, participants were asked if they would like to see their date again. They were also asked to rate their date on six attributes: Attractiveness, Sincerity, Intelligence, Fun, Ambition, and Shared Interests. The dataset also includes questionnaire data gathered from participants at different points in the process. These fields include: demographics, dating habits, self-perception across key attributes, beliefs on what others find valuable in a mate, and lifestyle information. See the Speed Dating Data Key document below for details. 
- The dataset itself can be found in the Speed_Dating_Data.csv file

Notebooks:
- Speed_Dating_Cleaning_and_EDA: includes the cleaning of the original dataset, as well as exploratory data analysis mainly based in demographic differences.
- Speed_Dating_Feature_Engineering: Determining model perceived feature importance from regression, XGBoost, and random forest models. Insights from this were used for a little more exploratory data analysis.
- Spped_Dating_Final_Model: using SMOTE balancing to attempt to develop a predictive model for matching based on pre-interaction features.

