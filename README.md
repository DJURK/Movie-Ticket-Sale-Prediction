# Movie-Ticket-Sale-Prediction
I used data scraping techniques (beautifulsoup, selenium) to gather data on movies from 1995 to 2017. I then used several different regression models to find an optimal prediction for movie ticket sales.


## Strategy

1. Beautifulsoup - Used html elements on http://www.boxofficemojo.com/ to obtain information on 700 movies each year from 1995-2017
2. Selenium - Used previously scraped movie names to find their respective ratings from https://www.imdb.com/
3. Performed regression analysis to find trends in movie ticket sales
