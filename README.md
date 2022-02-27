# seattle-calls-data-eda-imt562
Interactive Information Visualization Group Project on Seattle Calls Data

## Setup
1. Clone the repo
2. Create a folder folder named 'data' inside the main folder and copy 'Call_Data(2017-Present).csv' into it

## Getting the location and calls data in Tableau

Description of Seattle Police Beats:
Seattle is divided into five geographic areas. Within those areas are the 5 precincts or police stations: North, East, South, West and Southwest. Precinct boundaries were determined through consideration of neighborhood boundaries, geographic and other natural boundaries.
Each precinct contains smaller geographic areas called Sectors. There are 17 sectors total in the city.
Each of these Sectors are divided into between 3 smaller sections called Beats (i.e. Ocean sector has three beats O1, O2, O3) These are the areas that individual patrol officers are assigned responsibility for.

1. To get the geographical data of the precincts, sectors and beat use the **Esri ArcGIS Server** and paste the following server link into it:
https://gisdata.seattle.gov/server/rest/services/SPD/SPD/MapServer/2
Alternatively this link can be found on this website - https://www.arcgis.com/home/item.html?id=36378b7acb8a464c8019b9618fecd0dd

2. Add the calls data csv file into Tableau

3. Establish a relation between location and call dataset by going to the 'Edit Relationship' window. Set 'Beat' in Beats2018-present dataset equal to 'Beat1' column in Calls dataset. Set the cardinality to one to many relationaship.

