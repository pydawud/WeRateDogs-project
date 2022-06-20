# WeRateDogs Data Wrangling
***
This project is one of the three projects undertaken during the Udacity Data Analysis Nanodegree program, The Dataset is from the popular Twitter account [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs) with the username [@dog_rates](https://twitter.com/dog_rates) with over 9m followers on Twitter downloaded their Twitter archive and sent it to Udacity via email exclusively to be used in this project. The archive contains basic tweet data (tweet ID, timestamp, text, etc.) not later than August 1, 2017. The tweets are about rating dogs with humorous comments with a rating of 10-15 for Numerators and 10 for the denominator along with the dog stages, the stages can be doggo, floofer, pupper, and puppo. For example:
> This is Phineas. He's a mystical boy. Only ever appears in the hole of a donut. 13/10 https://t.co/MgUWQ76dJU

The task is to gather, assess, clean and analyze the data using python and its various libraries.
## Gather
***
Three datasets are needed in other to complete the tasks, namely:
1. `Twitter-enhanced-archive` dataset: this dataset was given by the Udacity which is made up of tweets, retweets, and replies to the original tweets about dogs
2. `image-prediction` dataset: This data is made up of results of a Neural Network classifiers on some sets of images, and their predicted breeds. the data need to be downloaded programmatically using the `requests` library.
3. `tweet_json.txt` dataset:  A JSON data extracted from the `Twitter`, accessing Twitter data will involve the use of API, we need to write an application for requesting access to the API, if approved, we then used the `tweepy` to extract data from the Twitter archive.
## Assess
***
Visual and Programmatic Assessment was employed, best on project requirements, we need to assess at least 8 quality issues and 2 Tidiness issues. In this project, we address 16 quality issues and 3 Tidiness Issues.
## Clean
***
The `Define-Code-Test` was employed in cleaning the aforementioned issues
## Reports
***
A wrangle and act report is attached that captures the efforts in the wrangling and the analysis stage. 
## Research Questions
***
1. What are the top-rated dogs?
2. What are the top-rated dog stages?
3. What is the most dog stage tweeted?
4. What are the most tweeted dog breeds?
5. What is the relationship between retweets and likes on dog tweets?
6. What is the most like dog breed? etc.
## Installation
***
Install anaconda (all will be available) or install them via `conda` or `pip` 
- pandas
- NumPy
- requests
- tweepy
- matplotlib.pyplot
- seaborn
- JSON
- config parser

## License
***
The content of this repository is covered under [GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)