# Kindle-Sentiment-Analysis (Using Natural Language Processing)

This Project is done using Natural Language Processing (NLP) Techniques. Python libraries like Pandas (for Data Cleaning/Handling), NLTK, TextBlob, Scikit-learn (for text preprocessing) and Naive Bayes (for model building)
## Dataset 
- <a href="https://github.com/Richa-goyal06/Kindle-Sentiment-Analysis-/blob/main/all_kindle_review.csv.xls">Dataset</a>

## Pipeline
1.Performed data cleaning and EDA using Pandas and NumPy.

2. Applied text preprocessing: tokenization, stopword removal, and lemmatization using NLTK.
   
4. Extracted sentiment polarity features using TextBlob.
   
6. Converted text into numerical features using Bag-of-Words and TF-IDF.
   
8. Trained a Multinomial Naive Bayes classifier.
   
10. Evaluated model using accuracy score and confusion matrix.

## Key improvements and Results
-Initial model using Bag-of-Words achieved 53% accuracy.

-Optimized by:

    -Converting ratings into binary sentiment (positive/negative).
    
    -Using TF-IDF vectorization.
    
Final model achieved 89% accuracy on test data.

