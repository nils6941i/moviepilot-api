# Introduction #

The "include" parameter can be added to include datatypes. There must be a relation between the object you ask for and the object you want to include.

# Details #


To include multiple resources you must seperate them with "," for example:

http://www.moviepilot.de/movies.json?include=images,broadcasts,genres

|resource|what can be included|
|:-------|:-------------------|
|ResourceMovie| images, broadcasts, genres|
|ResourceMovieNeighbour|images, broadcasts, genres, watchlist, rating, forecast|