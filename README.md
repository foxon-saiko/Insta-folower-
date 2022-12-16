# this project is not maintained anymore


# Instagram Follower Scraper
> Scrapes all the followers from instagram pages and stores them in a csv file

_The scraper uses the awesome library [Instaloader](https://instaloader.github.io/) to get data from instagram._
_This doesn't use the instagram API because it is slow and has other limitations. Please don't run multiples instances of this scraper at same time from same device._


## Installation

OS X & Linux:

Open terminal

1. ``` git clone  ( copy clone url and past your terminel )```
2. ``` cd Instagram-Follower-Scraper/ ```
3. ``` pip install -r requirements.txt ```



## Usage example

put the list of accounts to scrape in ```input.txt```

```python instabot.py ```

if you are running on a server than. 

``` nohup python instabot.py &```


Use this to view the logs

``` tail -f nohup.out```
