## AirBnB-Data-Analysis-NLP-Regression

### Motivation
For this project, I wanted to delve deep into Kaggla AirBnB datasets for Seattle and Boston. I will be focusing on answering three questions below in the jupyter notebook. The first two questions will be basic data analysis on the data while the last question will be require us to process a full Natural Language Processing pipeline.

Question 1: How are the pricing of the properties in Boston and Seattle? Do they have seasonality? Are there any events that cause jumps in price?

Question 2: How is the availability of the properties in both cities throughout the year?

Question 3: Can we predict the review score from comments using regression? Do the comments of the visitors on a listing give us enough information for us to guess the review score of that listing

### Installation
The libraries we will be using will be:
Python 3.6.5 Anaconda Distribution
[xgboost] (https://xgboost.readthedocs.io/)
[catboost] (https://tech.yandex.com/catboost/)
[nltk](https://www.nltk.org/data.html)

## File Descriptions
* `calendar.csv` and `calendar_boston.csv` - csvs containing **home_id**, **availability**, and **price** for every listing/date combination

* `listings.csv` and `listings_boston.csv` - **id**, **review_scores_rating** for each listing

* `reviews.csv` and `reviews_boston.csv` - csvs containing the **home_id**, **date** of review, **reviewer_id**, **reviewer_name**, and reviewer **comments** for the reviewed stays.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Data used are provided through Kaggle by AirBnB : [Boston data on Kaggle](https://www.kaggle.com/airbnb/boston) and for the [Seattle data](https://www.kaggle.com/airbnb/seattle).
