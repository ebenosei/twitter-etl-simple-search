# twitter-etl-simple-search

### This project is to a script that downloads tweets data on a specific search topic using the standard search API. The script should contain the following functions: 
#### 1. scrape_tweets() that has the following parameters:
* Search topic (#ArtetaOut)
* The number of tweets to download per request (1500)
* The number of requests

And returns a dataframe.

#### 2. Save_results_as_csv() that has the data frame from above


The following attributes of the tweets should be extracted:

* Tweet text
* Tweet id
* Source
* Coordinates
* Retweet count
* Likes count
* User info
* Username
* Screenname
* Location
* Friends count
* Verification status
* Description
* Followers count


### The topic chosen here is '#ArtetaOut', a hashtag calling for the dismissal of Mikel Arteta, the manager of Arsenal Football Club
