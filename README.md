
## Overview
This project is aimed at performing sentiment analysis on Amazon customer reviews and identifying customer behavior for product recommendations. It uses NLP techniques to analyze the sentiments expressed in the reviews and provides insights into the overall sentiment of the products based on these reviews.

## Features

- **Sentiment Analysis:** Utilizes machine learning and natural language processing to determine the sentiment of customer reviews.

- **Data Collection:** Python scripting for scraping Amazon customer reviews for various products.

- **Data Preprocessing:** Cleans and prepares the text data for analysis, including tokenization, removing stop words, and stemming or lemmatization.

- **Visualization:** Generates visualizations and reports to understand sentiment trends across products.


## Data Dictionary

* Id: Serial Number<br>
* ProductId: Unique identifier for the product<br>  
* UserId: Unique identifier for the user<br>
* ProfileName: Name users have used<br>
* Indicator_Positive: No. of users who found the review helpful<br>
* Indicator_Negative: No. of users who indicated whether they found the review helpful or not<br>
* Score: Rating product between 1 and 5<br>
* Time: Timestamp of the review<br>
* Summary: Brief description of the review<br>
* Text: Actual review provided by the customer<br>

## File Execution
* Reviews.csv: Dataset containing approx 500k Amazon customers, products, and their review<br>
* Final Amazon Customer Review.ipynb: Jupyter Notebook consisting of EDA and analysis performed on customer reviews.




