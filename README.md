# ETL_group-Project

Gathered CSV files from kaggle.com

https://www.kaggle.com/ritesaluja/beer-beer-beer
https://www.kaggle.com/nickhould/craft-cans#breweries.csv

stepes to execute code
1. Run "Beers_DB_Create.ipynb" this creates DB and creates tables
2. Run "BBB-clean.ipynb" this opens "open-beer-database.csv", cleans the data and save a new CSV called "bbb_clean.csv",
it will then insert the date into the "craft_beer.Beer_locations table.
3. Run  "can beer.ipynb this opens "Beers.csv", cleans the data and saves a new CSV called "Beers.csv",
it will then insert the data into the "craft_beer.Beers"

