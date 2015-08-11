# What do you get? #

Movies which are related to the given movies. so called neighbours. This movies are rated by the same people in the same way.


# URL to call #

Via GET the URL of [Movie](ResourceMovie.md)  plus _/neighbours.json_ .

## parameters for GET ##

|**parameter**|**description**|**optional**|
|:------------|:--------------|:-----------|
|''api\_key'' |ApiKey         |needed      |


# examples #
## request for neighbours of the movie "oben" ##

_/movies/oben/neighbours.json_


## curl request for neighbours of the movie "oben" ##

```
curl http://de.api.moviepilot.com/movies/oben/neighbours.json?api_key=APIKEY
```

## example response ##

```
 
  {
       "item_neighbours": [{
           "distance": 0.177128,
           "restful_url": "http://www.moviepilot.de/item_neighbours/52716195",
           "neighbour_movie": {
               "average_community_rating": 79.9246,
               "premiere_date": "2008-05-15",
               "cinema_start_date": "2008-05-15",
               "short_description": "Urlaub haben sie sich verdient, so viel ist klar. ....",
               "dvd_start_date": "2009-08-14",
               "long_description": "Der Film startete in den deutschen Kinos a ...",
               "average_critics_rating": 76.0256,
               "restful_url": "http://www.moviepilot.de/movies/bruegge-sehen-und-sterben",
               "countries_list": "GB,BE",
               "runtime": 107,
               "production_year": "2008",
               "display_title": "Brügge sehen... und sterben?",
               "on_tv": false,
               "homepage": null
           },
           "movie_restful_url": "http://www.moviepilot.de/movies/oben"
       },
       {
           "distance": 0.2221205,
           "restful_url": "http://www.moviepilot.de/item_neighbours/52716196",
           "neighbour_movie": {
               "average_community_rating": 74.9027,
               "premiere_date": "2003-11-20",
               "cinema_start_date": "2003-11-20",
               "short_description": "Der Schreck sitzt dem ohnehin notorisch ängstlichen ... ",
               "dvd_start_date": "2008-09-11",
               "long_description": "Der Film erzählt die Geschichte des kleinen bunten Clownfisches ...",
               "average_critics_rating": 76.4286,
               "restful_url": "http://www.moviepilot.de/movies/findet-nemo",
               "countries_list": "US",
               "runtime": 101,
               "production_year": "2003",
               "display_title": "Findet Nemo",
               "on_tv": false,
               "homepage": null
           },
           "movie_restful_url": "http://www.moviepilot.de/movies/oben"
       },
       {
           "distance": 0.2277455,
           "restful_url": "http://www.moviepilot.de/item_neighbours/52716197",
           "neighbour_movie": {
               "average_community_rating": 77.3901,
               "premiere_date": "2008-03-20",
               "cinema_start_date": "2008-03-20",
               "short_description": "Gestatten: Juno MacGuff - selbstbewusster, offenherziger Teenager, ...",
               "dvd_start_date": "2008-11-26",
               "long_description": "Die 16-jährige Juno hatte vor kurzem mit ihrem ....",
               "average_critics_rating": 79.7959,
               "restful_url": "http://www.moviepilot.de/movies/juno-2",
               "countries_list": "US",
               "runtime": 96,
               "production_year": "2007",
               "display_title": "Juno",
               "on_tv": false,
               "homepage": null
           },
           "movie_restful_url": "http://www.moviepilot.de/movies/oben"
       }
       ],
       "total_entries": 139
  }
  
```