# NLP Project-

## Dataset-
- Used ‘Amazon Customer Reviews’ Dataset which is a vast dataset containing key information about the product sold and the respective customer reviews.
- Some prominent columns include ‘name’, ‘brand’, ‘reviews.rating’, ‘reviews.numHelpful’ (indicating the helpfulness of the review), and ‘reviews.text’ (containing the actual review which is to be analysed.
  
## Problem Statement-
- The main objective is to build a model that tells you if an aforementioned review is ‘Positive’ or ‘Negative’. 
- This will help business get an overview of the consensus around a product and how the public is reacting to it.
  
## Methodology-
- Data Preprocessing and Visualisation - First step was the remove null values in some prevalent columns such as ‘reviews.rating’ and ‘reviews.text’ and replace them with the string “Missing”. Next I visualised the ratings column to see the general distribution of positive and negative reviews.
### Model Building -
- Stop word Removal- A stop word is a commonly used word (such as “the”, “a”, “an”, or “in”) that a search engine has been programmed to ignore, both when indexing entries for searching and when retrieving them as the result of a search query. These words are not important in our analysis since they don’t convey any emotion in the review. 
- Lemmatization is the process of grouping together the different inflected forms of a word so they can be analyzed as a single item. Lemmatization is similar to stemming but it brings context to the words. We performed Lemmatization on the words using NLTK.
- After this the final step was to make a training and testing model and making a confusion matrix to predict if a review is Positive or Negative.
  
## Results and Conclusions-
- The final result was encouraging as the model had an accuracy of 97% and was able to say if a given written review has a Positive or Negative outcome.
