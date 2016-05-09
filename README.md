# IMDB_ABC
​crawl the IMDB REST API using Python, to collect seasons, episodes and ratings of ABC shows

Approaches:

1) Use sql to query the database, to get the product company is ABC
2) Web scrapy Wiki first to get the name of ABC show, then use IMDbpy to retrieve the information of ABC show.

Set up:

1. Using IMDbPY, a Python package, to retrieve and manage the data of the IMDb movie database, ABC shows in this case.
2. The data were parsed on episode level.
3. Relation database will be used here, psql
