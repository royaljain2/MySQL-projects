In this project, we'll work with data from the CIA World Factbook, a compendium of statistics about all of the countries on Earth. The Factbook contains demographic information like:

population - The population as of 2015. population_growth - The annual population growth rate, as a percentage. area - The total land and water area.

In this project, we'll use SQL in Jupyter Notebook to explore and analyze data from this database.

## Database:
The dataset is quite simple and will not allow us to answer complicated question. It is composed of 11 colums and 262 row.

1). id - id number attribuated to a country.

2). code - country code, made from the two first letters of the country.

3). area - total area of the country (area_water + area_land).

4). population - population of the country

5). population_growth - ratio of the population growth in 2015

6). birth_rate

7). death_rate

8). migration_rate - ratio of people that left the country to another.

 It is important to note that the last row (id 262) is not a country but "World" (code: xx). In the end the data is only composed of 261 countries.

## Notes:
The database being very simple, we could answer complicated questions. This project was intented to practise my SQL skills and show knowledge of simple and more complicated queries (subqueries).
