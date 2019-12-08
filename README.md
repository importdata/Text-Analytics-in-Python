# Text-Analytics-in-Python

Data:
For this analysis we’ll be using a dataset of 50,000 movie reviews taken from IMDb. IMDb lets users rate movies on a scale from 1 to 10. To label these reviews the curator of the data labeled anything with ≤ 4 stars as negative and anything with ≥ 7 stars as positive. Reviews with 5 or 6 stars were left out. The data is split evenly with 25k reviews intended for training and 25k for testing your classifier, where the first 12.5k are positive and the last 12.5k are negative in each set.

- Task 1: 
Clean and preprocess: remove any special characters with space, remove the stop-words.

- Task 2:
The simplest form of this is to transform each review into one row containing 0s and 1s, where 1 means that the word in the corpus (where the corpus is all 50k reviews in our case) corresponding to that column appears in that review. (you can also use other vectorization methods such as bag of words and tf-idf).

- Task 3: 
Applied K-Nearest Neighbor and SVM on the training dataset and predict on the test dataset and reported the testing accuracy and plot the ROC curve for each method.

------------------------------------------------------------------------------
- PDF file contains the hand-written part of the questions.
