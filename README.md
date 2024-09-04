# Function
Built a scraper which can scrape upto 525 reviews of a particular movie 
and convert them into dashboard-like graphs to get a snapshot view of the reviews scraped.

# Language:  

Python3

# Technologies used

## For scraping:

- Selenium
- BeautifulSoup


## For text-preprocessing:

- NLTK
- Gensim


## For Classification:

- Tensorflow
- Keras

## Dashboard Creation:

- matlplotlib
- mpld3


# Files:

- Data Collection:  
For making a deep learning model, I randomly selected 100 movies and scraped about 250 reviews of them in this file. 

- Model Training 2.0:  
Trained the model for classifying the reviews as positive, negative or neutral

- lstm_classifier_4.0:  
The trained model

- IMDb Reviewer:  
The main file for scraping, processing, classifying and creating the dashboard.

