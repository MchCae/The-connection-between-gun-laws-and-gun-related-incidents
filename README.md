# The-connection-between-gun-laws-and-gun-related-incidents

## Motivation

Gun violence is a pervasive issue, both in the US and in the rest of the world. Since the US in particular is plagued by gun violence, it serves as an example for an analysis of gun violence in countries with high gun availability.


## Data

Data is downloaded from https://www.kaggle.com/datasets/jameslko/gun-violence-data/data, and acquired trough https://www.gunviolencearchive.org/.
"Gun Violence Archive (GVA) is a not for profit corporation formed in 2013 to provide free online public access to accurate information about gun-related violence in the United States. GVA will collect and check for accuracy, comprehensive information about gun-related violence in the U.S. and then post and disseminate it online."

To enhance my analysis I added the gun laws and the total population in each state and year. The gun law data is from https://statefirearmlaws.org/national-data/2018 and the Population data from the Us Census Bureau. -> The Population data lacks the numbers for 2018, so I imputed them with the mean in each state.

 Due to data quality issues the years 2013 and 2018, which are part of the original data set, will be dropped.


## Key Question

This project centres on the question of whether the quantity of gun laws has an influence on incidents, fatalities and injuries within a state. 
For this reason the data gets aggregated yearly and for each state.

After the explorative analysis I conclued 3 hypothesis:

1. The more gun laws, the fewer gun-related incidents.
2. The more gun laws, the fewer gun-related killings.
3. The more gun laws, the fewer gun-related injuries.


## Tools
Pandas: for data analysis

Numpy: for mathematical equations

Seaborn: for data visualizations

Matplotlib: for data visualizations

SciPy: for mathematical equations

Sklearn: machine learning 


## Folder Structure

   Scripts: Jupyter notebooks with commentary.


## Final Dashboard:

https://public.tableau.com/app/profile/max.caesar/viz/Theconnectionbetweengunlawsandgunrelatedincidents/Story1?publish=yes
