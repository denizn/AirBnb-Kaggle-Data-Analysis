
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

You will need the standard data science libraries found in the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.  

You will also want to download [nltk](https://www.nltk.org/data.html) - directions for this can be found in the text processing portion of the workbook.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in analyzing data from AirBnB homes located in Seattle and Boston.  Specifically, I looked at the following questions:

1. How much do people charge to rent their homes (on average, minimum, maximum)? How does this compare from Boston to Seattle?
2. How many days a year do homeowners make their homes available to rent? How does this compare from Boston to Seattle?
3. Are there seasonality components or price spiking components for how hosts set their home prices? How does this compare from Boston to Seattle?
4. How many reviews do homes tend to get? How does this compare from Boston to Seattle?
5. What are the most common words used to describe a listing? Are the same words used for Seattle and Boston homes?


## File Descriptions <a name="files"></a>

The following are the files available in this repository:

* `AirBnB_Project_1_Analysis.ipynb` - a notebook of the analysis performed following the CRISP-DM process

* `calendar.csv` and `calendar_boston.csv` - csvs containing **home_id**, **date**, **availability**, and **price** for each home

* `listings.csv` and `listings_boston.csv` - these were not used for this particular analysis, but they were available from the original kaggle link

* `reviews.csv` and `reviews_boston.csv` - csvs containing the **home_id**, **date** of review, **reviewer_id**, **reviewer_name**, and reviewer **comments** for the reviewed stays.

It is worth noting here that the reviews and calendar files did not have overlapping dates, and there were no numeric values associated with reviews.

## Results<a name="results"></a>

The main findings of the code can be found at the [blog post available here](https://medium.com/@josh_2774/a-comparison-of-airbnb-homes-seattle-vs-boston-cdc0df2cfcd7).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to AirBnB and Kaggle for the data.  You can find the Licensing for the data and other descriptive information for the [Boston data on Kaggle](https://www.kaggle.com/airbnb/boston) and for the [Seattle data](https://www.kaggle.com/airbnb/seattle).  
