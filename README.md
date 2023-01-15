# Covid-19-Tweet-Sentiment-Prediction
#### In this project we have data related to covid-19 tweets, where we have done exploratory data analysis, applied multiple text preproicessing techniques, vectorisation of textual data and we have also handled the imbalance in our dataset. And finally we build multiple machine learning models, where Support Vector Classifier was the best model because it gives the highest accuracy on test data as compared to other models.

Some of the key insights found from this project are as follows👇🏻-:

1. Most of the tweets found were in March and April 2020, as the first wave of covid spread widely around the world and many countries declared lockdowns.

2. Majority of the sentiments are positive as people try to keep a brave face during the pandemic.

3. Username and ScreenName were not important for our analysis because they contained all unique IDs

4. Majority of the tweets came from the US, UK, and India as these were the most affected geographies.

5. Most of the hashtags used in tweets will be either #COVID19 or #coronavirus.

6. Food and coronavirus, covid 19 should be some of the most common words because there was a shortage of food in grocery stores during the pandemic.

7. We extracted new features like num_char, num_words, num_sentences to check the sentiment of a tweet. We saw that if there are more words, characters and sentences, then the sentiment of the tweet is more positive. Tweets with neutral sentiment contain fewer words, characters, and sentences.

8. If the performance of the multiclass models was not satisfactory, we would convert the problem to a binary class where the target variable could be changed to (0 and 1)

9. For vectorization, we tried TF-IDF vectorization for vectorization and used an unbalanced method using smote over_sampling to balance the data because most of the tweets were positive.

10. The feature importance is calculated based on the most frequent words in each class. We can see that London, United States, New York, Washington DC, United Kingdom, India, Australia, USA are the places in terms of the number of tweets.

11. We can see that the maximum number of tweets was made on March 20, 2020, when the first lockdown was announced. People were more active on Twitter in March because it was the early stage of the coronavirus pandemic and people wanted to know more about the disease.

12. We evaluated the multi-class models as categories – positive, neutral, and negative.

13. We have applied multiple classification machine learning models where Support Vector Classifier is the one with best accuracy on testing Data.

14. And at last we saved our SVC model into a pickle file for further process of deployment.
