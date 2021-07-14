# Approach-to-Sentiment-Analysis

Here I tried to make sentiment analysis using the tensorflow.

Sentiment analysis is the contextual study that aims to determine the opinions, feelings,
outlooks, moods and emotions of people towards entities and their aspects. The primitive
functions of sentiment analysis are emotion recognition that focuses on extracting a cluster of
emotion labels and polarity detection which aims to classify the writer’s attitude as positive,
negative and neutral.

Data Source: [Women’s Clothing E-Commerce dataset](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews)<br /><br />

This dataset includes 23486 rows and 10 feature variables. Each row corresponds to a customer
review, and includes the variables:

* Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.

* Age: Positive Integer variable of the reviewers age.

* Title: String variable for the title of the review.

* Review Text: String variable for the review body.
* Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1
Worst, to 5 Best.

* Recommended IND: Binary variable stating where the customer recommends the product
where 1 is recommended, 0 is not recommended.

* Positive Feedback Count: Positive Integer documenting the number of other customers who
found this review positive.

* Division Name: Categorical name of the product high level division.

* Department Name: Categorical name of the product department name.

* Class Name: Categorical name of the product class name.
