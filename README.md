# Classifying-Sentiment-of-Restaurant-Reviews-YELP
Prediction of the rate made by a user on a restaurant based on the review given by the user

Using the Yelp Review Dataset, we are going to classify the reviews made by the users into positive or negative reviews.
The samples in this dataset have different columns, such as rating, review, user_id, business_id... for the purpose of this project we are only going to use the columns review and rating.

Because we are classifying in to negative and positive, we have to set up which number of stars corresponds to positive and negative. IT is been established to set up 1, 2 and 3 stars into negative and 4 and 5 stars as positive review.

I the first script, Spliting the data into Training_Validation_Test & Preprocessing.ipynb, the rating has been transform from stars to positive/negative range.We also split the data into training, validation and test datasets.

Once the data has been preprocessed and split, we proceed to train the model wiht the script: Yelp review classifier.ipynb.

The accuracy obtained for the test dataset is 82,5%.
