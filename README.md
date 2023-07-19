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



SUM UP OF THE DESCRIPTIVE ANALYSIS:

-----POTENTIAL CUSTOMER LOST-----

"This information represents people who was thinking about buying an ebike but they are not doing it anymore."
First thing to take into account is that in any case the mean is higher than 20%. with is a low value.
Apart from that in the table at the botom  of the code we can see that std is much higher than the mean.But in this case the std doesn´t give us a lot of information because
it is directly related with the mean as the information studied is yes/no type.
We can see in the plot that women, increases the number of people who is included in this case along with the age.
However, men get their top value in the range of age 35-45 years. That means men older than this are still potential customers.

-----POTENTIAL CUSTOMER-----
The size of the sample was 80. Not a suitable size to make this study. That is why things happen, like having 100% of potential customers in Men between 35 & 45 years.
But, that shows that the number of potential customer with that profile is very high which means that we should focus actions in that group to produce the highest increasing in the sells possible.
The number of people who is potential customer surprised to me. It is quite high. In the predictive study I will check how to turn these potential customers into real customers.

-----NOT POTENTIAL CUSTOMER-----
NOt so much to tell about this plot and table because is directly realted with the pot. customers..
Just mention that in the sample there is no answers of young woman.

-----CURRENT OWNERS OF EBIKE-----
The means showed in this plot are quite lower than potential customer. We can infere that, with that there are chances to make this market field bigger. 
In this sample the most of the owners are  women. And they come from just 2 range of ages. 

Inferential: 

I will use the following methods.
  -chi^2Useful in cases where I want to check the independance of 2 categorical
variables. For example, be a potential customer & age /gender 

  -Confidence intervals: As the sample size is small, I would use confidence intervals
based on T-Student distribution.

  - Logistic regression: If I want to predict a binary result. f.e: If a potential customer will
buy an ebike.  
