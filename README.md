# HypothesisTesting_BostonFoodComplains_EDA

Contributors:
  Rushabh Shah
  

*Overview*:

The Health Division of the Department of Inspectional Services ensures that all food establishments in the City of Boston meet relevant sanitary codes and standards. Businesses that serve food are inspected at least once a year, and follow-up inspections are performed on high risk establishments. Health inspections are also conducted in response to complaints of unsanitary conditions or illness. 
# FactFinder is the website by American goverment which has census data. The data is collected from surveys. Boston Census data includes data per zipcode of the city Boston.




*Hypotheis Testing*:

1) If the population is high then there would be more food inspections and complaints. 

2) The complaints/inspections would be more on weekends than weekdays as there is more rush on weekends than weekdays.

Question:

1) Which owner is highly inspected or have more complaints reported?

2) In which year most of the inspections were reported?



*Data Summary:*

Size of Food inspection data: 228.8 MB 

Size of Census Data: 204.3 KB

Size of jupyter notebook: 110 KB

Number of rows Food inspection data :594789 

Number of columns Food inspection data :26

Number of rows Censu data :500 

Number of columns Census data :6

The data was provided by the Boston goverment data portal.

Data Consistences:The Boston food establishment data was updated regularly. So, while performing the analysis, there were some inconsistencies as the new data had some missing values. Many other columns also had missing values, but as I was not going to use it I have not filled them or dropped them. There were multiple columns with date and time. The meaning of the columns was not known so ‘issdttm’ is assumed to be the column in which the inspections or complaints is reported. To see whether the complaints were uploaded bt the other organization on the data was entered when the inspection was registered graph was plot. The results of the graph shows that the majority of the complaints was reported on weekdays.  

To find the owner with the maximum complaints value_count function was used. 

To check the number of complaints per zip code population, a new dataframe was created which had the number of complaints per zip code and the population of the zip code. The graph suggested that, the hypothesis was invalid. The graph illustrates that even in the highly populated area there were fewer complaints than with the area which had more population.
  


