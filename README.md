# python-himalayan-expeditions-analysis
The purpose of this repository is to demonstrate sourcing open data and executing exploratory
analysis, defining variable relationships, and analyzing time series data. With this project, 
I've created geographical visualizations and conduct geospation analysis within Python. I also
started to dive into regression and clustering analysis within Python. Finally, a storyboard 
in Tableau was created to outline a use-case and describe my findings regarding Himalayan 
expeditions from 1990 - 2019.

## Project Objective
Responsible Expeditions is a fictitious, new tourism agence focused on offering expedition 
tours through the Himalayas. The agency's top priorities are 
(1) offering expertise for climbing expeditions, 
(2) taking care of the mountain range by understanding the amount of expedition traffic each
season, and 
(3) employing local guides to support the local economy.
As a data analyst for Responsible Expeditions, I've created a storyboard to give the team 
historical infoarmiton about expeditions to help them with their staffing stragey and seasonal 
planning. 

## Tools
For this project, the following Python libraries were used:
- pandas
- numpy
- seaborn
- matplotlib
- matplotlib.pyplot
- os
- sklearn (importing the following)
      - from sklearn import preprocessing
      - from sklearn.cluster import KMeans
      - from sklearn.preprocessing import StandardScaler
- pylab
      - from pylab import rcParams
- statsmodels.api
      - from statsmodels.tsa.stattools import adfuller
      - from statsmodels.graphics.tsaplots import plot_acf, plot_pacf
- warnings
- datetime

In addition to using Python, Tableau was used to create the final storyboard.


## Executing the Code
The data can be downloaded in the following links:
- [Himalayan Expeditions](https://www.kaggle.com/datasets/raskoshik/himalayan-expeditions?select=expeditions.csv).
      - The dataset "expeditions.csv" from the above link was the primary dataset
      - The dataset "summiters.csv" was used for time series analysis.

The original data source for this Kaggle dataset can be found at the following link:
- [The Himalayan Database](https://www.himalayandatabase.com/)

The code is available as Jupyter notebooks, available under 
/05-2023 Instacart Basket Analysis/Scripts/.

The final report can be found on Tableau Public via the following link:
- [Himalayan Expeditions Project (1990-2019)](https://public.tableau.com/app/profile/ana.renahan/viz/HimalayanExpeditionsProject1990-2019/STORYBOARD?publish=yes)

## Resources
Data Citation:
- "Himalayan Expeditions", Accessed from https://www.kaggle.com/datasets/raskoshik/himalayan-expeditions?select=expeditions.csv on 05/23/2023. 
- “The Himalayan Database”, Accessed from 
https://www.himalayandatabase.com/ on 05/23/2023.

For Additional Learning about the Himalayas:
- "New Everest Rules Could Significantly Limit Who Gets to Climb." Accessed from https://www.nytimes.com/2019/08/14/world/asia/everest-climbing-rules.html on June 1, 2023.
- “Overcrowding on Mount Everest contributes to rise in deaths.” Accessed from
https://www.pbs.org/newshour/world/overcrowding-on-mount-everest-contributes-to-rise-in-deaths on May
19, 2023.
- “Responsible Tourism in the Himalayas.” Accessed from https://www.edreams.com/blog/responsible-tourismin-the-himalayas/ on May 19, 2023.
- “Should Everest be closed?” Accessed from
https://www.theguardian.com/world/2006/oct/08/conservation.environment on May 19, 2023.
- “Trash and Overcrowding at the Top of the World.” Accessed from
https://education.nationalgeographic.org/resource/trash-and-overcrowding-top-world/ on May 19, 2023.
- “’Why Are You Doing This?’ On Mountaineering in the 21st Century.” Accessed from https://lithub.com/whyare-you-doing-this-on-mountaineering-in-the-21st-century/ on May 19, 2023.
