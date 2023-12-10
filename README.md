# data-sourcing-challenge
AI Bootcamp Challenge 6

# Data Sourcing
This challenge is to use our knowledge on using open APIs to retrieve data, manipulate and convert to dataframes. We are using New York Times and The Movie Data Base open APIs to create movie reviews with headline love. Below are API references from NYT and TMDB,

[New York Times Article Search API Overview](https://developer.nytimes.com/docs/articlesearch-product/1/overview)

[TMDB API Guide](https://developer.themoviedb.org/reference/intro/getting-started)

# APIs Usage and Keys
This assignment shows how to use APIs by using multiple URLs with passing api keys or tokens and also specific parameters to retrieve data. Provides opportunity to understand API usage, data retrieval process, error handling and frequency of calls. 

# Data Collection and Manipulation
Used NYT APIs to search for movie review articles with headline love. Once data is retrieved we store 200 reviews from 20 different pages. Then extract the title of movies and store in a list. Use this list to search movie details from TMDB using search movie and movie details APIs. 

Combine both data to single dataframe using the title and cleanup data before exporting to csv.



