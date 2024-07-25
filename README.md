# dl-group-project


# Pre-Processing
Combining [IMDB data](https://datasets.imdbws.com/) with the [Kaggle Poster data](https://www.kaggle.com/datasets/rezaunderfit/48k-imdb-movies-with-posters) into a csv file

Data exported to movie_data.csv

https://drive.google.com/drive/folders/1rprgWfqH0HiV_yQ-KAmuSCMV5VAZ_342?usp=sharing

|Column|Data Type|Remarks|
|--|--|--|
|tconst|object|IMDB title ID / Primary Key|
|titleType|object|Video Type
|primaryTitle|object|Title of the movie|
|originalTitle|object|
|isAdult|float64|
|startYear|float64|Release Year|
|endYear|float64|
|runtimeMinutes|object|Movie Duration|
|genres|object| Genre(s)|
|Poster|object| Poster Link|
|averageRating|float64|
|numVotes|int64|
|ordering|int64|
|nconst|object| IMDB Crew Name ID|
|category|object|Crew Job Type| 
|job|object|
|characters|object|Crew Character Played|
|primaryName|object|Crew Name|
|birthYear|float64|
|deathYear|float64|
|primaryProfession|object|
|knownForTitles|object|
