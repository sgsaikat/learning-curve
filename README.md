# learning-curve
This Repository hosts Assignments using the [Amazon Fine Food Reviews](https://www.kaggle.com/snap/amazon-fine-food-reviews) dataset.
The files contain the various techniques and ML algorithms learnt as gradual progression of the course.

Some of the details are highlighted below :-
* Create_Support_Files - This file is used to preprocess the text data and store the Vectorized data in files to be used in other Assignments.
* **Objective** of each Program is to Predict whether a given Review is Positive or Negative.
* Programs contain codes to achieve the common objective by utilizing various ML Algos.
* Various Preprocessing of Text data before Vector transformations -
  * Remove punctuations, HTML tags, Stopwords and duplicate records (based on certain combo of features).
  * Stemming - SnowballStemmer used in this case.
* 'Accuracy' metric doesn't work very well for Imbalanced data - use other metrics like 'precision', 'recall', 'f1', etc.
* Use Dimensionality Reduction techniques like TruncatedSVD or PCA to reduce dimensions of the dataset since Vectorized data tends to blow up in no. of features (for BOW or TFIDF Vectorizers).
* Plot out Train and Test Scores - helps in understanding the Optimal params selected and how the model is performing.
* **Never** use Test Data to evaluate the Hyper-parameters - use cross validation instead!!
* Work with Sparse Vectors using Scipy's 'sparse' module - increases performance when dealing with large datasets with sparse data (Ex- Text Vectors).
* Use Wordcloud to highlight important words (features) used to evaluate Review polarities.
Use GraphViz to Visualize Decision Trees.
