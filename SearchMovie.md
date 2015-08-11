# Introduction #

Search for movie by giving title information.

# What do you get? #

Movies which are related to the given searchterm.en.

# URL to call #

Via GET _/searches/movies.json?q=SEARCHTERM_

# parameter for GET #

|parameter|description|optional?|
|:--------|:----------|:--------|
|api\_key |ApiKey     |needed   |
|q        |searchterm |needed   |

# example request #

searching for movies with "matrix" within the title

_/searches/movies.json?q=matrix_

## curl request ##
```
curl http://www.moviepilot.de/searches.json?q=matrix&api_key=APIKEY
```