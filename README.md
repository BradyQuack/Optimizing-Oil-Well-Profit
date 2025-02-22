# Optimizing Oil Well Profit
View project: [Optimizing Oil Well Profit](https://github.com/BradyQuack/Optimizing-Oil-Well-Profit/blob/main/Project9.ipynb)
## Project Overview:
This project tackles the challenge of maximizing profitability in oil well development by strategically selecting the most promising region for drilling. Leveraging synthetic geological exploration datasets from three regions, the project uses linear regression models to predict oil reserve volumes and bootstrapping techniques to assess profit distributions and associated risks.
## Data Description:
Geological exploration data for the three regions are stored in files:

geo_data_0.csv

geo_data_1.csv

geo_data_2.csv

id — unique oil well identifier

f0, f1, f2 — three features of points (their specific meaning is unimportant, but the features themselves are significant)

product — volume of reserves in the oil well (thousand barrels).

Conditions:

Only linear regression is suitable for model training (the rest are not sufficiently predictable).

When exploring the region, a study of 500 points is carried with picking the best 200 points for the profit calculation.

The budget for development of 200 oil wells is 100 USD million.

One barrel of raw materials brings 4.5 USD of revenue The revenue from one unit of product is 4,500 dollars (volume of reserves is in thousand barrels).

After the risk evaluation, keep only the regions with the risk of losses lower than 2.5%. From the ones that fit the criteria, the region with the highest average profit should be selected.
