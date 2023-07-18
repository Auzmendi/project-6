# project-6
This project try to solve a problem about E-bike market.

As initial information, I have started with a dataset with info about the demands expected in this field  made in 2020, and a new revision of the dataset 2 years after where the demands expected have decreased around 50%.
The target of this project is to find possible answer to this situation, and find potential actions to increase this demandas as much as possible.

The data that I will use come from:
  - Small dataset with demandas variation provided by a person who works in this sector.
  - A survey made to random potential customers. (sample with size at least 40 people) --> 80 answers gathered in the end.
  - Demographic dataset. This dataset will help to take outputs in the context of the whole spanish population.

SURVEY.

The survey tries to income information from at least 40 people. The survey is oriented to be answered with a random group of people from Spain, which the is the population in  study.
The sample was taken as arandomly as possible but there are several relations between individuals. 
The survey gives information about demographics, current information about owning an ebike and intentions to buy one. And also information about reasons to buy and not to buy an ebike, which will be taken into account in order to find potential actions to increase sells.

The df obteined from the survey could be divided in 2 dfs. 
  1. Descriptive data from current market situation. --> descriptive_df
  2. Data useful for potential actions to increase sells. --> predictive_df
Of course, some of the columns will be presented in both df.

