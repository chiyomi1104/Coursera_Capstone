# IBM Data Science Course Final Project (Python)
## Introduction
Los Angeles is one of the largest city in the United States. Our stakeholder is willing to open the Japanese restaurant in Los Angeles with middle to high level prices. In Los Angeles, choosing a location for business is one of the most important decision and stressful tasks. Also there are many criteria that have to be satisfied in order to achieve the highest revenue, including;
• The density of Asian restaurant
• population around the location
• solvency of the population around the location
In this project, we will investigate the basic analysis to find the optimal area to open the Japanese restaurant by those criteria.
There are many other factors to determine the optimal area more than above. Those deeper insights will be needed after this basic analysis and won’t be completed within this project.
## Data
The problem will be addressed using two datasets:
• The first dataset is a collection of latitude/longitude coordinates for each LA city (obtained from: https://simplemaps.com/data/us-cities. It requires us to download the data rather than scraping. So it’s imported to the IBM Watson studio.
• The second dataset is the Foursquare data. This will be used to obtain information about each location, including restaurants in each area. The data will be used to calculate: (1) the Euclidean distance from each suburb to the nearest Japanese restaurant, (2) the number of restaurants in each district, (3) the diversity of restaurants in each area (using the Simpson-Gini coefficient).



