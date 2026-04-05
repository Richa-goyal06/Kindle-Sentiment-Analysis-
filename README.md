# Kindle-Sentiment-Analysis (Using Natural Language Processing)

This Project is done using Natural Language Processing (NLP) Techniques. Python libraries like Pandas (for Data Cleaning/Handling), NLTK, TextBlob, Scikit-learn (for text preprocessing) and Naive Bayes (for model building)
## Dataset 
- <a href="https://github.com/Richa-goyal06/Bank-loan-Analysis/blob/main/financial_loan.csv">Dataset</a>

## Pipeline
1.Performed data cleaning and EDA using Pandas and NumPy.
2. Applied text preprocessing: tokenization, stopword removal, and lemmatization using NLTK.
3. Extracted sentiment polarity features using TextBlob.
4. Converted text into numerical features using Bag-of-Words and TF-IDF.
5. Trained a Multinomial Naive Bayes classifier.
6. Evaluated model using accuracy score and confusion matrix.

## Key improvements and Results
-Initial model using Bag-of-Words achieved 53% accuracy.
-Optimized by:
    -Converting ratings into binary sentiment (positive/negative).
    -Using TF-IDF vectorization.
Final model achieved 89% accuracy on test data.

