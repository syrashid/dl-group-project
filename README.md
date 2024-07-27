# dl-group-project


# Pre-Processing
Combining [IMDB data](https://datasets.imdbws.com/) with the [Kaggle Poster data](https://www.kaggle.com/datasets/rezaunderfit/48k-imdb-movies-with-posters) into a csv file

Data exported to
- [movie_data.csv](https://drive.google.com/file/d/1yP8Fk7d4zlstBxxkudYFB29RtPfOxaWm/view?usp=sharing)
- [title_poster_ratings.csv](https://drive.google.com/file/d/1yQ_QBzqNaNcI4BiZ74xc-JEnRJ-qpt2U/view?usp=sharing)
- [title_poster_ratings_principals.csv](https://drive.google.com/file/d/1yQT5H8VrxHfeb6t5gYT9GWp4QldSdDhh/view?usp=sharing)

https://drive.google.com/drive/folders/1rprgWfqH0HiV_yQ-KAmuSCMV5VAZ_342?usp=sharing

InceptionV3 - Best Model Parameters
- [Best_model.pth](https://drive.google.com/file/d/1yVOQkAipxNjb3AG_Jl4HfUvb1luoeOec/view?usp=sharing)
- Parameters:
  - Learning Rate - 1.1e-5
  - Batch Size -16
  - Epoch - 30

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
